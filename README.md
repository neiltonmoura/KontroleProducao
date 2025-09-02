# 🏭 Krontrole Produção

**Krontrole Produção** é uma ferramenta web desenvolvida para auxiliar o gerenciamento de produção em setores industriais, com funcionalidades voltadas ao controle de dados produtivos mensais/anuais e solicitações de materiais de maneira prática e organizada.

## 🚀 Funcionalidades

### 📊 Dashboard de Produção
- Visualização da produção **mensal** e **anual** com gráficos interativos (utilizando Chart.js).
- Dados segmentados por setores (Produção A, B, C).
- Interface responsiva com layout moderno usando TailwindCSS.

### 📦 Solicitação de Materiais
- Formulário intuitivo para registrar solicitações de materiais.
- Campos obrigatórios:
  - Código do produto
  - Quantidade (validação para valores positivos)
  - Unidade de medida
  - Utilização / Descrição
- Preenchimento automático do nome do produto ao digitar o código, com base em uma lista interna.
- Cada solicitação registrada aparece abaixo do formulário, exibindo:
  - Código
  - Quantidade
  - Unidade
  - Utilização
  - **Status** atual ("Solicitado") com botão para **exclusão** ou futura alteração.

## 📱 Responsividade

A aplicação é totalmente responsiva, funcionando perfeitamente em dispositivos móveis, tablets e desktops.

- **Menu hambúrguer** funcional para navegação mobile
- Estilização flexível com TailwindCSS
- Elementos adaptativos para diferentes larguras de tela

## 🛠️ Tecnologias Utilizadas

- **HTML5**
- **TailwindCSS** – Estilização rápida e responsiva
- **JavaScript (Vanilla)** – Interações no formulário e gráficos
- **Chart.js** – Visualização de dados em gráfico

## 📁 Estrutura

/index.html -> Página inicial (Home)
|-- dashboard.html -> Visualização de gráficos de produção
|-- producao.html -> Página de controle de solicitações
|-- assets/ -> Imagens e ícones
|-- css/ -> Arquivos de estilo (caso haja personalizados)
|-- js/ -> Scripts adicionais

bash
Copiar código

## 📦 Como usar

1. Clone este repositório:

```bash
git clone https://github.com/seu-usuario/krontrole-producao.git
Abra o arquivo index.html ou dashboard.html em seu navegador.

Não há necessidade de back-end para rodar a aplicação. Tudo é feito no front-end.

✅ Futuras melhorias (To-do)
Integração com banco de dados (MySQL / Firebase)

Sistema de login e autenticação

Exportação de relatórios em PDF/Excel

Histórico de status das solicitações

Dashboard por usuário/setor

🧑‍💻 Autor
Desenvolvido por [Neilton Moura].
Projeto criado com foco em usabilidade e produtividade no ambiente industrial.
