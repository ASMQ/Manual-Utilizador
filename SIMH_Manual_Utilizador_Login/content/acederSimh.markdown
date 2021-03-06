---
layout: default
title: "Introdução"
---


---

# 1. Sobre este Manual

Este manual tem como objetivo ajudar o utilizador a interagir com o sistema de uma forma eficaz, dotando-o de todo o conhecimento necessário para a sua compreensão e uso. 
Este encontra-se organizado da seguinte forma:

- “Sobre este Manual”, o capítulo atual que descreve o conteúdo do manual, qual a sua organização e como pode ser consultado;
 
- “Tabela de  Acrónimos”, que contém todos os acrónimos usados ao longo deste manual e que permitirá familiarizar desde já o utilizador com determinadas abreviaturas apresentadas na aplicação;
 
- “Introdução”, onde é apresentado o sistema SIMH, qual o seu contexto e propósito,  incluindo os seguintes subcapítulos: 
	* “Objetivos do Sistema”, onde se descrevem os propósitos da utilização da aplicação informática;	 
	* “Conceitos básicos”, onde se explicam os principais conceitos que suportam a aplicação, concretamente conceitos tipo “navegação" no sistema, explicando o que se entende por isso;	 
	* “Instruções de acesso”, onde é descrito como o utilizador pode aceder ao sistema.
	 
- “Módulos do Sistema”, onde cada módulo principal do sistema será apresentado numa secção individual.
 
---
 
# 2. Tabela de Acrónimos

A tabela seguinte contém a descrição de várias siglas usadas ao longo do documento.

|  Sigla   |  Designação             													  	|	           
|----------|--------------------------------------------------------------------------------|
|  SIMH    |  Sistema de Informação para a Morbilidade Hospitalar 						  	|
|  ACSS    |  Administração Central do Sistema de Saúde									  	|
|  SPMS    |  Serviços Partilhados do Ministério da Saúde									|
|  SNS     |  Serviço Nacional de Saúde														|
|  GDH     |  Grupos de Diagnóstico Homogéneo												|
|  RNP     |  Registo Nacional de Profissionais              								|                                    
|  ICD9CM  |  International Classification of Diseases 9th revision Clinical modification 	|
| ICD10CM  |  International Classification of Diseases 10th revision Clinical modification 	|
| ICD10PCS |  ICD-10 Procedure Coding System          										|
| APR-DRG  |  All Patient Refined Diagnosis Related Groups									|
|  AP 27   |  GDH All Patient Refined Diagnosis Related Groups, versão 27					|
|  AP 21   |  GDH All Patient Refined Diagnosis Related Groups, versão 21					|
|  SI      |  Sistema de Informação															|           

---

# 3. Introdução

O Sistema de Informação para a Morbilidade Hospitalar (*SIMH*) é um projeto estruturante, para o sistema de informação de saúde, de consolidação das versões do sistema WebGDH, com vista a centralizar e melhorar os processos de codificação de episódios de internamento, de cirurgia de ambulatório e de ambulatório médico em GDH.

Objetivos do Sistema:

* Consultar e codificar episódios de internamento, de cirurgia de ambulatório e de ambulatório médico em GDH;
* Maior celeridade e facilidade no processo de codificação de episódios, por parte dos organismos utilizadores e na manutenção e gestão do sistema;
* Dispor de uma única solução central ao nível aplicacional e de armazenamento de dados, transversal a todas as entidades hospitalares, através da consolidação das versões WebGDH;
* Dispor de uma solução mais robusta, rápida, segura e compatível com diversos dispositivos (incluindo móveis);
* Reduzir os custos de manutenção evolutiva;
* Otimizar a gestão dos recursos disponíveis.

---

# 4. Conceitos Básicos

Associada à interação com o sistema existe um conjunto de conceitos para os quais é chamada a atenção neste Capítulo.
Todos os formulários que permitem a criação ou edição de dados têm um conjunto de regras de negócio e validações para facilitar o preenchimento correto dos dados.
Para auxiliar as validações existem 4 tipos de mensagens:

* Mensagem de Informação

![logo](img/informacao.jpg)

* Mensagem de Alerta

![logo](img/alerta.jpg)

* Mensagem de Erro

![logo](img/erro.jpg)

* Mensagem de Sucesso

![logo](img/sucesso.jpg)

No cabeçalho das páginas do *SIMH* existe um conjunto de dados que serve para informação/contextualização do utilizador:

