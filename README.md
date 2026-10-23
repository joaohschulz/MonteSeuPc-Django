
# 🖥️ PC Builder — Sistema de Montagem de Computadores

Sistema web desenvolvido em **Python e Django** que permite aos usuários criar, personalizar e gerenciar configurações de computadores por meio de uma interface intuitiva.

O projeto foi desenvolvido com o objetivo de aplicar conhecimentos de desenvolvimento web, programação orientada a objetos, banco de dados e autenticação de usuários.

## 📌 Sobre o Projeto

O **PC Builder** é uma aplicação web que possibilita montar configurações de computadores selecionando diferentes componentes de hardware.

Cada usuário possui sua própria conta, podendo cadastrar, visualizar e excluir seus computadores de maneira independente.

A aplicação utiliza o framework Django para gerenciar as regras de negócio, persistência dos dados e autenticação.

## 🚀 Funcionalidades

- ✅ Cadastro de usuários.
- ✅ Login e autenticação.
- ✅ Dashboard personalizado.
- ✅ Criação de configurações de computadores.
- ✅ Seleção de componentes de hardware.
- ✅ Listagem dos computadores cadastrados.
- ✅ Exclusão de computadores.
- ✅ Associação de computadores aos respectivos usuários.
- ✅ Controle de acesso às páginas protegidas.
- ✅ Interface web personalizada.

## 🔧 Componentes de Hardware

O sistema trabalha com diferentes categorias de componentes:

- **Processador (CPU)**
- **Placa-mãe**
- **Memória RAM**
- **Armazenamento**
- **Placa de vídeo (GPU)**
- **Fonte de alimentação**

Os componentes são utilizados para compor as configurações dos computadores cadastrados pelos usuários.

## 🛠️ Tecnologias Utilizadas

- **Python** — Linguagem de programação utilizada no backend.
- **Django** — Framework responsável pela estrutura da aplicação.
- **HTML5** — Estrutura das páginas.
- **CSS3** — Estilização e interface visual.
- **Django Templates** — Renderização dinâmica das páginas.
- **Django ORM** — Comunicação com o banco de dados.
- **Git** — Controle de versionamento.
- **GitHub** — Hospedagem e gerenciamento do código-fonte.

## ⚙️ Instalação e Execução

### 1. Clone o repositório

```bash
git clone https://github.com/joaohschulz/Sistema-de-Cria-o-de-PCs-a-partir-de-suas-pe-as.git
```

### 2. Acesse o diretório do projeto

```bash
cd Sistema-de-Cria-o-de-PCs-a-partir-de-suas-pe-as
```

### 3. Crie um ambiente virtual

```bash
python -m venv .venv
```

### 4. Ative o ambiente virtual

**Windows:**

```bash
.venv\Scripts\activate
```

**Linux/macOS:**

```bash
source .venv/bin/activate
```

### 5. Instale as dependências

Caso o projeto possua um arquivo `requirements.txt`:

```bash
pip install -r requirements.txt
```

### 6. Configure o banco de dados

No diretório que contém o arquivo `manage.py`, execute:

```bash
python manage.py migrate
```

### 7. Inicie o servidor

```bash
python manage.py runserver
```

Acesse no navegador:

```text
http://127.0.0.1:8000/
```

> **Observação:** dependendo da configuração do ambiente, pode ser necessário ajustar variáveis de ambiente e instalar dependências adicionais.

## 👤 Autenticação e Segurança

O projeto utiliza o sistema de autenticação do Django para controlar o acesso dos usuários.

Cada computador cadastrado é associado ao usuário responsável por sua criação.

Dessa forma, o sistema permite organizar os registros individualmente, mantendo a separação entre os dados das diferentes contas.

## 🎯 Objetivos do Projeto

O desenvolvimento da aplicação teve como principais objetivos:

- Aplicar conceitos de programação com Python.
- Desenvolver uma aplicação utilizando Django.
- Trabalhar com operações CRUD.
- Implementar autenticação e controle de acesso.
- Utilizar modelos e relacionamentos de banco de dados.
- Desenvolver formulários com Django.
- Criar interfaces utilizando HTML e CSS.
- Praticar a arquitetura Model-Template-View (MTV).
- Desenvolver um projeto completo para portfólio.

## 📚 Conhecimentos Aplicados

Durante o desenvolvimento foram utilizados conceitos como:

- Programação orientada a objetos.
- Modelagem de banco de dados.
- Django Models e Django ORM.
- Class-Based Views (CBVs).
- Django Forms.
- Autenticação e gerenciamento de sessões.
- Relacionamentos entre modelos.
- Renderização de templates.
- Controle de versionamento com Git.

## 📊 Status do Projeto

✅ **Projeto finalizado.**

O sistema foi desenvolvido como projeto prático de aprendizado e portfólio, contemplando funcionalidades de autenticação, criação e gerenciamento de configurações de computadores.

## 👨‍💻 Desenvolvedor

**João Henrique Schulz**

Desenvolvedor em formação, com foco em desenvolvimento backend utilizando Python e Django.

🔗 [GitHub](https://github.com/joaohschulz)

---

⭐ Se você gostou do projeto, considere deixar uma estrela no repositório!
