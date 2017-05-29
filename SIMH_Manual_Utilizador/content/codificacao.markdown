---
layout: default
title: "Episódios"
---


---
<div id="codificar"></div>

# 6. Episódios

Através deste módulo é possível fazer a codificação de episódios de uma determinada entidade hospitalar.

Para isso, o utilizador deve, a partir da página inicial, aceder ao módulo "Codificação do Episódio", tal como ilustra a [](#figAcessoCodificacaoEpisodios).

![figAcessoCodificacaoEpisodios](img/pages/6_1.jpg)

<p class="caption" id="figAcessoCodificacaoEpisodios">Módulo Codificação do Episódio</p>

Ao aceder a este módulo, aparecerá a seguinte página:

![figCodificacaoEpisodios](img/pages/6_2.jpg)

<p class="caption" id="figCodificacaoEpisodios">Página de entrada do módulo Codificação do Episódio</p>

Aqui, é possível realizar três ações distintas: **Pesquisa**, **Consulta** ou **Edição** de episódios.

<div id="processo-codificacao"></div>

## 6.0. Processo de Codificação

Antes de dar a conhecer as diferentes ações possíveis a realizar na aplicação sobre os episódios, será introduzido ao utilizador o conjunto de estados e ações passíveis de realizar sobre um episódio durante a sua existência.
 
Este fluxo de estados pode ser consultado a partir da [](#figEstadosCodificacaoEpisodio).

![figEstadosCodificacaoEpisodio](img/episodio_estados_accoes.png)

<p class="caption" id="figEstadosCodificacaoEpisodio">Fluxo de estados e operações sobre um episódio Por Codificar</p>

![figEstadosCodificacaoEpisodio1](img/episodio_estados_accoes1.png)

<p class="caption" id="figEstadosCodificacaoEpisodio1">Fluxo de estados e operações sobre um episódio Em Auditoria</p>

![figEstadosCodificacaoEpisodio2](img/episodio_estados_accoes2.png)

<p class="caption" id="figEstadosCodificacaoEpisodio2">Fluxo de estados e operações sobre um episódio Finalizado</p>

Um episódio começa sempre no estado **Por Codificar**. A única forma de o colocar disponível para faturação, é ao transitá-lo para o estado **Finalizado**.
Para que transite para este estado, o episódio deve primeiro sofrer agrupamento GDH. Um episódio pode, adicionalmente, ser guardado em rascunho ou ser auditado. Caso o utilizador esteja à procura de uma visão mais completa e abrangente do fluxo de estados e ações associado a um episódio, pode sempre consultar o seguinte [diagrama](img/episodio_estados_accoes_detalhe.png).

<div id="codificacao-pesquisa-de-episodios"></div>

## 6.1. Pesquisa de episódios por codificar

Na pesquisa de episódios por codificar, um utilizador deve preencher obrigatoriamente um dos seguintes campos:

* **Nº Processo** - Número de processo associado aos episódios a pesquisar;
* **Nº Episódio** - Número que identifica de forma inequívoca o episódio na entidade hospitalar do utilizador;
* **Nº Utente** - Número de utente de saúde do doente associado aos episódios a pesquisar;
* **Estado** - Estado associado ao episódio a pesquisar;
* **Data de alta de** - Permite a pesquisa de episódios em que o doente teve data de alta a partir da data aqui definida;
* **até** - Permite a pesquisa de episódios em que o doente teve data de alta até a data aqui definida;
* **Especialidade** - Permite a pesquisa de episódios em que o utente tenha passado pela especialidade médica aqui definida;
* **Serviço** - Permite a pesquisa de episódios em que o utente tenha passado pelo serviço aqui definido;
* **Médico Codificador** - Médico codificador associado aos episódios a pesquisar;
* **Módulo** - Módulo associado ao episódio a pesquisar.


De seguida deve clicar no botão **Pesquisar**.

A pesquisa realizada apenas devolve episódios relativos à entidade hospitalar do utilizador que efetuou a pesquisa.

A [](#figPesquisaCodificacaoEpisodios) ilustra como exemplo uma pesquisa de episódios no estado ´Por Codificar´ efetuada por um utilizador.

![figPesquisaCodificacaoEpisodios](img/pages/6_1_1.jpg)

<p class="caption" id="figPesquisaCodificacaoEpisodios">Pesquisa de episódios por codificar</p>

<div id="detalhe"></div>
<div id="codificacao-consulta-de-episodios"></div>

## 6.2. Consulta de um episódio

Após realizar a pesquisa de episódios segundo um conjunto de critérios (ver [6.1. Pesquisa de episódios por codificar](#codificacao-pesquisa-de-episodios)), e ao selecionar um episódio, passa a ser possível a consulta do mesmo.
Para tal, deve-se clicar no botão **Consultar**, tal como a [](#figConsultaCodificacaoEpisodios) ilustra.

![figConsultaCodificacaoEpisodios](img/pages/6_2_1.jpg)

<p class="caption" id="figConsultaCodificacaoEpisodios">Consulta dos detalhes de um episódio</p>

Ao clicar neste botão, o utilizador transita para a página de detalhe do episódio tal como a [](#figDetalheCodificacaoEpisodios) ilustra.

![figDetalheCodificacaoEpisodios](img/pages/6_2_2.jpg)

<p class="caption" id="figDetalheCodificacaoEpisodios">Detalhe de um episódio</p>

Nesta página é possível visualizar a seguinte informação:

* **Identificação do Episódio**
![figDetalheCodificacaoEpisodios1](img/pages/6_2_3.jpg)

* **Dados do Episódio**
![figDetalheCodificacaoEpisodios2](img/pages/6_2_4.jpg)

* **Dados da Codificação**
![figDetalheCodificacaoEpisodios3](img/pages/6_2_5.jpg)

* **Dados das Sessões**
![figDetalheCodificacaoEpisodios5](img/pages/6_2_7.jpg)

* **Dados da Auditoria**
![figDetalheCodificacaoEpisodios4](img/pages/6_2_6.jpg)

A informação presente na área **Identificação do Episódio** encontra-se sempre visível durante as transições entre as abas **Dados do Episódio**, **Dados da Codificação** e **Dados da Auditoria**.
Durante a consulta de um episódio todos os campos se encontram bloqueados, não sendo possível realizar alterações ao mesmo.

<div id="codificacao"></div>
<div id="codificacao-edicao-de-episodios"></div>

## 6.3. Edição de um episódio


Após efetuar uma pesquisa por episódios por codificar ([6.1. Pesquisa de episódios por codificar](#pesquisa-de-episodios-por-codificar)) e ao selecionar um episódio devolvido pela mesma passa a ser possível a edição do mesmo.
Para tal, deve-se clicar no botão **Editar**, tal como a [](#figEditaCodificacaoEpisodios) ilustra.

![figEditaCodificacaoEpisodios](img/pages/6_3_1.jpg)

<p class="caption" id="figEditaCodificacaoEpisodios">Edição de um episódio</p>

Ao clicar neste botão, o utilizador transita para a página de codificação do episódio tal como a [](#figCodificacaoCodificacaoEpisodios) ilustra.

![figCodificacaoCodificacaoEpisodios](img/pages/6_3_2.jpg)

<p class="caption" id="figCodificacaoCodificacaoEpisodios">Codificação de um episódio</p>

A codificação de um episódio segue, essencialmente, a sequência descrita na [](#figFluxoCodificacaoEpisodio).

![figFluxoCodificacaoEpisodio](img/fluxo_episodio.png)

<p class="caption" id="figFluxoCodificacaoEpisodio">Fluxo de codificação de um episódio</p>

Inicialmente, é necessário preencher a secção de **Informação do Episódio** e a de **Registo** do episódio.
Caso o utilizador deseje simplesmente marcar o episódio como não codificável, deverá clicar no botão **Não Codificar**.
Poderá também em qualquer altura marcar o episódio como Rascunho, para que o possa codificar/alterar mais tarde.

Na secção de **Informação do Episódio** (ver [](#figCodificacaoInformacaoCodificacaoEpisodios)), secção onde o utilizador começa a codificação do episódio, é possível visualizar e editar a seguinte informação: **Natureza da Admissão**, **Destino após Alta** e **Outros Dados**.
**As restantes informações vêm do Sistema de Informação fonte e qualquer alteração terá de ser feita no mesmo.**

Os seguintes campos contêm algumas regras que o utilizador deve conhecer:

* **Natureza da Admissão**

	* Campo Proveniência – não é de preenchimento obrigatório. Se a opção "Da própria instituição" for selecionada e se tratar de um episódio de internamento, então terá de selecionar o tipo de proveniência da própria instituição. Caso selecione "De outra instituição", deverá preencher a unidade de origem.<br>
	* Tipo de Admissão – este campo vem preenchido do SI fonte. Podendo ter as seguintes opções (vindo do SONHO):
		* Episódios de internamento: URGENTE ou PROGRAMADA
		* Episódios de ambulatório: PROGRAMADA

* **Destino após Alta**

	* Se o módulo do episódio for de ambulatório (CON, MCDT, HDI), então este campo pode ser editado pelo utilizador, caso contrário, só poderá ser alterado no SI fonte. <br>
	* Existem alguns tipos de destino que exigem o preenchimento do motivo de transferência. Como se consulta na figura seguinte:
 
![figDestinoAposAlta](img/pages/6_3_8.jpg)

<p class="caption" id="figDestinoAposAlta">Exemplo Destino Após Alta com Transferido para e Motivo de Transferência</p>
 
* **Outros Dados**

	* Os campos do **Número de Dias em Cuidados Intensivos** e **Número de Dias de Ventilação Mecânica Invasiva** podem ser preenchidos pelo utilizador. Já o **Peso à Nascença** e **Semanas de Gestação** vêm preenchidos do SI fonte.

![figCodificacaoInformacaoCodificacaoEpisodios](img/pages/6_3_3.jpg)

<p class="caption" id="figCodificacaoInformacaoCodificacaoEpisodios">Passo 1 da codificação: Informação do Episódio </p>

Nesta página irá estar visível o botão **Simular** para utilizadores com perfil médico codificador. Ao clicar neste botão, o utilizador será transportado para um ecrã com o nome **Simular Codificação** (ver [](#figCodificacaoSimularCodificacaoEpisodios)) onde será possível realizar a simulação da codificação do episódio (ver [7. Simuladores](#simulador)).

![figCodificacaoSimularCodificacaoEpisodios](img/pages/6_3_4.jpg)

<p class="caption" id="figCodificacaoSimularCodificacaoEpisodios">Simular de Codificação</p>

Para prosseguir para a secção de **Registo** (ver [](#figRegistoCodificacaoEpisodios)) do episódio o utilizador deve premir o botão **Registar**. 
Nesta secção, é possível visualizar e editar a seguinte informação: **Identificação do Episódio**, **Identificação do Doente**, **Identificação do Médico**, **Intervenção Cirúrgica**, **Diagnósticos**, **Procedimentos** e **Dispositivos Médicos**.

Os seguintes campos contêm algumas regras que o utilizador deve conhecer:

* **Intervenção Cirúrgica**

	* No caso de ser um episódio de internamento e ter como Tipo de Proveniência a opção cirurgia de ambulatório, as datas de cirurgia podem ser antes da data de admissão do episódio. <br>
	* Se for um episódio de cirurgia de ambulatório este deverá conter o Tipo de Programação de acordo com o sistema de informação fonte. Para que os episódios sejam integrados no SIMH este campo deve ser mapeado no respectivo separador do módulo [Mapeamentos](#mapeamentos).

![figRegistoCodificacaoEpisodios](img/pages/6_3_5.jpg)

<p class="caption" id="figRegistoCodificacaoEpisodios">Passo 2 da codificação: Registo do Episódio </p>

Para adicionar um novo diagnóstico à tabela de diagnósticos ou um novo procedimento à tabela de procedimentos, é necessário preencher um código na caixa de código e adicioná-lo à tabela ![logo](img/pages/6_3_6.jpg).
Quer na tabela de diagnósticos, quer na tabela de procedimentos, os códigos adicionados podem ser removidos ao clicar em ![logo](img/remover.jpg) ou reposicionados, usando para isso a opção ![logo](img/subir.jpg) para mover o código para cima ou a opção ![logo](img/descer.jpg) para mover o código para baixo.

No caso de o episódio pertencer ao módulo de internamento (tal como ocorre com o episódio de exemplo), a área de diagnósticos terá informação relativa ao indicador PNA (Presente na admissão):
![figRegistoCodificacaoEpisodios1](img/pages/6_3_7.jpg)
Para adicionar um novo diagnóstico a esta tabela, terá de se indicar o PNA correspondente.
<br>
Quando finalizada a edição de um episódio, podem ser realizadas três ações distintas: 

* **Rascunho** - Permite gravar a folha de codificação com o estado de rascunho, se o episódio passar nas validações da codificação então este rascunho será considerado válido, caso contrário não será tido em conta na pesquisa do módulo [Ações em Bloco](#acoesBloco)

* **Auditar** - Permite gravar a folha de codificação com o estado de auditoria;

* **Finalizar** - Permite gravar a folha de codificação com o estado de finalizado, de forma a este episódio poder ser faturado.

<br>
### 6.3.1. Copiar Codificação de Outras Sessões

<p class="faq">Copiar Codificação de Outras Sessões</p>
<br>
É possível **Copiar Codificação** entre sessões de episódios de ambulatório. Para que a opção fique visível, é necessário ter codificado pelo menos uma sessão pertencente ao mesmo episódio de ambulatório, ou seja, que exista outra sessão do mesmo episódio de ambulatório no estado **FINALIZADO**. Se existir mais que uma sessão codificada, o sistema opterá por ir buscar a foi **codificada mais recentemente**.

![figRegistoCodificacaoEpisodios](img/pages/6_3_9.jpg)

<p class="caption" id="figRegistoCodificacaoEpisodios">Exemplo do botão de Copiar Codificação</p>

Quando pressionado o botão de **Copiar Codificação** este usa a última sessão válida codificada e copia a codificação dessa para o episódio em que o utilizador se encontra atualmente. No caso de haver mais que uma sessão codificada, o sistema vai buscar a última sessão codificada válida.