* Nome do utilizador;
* Nome da entidade hospitalar, caso exista, associada ao utilizador;
* Botão das opções avançadas ![logo](img/definicao.png). Ao clicar neste, o utilizador tem acesso a um conjunto de opções relativas ao perfil do utilizador, como por exemplo alterar password ([4.2. Alteração da senha](#alterao-da-senha)) ou as folhas de codificação para internamento e ambulatório;
<img id="figDefinicaoEntradas" src="img/pages/4_1.jpg" style="display:block; margin:auto;"/>
* Botão de acesso rápido ao manual de utilizador ![logo](img/manual.jpg);
* Contexto de navegação atual do utilizador, presente na barra *breadcrumbs* ![logo](img/breadcrumbs.jpg), que são clicáveis se o utilizador pretender voltar a uma página já navegada.

De seguida, apresenta-se como decorre a primeira interação do utilizador com a aplicação.

## 4.1. Aceder ao SIMH

O acesso ao SIMH é realizado através da navegação ao endereço em <http://simh.min-saude.pt/SIMH/>. Ao aceder irá surgir a página que aparece na [](#figLogin).

![figLogin](img/pages/4_1_1.jpg)

<p class="caption" id="figLogin">Página de acesso do SIMH </p>

Aqui, o utilizador deve inserir as suas credenciais nos campos obrigatórios e clicar em **Avançar**.

|    |  Campos Obrigatórios [](#figLogin)  															|	           
|----|----------------------------------------------------------------------------------------------|
| a) | Nome de utilizador (utilizador do RNP ou o utilizador criado na aplicação SIMH)  			|
| b) | Password								  														| 

> Os médicos registados na plataforma RNP podem entrar no SIMH com as credenciais da mesma. Apenas é necessário que o administrador da entidade hospitalar a que o médico pertence, faça a associação desse médico à sua entidade. Uma vez realizado, o médico ficará com o perfil de médico codificador e fica habilitado a entrar no SIMH (ver capítulo [8. Médicos Codificadores](#gestaoMedicos) para mais informações).
> Os restantes utilizadores, devem ser primeiro criados conforme descrito no capítulo [5. Gestão de Utilizadores](#gestaoUtilizadores).

Caso o utilizador, por algum motivo, necessite de uma nova senha gerada pelo sistema, deverá clicar em **Recuperar Senha**.

![figLoginRecuperacao](img/pages/4_1_2.jpg)

<p class="caption" id="figLoginRecuperacao"> Recuperação da Senha </p>
De seguida, deverá preencher os campos obrigatórios do formulário e clicar em **Enviar**.  

|    |  Campos Obrigatórios [](#figLoginRecuperacao)  											|	           
|----|------------------------------------------------------------------------------------------|
| a) | Nome de utilizador (utilizador do RNP ou o utilizador criado na aplicação SIMH) 			|

Serão enviadas as intruções de recuperação de password para o e-mail associado ao utilizador introduzido no campo.

Uma vez identificado e autenticado, é apresentada ao utilizador a página de entrada do *SIMH* ([](#figPaginaEntrada)), onde este pode aceder às funcionalidades que lhe estão disponíveis.

![figPaginaEntrada](img/pages/4_1_3.jpg)

<p class="caption" id="figPaginaEntrada"> Página de entrada no SIMH </p>
 
Dentro de cada módulo é possível aceder aos restantes menus bastando para isso clicar no logotipo da aplicação, no canto superior esquerdo, e selecionar o módulo para onde se deseja transitar, tal como ilustrado na [](#figMudaModulo).

![figMudaModulo](img/pages/4_1_4.jpg)

<p class="caption" id="figMudaModulo">Transição entre módulos</p> 
 
Na primeira vez que o utilizador acede a aplicação, aparecerá a página para alterar a sua senha ([4.2. Alteração da senha](#alterao-da-senha)).
O utilizador pode sair do sistema a qualquer momento, bastando para isso clicar no botão **Terminar Sessão** ![logo](img/logout.jpg).

<div id="alteraPassword"></div>

## 4.2. Alteração da senha

A qualquer momento, o utilizador pode fazer a alteração da sua senha, clicando no botão das opções avançadas situado no canto superior direito da página (ver [4.Conceitos Básicos](#conceitos-bsicos)). 
Após clicar em **Alterar Password** é apresentada uma página de alteração de senha, ver [](#figAlteraSenha).

![figAlteraSenha](img/pages/4_2_1.jpg)

<p class="caption" id="figAlteraSenha"> Página de alteração de senha </p>

O utilizador deverá preencher os seguintes campos obrigatórios:

|    |  Campos Obrigatórios [](#figAlteraSenha)  |           
|----|----------------------------------------------|
| a) |  senha utilizada atualmente            		| 
| b) |  nova senha pretendida                 		|  
| c) |  repetição da senha pretendida         		|

Após o preenchimento dos campos, o utilizador deverá finalizar a alteração clicando em **Alterar**.