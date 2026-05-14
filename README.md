# 💸 App do André Pereira de Organização de Finanças Pessoais com Vibe Coding

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

-  PRD refinado no Qwen3.6-Plus

-  '''markdown
-  # PRD - Aplicativo de Organização Financeira por Chat (MVP)

## 1. Visão do Produto
Criar um aplicativo web/mobile-first de organização financeira pessoal onde o usuário registra, acompanha e recebe insights sobre seus gastos apenas conversando em linguagem natural. Zero planilhas, zero formulários rígidos. Compromisso com Design Universal e preferência visual: experiência usável, acessível e inclusiva para todos, com suporte nativo a modo claro e escuro.

## 2. Problema e Oportunidade
- Dor: Aplicativos financeiros atuais exigem entrada manual repetitiva, categorização burocrática e ignoram necessidades visuais (fadiga ocular, fotofobia, uso noturno) e cognitivas.
- Oportunidade: Combinar IA conversacional, automação de classificação e princípios de Design Universal para reduzir o atrito de registro e entregar uma experiência confortável em qualquer contexto de uso.

## 3. Público-Alvo
- Iniciantes em educação financeira (18 a 45 anos).
- Pessoas com deficiências visuais, motoras, auditivas ou cognitivas.
- Usuários com fotofobia, fadiga visual, enxaqueca ou preferência por ambientes escuros.
- Pessoas com baixa alfabetização digital ou financeira.
- Usuários de dispositivos antigos, conexões lentas ou telas pequenas.

## 4. Escopo do MVP
Inclui:
- Chat principal para registro de transações (texto e voz)
- Classificação automática por IA
- Definição e acompanhamento de metas financeiras
- Painel de resumo mensal
- Agente Financeiro com dicas contextualizadas
- Alternância de tema (Light/Dark) com detecção automática do sistema e preferência salva

Fora do MVP:
- Integração bancária automática (Open Finance)
- Multi-usuário ou perfis familiares
- Relatórios avançados ou exportação de dados
- Notificações push agendadas

## 5. Funcionalidades Detalhadas (User Stories e Critérios de Aceitação)

1. Registro por Chat
- User Story: Como usuário, quero digitar ou falar um gasto em linguagem natural e vê-lo salvo automaticamente.
- Critério de Aceitação: O sistema extrai valor, data e descrição. Confirma no chat. Suporte a ditado por voz, labels ARIA, foco visível no teclado e mensagens de erro claras.

2. Classificação Automática
- User Story: Como usuário, quero que o aplicativo categorize meus gastos sem esforço manual.
- Critério de Aceitação: IA sugere categoria; o usuário corrige com um clique. Botões com área mínima de 44x44 pixels, contraste mínimo de 4.5:1 em ambos os temas.

3. Metas Financeiras
- User Story: Como usuário, quero criar uma meta de economia e acompanhar o progresso.
- Critério de Aceitação: Barra de progresso com descrição textual alternativa, status acessível por leitores de tela e navegação completa por teclado.

4. Agente Financeiro
- User Story: Como usuário, quero receber dicas de economia baseadas nos meus padrões reais de gasto.
- Critério de Aceitação: Mensagens em linguagem simples, compatível com leitores de tela, contraste validado no tema ativo.

5. Painel de Resumo
- User Story: Como usuário, quero visualizar um resumo simples dos meus gastos do mês.
- Critério de Aceitação: Gráficos com descrição textual e padrões visuais (não apenas cor). Cores ajustadas para manter contraste mínimo de 3:1 para elementos de interface e 4.5:1 para texto em ambos os temas.

6. Alternância de Temas
- User Story: Como usuário, quero usar o aplicativo no tema claro ou escuro conforme minha preferência ou ambiente.
- Critério de Aceitação: Detecta preferência do sistema automaticamente. Botão de alternação acessível por teclado e leitor de tela. Preferência salva no armazenamento local. Transição suave inferior a 300ms.

## 6. Requisitos de Design Universal e Temas
- Uso equitativo: Ambos os temas são nativos e oferecem a mesma funcionalidade, sem segregação.
- Flexibilidade: Respeita contexto físico (iluminação) e fisiológico (sensibilidade visual).
- Informação perceptível: Conformidade com WCAG 2.1 Nível AA. Contraste mínimo validado em ambos os modos. Cores nunca são o único indicador de informação.
- Tolerância a erros: Alteração de tema não interfere em dados salvos e é reversível instantaneamente.
- Baixo esforço físico: Botão de alternação requer um toque, sem menus profundos.
- Especificações técnicas de tema: Uso de variáveis CSS ou Tailwind dark mode. Respeito a prefers-color-scheme. Evitar preto puro (#000000) ou branco puro (#FFFFFF) para reduzir fadiga visual. Transições suaves sem flash de conteúdo. Preferência persistida via localStorage ou banco de dados.

## 7. Modelo de Dados Sugerido
- users: id, email, created_at, theme_preference
- transactions: id, user_id, amount, category, date, description, is_confirmed
- goals: id, user_id, title, target_amount, current_amount, deadline
- chat_messages: id, user_id, role, content, timestamp

## 8. Requisitos Não-Funcionais
- Privacidade: Dados criptografados em repouso e em trânsito. Sem venda ou compartilhamento.
- Performance: Resposta do chat inferior a 2 segundos. Carregamento do painel inferior a 1.5 segundos.
- Acessibilidade: Navegação 100% por teclado, compatibilidade com leitores de tela (VoiceOver, TalkBack, NVDA), suporte a zoom de 200% sem quebra de layout.
- Idioma e Tom: Português (Brasil). Linguagem clara, educativa e livre de jargões financeiros complexos.

## 9. Métricas de Sucesso e Validação
Métricas:
- 60% dos usuários registram pelo menos 3 transações na primeira semana
- 40% criam pelo menos uma meta
- Tempo médio de registro inferior a 15 segundos
- 100% das telas navegáveis por teclado em testes internos

Validação:
- Teste com 10 a 15 usuários reais, incluindo pelo menos 3 pessoas com deficiência ou necessidades visuais específicas
- Coleta de feedback sobre clareza do chat, precisão da classificação, conforto visual em ambos os temas e facilidade de uso com tecnologias assistivas
- Iteração de melhorias antes do lançamento público

## 10. Prompt Base para Lovable

Crie um app web responsivo (React + Tailwind) com backend Supabase, seguindo Design Universal, WCAG 2.1 AA e suporte nativo a Light/Dark Mode.

Fluxo principal:
1. Login/registro simples com labels acessíveis e navegação por teclado.
2. Dashboard com resumo mensal: gráfico com descrição textual, total gasto, metas ativas.
3. Chat fixo na parte inferior: suporte a texto e voz (Web Speech API), botões com área mínima de 44x44px.
4. Extração de valor, data e descrição via função edge. Salva em transactions. Confirma no chat.
5. Tela de Metas com CRUD simples e barra de progresso acessível.
6. Agente gera uma dica semanal em linguagem clara.

TEMAS:
- Detecta automaticamente prefers-color-scheme do sistema operacional.
- Toggle de tema no header: acessível por teclado e leitor de tela, com aria-label correspondente.
- Usa Tailwind dark: ou CSS variables. Mantém contraste mínimo de 4.5:1 para texto e 3:1 para elementos de UI em ambos os temas.
- Salva preferência do usuário. Transição suave inferior a 300ms. Sem flash de conteúdo.
- Cores neutras no dark mode: evite preto puro. Use tons de cinza escuro (#121212 ou similar). Texto nunca abaixo de #9CA3AF em fundo escuro.

Design: tipografia mínima de 16px, ícones sempre acompanhados de texto, modo alto contraste opcional. Todos os textos em PT-BR, tom educativo. Priorize MVP funcional e acessível sobre perfeição visual.

- <img width="1536" height="1183" alt="Sem " src="https://github.com/user-attachments/assets/20df3fbf-6034-4927-8933-29683de680c2" />
 
- Interações com o Lovable:
- crie um app de finanças pessoais, com base no seguinte PRD (Product  Requirement Document)
- não está funcionando favor corrigir este erro
- preciso que corrija erros em questão de cadastro e login
- preciso que a inteligencia tenha uma melhor interpretação de linguagem natural, pois ela não está entendendo o que eu escrevi
- Crie a funcionalidade de criaçãode metas, e crie opção de apagar registros

  
- Reflexão:
  - O que funcionou bem: A refinagem do PRD ajudou muito, pois os créditos do Lovable possibilita poucas interações
  - O que não funcionou como o esperado: Esperava interagir mais com o Lovable gratuitamente, mas as interações foram suficiente para apreder sobre Vibe Coding
  - O que aprendeu sobre conversar com IAs: Aprendi que é identico a conversar com uma pessoa, quanto mais informaçõe e clareza, melhor a interação
 
  - - Resumo:
  '''markdown
  - # ContaLeve
