# 💸 FinFamilyChat - App de Organização de Finanças Pessoais com Vibe Coding

**Solução com IA** de forma criativa, guiando ferramentas como o **Copilot** e o **Lovable** com uma comunicação simples e natural. MVP (Produto Mínimo Viável) de um **App de Organização de Finanças Pessoais**, que permite **controlar as finanças por meio de uma conversa simples**, com **agentes de IA** capazes de criar **planos de economia personalizados e automatizados** aplicando o **jeito Vibe de programar com IA**.

---
## #️⃣ Prompt refinado no Copilot Web (PRD - Product Requirements Document)

### #️⃣ Parte 1

```
PRD - Aplicativo de Organização de Finanças por Conversa (Versão para MVP)

Visão resumida
Criar um aplicativo conversacional de finanças pessoais que permita registrar despesas, acompanhar metas e receber recomendações, oferecendo uma experiência inclusiva e personalizável para o máximo de usuários possível.

Problema
Usuários desistem de controlar gastos por fricção de formulários e falta de adaptação a diferentes capacidades. A solução reduz entrada manual com conversas naturais, classificação automática e recomendações proativas, e aplica Design Universal para ampliar a usabilidade.

Público alvo
Iniciantes em organização financeira, incluindo pessoas com diferentes habilidades sensoriais, motoras e cognitivas, idosos e pessoas com baixa literacia digital.

Objetivos do produto
- Reduzir esforço de registro em pelo menos 70% vs apps tradicionais.
- Aumentar retenção em 30 dias.
- Garantir experiência acessível e consistente para diversos perfis de usuário.

Funcionalidades Principais (priorizadas)
1. Registro por chat: entrada em linguagem natural por texto e voz; confirmação clara e correção rápida.
2. Classificação automática: categorias sugeridas com edição fácil e feedback para re‑treino.
3. Metas e acompanhamento: criar metas por conversa; notificações e resumo semanal.
4. Agente Financeiro: dicas proativas em texto e áudio; alertas configuráveis.
5. Relatórios simples: resumo mensal em linguagem acessível; gráficos com descrições textuais.
6. Privacidade e segurança: criptografia, controle de exportação e exclusão de dados.
7. Configurações de Acessibilidade: tamanho de fonte ajustável, modo alto contraste, leitura por voz, navegação por teclado/gestos.
8. Modo Escuro e Modo Claro: tema ajustável pelo usuário; opção de seguir tema do sistema.

Requisito não funcional obrigatório
Design Universal e suporte a dark/light mode desde o onboarding.

Critérios de sucesso e métricas
- Taxa de registro via chat: % de transações inseridas por conversa.
- Retenção 30 dias: usuários ativos após 30 dias.
- Precisão de classificação: % de transações categorizadas sem correção.
- Satisfação de acessibilidade: ≥ 90% entre testadores com necessidades diversas.
- Adoção do tema: % de usuários que escolhem dark vs light e impacto na satisfação.

Plano de MVP

Escopo do MVP
- Fluxo conversacional básico (texto e voz).
- Classificador com 10 categorias iniciais: Alimentação; Transporte; Moradia; Lazer; Saúde; Educação; Assinaturas; Compras; Investimentos; Outros.
- Tela de metas simples (criar, acompanhar progresso).
- Relatório mensal resumido em linguagem natural.
- Agente Financeiro com 3 tipos de dicas (economia imediata, ajuste de meta, alerta de gasto recorrente).
- Onboarding conversacional com opções de acessibilidade e escolha de tema (dark/light).

Principais telas do MVP
- Tela Conversa (chat principal): entrada texto/voz; histórico; confirmação rápida; alternância de tema.
- Tela Transações: lista filtrável; edição rápida; botão para corrigir categoria.
- Tela Metas: criar meta por conversa; progresso visual e feedback sonoro.
- Tela Relatórios: resumo textual; gráfico de tendência; descrições alternativas.
- Tela Perfil Acessibilidade: ajustes de contraste, tipografia, leitura por voz e seleção de tema.
- Tela Perfil/Segurança: configurações de privacidade e backup.

Recursos necessários
- Frontend: app mobile (iOS/Android) com componente de chat, gravação de voz e suporte a temas.
- Backend: API para processamento de linguagem natural, classificação e armazenamento seguro.
- ML/NLP: modelo de NLU para extrair valor, categoria, data e contexto; pipeline de classificação com feedback humano para re‑treino.
- Design: UX focado em conversas, microcopy educativo, tokens de design para dark/light e fluxos de correção rápida.
- Legal/Segurança: política de privacidade, criptografia, conformidade LGPD.
- Equipe mínima: 1 PM, 1 designer UX com experiência em acessibilidade, 2 devs mobile, 1 backend, 1 ML/NLP, 1 QA com foco em usabilidade inclusiva.

Validação Inicial (esboço)

Hipóteses a testar
- H1: Usuários iniciantes preferem registrar despesas por conversa a usar formulários.
- H2: Classificação automática reduz tempo de organização em comparação com entrada manual.
- H3: Dicas do Agente Financeiro aumentam a probabilidade de ajuste de comportamento financeiro.
- H4: Aplicação de Design Universal e opções de tema permitem que usuários com diferentes necessidades usem o app com eficiência similar.

Experimentos rápidos
1. Protótipo conversacional (Figma ou protótipo interativo) com 15–20 usuários diversos; medir facilidade de uso e intenção de continuar.
2. Wizard of Oz: simular o Agente Financeiro com moderador humano para avaliar relevância das dicas.
3. A/B test: onboarding conversacional com opções de acessibilidade e escolha de tema vs onboarding padrão.
4. Teste de classificação: coletar 200 transações reais via teste para medir precisão inicial.
5. Teste de acessibilidade: checklist de Design Universal aplicado por especialistas e por usuários reais, incluindo cenários em dark e light.

Critério de aceitação para avançar
- ≥ 70% dos testadores preferem o fluxo conversacional e conseguem registrar 5 transações em menos de 5 minutos.
- Classificação automática com ≥ 80% de precisão nas categorias mais comuns.
- ≥ 90% de satisfação entre grupos com necessidades diversas em tarefas-chave.

Design Universal — Diretrizes e Checklist

Definição
Design Universal: projetar produtos para que sejam utilizáveis pelo maior número possível de pessoas, independentemente de idade, habilidade ou contexto de uso.

Princípios essenciais aplicados ao app
- Uso Equitativo: entrada por voz e texto.
- Flexibilidade no Uso: múltiplas formas de interação; opção de tema.
- Simplicidade: microcopy curto, exemplos e fluxos guiados.
- Tolerância ao Erro: confirmação antes de salvar; fácil correção.
- Perceptibilidade: informação acessível por diferentes sentidos (texto, áudio, ícones).

Checklist prático (prioridade inicial)
- Incluir opções de acessibilidade no onboarding.
- Garantir contraste mínimo e tipografia escalável.
- Fornecer alternativas de entrada (voz, teclado, toque).
- Implementar descrições textuais para gráficos.
- Oferecer dark/light mode e opção de seguir tema do sistema.
- Testar com usuários reais de diferentes perfis e documentar ajustes.
- Validar contraste com ferramentas automatizadas e testes manuais.

Dark / Light Mode — Recomendações rápidas
- Garantir contraste adequado em ambos os temas.
- Usar paleta semântica e tokens de design para cores e tipografia.
- Fornecer ícones e imagens adaptáveis ou versões alternativas.
- Persistir preferência do usuário e permitir seguir configuração do sistema.
- Testar legibilidade, espaçamento e gráficos em ambos os temas.
- Implementar transições suaves ao alternar tema.

Riscos e Mitigações
- Dependência de NLP: mitigar com fallback manual e correção rápida pelo usuário.
- NLU com sotaques/variações: treinar com amostras diversas; oferecer confirmação passo a passo.
- Interface visual pouco legível: modos de alto contraste, tipografia escalável e testes com baixa visão.
- Privacidade e conformidade: projetar consentimento claro, criptografia e controles de exportação/exclusão.

Próximos passos recomendados
- Atualizar PRD oficial incluindo Design Universal e dark/light mode como requisitos não funcionais obrigatórios.
- Construir protótipo conversacional com opções de acessibilidade e seleção de tema no onboarding.
- Rodar testes Wizard of Oz e testes de usabilidade inclusiva em dark e light.
- Implementar pipeline de classificação com logs para re‑treino e métricas de acessibilidade.
- Definir critérios de aceitação por história de usuário incluindo verificações de contraste e usabilidade em ambos os temas.

Anexos sugeridos (para desenvolvimento)
- Exemplos de microcopy para onboarding e mensagens do Agente Financeiro.
- Tokens de design (cores, tipografia, espaçamentos) para dark e light.
- Checklist de testes de acessibilidade e roteiro de entrevistas para participantes.
- Plano de coleta de dados para re‑treino do classificador (consentimento explícito).

Fim do documento.

```

