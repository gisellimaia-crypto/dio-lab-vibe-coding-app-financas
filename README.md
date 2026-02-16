# 📱 Aplicativo de Finanças Pessoais Conversacional - Finança Fácil

## 🎯 Objetivo
Este projeto tem como objetivo criar um aplicativo de **Organização de Finanças Pessoais** que funcione por meio de conversas em linguagem natural.  
A ideia é facilitar o controle financeiro de forma simples e prática, sem formulários manuais ou planilhas complexas.

---

## 🧩 Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e oferecem pouca personalização.  
Nosso app resolve isso com uma experiência conversacional e recomendações automáticas de economia.

---

## 👥 Público-Alvo
- Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação.  
- Principalmente iniciantes no controle financeiro.

---

## ⚙️ Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural.  
2. Classificar automaticamente as transações.  
3. Definir e acompanhar metas financeiras.  
4. Receber dicas de economia do “Agente Financeiro” (chatbot com IA).  
5. Visualizar relatórios simples e personalizados em dashboards.  
6. Botões de ação rápida com base nos recursos mais utilizados.  
7. Integração com API dos principais bancos.  
8. Upload de arquivos (planilhas/PDFs) com extratos e faturas para inserção automática.  
9. Notificações de metas e limites por categoria.  
10. Login via Google ou outras contas.  
11. Lembretes de pagamento de contas configuráveis.  

---

## 🎨 Design
- Estética simples e acessível.  
- Modo escuro disponível.  
- Paleta de cores diferenciada (evitar azul/verde padrão).  
- Linguagem educativa e acessível em português do Brasil.  

---

## 📊 Principais Telas
- Onboarding (objetivo inicial).  
- Chat Financeiro.  
- Metas.  
- Relatórios/Dashboard.  
- Dicas Personalizadas.  

---

## ✅ Finalidade
- Exercício do curso de IA na Prática DIO - CEF:  
  - Criação de app de finanças pessoais com Vibe Coding Colpilot + Lovable.  
 
---

## 💬 Prompts Utilizados

### Prompt de PRD inicial Copilot
```snipped
Estou criando um app de finanças pessoais voltado para pessoas que desejam economizar e organizar suas finanças mas não se adaptam a apps complicados e planilhas. 
Irei criar o MVP (minimal viable product) no Lovable.
Preciso do PRD (produc riquerement document). 

Minhas interações com o lovable são limitadas em razão do plano gratuito. Então, preciso que me ajude a criar o prompt para conseguir o melhor produto com o mínimo de interações possível com o Lovable. 

# Contexto
Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas com o usuário em linguagem natural.  
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
4. Receber dicas de economia do “Agente Financeiro” (chatbot com IA com dicas de economia  e instruções para o uso do app).  
5. Visualizar relatórios simples e personalizados com gráficos e dashboards.
6. Botões de ação rápida com base nos recursos mais utilizados pelo usuário.
7. Integração com API dos principais bancos.
8. Função de upload de arquivos (planilhas e pdfs) com extrato do banco e fatura do cartão de crédito, como foram de inserção de dados. Adicionar esses dados, classificar automaticamente (ex.: alimentação, contas, lazer, investimento, etc.) e criar relatórios e gráficos e usar como base para as dicas financeiras.
9. Definir metas e emitir notificações quando estiver perto da meta geral e por categoria (Ex. Você gastou 50% da meta de gastos deste mês. Você usou 80% do seu limite do cartão de crédito. Você usou 30% do seu limite de gastos com lazer.) Dar opção de realocar limite de uma categoria pra a outra. 
10. Aceitar login via google ou outras contas.
11. Emitir lembretes de pagamento de contas. (Ex. A conta de luz vence daqui a 2 dias. Agende o pagamento agora.) Com opção para o usuário escolher quantos dias antes deve emitir o lembrete (dia que recebe o salário, 5 dias antes do vencimento, etc.)

# Entregável da IA
Gerar um plano de MVP com as principais telas, recursos necessários e um esboço de validação inicial.  
Usar tom educativo e linguagem acessível, em português do Brasil e com design universal.
Estética simples, com opção de modo escuro, cores menos usadas por apps já existentes.
````

### Prompt de ajuste Copilot 1
```snipped
O lovable terminbou, mas Não consigo ver o botão para subir arquivos (planilhas e extratos e faturas). Também não consigo interagir com o app. Os botões de inserção de dados não funcionam e as interações com o chatbot não registram as informações. O que pode ser? como posso corrigir isso?
````

