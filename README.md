# ✅ Lista de Tarefas

O **Lista de Tarefas** é um gerenciador completo, rápido e intuitivo, desenvolvido com **HTML, CSS e JavaScript puro**, totalmente funcional e com **salvamento automático no LocalStorage**.

É ideal para organização pessoal e demonstração de habilidades de front-end.

🔗 **Acesse o projeto online:**  
https://todolistdevmaximo.vercel.app/

---

## 🚀 Funcionalidades

- ➕ **Adicionar tarefas**
- ✏️ **Editar tarefas**
- ✔️ **Marcar como concluídas**
- ❌ **Excluir tarefas**
- 🔍 **Pesquisar tarefas** em tempo real
- 🎚️ **Filtrar tarefas** (Todos / Feitos / A fazer)
- 🔄 **Salvar automaticamente** no LocalStorage
- 🔧 Modo de **edição rápida**
- 🎨 Layout responsivo e interface limpa

---

## 🧠 Como funciona

Todas as tarefas são armazenadas no **LocalStorage**, garantindo que elas permaneçam mesmo após fechar o navegador.

O formato salvo é:

```json
{
  "text": "Nome da tarefa",
  "done": false
}

O JavaScript gerencia:

criação
exclusão
edição
marcação como feito
filtros
busca
sincronização com LocalStorage

🖥️ Tecnologias utilizadas

HTML5
CSS3
JavaScript Vanilla
LocalStorage
Font Awesome Icons
Vercel (deploy)

📂 Estrutura do projeto
/
├── index.html      # Estrutura da aplicação
├── style.css       # Estilização
├── script.js       # Lógica e CRUD das tarefas
└── README.md       # Documentação

📦 Deploy

O projeto está hospedado na Vercel:
👉 https://todolistdevmaximo.vercel.app/
