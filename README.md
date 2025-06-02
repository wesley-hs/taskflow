# 🚀 TaskFlow - Gerenciador de Tarefas Colaborativas

<div align="center">
  <!-- Espaço reservado para futura imagem -->
  <p>
    <img src="https://img.shields.io/badge/react-%2320232a.svg?logo=react" alt="React">
    <img src="https://img.shields.io/badge/typescript-%23007ACC.svg?logo=typescript" alt="TypeScript">
    <img src="https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?logo=tailwind-css" alt="TailwindCSS">
    <img src="https://img.shields.io/badge/license-MIT-blue" alt="License">
  </p>
  <p>🚧 Screenshot será adicionado após primeira implementação 🚧</p>
</div>

## ✨ Funcionalidades
- ✅ **Quadro Kanban** com drag-and-drop
- 🌙 **Dark/light mode** toggle
- 🔔 **Notificações em tempo real** (Socket.IO)
- 📁 **Exportar tarefas** para PDF/CSV
- 👥 **Tarefas colaborativas** em equipe

## 🛠️ Tecnologias
| Camada          | Tecnologias                           |
|-----------------|---------------------------------------|
| **Frontend**    | React 18, TypeScript, TailwindCSS     |
| **Backend**     | Node.js (Express) ou .NET Core        |
| **Banco**       | PostgreSQL (Docker)                   |
| **Infra**       | Docker, GitHub Actions                |

## 📦 Instalação Local

### Pré-requisitos
- Node.js 16+
- Docker 20+
- VS Code (recomendado)

```bash
# 1. Clone o repositório
git clone https://github.com/seu-usuario/taskflow.git
cd taskflow

# 2. Inicie o PostgreSQL
docker-compose up -d

# 3. Configure backend (Node.js)
cd backend
npm install
npm run dev

# 4. Configure frontend
cd ../frontend
npm install
npm run dev
