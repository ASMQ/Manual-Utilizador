---
layout: default
title: "Impressoes"
---


---
<div id="impressoes"></div>

# 14. Impressões

A plataforma SIMH permite ao utilizador fazer a impressão de folhas de codificação dos episódios a apresentar nos resultados das pesquisas que existem em vários módulos da aplicação.
A impressão encontra-se atualmente disponível nos seguintes módulos:

* **Episódios**
* **Gestão de Processos** - É necessário selecionar nos filtros o estado **Por codificar**, **Rascunho** ou **Alterado SI**.
* **Relatórios**
* **Auditoria**

Para ativar o botão de impressão, **o utilizador deverá escolher um intervalo de datas inferior ou igual a 31 dias nos filtros de pesquisa**, demonstrado na figura seguinte:

![figAcessoImprimir](img/pages/15_1.jpg) 

<p class="caption" id="figAcessoImprimir">Exemplo de datas nos filtros do Módulo de Episódios</p>

Ao selecionar o botão **IMPRIMIR** o utilizador será enviado para a seguinte página:

![figImprimir](img/pages/15_2.jpg) 

<p class="caption" id="figImprimir">Página de Impressão de Episódios</p>

A lista de episódios está dividida em lotes de 100 episódios por ficheiro PDF. Foi necessário subdividir os ficheiros em lotes limitados de tamanho, para precaver a sobrecarga do sistema, caso contrário não seria possível gerar a informação pretendida.
Existem dois tipos de impressões:

* **Folha de Codificação Pré-Preenchida** - Contém apenas a informação administrativa do episódio, dando margem ao utilizador para preencher os restantes dados do episódio.
* **Lista Exaustiva** - Contém a lista de episódios com o preenchimento já proveniente do SIMH, ou seja, a lista de diagnósticos, de procedimentos, dispositivos médicos e alertas vêm de acordo com os dados inseridos no SIMH.
* **Ficheiro CSV** - Ficheiro no formato csv que contém informação detalhada sobre os episódios obtidos do filtro.
* **Resumo** - Contém a lista dos episódios obtidos da pesquisa com as informações básicas do episódio (Nº processo, Nº Episódio, Data Alta, Módulo, Médico Codificador, Especialidade, Estado e GDH). Este resumo pode ser retirado em formato EXCEL ou PDF. 
O formato em EXCEL esta presente na página de pesquisa como se pode ver na imagem seguinte:

![figImprimir](img/pages/15_3.jpg) 

<p class="caption" id="figImprimir">Página de Pesquisa com Simbolo da impressão de Resumo</p>

Estes tipos estão disponíveis de acordo com o módulo selecionado como transcreve a figura seguinte:

![figImpressao](img/impressao.png) 

<p class="caption" id="figImprimir">Tipos de Lista disponíveis para cada módulo</p>

Se o utilizador avançar para a última página da lista de impressão de episódios aparecerá a consulta do **RESUMO** dos episódios, como pode consultar na figura [](#figImprimir). 

Os dados presentes na Impressão vão variar com o módulo do SIMH em que se acede ao botão de **IMPRIMIR**.
<br>
<br>
O link seguinte demonstra como utilizar esta funcionalidade:
<p style="text-align: center; font-weight: bold;"><a href="./file/Impressoes.mp4">Demonstração da Utilização da Página de Impressão</a></p>