### Prompt de ajuste Copilot 2
```snipped
só me dê o prompt pedindo para o lovable corrigir os erros.
````

### Prompt de PRD incial Lovable
```snipped
Prompt para Lovable (PRD do MVP)
Título do Projeto:  
Aplicativo de Organização de Finanças Pessoais Conversacional

Objetivo:  
Criar um MVP que permita aos usuários organizar suas finanças de forma simples e prática, por meio de conversas em linguagem natural, sem depender de planilhas complexas ou entradas manuais extensas.

Problema a Resolver:  
Muitos usuários desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e oferecem pouca personalização. O objetivo é oferecer uma experiência fluida, conversacional e personalizada, com recomendações automáticas de economia.

Público-Alvo:  
Pessoas iniciantes no controle financeiro que desejam economizar e organizar suas finanças sem complicação.

Funcionalidades-Chave do MVP:

Registrar gastos via chat em linguagem natural.

Classificar automaticamente as transações (alimentação, transporte, lazer, contas, investimentos).

Definir e acompanhar metas financeiras (mensais e por categoria).

Receber dicas de economia do “Agente Financeiro” (chatbot com IA).

Visualizar relatórios simples e personalizados em dashboards com gráficos básicos.

Botões de ação rápida com base nos recursos mais usados pelo usuário.

Integração inicial com API de bancos (mesmo que em versão simulada).

Upload de arquivos (planilhas e PDFs de extratos/faturas) para inserção automática de dados e classificação.

Notificações de metas e limites (ex.: “Você gastou 80% do limite de lazer”).

Login via Google ou outras contas.

Lembretes de pagamento de contas com opção de configurar antecedência.

Design e Experiência:

Estética simples e acessível, com design universal.

Opção de modo escuro.

Paleta de cores diferenciada (evitar azul/verde padrão de apps financeiros).

Linguagem educativa e acessível em português do Brasil.

Principais Telas do MVP:

Onboarding (explicação rápida + definição de objetivo inicial).

Chat Financeiro (registro de gastos e interação com o Agente Financeiro).

Metas (definição e acompanhamento).

Relatórios/Dashboard (gráficos simples e insights automáticos).

Dicas Personalizadas (curtas e práticas).

Validação Inicial:

Teste com grupo piloto de 10–20 pessoas.

Métricas:

% de usuários que registram pelo menos 5 transações na primeira semana.

% que definem ao menos uma meta.

Feedback qualitativo sobre simplicidade e utilidade.
````

