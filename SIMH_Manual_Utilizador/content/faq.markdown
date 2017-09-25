---
layout: default
title: "FAQ's"
---


---

<div id="faq"></div>

# FAQ's

<p class="faq"> 1. Porque não aparecem alguns episódios na pesquisa? </p>
 
Existem três hipóteses para que o episódio não surja no SIMH:

* **Hipótese 1:** O episódio em causa já se encontra codificado no WEBGDH.
* **Hipótese 2:** O episódio em causa não reúne as condições necessárias para ser codificado.
* **Hipótese 3:** Os episódios poderão não estar a integrar no SIMH, ou poderá não ser possível proceder com a codificação de episódios, devido à incongruência de informação no SONHO e no SIMH.
<br>
No seguinte ficheiro <a href="./file/SIMH_IntegraçãoSONHO.pdf">Integração SIMH-SONHO</a> podem consultar detalhadamente quais as possiveis razões de o episódio não aparecer no SIMH.
<br>
É de fazer notar que **nos mapeamentos os códigos deverão mapear um ou mais códigos do sonho para apenas um no SIMH, não sendo possível mapear um código do sonho para mais que um do SIMH.**
<br>
<br>
<p class="faq"> 2. Porque as imagens aparecem desformatadas? Porque não consigo pesquisar? </p>

Valide se a versão do browser que está a ser usada é a correta para o uso da aplicação. Essa informação consta na página de login no fim da mesma:

![figGestaoEspecialidades](img/pages/browsersCompativeis.jpg)

<p class="caption" id="figBrowsersCompativeis">Descrição dos Browsers Compativeis com a Aplicação</p>

<br>
<br>

<p class="faq"> 3. O que fazer quando o médico codificador não está no Registo Nacional de Profissionais? </p>

Existem, na aplicação, duas maneiras de criar um médico codificador: 

* Através da associação do mesmo pelo RNP (módulo [Médicos Codificadores](#gestaoMedicos)) **OU**
* Na [Gestão Utilizadores](#gestaoUtilizadores). 

**A TER EM CONTA:** 

* **Apenas deverão criar o Médico Codificador NUM dos módulos acima referidos e não em ambos.**
* **Apenas deverão criar um médico no módulo da Gestão de Utilizadores no caso de não conseguirem no módulo Médicos Codificadores (por não se encontrar inscrito no RNP, por exemplo).** 
* **No caso de o médico não estar inscrito no RNP, deverão então criá-lo na Gestão de Utilizadores. Para tal, coloquem o tipo de utilizador como “Utilizador Médico Codificador” e não como “Utilizador Aplicacional” ou o sistema não deixará que o mesmo codifique episódios.**

<br>
<p class="faq"> 4. Como imprimir o Manual de Utilizador? </p>

*	No browser que estiver a utilizar, escolher a opção de imprimir, como mostra o exemplo abaixo:

![figGestaoEspecialidades](img/pages/imprimirManual1.png)

<p class="caption" id="figImprimirManual1">Passo 1 para Imprimir o Manual</p>

*	Irá abrir uma janela, que deverá ter a opção Print to PDF (ou semelhante):

![figGestaoEspecialidades](img/pages/imprimirManual2.png)

<p class="caption" id="figImprimirManual2">Passo 2 para Imprimir o Manual</p>

*	Depois é só salvar o documento como PDF, e a partir daqui já poderá ser impresso

![figGestaoEspecialidades](img/pages/imprimirManual3.png)

<p class="caption" id="figImprimirManual2">Passo 3 para Imprimir o Manual</p>

**NOTA: O manual encontra-se ainda em constantes modificações, pelo que se guardar uma versão do mesmo deverá ter em conta que poderá estar desatualizada**
<br>
<br>
<p class="faq"> 5. O que fazer quando o mesmo episódio aparece no SIMH e no WEBGDH?  </p>

Existirão episódios codificados no WEBGDH que irão aparecer no SIMH para codificar devido a uma questão de sincronização com os dados do SONHO.

Caso alguns destes episódios surjam na pesquisa no SIMH, mas já estejam codificados no WEBGDH, deverão marcar estes episódios para **Não Codificável** no SIMH com a causa **Codificado em ICD9CM**.
<br>
<br>
<p class="faq"> 6. Porque é que não aparecem especialidades nos episódios de Cirurgia de Ambulatório?  </p>

Os episódios de cirurgia de ambulatório não possuem especialidade, uma vez que no SONHO não existe o novo código de serviço para os serviços dos episódios deste tipo, código esse, que indica qual a especialidade do serviço.
<br>
<br>
<p class="faq"> 7. Porque é que a Hora de Admissão dos episódios de HDI não corresponde à hora de entrada? </p>

A hora de admissão das sessões de HDI pode não ser preenchida no SONHO conforme necessitamos dela no SIMH, devido à definição de cada instituição sobre a hora da sessão e hora de entrada identificada no episódio. Depois de análise conjunta da ACSS e SPMS, a hora de admissão para estes episódios tornou-se um campo editável de forma a ser possível avançar com a codificação no SIMH.

<br>
<br>
<p class="faq"> 8. Como separar o conteudo do ficheiro .csv por colunas? </p>

Poderá consultar o guia em: <a href="./file/guias/FicheirosCSV-Excel.pdf">Ficheiro csv em colunas</a>

<br>
<br>
<p class="faq"> 9. Como juntar múltiplos ficheiros .csv num único ficheiro? </p>

Poderá consultar uma explicação em: <a href="./file/guias/Juntar múltiplos ficheiros CSV em um único ficheiro CSV.docx" download="Juntar múltiplos ficheiro csv"> Juntar múltiplos ficheiro csv</a>