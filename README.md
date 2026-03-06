# 💸 App de Organização de Finanças Pessoais com Vibe Coding

Aprenda a **criar soluções com IA** de forma criativa, guiando ferramentas como o **Copilot** e o **Lovable** com uma comunicação simples e natural. O foco é desenvolver o conceito de um **App de Organização de Finanças Pessoais**, mas, acima de tudo, aprender o **jeito Vibe de programar com IA**.

## ✨ O que é Vibe Coding

**Vibe Coding** é uma forma leve e criativa de desenvolver com IA, baseada em **conversas naturais e bem estruturadas**. Você não precisa escrever código linha por linha. Em vez disso, aprende a **guiar a IA** descrevendo suas ideias de forma clara, com **intenção e contexto**. Em outras palavras:

> Você mostra a vibe da sua ideia e a IA transforma em solução (ou em um caminho para ela).

## 🎯 Desafio

Problema: Muitas pessoas não conseguem manter um controle financeiro porque os aplicativos exigem muita entrada de dados manual, e a criação de orçamentos é vista como algo tedioso. 

Precisamos de uma solução que permita **controlar as finanças por meio de uma conversa simples**, com **agentes de IA** capazes de criar **planos de economia personalizados e automatizados**. Você deve utilizar as ideias de **Vibe Coding** e **MVP (Produto Mínimo Viável)** para desenvolver o **conceito de um aplicativo** que resolva o problema citado.

> [!IMPORTANT]
> Você **não precisa construir o código**! O foco está em **usar a IA como sua parceira criativa**, transformando boas ideias e prompts em conceitos funcionais que simulam um produto real.

## 🪄 Etapas do Desafio

### 1. Saber o que Pedir é a Chave! Otimize seus Prompts!

Antes de pedir para a IA "criar um app", é importante definir com clareza o que você quer construir e por quê. Para isso, você vai criar um **PRD (Product Requirements Document)** simplificado, uma especificação que serve como _briefing_ para a IA entender sua ideia.

Um bom PRD deve descrever o problema, quem será beneficiado, as principais funcionalidades e o que você espera que a IA entregue. Use o modelo abaixo como ponto de partida e adapte conforme o seu estilo:

```txt
Crie um app de Finanças Pessoais Leandro Palavra com base no seguinte PRD (Product Requirements Document): 
PRD – Aplicativo de Finanças Pessoais Leandro Palavra

Contexto
Criar um aplicativo de Finanças Pessoais que funcione por meio de conversas em linguagem natural.
O objetivo é simplificar o controle financeiro, eliminando formulários complexos e planilhas, oferecendo uma experiência fluida e acessível.

Problema
Muitos usuários desistem de controlar seus gastos porque:
- Os apps atuais exigem muita entrada manual.
- Há pouca personalização na experiência.

A solução proposta é um assistente financeiro conversacional, que registra gastos, sugere economias e ajuda a organizar metas de forma natural.

Público-Alvo
- Pessoas que desejam começar a organizar suas finanças sem complicação.
- Principalmente iniciantes que buscam praticidade e orientação simples.
- Usuários diversos, com diferentes níveis de familiaridade tecnológica, garantindo acessibilidade ampla.

Funcionalidades-Chave
1. Autenticação segura: dashboard com login e senha. 
2. Primeiro Registro a ser feito após o Logins tem que ser o Salário ou Valor de Receita Recebível.
3. Registro de gastos via chat: em linguagem natural. Atualizando os dados Receitas e Despesas automaticamente.
4. Classificação automática das transações.
5. Metas financeiras: definir e acompanhar objetivos.
6. Agente Financeiro: dicas de economia personalizadas.
7. Relatórios simples e personalizados: visão clara da situação financeira, com receitas (entradas) e Despesas (saídas) com suas respectivas datas e seus valores.
8. Sistema de “Potes” com seu nome especificado para alocação automática do salário inicial a ser incluso pelo usuário, como demais receitas e despesas:
   - 7% → Tempo com a Família
   - 5% → Educação
   - 5% → Diversão
   - 8% → Eventualidades
   - 10% → Investimento
9. Design Universal: interface e experiência pensadas para serem inclusivas, garantindo que o máximo de pessoas possa usar o app com conforto e eficiência.
10. O App tem que apresentar o valor zerado, para que haja a interação e a posterior inclusão de Receitas e Despesas.
11. Especificar Pote Investimento como Botão para sugerir onde poupar e o valor guardado.
12. Botão “SAIR” para deslocar o usuário do APP.

Entregável da IA
- Plano de MVP com:
  - Principais telas (login, chat, dashboard, relatórios).
  - Recursos necessários (chatbot, categorização automática, relatórios específicos e analíticos).
  - Validação inicial com usuários para feedback.
- Linguagem acessível e educativa em português.
- Aplicação dos princípios de Design Universal desde o início.


Podemos incluir nas aplicações, gráficos detalhados onde você possa enxergar cada gasto, ou cada receita individualmente. Como também, no chat, a inclusão ser feita na respectiva categoria, sem ter a necessidade de perguntar novamente. algo que seria interessante, podemos começar com um salário de R$5000,00 reais como salário, e receita Principal e depois, as demais receitas, como doações, caixinhas e demais recebimentos estivessem sendo incluídos no valor total de Receita.

```

Depois de preencher o modelo, use o Copilot Web para revisar e melhorar o seu prompt antes de ir ao Lovable. A ideia é lapidar o texto até que ele fique claro, direto e reflita exatamente a sua intenção.

> [!TIP]
> Pense no PRD/Prompt como “o briefing que a IA precisa para entender sua vibe”. Portanto, quanto mais claro e intencional for o texto, mais próximas do ideal serão as respostas da IA.

### 2. Explorando o Lovable na Prática

Com seu PRD pronto e revisado, é hora de colocar a IA em ação. Abra o Lovable, cole seu prompt completo e peça o plano inicial do MVP do seu aplicativo. Como o plano gratuito limita você a 5 interações por dia, seja estratégico:
- Faça perguntas diretas e construtivas, como “crie o fluxo de telas com base nas funcionalidades listadas” ou “gere uma versão resumida do plano de MVP”;
- Priorize clareza nas instruções para aproveitar ao máximo cada resposta;

Durante essa etapa, você pode orientar a IA para três entregas principais:
1. Agente Financeiro: defina o comportamento e o tom de voz de um consultor financeiro pessoal, alinhado ao público e objetivo do app.
2. Fluxo de Telas: peça à IA para gerar o fluxo conceitual de telas com base nas funcionalidades descritas no PRD, simulando a interação por conversa.
3. Plano de MVP: solicite um resumo das 5 funcionalidades principais, dos recursos necessários e um plano de validação inicial (como medir se o app cumpre seu propósito).

> [!TIP]
> Se preferir, você pode fazer tudo com o **Copilot**. O importante é exercitar a habilidade de transformar intenções em instruções claras e testar os limites da IA como parceira criativa.

### 3. Entregando o Desafio na DIO

Finalize seu projeto criando um **repositório no GitHub** (pode ser um **fork** deste).  
No README do seu repositório, inclua:

- Seu **prompt final** (PRD);  
- Prints ou pequenos vídeos das interações com a IA;  
- Um resumo do que o seu **App de Finanças Pessoais** faz;  
- Uma breve **reflexão sobre o processo**:
  - O que funcionou bem?  
  - O que não funcionou como o esperado?  
  - O que aprendeu sobre conversar com IAs?

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