### Prompt de ajuste Lovable 1
```snipped
Corrija os seguintes problemas no meu MVP de Finanças Pessoais Conversacional:

Os botões de inserção de dados não estão funcionando — preciso que executem ações reais (ex.: registrar gasto, abrir upload).

O botão de upload de arquivos (planilhas, extratos, faturas) não aparece. Quero que seja visível e funcional.

As interações com o chatbot não registram informações. Preciso que o chat salve os dados inseridos pelo usuário em uma lista ou banco de dados simples.

Garanta que os relatórios e dashboards mostrem os dados registrados.

Ajuste para que os lembretes e notificações sejam disparados corretamente.

Mantenha o design simples, com modo escuro disponível, e preserve todas as funcionalidades descritas no PRD.
````

Desafio
# 💸 App de Finanças Pessoais: Finanças Fácil - Giselli Maia

Aprenda a **criar soluções com IA** de forma criativa, guiando ferramentas como o **Copilot** e o **Lovable** com uma comunicação simples e natural. O foco é desenvolver o conceito de um **App de Organização de Finanças Pessoais**, mas, acima de tudo, aprender o **jeito Vibe de programar com IA**.

## 🎯 Desafio

Problema: Muitas pessoas não conseguem manter um controle financeiro porque os aplicativos exigem muita entrada de dados manual, e a criação de orçamentos é vista como algo tedioso. 

Precisamos de uma solução que permita **controlar as finanças por meio de uma conversa simples**, com **agentes de IA** capazes de criar **planos de economia personalizados e automatizados**. Você deve utilizar as ideias de **Vibe Coding** e **MVP (Produto Mínimo Viável)** para desenvolver o **conceito de um aplicativo** que resolva o problema citado.

> [!IMPORTANT]
> Você **não precisa construir o código**! O foco está em **usar a IA como sua parceira criativa**, transformando boas ideias e prompts em conceitos funcionais que simulam um produto real.

## 🪄 Etapas do Desafio

### 1. Otimizear Prompts com ajuda do Copilot

Antes de pedir para a IA "criar um app", é importante definir com clareza o que você quer construir e por quê. Para isso, você vai criar um **PRD (Product Requirements Document)** simplificado, uma especificação que serve como _briefing_ para a IA entender sua ideia.

Um bom PRD deve descrever o problema, quem será beneficiado, as principais funcionalidades e o que você espera que a IA entregue.

### 2. Explorando o Lovable na Prática

Com seu PRD pronto e revisado, é hora de colocar a IA em ação. Abra o Lovable, cole seu prompt completo e peça o plano inicial do MVP do seu aplicativo. Como o plano gratuito limita você a 5 interações por dia, seja estratégico:
- Faça perguntas diretas e construtivas, como “crie o fluxo de telas com base nas funcionalidades listadas” ou “gere uma versão resumida do plano de MVP”;
- Priorize clareza nas instruções para aproveitar ao máximo cada resposta;

Durante essa etapa, você pode orientar a IA para três entregas principais:
1. Agente Financeiro: defina o comportamento e o tom de voz de um consultor financeiro pessoal, alinhado ao público e objetivo do app.
2. Fluxo de Telas: peça à IA para gerar o fluxo conceitual de telas com base nas funcionalidades descritas no PRD, simulando a interação por conversa.
3. Plano de MVP: solicite um resumo das 5 funcionalidades principais, dos recursos necessários e um plano de validação inicial (como medir se o app cumpre seu propósito).

### 3. Entregando o Desafio na DIO

Finalize seu projeto criando um **repositório no GitHub** (pode ser um **fork** deste).  
No README do seu repositório, inclua:

- Seu **prompt final** (PRD);  
- Prints ou pequenos vídeos das interações com a IA;
<img width="886" height="536" alt="image" src="https://github.com/user-attachments/assets/ae4f1019-e005-448d-8413-a23433f7eead" />
<img width="886" height="530" alt="image" src="https://github.com/user-attachments/assets/eb11ace7-f1e9-4b3f-bb04-8bed31d2cfdc" />
<img width="886" height="530" alt="image" src="https://github.com/user-attachments/assets/8e024c4f-904f-410f-b584-65532b7afa3e" />
<img width="886" height="511" alt="image" src="https://github.com/user-attachments/assets/5400fffe-c6d0-42b3-a477-ee6a30dcfad9" />
<img width="886" height="530" alt="image" src="https://github.com/user-attachments/assets/4b85df2c-bcef-4dda-8ad5-864b9bb1727d" />
<img width="886" height="511" alt="image" src="https://github.com/user-attachments/assets/cc602c0c-147d-49fb-b0c3-c06cf99f7cd9" />
<img width="886" height="528" alt="image" src="https://github.com/user-attachments/assets/831f79b5-a9a7-4cbd-9e58-385b78115c31" />
<img width="886" height="526" alt="image" src="https://github.com/user-attachments/assets/9025181f-8dd9-4876-94d6-16bcaca5ddaa" />
<img width="886" height="528" alt="image" src="https://github.com/user-attachments/assets/f863fe55-5d84-438f-8a4e-257354f1e014" />

Tela após correcção
<img width="886" height="548" alt="image" src="https://github.com/user-attachments/assets/97b4a44e-690e-4f4a-a4dc-ffa008f65e70" />

- Um resumo do que o seu **App de Finanças Pessoais** faz;
  Controla finanças pessoais, dá dicas de economia, mostra a classificação dos gastos por categoria para identificar mais facilmente onde economizar, permite upload de extratos bancários e faturas de cartão de crédito para facilitar o input de dados, realiza inputs por conversa em linguagem natural e cria botões de acesso rápido com base nas interações frequentes do usuário, cria gráficos e dashboards para melhor visaualização e análise dos dados, permite a criação e monitoramento de metas estabelecidas pelo usuário.
  
- Uma breve **reflexão sobre o processo**:
  - O que funcionou bem?
    As funcionalidades e telas determinadas no PRD foram atendidas, assim como a estética do app e as principais análises. 
  - O que não funcionou como o esperado?
    Inicialmente os botões não funcionaram e os inputs de dados também não funcionaram. Só tive direito a 2 interações com o lovable e não foi possível fazer o app funcionar exatamente como desejado com essas interações. Será necessária a reformulação do app para que todas as funcionalidades sejam operacionais. 
  - O que aprendeu sobre conversar com IAs?
    Paciência é a chave. É importante usar várias IAs em conjunto para facilitar o processo e alcançar melhores resultados.

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.
> Link do app: https://simple-cash-chat.lovable.app

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
