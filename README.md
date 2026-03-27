# vibe-dio-app-financas
App de finanças para o dia dia.

# BudgetBot — App de Organização Financeira Pessoal via Chat

> Projeto desenvolvido como parte de um exercício prático de engenharia de prompts com IA generativa.
> Foi usado o Claude IA.

---

# O que é o BudgetBot?

O *BudgetBot* é um aplicativo mobile de organização de finanças pessoais que funciona por meio de conversas em linguagem natural. Em vez de formulários e planilhas, o usuário simplesmente digita o que gastou — e o app classifica, registra e analisa automaticamente.

# Funcionalidades principais

- *Chat financeiro*: registre gastos conversando normalmente (ex: *"gastei 45 reais no almoço hoje"*)
- *Classificação automática*: as transações são categorizadas sem esforço manual
- *Metas financeiras*: defina e acompanhe objetivos simples de economia
- *Agente Financeiro*: receba dicas personalizadas com base nos seus padrões de gasto
- *Relatórios visuais*: resumos mensais e por categoria, de forma simples e acessível

# Público-alvo

Pessoas físicas iniciantes em educação financeira que querem organizar as finanças de forma prática, sem complicação, pelo celular.

---

# Prompt Final (PRD)

> Este é o prompt refinado utilizado para gerar o plano de MVP do aplicativo com auxílio de IA.

```
# Contexto
Quero criar um MVP de um aplicativo de Organização de Finanças Pessoais
que funcione por meio de conversas com o usuário. A ideia é facilitar o
controle financeiro de forma simples e natural, sem formulários manuais
ou planilhas complexas.

# Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais
exigem muita entrada manual e pouca personalização. Quero resolver isso
com uma experiência conversacional e recomendações automáticas de economia.

# Público-Alvo
Pessoas físicas (uso individual) que querem começar a organizar suas
finanças de forma prática, principalmente iniciantes em educação financeira,
com foco em uso mobile no dia a dia.

# Funcionalidades do MVP
1. Registrar gastos via chat em linguagem natural
2. Classificar automaticamente as transações por categoria
3. Definir e acompanhar metas financeiras simples
4. Receber dicas de economia do "Agente Financeiro" com base nos gastos
5. Visualizar relatórios simples e personalizados (resumo mensal, por categoria)

# Restrições e Não-Escopo
Este MVP NÃO incluirá:
- Integração com bancos ou Open Finance
- Suporte a múltiplos usuários ou perfis familiares
- Gestão de investimentos ou renda variável
- Versão web (foco exclusivo em mobile)

# Contexto de Desenvolvimento
- Projeto solo, sem equipe
- Stack: sem restrição definida (sugestões são bem-vindas)

# Entregável Esperado
Gerar um plano de MVP completo contendo:
1. Lista das principais telas com descrição funcional de cada uma
2. Recursos técnicos necessários (stack sugerida, APIs, armazenamento)
3. Esboço de validação inicial com métricas de sucesso mensuráveis
4. Priorização das funcionalidades por impacto e esforço (matriz simples)
5. Riscos principais e como mitigá-los

Use tom educativo, linguagem acessível e escreva tudo em português brasileiro.
```

---

# Prints e Interações com a IA

> Adicione abaixo os prints ou vídeos das suas conversas com a IA durante o processo de criação.

### Interação 1 — Refinamento do Prompt

<!-- Substitua o caminho abaixo pelo print real -->
![Refinamento do prompt](./assets/interacao-01-refinamento.png)

*Descrição: Conversa onde o prompt original foi refinado com base em perguntas sobre público-alvo, restrições e formato do entregável.*

---

### Interação 2 — Geração do Plano de MVP

<!-- Substitua o caminho abaixo pelo print real -->
![Geração do MVP](./assets/interacao-02-mvp.png)

*Descrição: Resultado gerado pela IA a partir do prompt refinado, contendo as telas, stack sugerida e matriz de priorização.*

---

### Interação 3 — [Adicione o título da sua interação]

<!-- Adicione mais prints conforme necessário -->
![Interação adicional](./assets/interacao-03.png)

*Descrição: [Descreva o que aconteceu nessa conversa]*

---

## 🪞 Reflexão sobre o Processo

### ✅ O que funcionou bem?

<!-- Escreva aqui o que você achou mais eficaz na sua experiência com a IA -->

- Dar **contexto claro** desde o início (problema, público, funcionalidades) fez a IA gerar respostas muito mais relevantes.
- Definir o **não-escopo** explicitamente evitou sugestões desnecessariamente complexas para um projeto solo.
- Pedir um entregável **estruturado em tópicos numerados** garantiu uma resposta organizada e acionável.

---

### ❌ O que não funcionou como o esperado?

<!-- Escreva aqui as frustrações ou surpresas negativas durante o processo -->

- A primeira versão do prompt era vaga demais — a IA gerou um plano genérico, sem considerar as restrições do projeto.
- Sem especificar o formato do entregável, a resposta inicial misturava estilos e não tinha uma estrutura clara.
- *[Adicione suas próprias observações aqui]*

---

### 🧠 O que aprendi sobre conversar com IAs?

<!-- Escreva suas principais aprendizagens sobre engenharia de prompts -->

- **Precisão importa mais do que tamanho**: um prompt curto e bem estruturado supera um prompt longo e vago.
- **Iteração é parte do processo**: o prompt ideal raramente sai na primeira tentativa — refinar é esperado.
- **A IA segue o que você diz, não o que você quer dizer**: ser explícito sobre restrições e formato é fundamental.
- **Perguntas abertas geram respostas abertas**: quanto mais específica a pergunta, mais útil a resposta.
- *[Adicione suas próprias aprendizagens aqui]*

---

## 🛠️ Stack Sugerida pela IA

| Camada | Tecnologia |
|--------|-----------|
| Frontend mobile | React Native / Flutter |
| Backend / API | Node.js + Express ou Firebase Functions |
| Banco de dados | Firebase Firestore ou SQLite local |
| IA conversacional | OpenAI API (GPT-4o) ou Claude API |
| Autenticação | Firebase Auth |

---

## 📁 Estrutura do Repositório

```
/
├── README.md           # Este arquivo
├── assets/             # Prints e mídias das interações
│   ├── interacao-01-refinamento.png
│   ├── interacao-02-mvp.png
│   └── interacao-03.png
└── docs/               # Documentação adicional (opcional)
    └── plano-mvp.md
```

---

## 📄 Licença

Este projeto foi desenvolvido para fins educacionais.

---

*Feito com 💚 e muita conversa com IA.*
