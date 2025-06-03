# Projeto Filmes

Este é um projeto web desenvolvido em PHP, nascido da ideia de criar uma plataforma intuitiva para **gerenciamento e classificação de filmes**.

O intuito inicial foi proporcionar um ambiente onde entusiastas de cinema, como uma amiga próxima, pudessem registrar seus filmes favoritos, classificá-los e, de quebra, servir como um ponto de partida para a criação de um **círculo social em torno do cinema**, incentivando a troca de ideias e a descoberta de novas obras.

Profissionalmente, este projeto representa a aplicação prática dos conhecimentos adquiridos em disciplinas como **Programação Web, Banco de Dados e Programação Avançada com PHP**, demonstrando habilidades em desenvolvimento back-end e front-end (com foco em expansão), e a construção de um sistema web funcional e escalável.

Este projeto está atualmente em **fase de desenvolvimento inicial** e pretendo realizar **atualizações semanais** para adicionar novas funcionalidades e refinar as existentes.

### Tecnologias Utilizadas

* **PHP:** Linguagem de programação back-end.
* **MySQL:** Sistema de gerenciamento de banco de dados relacional.
* **PDO:** Extensão do PHP para acesso a banco de dados.
* **HTML:** Para a estrutura das páginas web.
* **CSS:** Para estilização das páginas (já em uso e será atualizado).
* **JavaScript (em breve):** Para interatividade front-end.
* **XAMPP:** Ambiente de desenvolvimento local.
* **Sublime Text:** Editor de código.

### Funcionalidades Atuais

* **Conexão Robusta com Banco de Dados:** Estabelecimento de uma conexão segura com o MySQL utilizando PDO, com tratamento de erros configurado.
* **Configuração de Ambiente Dinâmica:** Definição de uma URL base global para facilitar a construção de caminhos e recursos no projeto.
* **Estrutura de Projeto Modular:** Organização inicial do código em arquivos separados (`db.php`, `globals.php`, `index.php`), promovendo a reutilização e manutenção.
* **Página de Boas-Vindas:** Exibição de uma página HTML básica (`index.php`), confirmando o funcionamento do ambiente de desenvolvimento.

### Funcionalidades Futuras (Roadmap)

Este é um roteiro das funcionalidades que serão implementadas nas próximas semanas. [cite_start]O projeto visa concluir o desenvolvimento, incluindo a criação de arquivos como `editmovie.php` [cite: 3] [cite_start]e `search.php` [cite: 3][cite_start], e a atualização do `styles.css`.

* **Sistema de Autenticação:**
    * Cadastro de novos usuários.
    * Login e Logout de usuários.
* **Gerenciamento de Usuários:**
    * Edição de perfil do usuário (nome, sobrenome, e-mail, foto, "sobre mim").
* **Gerenciamento de Filmes (CRUD):**
    * Adicionar novos filmes (Título, Imagem, Duração, Categoria, Trailer, Descrição).
    * Visualizar detalhes de um filme.
    * Editar informações de filmes existentes.
    * Remover filmes.
* **Sistema de Avaliações:**
    * Usuários logados poderão classificar filmes com notas e comentários.
    * Exibição das avaliações de cada filme.
* **Pesquisa de Filmes:**
    * Funcionalidade de busca para encontrar filmes por título ou outros critérios.
* **Melhorias na Interface do Usuário:**
    * Aprimoramento do design e responsividade com CSS.
    * Implementação de interatividade com JavaScript.

### Como Rodar o Projeto

Para executar este projeto em sua máquina local, siga os passos abaixo:

1.  **Pré-requisitos:**
    * Certifique-se de ter o **XAMPP** (ou WAMP/MAMP) instalado em sua máquina. Ele inclui o Apache (servidor web) e o MySQL (servidor de banco de dados), além do PHP.
    * Um navegador web moderno (Google Chrome, Firefox, etc.).

2.  **Clonar o Repositório:**
    * Abra seu terminal ou prompt de comando.
    * Navegue até a pasta `htdocs` dentro da instalação do seu XAMPP (Ex: `C:\xampp\htdocs` no Windows, ou `/Applications/XAMPP/htdocs` no macOS).
    * Clone este repositório:
        ```bash
        git clone git@github.com:lualexan0/Projeto-Filmes.git Projeto-Filmes
        ```

3.  **Configuração do Banco de Dados:**
    * Inicie os módulos **Apache** e **MySQL** no painel de controle do XAMPP.
    * Acesse o **phpMyAdmin** no seu navegador, geralmente em `http://localhost/phpmyadmin/`.
    * Crie um novo banco de dados com o nome `projeto-filmes`.
    * **Importar o Esquema do Banco de Dados:**
        * Localize o arquivo `projeto-filmes.sql` (que contém a estrutura das suas tabelas `movies`, `reviews`, `users`) na raiz do seu projeto clonado.
        * No phpMyAdmin, com o banco de dados `projeto-filmes` selecionado, clique na aba **"Importar"**.
        * Clique em "Escolher arquivo" e selecione o arquivo `projeto-filmes.sql`.
        * Deixe as opções padrão e clique em **"Executar"** (ou "Go"). Isso criará as tabelas em seu banco de dados.

4.  **Acessar o Projeto:**
    * Após seguir os passos anteriores, abra seu navegador e acesse:
        ```
        http://localhost/Projeto-Filmes/
        ```
    * Você deverá ver a página inicial do projeto.

### Contribuição

Contribuições são bem-vindas! Se você tiver sugestões ou quiser contribuir com o código, por favor, abra uma issue ou envie um pull request.

### Autor

* **Luana Alexandre**

### Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo `LICENSE` (se houver) para mais detalhes.