### #️⃣ Parte 2 (PRD Complementar - Funcionalidade Adicionais)

```
PRD Complementar - Funcionalidades Adicionais (Gestão de Contas, Autenticação, Multiusuário, Edição, Relatórios Mensais, Recorrência)

Resumo
Complemento ao PRD principal para incluir: gestão de contas com seleção após lançamento, tela de login (Google/Apple/email), ambiente multiusuário compartilhado, edição de lançamentos, filtro mensal em relatórios e recorrência/parcelamento de lançamentos. Inclui critérios de aceitação, impactos técnicos e prioridades para MVP.

Novas Funcionalidades Detalhadas

1. Gestão de Contas e Seleção após Lançamento
- Fluxo: Após o usuário confirmar um lançamento no chat, o sistema envia mensagem solicitando qual conta será movimentada.
- Contas padrão: Carteira; Bradesco; Nubank; Itaú; Caixa.
- Gestão de contas: área para adicionar, editar nome, definir tipo (conta corrente, cartão, carteira), remover e marcar conta padrão.
- Comportamento padrão: se não houver resposta, usar conta padrão; permitir alteração posterior no lançamento.
- UX: botões sugeridos para seleção rápida; opção "Outra conta" e busca; confirmação após escolha.

2. Tela de Login e Autenticação Social
- Opções: Google Sign-In; Sign in with Apple; Email e senha.
- Fluxo: tela de login com CTAs claros; opção "Continuar como convidado" com persistência limitada.
- Recuperação: recuperação de senha por e‑mail.
- Segurança: OAuth 2.0 para provedores; tokens JWT; refresh token.
- Privacidade: explicitar permissões solicitadas no login.

3. Multiusuário e Ambiente Compartilhado
- Convite e permissões: convidar por e‑mail; papéis iniciais: Administrador; Colaborador; Visualizador.
- Indicação no chat: cada lançamento exibe o nome do usuário que efetuou o lançamento (estilo chat).
- Controle de atividades: log de auditoria com criação/edição/exclusão e autor.
- Gerenciamento de membros: adicionar/remover, alterar papéis, aceitar convites.
- Privacidade: opção de contas pessoais privadas; ambiente compartilhado mostra histórico e relatórios do grupo.

4. Edição de Lançamentos
- Campos editáveis: valor; conta; descrição; data; categoria; recorrência.
- Fluxo: botão editar em lista de transações e no histórico do chat; modal com campos preenchidos; salvar gera AuditLog.
- Validação: regras para evitar edições inválidas (ex.: data futura sem permissão).
- Undo: permitir desfazer alteração por curto período (ex.: 30s); manter histórico de versões.

5. Relatórios com Seleção por Período Mensal
- Filtro por período: seletor mês/ano; presets: mês atual, últimos 3 meses, ano.
- Comparação: opção de comparar meses lado a lado.
- Exportação: exportar resumo em CSV (MVP opcional) com consentimento.
- Visualização: gráficos e resumo textual adaptados a dark/light e acessibilidade.

6. Recorrência de Lançamentos
- Tipos: diária; semanal; mensal; anual; parcelamento (ex.: 10x).
- Configuração no lançamento: opção "Repetir" com parâmetros (intervalo, número de repetições, data de término).
- Parcelamento: criar parcelas automáticas vinculadas entre si.
- Gerenciamento: tela para ver/editar/pausar/retomar/cancelar recorrências.
- Notificações: lembrete antes do próximo lançamento; opção de confirmação automática ou manual.

Novas Telas e Componentes

- Tela Gestão de Contas: lista de contas; adicionar; editar; definir padrão; remover com confirmação.
- Tela Login: Google, Apple, Email; recuperar senha; continuar como convidado.
- Tela Membros do Ambiente: lista de membros; convidar; alterar papéis; histórico de convites.
- Tela Transação Detalhe: visualização completa; editar; histórico de alterações; indicação do autor.
- Tela Recorrências: lista de recorrências ativas; editar; pausar; cancelar.
- Tela Relatórios com Filtro Mensal: seletor mês/ano; gráficos; comparação; resumo textual.

Modelo de Dados e Regras de Negócio

Entidades principais
- User: id, nome, email, authProvider, preferências (tema, acessibilidade).
- Account: id, ownerId/organizationId, nome, tipo, saldo inicial, moeda, padrão.
- Transaction: id, amount, date, description, category, accountId, createdByUserId, createdAt, updatedAt, recurrenceId (nullable).
- Recurrence: id, transactionTemplate, frequency, interval, installments, endDate, nextRunDate, status.
- Organization/Environment: id, name, members[] (userId, role).
- AuditLog: id, entityType, entityId, action, userId, timestamp, diff.

Regras
- Transações vinculadas a contas; remoção de conta exige migração ou exclusão de transações com confirmação.
- Edição registra versão anterior no AuditLog.
- Parcelamento cria N transações vinculadas à mesma recurrenceId e referência entre parcelas.

Critérios de Aceitação e Casos de Teste

Gestão de Contas
- Ao criar lançamento, sistema solicita conta; seleção altera saldo da conta correta.
- Usuário consegue adicionar/editar/remover conta; remoção exige confirmação e tratamento de transações vinculadas.

Login
- Login via Google/Apple autentica e cria usuário; login por e‑mail funciona com recuperação.
- Sessão expira e refresh token renova sessão.

Multiusuário
- Convite cria membro com papel; membro acessa ambiente após aceitar.
- Lançamentos mostram autor no chat; logs registram ações.

Edição de Lançamentos
- Editar valor/conta/descrição/data atualiza relatórios e gera AuditLog.
- Undo funciona no tempo definido.

Relatórios Mensais
- Filtro por mês retorna transações e gráficos corretos; comparação entre meses mostra diferenças.

Recorrência
- Criar recorrência gera lançamentos futuros conforme configuração; parcelamento cria parcelas vinculadas.
- Pausar/retomar altera nextRunDate e comportamento de geração.

Impactos Técnicos e UX

Backend
- Endpoints para contas, membros, recorrências, edição e audit logs.
- Jobs agendados para processar recorrências e parcelamentos.
- Consistência transacional ao mover valores entre contas.

Frontend
- Componentes para seleção rápida de conta no chat; modais de edição; telas de gestão.
- Suporte a temas e acessibilidade em novos componentes.

Segurança e Privacidade
- OAuth 2.0 para provedores sociais; criptografia de dados sensíveis; consentimento explícito para compartilhamento de ambiente.
- Controle de acesso por papéis e logs de auditoria.

Performance
- Otimizar consultas de relatórios por período; indexar por date e accountId.
- Limitar geração massiva de transações em caso de recorrências mal configuradas.

Próximos Passos e Prioridades para MVP

Prioridade alta
1. Seleção de conta após lançamento e gestão básica de contas.
2. Tela de login com Google/Apple/email.
3. Edição de lançamentos com AuditLog.
4. Relatórios com filtro mensal.

Prioridade média
1. Recorrência básica mensal e parcelamento simples.
2. Indicação do autor no chat e log de atividades.

Prioridade baixa
1. Gestão avançada de papéis e permissões granulares.
2. Exportação avançada e integrações bancárias.

Riscos e Mitigações
- Risco: complexidade de recorrências e parcelamentos. Mitigação: começar com recorrência mensal e parcelamento simples; evoluir conforme uso.
- Risco: conflitos de edição em ambiente compartilhado. Mitigação: bloquear edição concorrente e mostrar aviso de versão.
- Risco: segurança em ambientes compartilhados. Mitigação: papéis claros, consentimento e logs auditáveis.

Resumo final
Este PRD complementar adiciona gestão de contas, autenticação social, multiusuário colaborativo, edição de lançamentos, filtros mensais em relatórios e recorrência de lançamentos, com critérios de aceitação, impactos técnicos e prioridades para implementação no MVP. Pode ser convertido em histórias de usuário com critérios de aceitação detalhados e tarefas técnicas por sprint.

```
---
## 💖 Interações com o Lovable

> Crie um app de finanças pessoais com base no PRD (Product Requirements Documents) abaixo:
>
> Complemente esse PRD com as Funcionalidades Adicionais de Gestão de Contas, Autenticação, Multiusuário, Edição, Relatórios Mensais, Recorrência.
> 
> P: Quer que eu ative o Lovable Cloud agora para começarmos pela autenticação e banco de dados?
> R: Não, quero só o frontend por enquanto
>
> P: Por qual bloco de funcionalidades quer que eu comece?
> R: Tudo na ordem do PRD
>
> pode finalizar com todas as implementações?
>
Posteriormente solicitei apenas correções de layout.

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