> Organização financeira pessoal via chat. Zero planilhas, zero formulários. Apenas conversa.

ContaLeve é um aplicativo web/mobile-first que transforma o registro de gastos em uma conversa natural. Utilizando IA para classificação automática e princípios de Design Universal, o app reduz o atrito da educação financeira e entrega uma experiência confortável, acessível e inclusiva para qualquer contexto de uso.

---

## Funcionalidades

### Registro por Chat (NLP)
- Digite ou fale seus gastos em linguagem natural (ex: `"gastei 240 com gasolina"`).
- A IA extrai automaticamente **valor**, **data** e **descrição**, classificando a transação sem menus ou formulários.
- Suporte a entrada por voz via `Web Speech API`.

### Painel de Resumo Inteligente
- Visão clara e direta de **Gastos**, **Receitas** e **Saldo** do mês.
- Gráfico de categorias com descrição textual e padrões visuais (não apenas cor).
- Histórico de últimos lançamentos para conferência rápida.

### Agente Financeiro
- Receba dicas contextualizadas baseadas nos seus padrões reais de consumo.
- Linguagem simples, educativa e livre de jargões complexos.
- Sugestões práticas para otimizar seu orçamento no próximo mês.

### Metas Financeiras
- Crie objetivos de economia e acompanhe o progresso com barras visuais e descrições acessíveis.
- CRUD simplificado com feedback imediato e navegação 100% por teclado.

