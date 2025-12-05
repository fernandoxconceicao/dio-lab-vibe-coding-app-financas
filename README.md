# 💸 App de Finanças Pessoais do Fernando com Vibe Coding

## Introdução

Este projeto foi desenvolvido como parte de um desafio de **Vibe Coding**, utilizando ferramentas de prototipação rápida e interação com IA.  
A proposta central é criar um **aplicativo de organização financeira pessoal** que funcione por meio de **interações em linguagem natural**, permitindo que o usuário registre gastos, acompanhe metas e receba recomendações de economia de forma simples e acessível.  

O objetivo é oferecer uma experiência fluida e inclusiva, baseada em conversas com um **Agente Financeiro virtual**, substituindo formulários complexos e planilhas tradicionais por uma abordagem mais intuitiva e prática.

## PRD refinado no Copilot Web

```markdown
PRD – Aplicativo de Organização de Finanças Pessoais

1. Contexto
O aplicativo tem como objetivo simplificar o controle financeiro pessoal por meio de conversas em linguagem natural.
A proposta é substituir formulários e planilhas complexas por uma experiência fluida e acessível, onde o usuário interage com um Agente Financeiro que entende suas necessidades e oferece recomendações personalizadas.
Princípio central: o design deve seguir o conceito de Design Universal, garantindo que o aplicativo seja inclusivo e ofereça uma boa experiência para o maior número possível de pessoas, independentemente de idade, nível de experiência digital ou possíveis limitações.

2. Problema
- Usuários desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual.
- Falta de personalização e de uma experiência amigável.
- Necessidade de uma solução que combine simplicidade, aconselhamento automático e acessibilidade universal.

3. Público-Alvo
- Pessoas que desejam iniciar sua organização financeira sem complicações.
- Usuários iniciantes que buscam praticidade e orientação básica.
- Pessoas que preferem interações conversacionais em vez de interfaces tradicionais.
- Indivíduos com diferentes perfis e necessidades, incluindo aqueles que podem ter limitações visuais, motoras ou cognitivas.

4. Funcionalidades-Chave
1. Registro de gastos via chat em linguagem natural.
2. Classificação automática das transações (alimentação, transporte, lazer etc.).
3. Definição e acompanhamento de metas financeiras (ex.: guardar R$200/mês).
4. Dicas de economia personalizadas fornecidas pelo Agente Financeiro.
5. Relatórios simples e visuais (gráficos e resumos adaptados ao perfil do usuário).
6. Design Universal: interface acessível, com linguagem clara, suporte a diferentes dispositivos e recursos de acessibilidade (ex.: contraste adequado, leitura de tela, navegação simplificada).

5. Entregável da IA (MVP)
- Principais telas:
  - Tela de chat (interação com o Agente Financeiro).
  - Tela de metas (definição e progresso).
  - Tela de relatórios (gráficos simples e personalizados).

- Recursos necessários:
  - Processamento de linguagem natural (NLP).
  - Motor de categorização automática de transações.
  - Sistema de recomendações financeiras.
  - Visualização de dados (gráficos e dashboards).
  - Implementação de boas práticas de Design Universal.

- Validação inicial:
  - Testes com usuários iniciantes para avaliar clareza e simplicidade.
  - Testes com diferentes perfis de usuários (incluindo pessoas com necessidades específicas).
  - Coleta de feedback sobre a experiência de conversa e acessibilidade.
  - Ajustes rápidos no fluxo de chat, nas dicas fornecidas e na interface.
```
## Interações com o Lovable

> Crie um App de Finanças Pessoais com base no seguinte PRD (Product Requirements Document): {PRD}  
> Tentei criar uma nova meta e não consigo, além disso o app não atualiza meu saldo quando deposito. Também queria que o saldo ficasse visível na primeira tela, com o saldo em cima, chat em baixo e as metas ao lado do chat.  
> - Vou criar um contexto global para compartilhar o estado entre componentes e redesenhar a interface em uma única tela.

**Resultado Final no Lovable:**  
[https://as-na-conversa.lovable.app](https://as-na-conversa.lovable.app)

### Screenshots

<img width="1649" height="947" alt="appfinances1" src="https://github.com/user-attachments/assets/f64ba726-d8a6-47b8-b232-c2802e9dc2b6" />  
<img width="1649" height="947" alt="appfinances2" src="https://github.com/user-attachments/assets/d40c4348-6715-49d0-88ea-ce1bb8e9980c" />

---

## Funcionalidades do App FinançasFácil

### 1. Assistente Financeiro via Chat
- Interação com um Agente Financeiro que entende linguagem natural.
- Registro de gastos com frases simples como "gastei 50 reais em festa".
- Respostas com confirmação e dicas personalizadas de economia.

### 2. Registro e Classificação de Gastos
- Registro automático de despesas informadas pelo usuário.
- Classificação por categoria (ex.: lazer, alimentação, transporte).
- Visualização clara de cada entrada com valor e tipo de gasto.

### 3. Painel de Resumo Financeiro
- Exibição dos principais indicadores:
  - Saldo Atual
  - Receitas
  - Despesas
- Visão geral rápida da situação financeira do usuário.

### 4. Metas Financeiras
- Definição de metas personalizadas (ex.: reserva de emergência, viagem, compra de notebook).
- Acompanhamento do progresso em valores e porcentagem.
- Organização visual das metas com barras de progresso.

### 5. Design Universal
- Interface acessível e intuitiva para diferentes perfis de usuários.
- Linguagem clara e visual amigável.
- Compatibilidade com leitores de tela, contraste adequado e navegação simplificada.
- Ideal para iniciantes e pessoas com limitações visuais, motoras ou cognitivas.

---

## Reflexão

### O que funcionou bem?
- O refinamento do PRD previamente feito no Copilot ajudou muito, pois os créditos do Lovable acabaram em apenas 3 interações.

### O que não funcionou como o esperado?
- Esperava poder interagir mais vezes gratuitamente com o Lovable, mas as interações feitas já foram de grande valor para aprender mais sobre Vibe Coding.

### O que aprendeu sobre conversar com IAs?
- Aprendi que é basicamente igual a conversar com uma pessoa: quanto mais detalhes e clareza você dá, melhor é a interação.

---

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica.  
O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo.  
Cada interação é um experimento: quanto mais clara for sua intenção, mais surpreendente será o resultado.
