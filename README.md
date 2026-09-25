# 💸 App de Organização de Finanças Pessoais com Vibe Coding

Uma experiência de desenvolvimento utilizando **Inteligência Artificial como parceira na construção de um produto**, explorando o conceito de **Vibe Coding**.

Neste projeto, utilizei ferramentas como **GitHub Copilot, ChatGPT e Lovable** para transformar uma ideia inicial em um aplicativo de organização financeira pessoal.

O objetivo foi experimentar uma nova forma de construir software: utilizando **linguagem natural, contexto, refinamento de ideias e interação contínua com a IA** para transformar requisitos em uma solução funcional.

---

# ✨ O que é Vibe Coding?

**Vibe Coding** é uma abordagem de desenvolvimento em que a Inteligência Artificial participa ativamente do processo de criação do software.

Em vez de escrever cada parte da solução manualmente, o desenvolvedor descreve o que deseja construir utilizando linguagem natural, fornecendo contexto, requisitos e objetivos. A IA então ajuda a transformar essas ideias em código, interfaces, funcionalidades e soluções.

Na prática, o processo se torna uma conversa:

> **Eu apresento a ideia, a IA ajuda a transformá-la em uma solução e, juntos, refinamos o resultado.**

Isso não significa deixar toda a responsabilidade para a IA. É necessário saber **explicar o problema, avaliar as respostas, identificar erros, fazer ajustes e tomar decisões sobre o produto**.

Por isso, clareza, comunicação e capacidade de avaliar o resultado continuam sendo fundamentais.

---

# 🎯 O Desafio

O desafio proposto foi desenvolver um **App de Organização de Finanças Pessoais utilizando IA**, explorando uma experiência mais simples e natural para o controle financeiro.

### Problema

Muitas pessoas têm dificuldade em manter um controle financeiro porque aplicativos tradicionais podem exigir uma quantidade significativa de entradas manuais, além de apresentarem informações que nem sempre são fáceis de interpretar.

A proposta é reduzir essa complexidade utilizando **conversação e Inteligência Artificial**.

Em vez de depender exclusivamente de formulários, o usuário pode interagir com um agente financeiro utilizando linguagem natural para registrar informações, consultar seus dados e receber análises sobre sua situação financeira.

### Objetivo

Criar uma aplicação capaz de ajudar o usuário a:

- Registrar receitas e despesas;
- Organizar suas movimentações;
- Acompanhar limites de gastos;
- Controlar dívidas;
- Criar metas financeiras;
- Acompanhar investimentos;
- Visualizar sua situação financeira;
- Receber insights baseados em seus dados;
- Interagir com um agente de IA através de linguagem natural.

---

# 🧠 Processo de Desenvolvimento

O desenvolvimento foi dividido em etapas, utilizando diferentes ferramentas de IA em cada momento do projeto.

A ideia não foi simplesmente gerar a aplicação de uma única vez, mas utilizar as IAs para **entender, estruturar, refinar e construir o produto**.

## 1. Construção do PRD

O primeiro passo foi transformar a ideia inicial em um **Product Requirements Document (PRD)**.

Utilizei o **GitHub Copilot** como ponto de partida para estruturar os requisitos do produto. A partir das primeiras respostas, fui refinando as funcionalidades e tomando decisões sobre a experiência que gostaria de oferecer.

Depois, utilizei o **ChatGPT** para revisar o PRD, identificar pontos que poderiam ser melhor definidos e organizar melhor a estrutura do produto.

Durante esse processo, algumas decisões também foram alteradas.

Por exemplo, inicialmente a ideia era concentrar grande parte da experiência no chat. Após analisar melhor o produto, decidi separar algumas responsabilidades:

- **Chat:** registrar movimentações e conversar com o agente;
- **Dashboard:** apresentar a situação financeira atual;
- **Insights:** apresentar análises e padrões identificados;
- **Notificações:** apresentar alertas importantes;
- **Investimentos:** acompanhar a carteira e informações relacionadas;
- **Metas, limites e dívidas:** organizar aspectos específicos da vida financeira.

### Prompt inicial utilizado

O modelo abaixo foi utilizado como ponto de partida e posteriormente adaptado conforme os requisitos e decisões tomadas durante as conversas com as IAs:

