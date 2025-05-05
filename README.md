# Semáforo inteligente

## 👨‍🎓 Integrantes
-Liedson Augusto Maciel Costa

## 💡 Ideia Principal
Construir um agente inteligente que seja capaz de calcular o melhor tempo para o tempo de ciclo para um cruzamento com 3 semáforos

## 🎯 Objetivos
- Melhorar o tempo médio de espera dos veículos
- Aumentar o fluxo de veículos que passaram do semáforo e diminuir os que estão a espera de passar
- Melhorar a qualidade de vida das pessoas a respeito do fluxo de trânsito

## 👥 Público-Alvo
Motoristas que forem atravessar o cruzamento específico da cidade de Campina Grande

## 🤖 Agentes Envolvidos
Liste os agentes que existirão no sistema e suas funções.
Exemplo:
- Agente Contador de veículos: Realiza a contagem dos veículos das 3 câmeras do cruzamento em específico, categorizando entre carro, moto e grande porte
- Agente Semáforo: Toma a decisão do tempo do ciclo para os 3 semáforos de acordo com o resultado da contagem do ciclo anterior

## 🧱 Tecnologias Pretendidas
- Frontend: Framework -> React | Linguagem -> Typescript
- Backend: Framework -> Nest | Linguagem -> Typescript
- Agente Contador de veículos: Framework -> YOLOv8 | Linguagem -> Python
- Agente Semáforo: Framework -> Stable_Baselines3 | Linguagem -> Python

> Justifique, sempre que possível, **por que escolheu cada ferramenta**.

## 📦 Entradas e Saídas Esperadas
**Entradas:**
- Quantidade dos veículos daquele semáforo

**Saídas:**
- Tempo do ciclo para aquele semáforo

## 🔁 Interação entre os Agentes
Através da contagem dos veículos realizado pelo o Agente Contador de Veículos, a saída será entregue ao Agente Semáforo
para que ele realize o cálculo do melhor tempo possível

## 🗂️ Organização e Planejamento do Projeto
O progresso deste projeto será monitorado através do **GitHub Projects**.

> Acesse a aba "Projects" do repositório para acompanhar:
- Tarefas pendentes
- Tarefas em andamento
- Tarefas concluídas

Cada integrante deve ser responsável por pelo menos uma tarefa no quadro.
Use etiquetas (labels) e comentários para detalhar o andamento e as decisões.

## 📌 Status Inicial do Projeto
- [ ] Ideia discutida e validada com o professor
- [ ] Estrutura básica do repositório criada
- [ ] Quadro no GitHub Projects criado
- [ ] Primeiras tarefas definidas e atribuídas

## 📄 Documentação Futura
Este repositório poderá incluir:
- Diagramas de arquitetura
- Relatórios parciais de progresso
- Scripts de testes ou simulações
- Resultados e conclusões finais

## 👨‍🏫 Acompanhamento pelo Professor
Para que o professor possa acompanhar e orientar o andamento do projeto, **adicione o usuário `igorbarcosta` como colaborador do repositório.**

### Como fazer:
1. Vá até a aba **"Settings"** do seu repositório.
2. Clique em **"Collaborators"** no menu lateral.
3. Digite o nome de usuário: `igormago`
4. Clique em **"Add collaborator"** e confirme.
