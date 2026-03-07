# 💸 App de Finanças Pessoais Leandro Palavra com Vibe Coding

Este projeto foi desenvolvido com as premissas de um Desafio da DIO de Vibe Coding utilizando o Lovable e o Copilot web. A Proposta foi criar um APP de Finanças Pessoais para uma organização financeira pessoal, baseado em interações com linguagem natural.


# 🎯 PRD Escrito e Refinado

Segue o prompt final (PRD) usado com a IA para criar esse APP, pensando de uma maneira ampla e também criteriosa sobre alguns pontos. 

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

## 🎯  2. **Interações com o Lovable**

1. Interações

**Primeira Interação:** Foi a criação do PRD: {PRD Escrito e Refinado}

**Segunda Interação:** Teste o fluxo completo: faça login, registre o salário, envie gastos e receitas pelo chat, e verifique se tudo aparece no Dashboard, Potes e Relatórios

**Terceira Interação:** Adicione a funcionalidade de definir e acompanhar metas financeiras com barra de progresso e prazo


## 🎯  **Resultado Final do nosso APP**

**Acesse o prototipo no Lovable:** https://vibe-your-finances.lovable.app/

2. Segue o passo a passo de como acessar o App e suas funcionalidades:
   
![app fINANÇAS0](https://github.com/user-attachments/assets/a6cf7c35-dc30-42de-a417-c2528afbf9f1)
![app fINANÇAS1](https://github.com/user-attachments/assets/93de91b1-d19a-4d67-8407-f95fed5d3fa8)
![app fINANÇAS2](https://github.com/user-attachments/assets/5a5821b1-c424-4092-8871-892bb93e1def)
![app fINANÇAS3](https://github.com/user-attachments/assets/503cea88-2e64-4d0b-a09a-0d677547a713)
![app fINANÇAS4](https://github.com/user-attachments/assets/b944f5cf-6ac3-4b67-ae9d-aed0d36c300d)
![app fINANÇAS5](https://github.com/user-attachments/assets/e892683c-6351-403a-aba6-980394c7774e)
![app fINANÇAS6](https://github.com/user-attachments/assets/d9ad95eb-589f-4dd0-bd59-3b37e312a2b7)
![app fINANÇAS7](https://github.com/user-attachments/assets/4daf1af7-5505-4a61-a1db-d7dd94169f03)



## 🎯 3. **Resumo**


  - Esse App tem como objetivo fornecer clareza de gastos e receitas individuais ou familiar, com um diferencial, "os potes" (que são os valores que poupamos para gerenciar algumas atividades para a nossa saúde física, emocional e espiritual), eles nos dão uma visão de que podemos sim ter momentos de excelência, diversão e ainda aperfeiçoar o nosso conhecimento, com a certeza e conficção que os nosso recursos não serão afetados com isso. Visa também ter sugestões de investimentos de renda fixa e menos exigente em termos de conhecimento abrangemte.Você também pode criar algumas metas, que outrora não foram abrangidas nos potes. Fornecendo sempre os relatórios das Receitas e Despesas sempre que solicitada.
    
    # 📱 Aplicativo de Finanças Pessoais – Leandro Palavra

## 🔑 Funcionalidades Principais

### 1. Acesso e Autenticação
- Login seguro com usuário e senha.
- Botão **Sair** para encerrar sessão.

### 2. Registro de Receitas e Despesas
- Primeiro registro obrigatório: **salário ou receita principal** (exemplo: R$ 5.000,00).
- Inclusão de demais receitas (doações, caixinhas etc.).
- Registro de despesas via **chat em linguagem natural**, sem formulários.
- Classificação automática das transações.

### 3. Dashboard Financeiro
- **Saldo atual** visível logo na entrada.
- Indicadores de **Receitas, Despesas e Meta do mês**.
- Gráfico de **Receitas vs Despesas** para acompanhamento visual.
- Lista de **últimas transações** com composição da receita e despesas.

### 4. Metas e Organização
- Definição e acompanhamento de **metas financeiras mensais**.
- Sistema de **Potes** com percentuais pré-definidos para alocação automática:
  - 7% → Tempo com a Família  
  - 5% → Educação  
  - 5% → Diversão  
  - 8% → Eventualidades  
  - 10% → Investimento
- Botão específico para o **Pote Investimento**, com sugestões de onde poupar e valor acumulado.

### 5. Relatórios e Gráficos
- Relatórios simples e personalizados.
- Gráficos detalhados para visualizar cada gasto ou receita individualmente.
- Visão clara de entradas e saídas com datas e valores.

### 6. Assistente Financeiro
- Agente conversacional que sugere economias e dá dicas personalizadas.
- Linguagem acessível e educativa em português.

### 7. Design Universal
- Interface inclusiva e acessível para diferentes perfis de usuários.
- Experiência pensada para ser prática e confortável.

---

# 📊 Em resumo

O app combina **simplicidade (chat para registro)**, **organização automática (potes e categorização)** e **visualização clara (dashboard e relatórios)**, criando uma experiência fluida para quem quer começar a controlar suas finanças sem complicação.



## 🎯  4. **Reflexão**


  - Para mim foi algo tão elucidador, pois uma tecnolologia abriu minha mente para algumas outras vertentes que posteriormente colocarei em prática em relação a IA, pois, se podemos fazer agentes que possam criar e pesquisar de conteúdos específicos direcionados pelo nosso comando, podemos sanar muitas daquelas alucinações outrora geradas por causa da busca de um vasto universo de informação.
  - Estou muito feliz e contente com o resultado, sei que aos poucos vou melhorando e criando com mais leveza e muito mais especificidade. Agradeço a cada professor e a cada treinador por dedicar seu tempo e sua expertise para nos ensinar.
  - Em se tratando agora da IA, eu percebi, entendi e compreendi que ela pode ser de grande valia, tanto na sintese, quanto na explanação de uma ideia, lógico com a condução humana e com os objetivos e caminhos claros.
  - Essa interação do Copilot com o Lovable, acrescentou muito mais destreza naquilo que parecia não ter tanta vida, pois as criação das imagens deram uma nova dimensão para a ideia e par ao ideal.
  - Acredito que isso é apenas o começo, e que muito mais coisas iremos fazer e desenvovler com essa parceria.
  - Como é maravilhoso poder aprender, mesmo que a intencionalidade da nossa realidade diga ao contrário, pois a criatividade e a criação está em todo tempo para ser apresentada. Mais uma vez, obrigado.

# 📊 Considerações Finais

- Tudo que foi ensinado, mostrado e dito, nos leva a um novo patamar de não ficar paralisado naquilo que aprendemos, posi existem novos horizontes apresentados a cada amanhecer. Só quero agradecer a toda equipe DIO e a todos que proprocionaram isso. **O Senhor vos abençoe e vos guarde; o Senhor faça resplandecer o seu rosto sobre vós e tenha misericórdia de vós; o Senhor sobre vós levante o seu rosto e te dê a paz.** Obrigado. 

