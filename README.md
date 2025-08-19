# Lista de Tarefas

## Descrição

Este é um projeto de lista de tarefas desenvolvido em **JavaScript puro**, com persistência em **Local Storage**.  
Permite adicionar, marcar como concluída, remover tarefas individuais e remover todas as tarefas concluídas.

O layout foi construído com **HTML e CSS**, e o JavaScript manipula tanto o **DOM** quanto o **Local Storage**.

---

## Funcionalidades

1. **Criar tarefas**
   - Usuário digita a descrição da tarefa e clica no botão `+`.
   - Cada tarefa recebe um `id` único.
   - Checkbox para marcar tarefa como concluída.
   - Botão `X` para remover tarefa individual.

2. **Remover tarefas**
   - Botão `X` remove uma tarefa específica.
   - Botão `Remover tarefas concluídas` remove todas as tarefas marcadas como concluídas.

3. **Persistência**
   - Todas as tarefas são salvas em **Local Storage**, mantendo o estado após o reload da página.

4. **Barra de progresso**
   - Mostra no rodapé o número de tarefas concluídas em relação ao total, por exemplo: `2/5 concluídas`.
   - É criada dinamicamente caso não exista (`id="tasks-progress"`).