---

## Acessibilidade e Design Universal

O ContaLeve foi construído seguindo rigorosamente as diretrizes **WCAG 2.1 Nível AA**:

- **Tema Claro/Escuro Nativo**: Detecção automática via `prefers-color-scheme` + toggle persistente. Otimizado para fotofobia, fadiga visual e uso noturno (sem preto/branco puro).
- **Navegação Completa**: 100% operável por teclado e compatível com leitores de tela (VoiceOver, TalkBack, NVDA).
- **Contraste e Toque**: Mínimo de `4.5:1` para texto e `3:1` para UI. Botões com área mínima de `44x44px`.
- **Zoom Responsivo**: Layout estável até `200%` de ampliação sem quebra de estrutura.
- **Idioma**: Português (Brasil) com tom educativo e inclusivo.

---

## Stack Tecnológica (MVP)

| Camada          | Tecnologias                     |
|-----------------|---------------------------------|
| Frontend        | React + Tailwind CSS            |
| Backend & DB    | Supabase (Auth, PostgreSQL)     |
| IA & Lógica     | Edge Functions (NLP/Classificação) |
| Voz             | Web Speech API                  |
| Acessibilidade  | ARIA labels, foco gerenciado, `prefers-color-scheme` |

---

## Escopo: MVP vs Roadmap

### Entregue no MVP
- Chat principal para registro (texto + voz)
- Classificação automática por IA
- Painel de resumo mensal + Top categorias
- Agente Financeiro com dicas contextuais
- Metas financeiras com acompanhamento
- Alternância de temas (Light/Dark) com persistência

### Planejado para Próximas Versões
- Integração bancária automática (Open Finance)
- Perfis familiares / multi-usuário
- Relatórios avançados e exportação de dados (CSV/PDF)
- Notificações push agendadas e lembretes de metas

---

## Como Rodar Localmente

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/contaleve.git
cd contaleve

# Instale as dependências
npm install

# Configure as variáveis de ambiente (.env)
cp .env.example .env

# Inicie o servidor de desenvolvimento
npm run dev

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