```txt
# Contexto
Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas com o usuário.  
A ideia é facilitar o controle financeiro de forma simples e natural, sem formulários manuais ou planilhas complexas.

# Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e pouca personalização.  
Quero resolver isso com uma experiência de conversa e recomendações automáticas de economia.

# Público-Alvo
Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação, principalmente iniciantes.

# Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural.
2. Classificar automaticamente as transações.
3. Definir e acompanhar metas financeiras.
4. Receber dicas de economia do “Agente Financeiro”.
5. Visualizar relatórios simples e personalizados.

# Entregável da IA
Gerar um plano de MVP com as principais telas, recursos necessários e um esboço de validação inicial.
Usar tom educativo e linguagem acessível, em português.
```
O PRD foi posteriormente ampliado e refinado antes de ser utilizado como base para a construção da aplicação.

---
## 2. Construindo a aplicação com o Lovable

Com o PRD estruturado e revisado, utilizei o Lovable para transformar os requisitos em uma aplicação funcional.

O PRD e as decisões tomadas durante a etapa anterior foram utilizados como base para criar o prompt de construção da aplicação.

Durante essa etapa, o Lovable foi orientado a implementar as principais partes do produto, incluindo:

- Dashboard financeiro;
- Chat com agente de IA;
- Registro de movimentações;
- Categorias;
- Limites de gastos;
- Insights financeiros;
- Autenticação;
- Interface responsiva.

A construção não aconteceu completamente de uma única vez.

O Lovable inicialmente implementou parte das funcionalidades e deixou algumas áreas indicadas como **“Em breve”**. Após uma nova interação, solicitei que as funcionalidades restantes fossem implementadas.

---

## 3. Resultado

O resultado foi uma aplicação de organização financeira com uma interface moderna e intuitiva.

O usuário consegue visualizar sua situação financeira através do dashboard e utilizar o chat para interagir com o agente.

Entre as funcionalidades implementadas estão:

### Dashboard

Apresenta um resumo da situação financeira do usuário, incluindo informações como:

- Saldo;
- Receitas;
- Despesas;
- Investimentos;
- Dívidas;
- Alertas e informações relevantes.

### Chat com IA

Permite interagir com o agente utilizando linguagem natural.

Exemplos:

> “Recebi R$ 2.500 de salário.”

> “Gastei R$ 90 com delivery.”

> “Quanto eu gastei esse mês?”

A ideia é tornar o registro e a consulta de informações mais naturais do que o preenchimento de diversos formulários.

### Movimentações

Área destinada ao acompanhamento das receitas e despesas registradas.

### Metas

Permite acompanhar objetivos financeiros.

### Dívidas

Área destinada ao acompanhamento de valores devidos.

### Investimentos

Área destinada ao acompanhamento dos investimentos e da carteira.

### Insights

Apresenta análises sobre os dados financeiros do usuário.

### Notificações

Centraliza alertas e informações que podem exigir atenção do usuário.

---

# 🔐 Autenticação

Durante a construção da aplicação, o Lovable também implementou autenticação utilizando Google.

Para acessar o aplicativo, o usuário pode realizar o login com sua conta Google e precisa concluir a confirmação solicitada no Gmail.

Essa funcionalidade não estava entre os principais requisitos que eu havia definido inicialmente, mas acabou sendo incorporada à aplicação durante o processo de construção.

---

## 4. Avaliação do Resultado

Após a aplicação ser construída, foi feita uma análise comparando o resultado com os requisitos definidos no PRD.

De forma geral, o resultado visual e funcional ficou próximo do que havia sido planejado.

Porém, também foram identificadas algumas limitações na implementação atual.

### ✅ O que funcionou bem?

As funcionalidades principais foram implementadas e a aplicação apresentou uma interface agradável, moderna e intuitiva.

O Lovable conseguiu transformar os requisitos descritos no PRD em uma aplicação visualmente consistente, com uma estrutura de navegação próxima da planejada.

Também foi interessante observar que a ferramenta conseguiu implementar funcionalidades que não estavam originalmente detalhadas em profundidade, como a autenticação utilizando Google.

A experiência mostrou que uma descrição clara do produto ajuda bastante a IA a compreender o contexto e produzir um resultado mais próximo do esperado.

---

