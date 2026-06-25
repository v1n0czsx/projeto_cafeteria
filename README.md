# 🏗️ Estrutura do Projeto

Este projeto foi organizado seguindo uma estrutura simples e modular, onde cada arquivo possui uma responsabilidade específica dentro da aplicação. Essa separação facilita o desenvolvimento, manutenção e futuras expansões do sistema.

---

## 🏠 index.html

Representa a porta de entrada da aplicação, sendo responsável por apresentar a interface principal ao usuário.

### Responsabilidades

* Construção da página inicial.
* Exibição do conteúdo principal.
* Navegação entre as páginas do projeto.
* Organização da estrutura HTML.

---

## 📞 contato.html

Responsável pela comunicação entre o usuário e a aplicação através de um formulário de contato.

### Responsabilidades

* Disponibilizar formulário de contato.
* Coletar informações do usuário.
* Manter a identidade visual da aplicação.
* Complementar a navegação do sistema.

---

## 🎨 style.css

Centraliza toda a camada visual do projeto, separando completamente a apresentação da estrutura HTML.

### Responsabilidades

* Definir cores, fontes e espaçamentos.
* Construir o layout da aplicação.
* Aplicar responsividade.
* Melhorar a experiência visual do usuário.
* Padronizar todos os componentes.

---

## ⚙️ server.js

Núcleo responsável pelo funcionamento da aplicação no servidor utilizando Express.js.

### Responsabilidades

* Inicializar o servidor.
* Disponibilizar os arquivos da aplicação.
* Gerenciar as rotas.
* Fornecer dados através da API.
* Controlar o ambiente de execução.

---

## 📦 package.json

Arquivo que define toda a configuração do projeto Node.js.

### Responsabilidades

* Gerenciar dependências.
* Definir scripts de execução.
* Configurar informações da aplicação.
* Especificar tecnologias utilizadas.

---

## 🔒 package-lock.json

Arquivo gerado automaticamente pelo NPM para garantir consistência entre diferentes ambientes de desenvolvimento.

### Responsabilidades

* Registrar versões exatas das dependências.
* Garantir instalações reproduzíveis.
* Evitar incompatibilidades entre bibliotecas.
* Assegurar estabilidade durante o desenvolvimento.

---

# 📁 Organização Geral

```text
Projeto
│
├── 📄 index.html        → Interface principal
├── 📄 contato.html      → Página de contato
├── 🎨 style.css         → Estilização da aplicação
├── ⚙️ server.js         → Servidor Express
├── 📦 package.json      → Configuração do projeto
└── 🔒 package-lock.json → Controle das dependências
```

---

# 🎯 Objetivo da Estrutura

A arquitetura foi organizada com foco na separação de responsabilidades, permitindo que cada componente desempenhe uma função específica dentro da aplicação. Essa abordagem torna o código mais limpo, reutilizável e de fácil manutenção, além de facilitar futuras implementações e a colaboração entre desenvolvedores.
