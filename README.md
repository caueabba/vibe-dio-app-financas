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

## 🖼️ Prints das Interações com a IA

### Interação 1 — Prompt inicial vago e resposta genérica

![Prompt inicial](./assets/Captura%20de%20Tela%20(97).png)
![Resposta genérica](./assets/Captura%20de%20Tela%20(98).png)

*A primeira tentativa com um prompt curto e sem contexto gerou uma resposta genérica, sem considerar público-alvo, restrições ou formato de entregável.*

---

### Interação 2 — Refinamento do Prompt

![Refinamento parte 1](./assets/Captura%20de%20Tela%20(99).png)
![Refinamento parte 2](./assets/Captura%20de%20Tela%20(100).png)
![Refinamento parte 3](./assets/Captura%20de%20Tela%20(101).png)

*A IA orientou como estruturar melhor o prompt, destacando contexto, público-alvo, não-escopo e formato do entregável.*

---

### Interação 3 — Geração do Plano de MVP e Telas

![Plano de MVP parte 1](./assets/Captura%20de%20Tela%20(102).png)
![Plano de MVP parte 2](./assets/Captura%20de%20Tela%20(103).png)
![Plano de MVP parte 3](./assets/Captura%20de%20Tela%20(104).png)
![Plano de MVP parte 4](./assets/Captura%20de%20Tela%20(105).png)
![Telas do MVP parte 1](./assets/Captura%20de%20Tela%20(106).png)
![Telas do MVP parte 2](./assets/Captura%20de%20Tela%20(107).png)
![Telas do MVP parte 3](./assets/Captura%20de%20Tela%20(109).png)
![Telas do MVP parte 4](./assets/Captura%20de%20Tela%20(110).png)

*Com o prompt refinado, a IA gerou um plano completo com telas, stack sugerida, métricas de validação, matriz de priorização e riscos.*
*Pergunta de aprofundamento sobre as 5 telas principais do MVP, com descrição funcional detalhada de cada uma.*

---

## Reflexão sobre o Processo

# O que funcionou bem?

- Dar *contexto claro* desde o início (problema, público, funcionalidades) fez a IA gerar respostas muito mais relevantes.
- Definir o *não-escopo* explicitamente evitou sugestões desnecessariamente complexas para um projeto solo.
- Pedir um entregável *estruturado em tópicos numerados* garantiu uma resposta organizada e acionável.

---

# O que não funcionou como o esperado?

- A primeira versão do prompt era vaga demais — a IA gerou um plano genérico, sem considerar as restrições do projeto.
- Sem especificar o formato do entregável, a resposta inicial misturava estilos e não tinha uma estrutura clara.

---

# O que aprendi sobre conversar com IAs?

- *Precisão importa mais do que tamanho*: um prompt curto e bem estruturado supera um prompt longo e vago.
- *Iteração é parte do processo*: o prompt ideal raramente sai na primeira tentativa — refinar é esperado.
- *A IA segue o que você diz, não o que você quer dizer*: ser explícito sobre restrições e formato é fundamental.
- *Perguntas abertas geram respostas abertas*: quanto mais específica a pergunta, mais útil a resposta.

---

# Stack Sugerida pela IA

| Camada | Tecnologia |
|--------|-----------|
| Frontend mobile | React Native / Flutter |
| Backend / API | Node.js + Express ou Firebase Functions |
| Banco de dados | Firebase Firestore ou SQLite local |
| IA conversacional | OpenAI API (GPT-4o) ou Claude API |
| Autenticação | Firebase Auth |

---

# Estrutura do Repositório

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
