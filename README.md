# iHealthFood
É um projeto de plataforma de negócio digital multilateral, envolve B2C e B2B, aberto, para demonstrar como desenvolver uma solução de delivery exclusiva para pessoas que possuem intolerância a glúten e lactose, baseado em experiências e fatos reais. Neste projeto enfatizamos o trabalho de **análise de requisitos** que deve ser feito para construção de software de valor.

![](http://www.etecnologia.com.br/images/fars/banner-ihealthfood.png)

# Visão do iHealthFood
**Para pessoas que tem intolerância a glúten e/ou lactose o iHealthFood é um serviço de entrega exclusivo através de aplicativo móvel e web, intuitivo, seguro e fácil de usar que oferece a possibilidade de encontrar os melhores restaurantes que fornecem comidas e pratos deliciosos sem glúten e sem lactose.Diferente de outros, nosso serviço é dedicado para clientes que se necessitam comprar alimentos sem glúten e sem lactose.**

# Desafios de Análise de Requisitos de Software:

O trabalho do Analista de Requisitos começa no momento que os artefatos: Visão do Serviço e Backlog do Serviço estão prontos, neste instante acontecerá um Workshop de Requisitos para descobrir os requisitos, entender as pessoas e negócio e especificar os requisitos. Contudo, antes do workshop os artefatos de negócio devem ser lidos e compreendidos, isso ajuda no entendimento do negócio, são eles:
- Business Story. Declaração do Problema 
- Modelo de Negócio. Mostra a lógica de negócio e a geração de valor do iHealthFood
- Business Value. Demonstra qual é valor de negócio que o iHealthFood deverá gerar.
- Mapa de Fluxo de Valor. Mostra quais as atividades devem ser feitas para garantir a geração de valor
- Regras de Negócio. Apresenta todas as regras de negócio que devem ser aplicadas ao iHealthFood

O workshop deve ser colaborativo, ou seja, participam o Dono de Negócio, Desenvolvedores e Testadores de forma ativa.
Objetivo primário é especificar todos os requisitos de software que farão partes das próximas Sprints. 
Para que você exercite suas habilidades de Análise de Requisitos de Software propomos 6 desafios 
apresentados abaixo:

**Desafio-1 – Identificação dos Requisitos que devem ser especificados. Você deve levar em consideração o nível de prioridade dos itens do Backlog.**
- Definir quais itens do Backlog de Serviço devem ser especificados.  

**Desafio-2 – Histórias do Usuário** 
- Escrever as histórias do usuário. 
<template>
Como <persona> posso <ação> 
para fazer meu <valor>.

Exemplo:
“Como cliente posso fazer “login” com e-mail e senha 
para fazer meu pedido.”

**Desafio-3 - Especificação de Requisitos (baseada em US e BDD)**
- Fazer a especificação dos requisitos 
<template> Estrutura de escrita dos cenários:

Funcionalidade: <nome da funcionalidade ou item do Backlog>
Ator: Cliente
Cenário: <descrição do cenário>
Given (Dado): <Estado inicial ou ponto de partida>
When (Quando) <Ação a ser realizada>
Then (Então) <Pós-condição, o que deve acontecer após a execução da ação>

<exemplo>
Funcionalidade: Fazer Login

Cenário: Fazer login com sucesso
Dado: Que entro na aplicação
Quando: Quando informo meu e-mail 
E: minha senha de acesso
Então: Recebo a autorização de acesso a App

E-mail	Senha	Resultado Esperado
Jose.ferreira@email.com
******	Autorizado (Login com sucesso)

Cenário: Fazer login com insucesso
Dado: Que entro na aplicação
Quando: Quando informo meu e-mail
E: minha senha de acesso
Então: Recebo a mensagem de erro <e-mail ou senha inválido>

E-mail |	Senha |	Resultado Esperado
-------|--------|
Jose.ferreira@email.com |
****** | Mensagem de erro

**Importante:**
Uma boa prática é sinalizar os itens do Backlog estão prontos para serem desenvolvidos. Por isso, após a especificação dos requisitos, os itens do Backlog correspondentes devem estar com status de DoR (Definition of Ready – Definição de Pronto).

