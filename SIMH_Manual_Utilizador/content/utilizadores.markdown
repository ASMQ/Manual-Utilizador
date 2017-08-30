---
layout: default
title: "Gestão de Utilizadores"
---


---

<div id="gestaoUtilizadores"></div>

# 5. Gestão de utilizadores

Através deste módulo é possível realizar a gestão de utilizadores pertencentes a uma entidade hospitalar. 

Esta gestão apenas está acessível a um utilizador que detenha o perfil de **administrador da entidade hospitalar** onde exerce funções.

Para isso, o utilizador deve, a partir da página inicial, ao módulo de “Gestão de Utilizadores”, tal como ilustra a [](#figAcessoGestaoUtilizadores).

![figAcessoGestaoUtilizadores](img/pages/5_1.jpg)

<p class="caption" id="figAcessoGestaoUtilizadores">Módulo de Gestão de Utilizadores.</p>

Ao aceder a este módulo, aparecerá a seguinte página:

![figGestaoUtilizadores](img/pages/5_2.jpg)

<p class="caption" id="figGestaoUtilizadores">Página de Gestão de Utilizadores.</p>

Aqui, é possível realizar três ações distintas: **Criação**, **Pesquisa** ou **Edição** de utilizadores. 

<div id="criarUtilizadores"></div>

## 5.1 Criação de utilizadores

Para criar novos utilizadores, o utilizador com perfil de administrador deve clicar no botão **Criar**, tal como a [](#figAcessoCriarUtilizadores) ilustra.

![figAcessoCriarUtilizadores](img/pages/5_1_1.jpg)

<p class="caption" id="figAcessoCriarUtilizadores">Página de criação de novos utilizadores.</p> 

Atenta-se que o administrador de uma entidade hospitalar apenas pode criar novos utilizadores para essa mesma entidade.

Ao clicar neste botão aparecerá a página de **Criar Utilizador** (ver [](#figCriarUtilizadores)).

![figCriarUtilizadores](img/pages/5_1_2.jpg)

<p class="caption" id="figCriarUtilizadores">Página de Criação de Utilizadores </p>

Para a criação de um utilizador devem ser preenchidos os seguintes campos obrigatórios:

|    |  Campos Obrigatórios [](#figCriarUtilizadores)				| 		|    
|----|--------------------------------------------------------------|-------|
| a) |  Tipo Utilizador       		                				|		|
| b) |  Nome       		                							|		|
| c) |  Nº Mecanográfico                   							|		|
| d) |  Nº Ordem dos Médicos (apenas Utilizador Médico Codificador) |		|
| e) |  Auditor (apenas Utilizador Médico Codificador) 				|		|
| f) |  E-mail				              							|		|
| g) |  Perfil 									 					| 		|
	
Os tipos de utilizador disponíveis para novos utilizadores são:

* **Utilizador Aplicacional** - Permite a este utilizador aceder como administrativo ou administrador da entidade. Quando selecionado, o campo perfil é obrigatório.
* **Utilizador Médico Codificador** - Permite a este utilizador aceder como médico da entidade hospitalar tornando-o responsável pela codificação de episódios. Quando selecionado, os campos Nº Ordem dos Médicos e Auditor são obrigatórios.

Os perfis disponíveis para novos utilizadores são:

* **Administrativo da Entidade** - Trabalhadores que pertencem a uma entidade hospitalar. Podem codificar episódios mas não são os responsáveis pela codificação de um episódio;
* **Médico Codificador** - Médico codificador com as permissões de auditar e finalizar episódios.
* **Médico Codificador que não finaliza** - Medico codificador que não tem permissões para finalizar episódios.

No final da edição, o administrador deve clicar no botão **Criar** para completar a criação de um novo utilizador.

<div id="pesquisaUtilizadores"></div>

## 5.2 Pesquisa de utilizadores

Para consultar por utilizadores existentes na entidade hospitalar, deve-se clicar no botão **Pesquisar**, tal como a [](#figAcessoPesquisarUtilizadores) ilustra.

![figAcessoPesquisarUtilizadores](img/pages/5_2_1.jpg)

<p class="caption" id="figAcessoPesquisarUtilizadores">Página de Criação de Utilizadores. </p>

Atenta-se que o administrador de uma entidade hospitalar apenas pode pesquisar por utilizadores que pertençam à sua entidade hospitalar.

Adicionalmente, os utilizadores a pesquisar podem ser filtrados por nome de utilizador, perfil ou estado.

Os perfis disponíveis para pesquisa são:

* **Administrativo** - Trabalhadores que pertencem a uma entidade hospitalar. Podem codificar episódios mas não são os responsáveis pela codificação de um episódio;
* **Consulta** - Utilizadores associados a uma determinada entidade hospitalar com permissão de consultar episódios;
* **Médico Codificador** - Médico que codifica episódios.
* **Médico codificador sem permissões para finalizar** - médico que codifica episódios mas não os poderá finalizar.

Os estados disponíveis para pesquisa são:

* **Ativo** - Utilizadores que pertencem à entidade e que podem aceder ao sistema.
* **Bloqueado** - Utilizadores que pertencem à entidade e que foram bloqueados de aceder ao sistema.

A [](#figPesquisaUtilizadores) representa um exemplo de uma pesquisa de utilizadores efetuada por um administrador de um hopsital, designado de Hospital Teste, EPE:

![figPesquisaUtilizadores](img/pages/5_2_2.jpg)

<p class="caption" id="figPesquisaUtilizadores">Pesquisa de utilizadores de uma entidade hospitalar.</p>

<div id="editarUtilizadores"></div>

## 5.3 Edição de utilizadores

Após efetuar uma pesquisa por utilizadores ([5.2. Pesquisa de utilizadores](#pesquisa-de-utilizadores)) e ao selecionar um utilizador devolvido pela mesma ([](#figPesquisaSeleccaoUtilizadores)),

![figPesquisaSeleccaoUtilizadores](img/pages/5_3_1.jpg)

<p class="caption" id="figPesquisaSeleccaoUtilizadores">Pesquisa e seleção de um utilizador</p>

as opções seguintes opções tornam-se disponíveis:

* **Editar** - Permite a edição dos dados referentes ao utilizador selecionado;
* **Remover** - Permite remover o utilizador selecionado do sistema;
* **Ativar** - Permite ativar o acesso ao sistema do utilizador de selecionado, caso ele esteja bloqueado. Encontra-se inativa se o utilizador selecionado já estiver ativo;
* **Bloquear** - Bloqueia o acesso ao sistema do utilizador selecionado, caso ele esteja ativo. Encontra-se inativa se o utilizador selecionado já estiver bloqueado.

A [](#figEdicaoUtilizadores) ilustra como exemplo a página de edição dos dados referentes a um utilizador, após o administrador o ter selecionado e clicado no botão **Editar**.

![figEdicaoUtilizadores](img/pages/5_3_2.jpg)

<p class="caption" id="figEdicaoUtilizadores">Edição de um utilizador</p>