### ⚠️ O que não funcionou como esperado?

O Lovable não implementou todas as funcionalidades solicitadas no primeiro momento.

A aplicação foi construída de forma incremental e algumas funcionalidades inicialmente ficaram disponíveis apenas como áreas indicadas com **“Em breve”**.

Após uma nova interação solicitando a implementação dessas funcionalidades, o Lovable conseguiu avançar e completar boa parte do que havia sido solicitado.

Outro ponto identificado foi a integração entre o Chat e algumas funcionalidades do sistema.

Atualmente, algumas informações registradas através do Chat são tratadas apenas como movimentações básicas.

Por exemplo, ainda existem limitações para:

- Criar uma dívida diretamente através do Chat;
- Criar uma meta através do Chat;
- Criar um investimento através do Chat;
- Atualizar automaticamente uma dívida a partir de uma movimentação relacionada;
- Atualizar automaticamente uma meta a partir de novas movimentações;
- Refletir determinadas movimentações diretamente na carteira de investimentos.

Ou seja, a interface apresenta essas funcionalidades, mas a integração entre elas e o agente de IA ainda não está completamente implementada.

---

## 5. O que aprendi sobre conversar com IAs?

O principal aprendizado foi perceber que a qualidade da comunicação influencia diretamente o resultado obtido com a IA.

Quanto mais claro estiver o problema, maior a chance de a IA compreender corretamente o que precisa ser construído.

Também percebi que não é necessário saber exatamente como resolver um problema antes de conversar com a IA. Podemos utilizar a própria IA para ajudar a:

- Estruturar uma ideia;
- Identificar requisitos;
- Encontrar problemas;
- Fazer perguntas;
- Comparar alternativas;
- Melhorar um PRD;
- Dividir uma tarefa complexa em partes menores.

Outro aprendizado importante foi entender a necessidade de dividir problemas grandes em etapas menores.

Quando uma aplicação possui muitas funcionalidades, pedir que a IA construa tudo de uma vez pode fazer com que algumas partes sejam ignoradas ou implementadas de maneira incompleta.

Trabalhar de forma incremental permite analisar cada resultado, identificar problemas e orientar melhor a próxima etapa.

---

## 6. Próximos passos

Embora o desafio tenha sido concluído, existem funcionalidades que podem ser evoluídas futuramente.

Entre elas:

- Integrar completamente o Chat às funcionalidades de dívidas, metas e investimentos;
- Permitir criação e atualização dessas entidades através de linguagem natural;
- Aprimorar os insights gerados pela IA;
- Adicionar mais automações;
- Melhorar os relatórios financeiros;
- Integrar dados reais de investimentos;
- Explorar integrações com Open Finance;
- Implementar notificações mais inteligentes.

Essas melhorias poderiam transformar o protótipo atual em uma solução financeira mais completa e integrada.

---

# 💬 Conclusão

Este projeto foi uma oportunidade de experimentar uma forma diferente de desenvolver software.

Mais do que construir um aplicativo de finanças, o desafio permitiu explorar como ferramentas de Inteligência Artificial podem participar de diferentes etapas do desenvolvimento: desde a definição do problema e dos requisitos até a construção da interface e das funcionalidades.

O maior aprendizado foi perceber que Vibe Coding não elimina a necessidade de pensar como desenvolvedor. Pelo contrário: quanto melhor conseguimos definir problemas, comunicar ideias, avaliar resultados e tomar decisões, melhor conseguimos utilizar a IA como ferramenta de desenvolvimento.

A ideia continua sendo humana. A IA ajuda a transformar essa ideia em algo real.

---

# 🛠️ Tecnologias e ferramentas

- **Lovable** — construção da aplicação
- **GitHub Copilot** — apoio na estruturação inicial do projeto e PRD
- **ChatGPT** — refinamento de requisitos, PRD e prompts

## Demonstração 

### Dashboard

### Chat com IA

### Movimentações 

### Investimentos

### Metas

# 📌 Projeto

Projeto desenvolvido como parte do desafio do curso de Produtos com IA / Vibe Coding da DIO.

O objetivo principal foi explorar o processo de criação de um produto utilizando Inteligência Artificial como parte ativa do desenvolvimento, desde a concepção da ideia até a construção da aplicação.
