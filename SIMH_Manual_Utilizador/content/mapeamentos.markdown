---
layout: default
title: "Mapeamentos"
---


---
<div id="mapeamentos"></div>

# 11. Mapeamentos

Este módulo permite fazer a correspondência de mapeamentos, de acordo com os valores identificativos do sistema de informação fonte de cada entidade. Há que ter em conta que a integração de episódios no SIMH depende dos mapeamentos feitos pela entidade. Caso estes estejam incompletos, poderão não aparecer episódios no SIMH.

Para isso, o utilizador deve, a partir da página inicial, aceder ao módulo de “Mapeamentos”, tal como ilustra a figura [](#figAcessoMapeamentos).

![figAcessoMapeamentos](../img/pages/12_1.jpg)

<p class="caption" id="figAcessoMapeamentos">Módulo de Mapeamentos</p>

Ao aceder a este módulo, aparecerá a seguinte página:

![figMapeamentos](../img/pages/12_2.jpg)

<p class="caption" id="figMapeamentos">Página de Visualização de Mapeamentos</p>

Como é possível ver nesta figura, existe um separador para cada secção de Mapeamento, ou seja, é possível manipular os mapeamentos de cada uma das seguintes secções:

* **Destino Após Alta**

* **Unidade de Saúde**

* **Entidade Financeira Responsável**

* **Motivo Transferência**

* **Tipo de Programação**

Para além dos separadores, também existêm dois campos de pesquisa:

* **Código no SONHO**

* **Mapeamento no SIMH**

Estes poderão ser utilizados para filtrar os dados da tabela de Mapeamentos, que tal como indicam os nomes dos campos, poderão ser filtrados por Código no SONHO ou por Mapeamento no SIMH

Aqui, poderão ser realizadas três ações distintas: **Criar**, **Editar** ou **Remover** mapeamentos de acordo com o separador que o utilizador selecionar.
<br>
<br>
O link seguinte demonstra como utilizar esta funcionalidade:
<p style="text-align: center; font-weight: bold;"><a href="./file/Mapeamentos.mp4">Demonstração da Utilização da Página de Mapeamentos</a></p>

<div id="criarMapeamentos"></div>

## 11.1 Criar Mapeamentos

Ao selecionar o botão **Criar** o utilizador é enviado para o seguinte ecrã:

![figCriaMapeamentos](../img/pages/12_3.jpg)

<p class="caption" id="figCriaMapeamentos">Página de Criação de Mapeamentos</p>

Neste ecrã constam os seguintes campos:

* O Tipo de mapeamento que vem sempre preenchido de acordo com o separador selecionado.
* O Mapeamento no lado do SIMH - deverá escolher uma das opções disponíveis da lista fornecida.
* A tabela do Sonho à qual aquele tipo de mapeamento corresponde.
* O código do mapeamento na tabela de Sonho (COD_DESTINO).
* A descrição que se encontra na tabela do Sonho (DES_DESTINO).

Quando se pretende criar um mapeamento é necessário preencher os seguintes campos obrigatórios:

|    |  Campos Obrigatórios 										| 		|    
|----|--------------------------------------------------------------|-------|
| a) |  Mapeamento       		                					|		|
| b) |  COD_DESTINO		                  							|		|

No final da criação, o utilizador deve clicar no botão **Criar**, para completar a mesma.

<div id="editarMapeamentos"></div>

## 11.2 Editar Mapeamentos

Quando no ecrã da figura [](#figMapeamentos), o utilizador pode selecionar um mapeamento já criado da lista, clicando no elemento da tabela, como mostrado de seguida:

![figSelecionaMapeamentos](../img/pages/12_4.jpg)

<p class="caption" id="figSelecionaMapeamentos">Seleção de um Mapeamento</p>

Só assim é possível aceder à página de Edição de mapeamentos, que se revela da seguinte maneira:

![figEditaMapeamentos](../img/pages/12_5.jpg)

<p class="caption" id="figEditaMapeamentos">Página de Edição de Mapeamentos</p>

Os critérios de preenchimento são semelhantes ao da página de criação.
O sistema permite, ao editar um mapeamento, que estas alterações se reflitam nos episódios já modificados.
Ao selecionar a opção Sim do campo "Atualizar registos anteriores", a edição efetuada será aplicada a todos os episódios já modificados para trás. Caso selecione Não, o novo mapeamento só terá efeito a partir do momento da mesma.

Uma vez concluídas as alterações pretendidas no mapeamento em edição, o utilizador deve clicar no botão **Alterar**.

<div id="removerMapeamentos"></div>

## 11.3 Remover Mapeamentos

Para aceder a esta página deverá selecionar um elemento da lista e selecionar o botão **Remover**, sendo enviado para o seguinte ecrã:

![figRemoveMapeamentos](../img/pages/12_6.jpg)

<p class="caption" id="figRemoveMapeamentos">Página de Remoção de Mapeamentos</p>

Uma vez neste ecrã deverá selecionar o botão **Remover** para remover o mapeamento pretendido.
