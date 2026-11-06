<h2 align="center">🚗 Beep Beep - IF | Carona Universitária</h2>

<p align="center">
  <img
    src="assets/equipe/Logo%20Beep%20Beep.jpg"
    width="260"
    alt="Logo Beep Beep - IF"
  />
</p>

<p align="center">
  <strong>Conectando universitários através de caronas compartilhadas!</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/STATUS-EM%20DESENVOLVIMENTO-yellow?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/React-Biblioteca-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React">
  <img src="https://img.shields.io/badge/SQLite3-Database-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite3">
</p>

---

<h2 align="center">📑 Índice</h2>

- [Descrição do Projeto](#-descrição-do-projeto)
- [Status do Projeto](#-status-do-projeto)
- [Funcionalidades](#-funcionalidades-do-projeto)
- [Demonstração da Aplicação](#-demonstração-da-aplicação)
- [Acesso ao Projeto](#-acesso-ao-projeto)
- [Como executar o projeto](#-como-executar-o-projeto)
- [Modelagem do Sistema](#-modelagem-do-sistema)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Pessoas Contribuidoras](#-pessoas-contribuidoras)
- [Pessoas Desenvolvedoras](#-pessoas-desenvolvedoras)
- [Licença](#-licença)

---

<h2 align="center">📖 Descrição do Projeto</h2>

O **Beep Beep - IF** é um sistema de caronas universitárias desenvolvido com o objetivo de facilitar a mobilidade dos estudantes, conectando pessoas que precisam de transporte com motoristas que possuem vagas disponíveis em seus veículos.

A plataforma busca proporcionar uma maneira organizada de oferecer e solicitar caronas, permitindo que os estudantes encontrem viagens de acordo com a origem, destino, dia e horário desejados.

O sistema também contempla o gerenciamento de usuários, veículos, rotas e solicitações de carona, além da possibilidade de avaliação das viagens realizadas.

Dessa forma, o Beep Beep busca incentivar o compartilhamento de transporte no ambiente universitário, promovendo praticidade, economia e colaboração entre os estudantes.

---

<h2 align="center">🚧 Status do Projeto</h2>

<p align="center">
  <img src="https://img.shields.io/badge/STATUS-EM%20DESENVOLVIMENTO-yellow?style=for-the-badge" alt="Em desenvolvimento">
</p>

<p align="center">
  O projeto encontra-se em desenvolvimento.
</p>

As funcionalidades apresentadas neste documento são baseadas nos requisitos e diagramas de modelagem do sistema, podendo sofrer alterações durante a implementação.

---

<h2 align="center">🔨 Funcionalidades do Projeto</h2>

As funcionalidades previstas para o sistema estão organizadas de acordo com os perfis de usuários.

<h3>👤 Usuário</h3>

- Cadastro utilizando e-mail institucional.
- Autenticação no sistema.
- Gerenciamento de informações pessoais.

<h3>🚶 Passageiro</h3>

- Buscar caronas disponíveis.
- Filtrar viagens por origem, horário e dia.
- Solicitar caronas.
- Consultar viagens.
- Acompanhar solicitações.
- Avaliar viagens realizadas.
- Enviar notas e comentários.

<h3>🚗 Motorista</h3>

- Cadastrar e gerenciar veículos.
- Publicar viagens.
- Definir dias recorrentes.
- Gerenciar rotas.
- Aceitar solicitações de carona.
- Recusar solicitações de carona.
- Atualizar a quantidade de vagas disponíveis.

<h3>⚙️ Administrador</h3>

- Autenticar-se no sistema.
- Manter e gerenciar usuários.

> **Observação:** as funcionalidades listadas representam os requisitos identificados na modelagem e não garantem que todas já estejam implementadas.

---

<h2 align="center">🖥️ Demonstração da Aplicação</h2>

Nesta seção serão disponibilizadas capturas de tela e demonstrações das funcionalidades do sistema.

As imagens serão adicionadas conforme o desenvolvimento da interface.

**Exemplos de telas que poderão ser apresentados:**

- Tela de login e cadastro;
- Tela de busca de caronas;
- Tela de publicação de viagens;
- Tela de solicitações;
- Tela de avaliação de viagens.

---

<h2 align="center">📁 Acesso ao Projeto</h2>

<p align="center">
  O código-fonte do projeto está disponível no GitHub.
</p>

<p align="center">
  <a href="https://github.com/micoliveira/Peep-Beep">
    <img src="https://img.shields.io/badge/GitHub-Repositório-181717?style=for-the-badge&logo=github" alt="Repositório GitHub">
  </a>
</p>

Para clonar o repositório, utilize:

```bash
git clone https://github.com/micoliveira/Peep-Beep.git
```

Entre na pasta do projeto:

```bash
cd Peep-Beep
```

---

<h2 align="center">⚙️ Como executar o projeto</h2>

As instruções específicas de instalação e execução serão adicionadas após a confirmação das configurações e dependências utilizadas na implementação.

**Pré-requisitos:**

- Git instalado;
- Node.js, caso utilizado na configuração do React;
- Ambiente de desenvolvimento compatível com o projeto.

**Etapas iniciais:**

1. Clone o repositório.
2. Abra a pasta do projeto em sua IDE.
3. Instale as dependências necessárias.
4. Configure o ambiente.
5. Execute a aplicação conforme as instruções específicas do projeto.

---

<h2 align="center">📐 Modelagem do Sistema</h2>

A modelagem do Beep Beep foi elaborada utilizando diagramas UML, representando a estrutura, os comportamentos e as interações do sistema.

<h3>Diagrama de Classes</h3>

Representa as entidades e seus relacionamentos, incluindo:

- Usuário;
- Endereço;
- Passageiro;
- Motorista;
- Veículo;
- Carona;
- Parada;
- Rota;
- Feedback.

<h3>Diagrama de Casos de Uso</h3>

Representa as interações dos atores com o sistema, incluindo aluno, passageiro, motorista e administrador.

<h3>Diagrama de Atividades</h3>

Apresenta os fluxos de atividades do sistema, detalhando os processos de acesso, utilização por universitários, gerenciamento de viagens por motoristas, avaliação e administração.

---

<h2 align="center">💻 Tecnologias Utilizadas</h2>

<p align="center">
  Tecnologias utilizadas no desenvolvimento do Beep Beep - IF.
</p>

<h3>JavaScript</h3>

Linguagem de programação utilizada no desenvolvimento das funcionalidades e regras de funcionamento da aplicação.

<h3>React</h3>

Biblioteca JavaScript utilizada para a construção da interface do usuário, permitindo o desenvolvimento de componentes reutilizáveis e interfaces dinâmicas.

<h3>SQLite3</h3>

Sistema gerenciador de banco de dados relacional utilizado para armazenar e organizar as informações da aplicação.

<h3 align="center">Ferramentas de desenvolvimento</h3>

- **Git:** ferramenta de controle de versão utilizada para acompanhar as alterações no código.
- **GitHub:** plataforma utilizada para hospedagem e gerenciamento do repositório do projeto.

---

<h2 align="center">🤝 Pessoas Contribuidoras</h2>

Esta seção é dedicada às pessoas que contribuíram para o desenvolvimento do projeto.

As contribuições poderão envolver implementação, documentação, modelagem, testes e melhorias no sistema.

<p align="center">
  <strong>Conheça a equipe responsável pelo desenvolvimento do Beep Beep - IF!</strong>
</p>

<table align="center">
  <tr>
    <td align="center" width="50%">
      <img src="assets/equipe/caroline.jpg" width="150" alt="Foto de Caroline">
      <br><br>
      <strong>Caroline Stephanie Paulino de Campos</strong>
    </td>
    <td align="center" width="50%">
      <img src="assets/equipe/francisco.jpg" width="150" alt="Foto de Francisco">
      <br><br>
      <strong>Francisco Henrique da Silva Neto</strong>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="assets/equipe/maria-gabriela.jpg" width="150" alt="Foto de Maria Gabriela">
      <br><br>
      <strong>Maria Gabriela Lopes dos Santos</strong>
    </td>
    <td align="center" width="50%">
      <img src="assets/equipe/michele.jpg" width="150" alt="Foto de Michele">
      <br><br>
      <strong>Michele Maria de Oliveira</strong>
    </td>
  </tr>
</table>

---

<h2 align="center">📜 Licença</h2>

A licença do projeto ainda não foi definida.

As informações sobre utilização, modificação e distribuição do software serão disponibilizadas após a escolha e inclusão da licença oficial no repositório.

---

<p align="center">
  Desenvolvido com 💚 para a comunidade universitária.
</p>

<p align="center">
  <strong>Beep Beep - IF | Carona Universitária 🚗</strong>
</p>
