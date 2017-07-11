---
layout: default
title: "Listagem de episódios"
---


---
<div id="Listagem de episódios"></div>

# 15. Listagem de episódios

O módulo "Relatórios" da plataforma SIMH permite ao utilizador obter inúmeras listagens de episódios dependente do filtro de pesquisa selecionado. A impressão destas listagens dos episódios estão disponíveis no formato PDF ("Lista Exaustiva" e "Resumo") e em Excel ("CSV"). O conteúdo presente em cada um destes tipos de impressões ("Lista Exaustiva", "Resumo" e "CSV") encontra-se descrito no capítulo 14 - Impressões do manual.
No campo de pesquisa da plataforma, o utilizador poderá obter uma listagem de episódios pelo prenchimento dos seguintes campos individuais: 

* **Estado ** 
* **Especialidade ** 
* **Médico Codificador ** 
* **Módulo ** 
* **Intervalo da data de alta ** 
* **Intervalo da data de codificação** 
* **Intervalo da data de auditoria** 
* **GDH** 
* **Tipo de GDH** 
* **Diagnóstico** 
* **Procedimento** 


Para uma filtragem de epósdios mais restrita, o utilizador poderá realizar uma combinação destes filtros de pesquisa. Caso de o utilizador pretenda obter uma listagem de episódos por diagnóstico, terá que digitar no campo de pesquisa o código pretendido, tal como se encontra ilustardo na figura         . De seguida, tal como se encontra mencionado no capítulo 14 - Impressões do manual, para ativar o botão de impressão, o utilizador deverá selecionar um espaço temporal inferior ou igual a 31 dias nos filtros de pesquisa. 

![figlistagemdiagnostico](img/listagemdiagnosticojpg) 

<p class="caption" id="figAcessoImprimir">Exemplo de obtenção de uma listagem de episódios por código de diagnóstico</p>






No modulo "Relatórios" existe o filtro de pesquisa por Diagnóstico. Este poderá ser utilizado para procurar episódios onde esteja presente o Diagnóstico procurado. De seguida,  tal como está indicado em https://simhspms.github.io/SIMH_REPO/SIMH_Manual_Utilizador/#impressoes,  para activar o botão de impressão,  o utilizador deverá escolher um intervalo de datas inferior ou igual a 31 dias nos filtros de pesquisa.







Apenas está acessível para os utilizadores que detenham o perfil de administradores e administrativos da entidade hospitalar onde exercem funções.
Para isso, o utilizador deve, a partir da página inicial, aceder ao módulo de “Finalizar Urgente”, tal como ilustra a figura [](#figAcessoFinalizarUrgente).

![figAcessoFinalizarUrgente](img/pages/10_1.jpg)   

<p class="caption" id="figAcessoFinalizarUrgente">Módulo de Finalizar Urgente</p>

Ao aceder a este módulo, aparecerá a seguinte página:

![figFinalizarUrgente](img/pages/10_2.jpg)

<p class="caption" id="figFinalizarUrgente">Página de Pesquisa do Episódio</p>

Nesta página terá de indicar o Nº Episódio e o Tipo de Episódio para que o sistema possa encontrar o episódio.
Este módulo pesquisa por qualquer episódio existente no sistema de informação fonte mesmo que ele ainda n esteja integrado no SIMH. Assim permite ao utilizador finalizar qualquer episódio que lhe seja urgente, colocando-o no SIMH e enviando o GDH para o SONHO.

Depois de selecionado o botão de **PESQUISAR**, será enviado para a página de codificação do episódio ([6.3. Edição de um episódio](#codificacao-edicao-de-episodios)) onde poderá concluir a codificação do episódio.

Após concluir o preenchimento dos dados do episódio, deverá seleccionar o botão **Finalizar Urgente** presente na página de Registo.

De seguida apresenta-se um vídeo de demonstração da utilização deste módulo: 
<p style="text-align: center; font-weight: bold;"><a href="./file/FinalizarUrgente.mp4">Demonstração da Utilização do Finalizar Urgente</a></p>


