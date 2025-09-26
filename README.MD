# 🔗 Integração com a API do GitHub

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

Este projeto é um exemplo simples de integração com a **GitHub REST API**, mostrando como buscar informações de um usuário e exibi-las em uma página web.

---

## ✨ Funcionalidades

- Exibe dinamicamente dados do usuário do GitHub:
  - Nome completo
  - Username
  - Avatar
  - Número de repositórios públicos
  - Seguidores
  - Seguindo
  - Link direto para o perfil do GitHub

---

## 🛠 Tecnologias

- HTML5
- CSS3
- JavaScript (Fetch API)

---

## 🚀 Como usar

1. Clone este repositório:

```bash
git clone https://github.com/Igorvieira97/exercicio_ajax.git 

```

2. Abra ajax.html em um navegador moderno.

3. Os dados do usuário Igorvieira97 serão carregados automaticamente.

Para mostrar outro usuário, altere a variável endpoint no arquivo ajax.html:

const endpoint = "https://api.github.com/users/OutroUsuario";

📂 Estrutura do projeto
├── ajax.html      # Página principal
├── main.css       # Estilos do projeto
└── README.md      # Este arquivo