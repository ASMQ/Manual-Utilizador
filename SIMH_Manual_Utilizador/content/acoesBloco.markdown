---
layout: default
title: "Acoes Bloco"
---


---
<div id="acoesBloco"></div>

# 13. Ações em bloco

Este módulo tem como objetivo agilizar a mudança de estado dos episódios, permitindo-o fazer em bloco.

Para aceder, o utilizador deve, a partir da página inicial, aceder ao módulo de "Ações Bloco", tal como ilustra a figura [](#figAcessoAcoesBloco). 

![figAcessoAcoesBloco](img/pages/14_1.jpg) 

<p class="caption" id="figAcessoAcoesBloco">Módulo de Ações em Bloco</p>

Ao aceder a este módulo, aparecerá a seguinte página:

![figAcoesBloco](img/pages/14_2.jpg)

<p class="caption" id="figAcessoAcoesBloco">Página Inicial das Ações em Bloco</p>

Este módulo apenas pesquisa por episódios no estado de **Rascunho**, **Por Codifcar** ou **Em Auditoria**, permitindo as seguintes alterações:
O utilizador será obrigado a preencher sempre o filtro do **Estado**, poderá ou não selecionar um dos outros filtros.
Existe ainda o campo **"Alterar estado para"** de preenchimento obrigatório, onde o utilizador deverá selecionar o estado para a qual pretende alterar os episódios da lista de resultados, e **"Causa de não codificar"** para quando se pretende passar um episódio para Não Codificável. 

<table>
  <thead>
    <tr align="center">
      <th colspan="2">Alterações de Estados</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="border-bottom: none; border-right: none; border-left: 1pt solid rgb(0, 80, 130);"><strong>Estado Atual do Episódio</strong></td>
      <td style="border-bottom: none; border-right: none; border-left: 1pt solid rgb(0, 80, 130);"><strong>Alterações Possíveis do Episódio</strong></td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td style="border-bottom: none; border-right: none; border-left: 1pt solid rgb(0, 80, 130);">Rascunho</td>
      <td style="border-bottom: none; border-right: none; border-left: 1pt solid rgb(0, 80, 130);">Finalizar <br> Auditar</td>
    </tr>
    <tr>
      <td style="border-bottom: none; border-right: none; border-left: 1pt solid rgb(0, 80, 130);">Por Codificar</td>
      <td style="border-bottom: none; border-right: none; border-left: 1pt solid rgb(0, 80, 130);">Não Codificável</td>
    </tr>
    <tr>
      <td style="border-bottom: none; border-right: none; border-left: 1pt solid rgb(0, 80, 130);">Em_Auditoria</td>
      <td style="border-bottom: none; border-right: none; border-left: 1pt solid rgb(0, 80, 130);">Finalizar</td>
    </tr>
  </tbody>
</table>

**Há dois pontos importantes a ter em conta neste módulo:**

* Para que os episódios em rascunho apareçam na pesquisa, têm de ter passado nas validações quando foram criados, ou seja, têm de ser considerados rascunhos válidos.

* No caso de o utilizador pretender alterar o estado de **"Por Codificar"** para **"Não Codificável"**, terá de preencher a **Causa de Não Codificar**. A causa escolhida será aplicada a todos os episódios selecionados.
 
Após realizar a pesquisa, os resultados ficarão visíveis de acordo com a seguinte figura:

![figResultadosAcoesBloco](img/pages/14_3.jpg) 

<p class="caption" id="figResultadosAcoesBloco">Lista de Resultados das Ações em Bloco</p>

O passo seguinte é selecionar o estado a alterar, e assim todos os episodios ficarão com a respetiva alteração. 
De seguida, ao selecionar o botão **"Alterar em Bloco"** aparecerá uma página de confirmação, que como mostra a figura a seguir, contem a informações de quantos episódios serão alterados e para que estado passarão.

![figResultadosAcoesBloco](img/pages/14_5.jpg) 

Caso seja o pretendido poderá clicar no botão **"Alterar"** para finalizar as mudanças de estado. 

O utilizador poderá também consultar os detalhes de um determinado episódio. O botão **Consultar** ficará disponível ao selecionar um episódio da lista de resultados, como demonstra a seguinte figura.

![figDetalhesAcoesBloco](img/pages/14_4.jpg) 

<p class="caption" id="figResultadosAcoesBloco">Consulta de Episódios</p>

Quando selecionado o botão de consulta o utilizador é enviado para o detalhe do episódio ([6.2. Consulta de um episódio](#codificacao-consulta-de-episodios))
