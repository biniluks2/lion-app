# 🦁 LION APP — Organizador de Informações para Imposto de Renda

## 📌 Sobre o projeto

O **LION APP** é uma ferramenta desenvolvida em **Microsoft Excel** com o objetivo de centralizar e organizar informações necessárias para auxiliar na preparação da declaração de Imposto de Renda.

A proposta é transformar uma planilha tradicional em uma interface mais organizada e intuitiva, permitindo que o usuário cadastre seus dados, registre informações financeiras e acompanhe suas entradas em um único ambiente.

O projeto foi desenvolvido como parte de um desafio prático, aplicando recursos de Excel para criação de uma solução funcional, estruturada e de fácil utilização.

---

## 🎯 Objetivos

- Centralizar informações relevantes para a declaração de Imposto de Renda;
- Facilitar o preenchimento e a consulta dos dados;
- Organizar informações do titular;
- Registrar informes de rendimentos bancários;
- Controlar entradas financeiras e rendimentos;
- Criar uma interface de navegação simples e intuitiva;
- Utilizar recursos do Excel para validação e automatização de informações;
- Demonstrar, na prática, os conhecimentos adquiridos durante o desafio.

---

## 🧩 Estrutura da solução

O arquivo Excel está organizado em diferentes áreas de navegação:

### 👤 Titular

Área destinada ao cadastro das informações pessoais do titular, incluindo:

- Nome;
- CPF;
- Data de nascimento;
- Título de eleitor;
- Cônjuge;
- Endereço;
- CEP;
- Telefone e celular;
- E-mail;
- Alterações da entrega anterior;
- Dependente do cônjuge;
- Residente no exterior.

### 🏦 Informes

Área destinada ao registro dos **informes de rendimentos bancários**.

Para cada instituição podem ser registrados:

- Banco;
- Valor atual;
- Anexo correspondente.

A ferramenta também apresenta o **valor total** dos rendimentos cadastrados, facilitando a consolidação das informações.

### 🧾 Notas

Área destinada ao lançamento das entradas financeiras, permitindo registrar:

- Data;
- Categoria;
- Valor.

Essa estrutura possibilita manter um histórico organizado das receitas informadas pelo usuário.

---

## 🖥️ Interface

A solução possui uma interface visual com identidade própria, utilizando o nome **LION APP** e um menu lateral para navegação entre as principais áreas da ferramenta.

A navegação também conta com botões como:

- **Anterior**
- **Próximo**
- Acesso direto às áreas **Titular**, **Informes** e **Notas**

O objetivo da interface é tornar a utilização da planilha mais próxima da experiência de uma pequena aplicação, reduzindo a necessidade de navegação manual entre células e abas.

---

## ⚙️ Recursos utilizados

O projeto utiliza recursos nativos do Microsoft Excel para construção da solução, incluindo:

- Organização de dados em tabelas;
- Fórmulas para consolidação de valores;
- Formatação condicional e formatação personalizada;
- Validação de dados;
- Listas e menus de seleção;
- Navegação entre áreas da planilha;
- Hiperlinks e/ou controles de navegação;
- Organização visual das informações;
- Estruturação de campos para preenchimento do usuário.

---

## 📸 Demonstração

### Tela — Dados do Titular

![Tela de dados do titular](images/titular.jpg)

### Tela — Informes de Rendimentos Bancários

![Tela de informes bancários](images/informes.jpg)

### Tela — Notas Bancárias ou Extratos de Holerites

![Tela de notas e entradas](images/notas.jpg)

---

## 📁 Estrutura do repositório

```text
LION-APP/
│
├── README.md
│
├── excel/
│   └── LION_APP.xlsx
│
└── images/
    ├── titular.jpg
    ├── informes.jpg
    └── notas.jpg
```

> Caso o arquivo Excel tenha outro nome, basta ajustar o nome no diretório `excel/`.

---

## 🚀 Como utilizar

1. Faça o download ou clone este repositório;
2. Acesse a pasta `excel`;
3. Abra o arquivo `LION_APP.xlsx` utilizando o Microsoft Excel;
4. Comece pelo cadastro dos dados do titular;
5. Preencha os informes de rendimentos;
6. Registre as entradas na área de notas;
7. Utilize os menus e botões de navegação para alternar entre as áreas.

---

## 🛠️ Tecnologias e ferramentas

- **Microsoft Excel**
- Fórmulas e funções do Excel
- Validação de dados
- Formatação de planilhas
- Recursos de navegação e interface
- **GitHub** para versionamento e documentação do projeto

---

## 📚 Aprendizados

Durante o desenvolvimento do projeto foram aplicados conhecimentos relacionados a:

- Organização e estruturação de planilhas;
- Criação de interfaces no Excel;
- Automatização de cálculos;
- Validação e padronização de dados;
- Organização de informações financeiras;
- Documentação técnica;
- Versionamento e publicação de projetos utilizando GitHub.

---

## 👨‍💻 Autor

**Rodrigo**

Projeto desenvolvido como parte de um desafio prático de Excel e GitHub.

---

## 📄 Observação

Este projeto possui finalidade **educacional e organizacional**. A ferramenta tem como objetivo auxiliar na organização das informações e não substitui a análise ou orientação de um profissional especializado em declaração de Imposto de Renda.
