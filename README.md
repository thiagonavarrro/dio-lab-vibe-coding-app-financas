# 💸 App de Organização de Finanças Pessoais FinChat com Vibe Coding

PRD refinado no Copilot Web:

````Markdown

PRD – Aplicativo de Organização de Finanças Pessoais Conversacional

1. Contexto
O aplicativo tem como objetivo simplificar o controle financeiro pessoal por meio de interações em linguagem natural.
Em vez de formulários complexos ou planilhas, o usuário conversa com um Agente Financeiro Virtual, que ajuda a registrar gastos, acompanhar metas e receber recomendações personalizadas.

2. Problema
- Baixa adesão: Muitos usuários abandonam apps de finanças por exigirem entradas manuais e pouco intuitivas.
- Falta de personalização: As soluções atuais não se adaptam ao estilo de vida do usuário.
- Experiência engessada: Interfaces tradicionais não oferecem a fluidez de uma conversa natural.

3. Público-Alvo
- Pessoas que desejam começar a organizar suas finanças sem complicação.
- Usuários iniciantes em controle financeiro.
- Jovens adultos e profissionais que preferem interações rápidas e acessíveis.

4. Funcionalidades-Chave
1. Registro de gastos via chat
   - O usuário informa despesas em linguagem natural (ex.: “Gastei R$50 no mercado”).
   - O sistema interpreta e armazena automaticamente.

2. Classificação automática de transações
   - Identificação da categoria (alimentação, transporte, lazer etc.) com base no texto.
   - Possibilidade de correção manual pelo usuário.

3. Metas financeiras
   - Definição de objetivos simples (ex.: “Quero economizar R$500 este mês”).
   - Acompanhamento do progresso com notificações amigáveis.

4. Agente Financeiro com dicas de economia
   - Recomendações personalizadas baseadas nos hábitos do usuário.
   - Sugestões práticas e educativas para reduzir gastos.

5. Relatórios simples e personalizados
   - Visualização em gráficos e resumos semanais/mensais.
   - Destaque para insights relevantes (ex.: “Você gastou 20% a mais em alimentação este mês”).

5. MVP – Plano de Entregáveis

Telas Principais
- Tela de Conversa: interface de chat para registrar gastos e interagir com o agente.
- Tela de Metas: definição e acompanhamento de objetivos financeiros.
- Tela de Relatórios: gráficos simples e resumos personalizados.

Recursos Necessários
- Motor de NLP (Processamento de Linguagem Natural) para interpretar mensagens.
- Banco de dados para armazenar transações e metas.
- Algoritmo de categorização automática.
- Módulo de geração de relatórios e gráficos.
- Sistema de notificações para lembretes e dicas.

Validação Inicial
- Teste com usuários iniciantes: verificar se conseguem registrar gastos sem instruções adicionais.
- Métricas de sucesso:
  - Taxa de registro de gastos por semana.
  - Número de metas criadas e acompanhadas.
  - Feedback sobre clareza das dicas do agente.

6. Design Universal
Para garantir acessibilidade e inclusão, o aplicativo seguirá princípios de Design Universal:

- Acessibilidade digital: suporte a leitores de tela, contraste adequado e fontes ajustáveis.
- Interação multimodal: além do chat escrito, permitir entrada por voz e resposta em áudio.
- Linguagem clara e inclusiva: evitar jargões financeiros complexos, usar exemplos práticos.
- Flexibilidade de uso: adaptação para diferentes perfis (usuários iniciantes, pessoas com deficiência visual ou motora).
- Feedback imediato: respostas rápidas e compreensíveis para reduzir frustração.
- Compatibilidade ampla: funcionamento em dispositivos móveis, tablets e web.

7. Tom e Linguagem
- Educativo e acessível: evitar termos técnicos complexos.
- Conversacional: respostas curtas e naturais, como em um bate-papo.
- Motivador: incentivar hábitos financeiros saudáveis sem tom punitivo.


````

Interações com o Locable:

>Crie um App de finanças pessoais com base no seguinte PRD (Product Requirements Document): {PRD}

>Fix these issues

>Implementar Fase 2: autenticação com email e tabelas de transações, metas e histórico no banco de dados

Resultado final no Lovable: https://coin-chatter-pro.lovable.app/

Interação com o Copilot:

![Copilot](https://github.com/user-attachments/assets/c5a70ddb-66dd-4046-a363-cd3aa46bc18f)

Interação com Lovable:

![lovable](https://github.com/user-attachments/assets/486ffdee-7fb5-4e35-985e-3d28653da6bc)


# Funcionalidades do FinChat

## Registro de Gastos
- O usuário informa despesas em linguagem natural (ex.: "Gastei R$50 no mercado").
- O sistema interpreta e registra automaticamente.

## Classificação Automática
- As transações são categorizadas (alimentação, transporte, lazer etc.).
- Possibilidade de ajuste manual pelo usuário.

## Metas Financeiras
- Criação de objetivos simples (ex.: "Quero economizar R$500 este mês").
- Acompanhamento do progresso com notificações amigáveis.

## Agente Financeiro
- Chatbot que oferece dicas de economia personalizadas.
- Recomendações práticas e educativas baseadas nos hábitos do usuário.

## Relatórios Personalizados
- Resumos semanais e mensais em gráficos simples.
- Destaque para insights relevantes (ex.: "Você gastou 20% a mais em alimentação este mês").

## Interface Intuitiva
- Botões de ação rápida:
  - Registrar gasto
  - Ver resumo
  - Criar meta
  - Receber dica de economia
- Navegação clara entre Chat, Metas e Relatórios.

## Design Universal
- Suporte a leitores de tela e contraste adequado.
- Entrada multimodal (texto e voz).
- Linguagem clara e inclusiva.
- Compatibilidade com dispositivos móveis, tablets e web.


# Reflexão sobre o Processo

## O que funcionou bem?
- A definição clara do problema e do público-alvo ajudou a manter o foco no desenvolvimento do PRD.  
- A estrutura em etapas (Contexto, Problema, Público-Alvo, Funcionalidades, MVP, Design Universal) facilitou a organização das ideias.  
- A interação com a IA permitiu transformar conceitos soltos em um documento coeso e pronto para uso.

## O que não funcionou como o esperado?
- Algumas funcionalidades precisaram ser ajustadas e detalhadas para ficarem mais práticas no MVP.  
- A tradução de ideias para requisitos técnicos exigiu refinamento, já que nem sempre a primeira versão estava suficientemente clara.  
- O processo de revisão mostrou que é fácil deixar pontos vagos se não houver atenção à acessibilidade e usabilidade.

## O que aprendi sobre conversar com IAs?
- A IA funciona bem como parceira de brainstorming, ajudando a estruturar e organizar ideias.  
- Quanto mais detalhado e específico o pedido, melhor o resultado gerado.  
- É importante revisar e adaptar o conteúdo sugerido pela IA, pois ela fornece uma base sólida, mas o ajuste final depende da visão do criador.  
- Conversar com IAs é um processo iterativo: cada interação refina e melhora o resultado.

