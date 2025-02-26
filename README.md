# 🎵 Spotify Imersão Alura

Desenvolvido durante a Imersão Front-End 2024 da Alura, esse projeto recria a interface inicial do Spotify do zero. Usando HTML, CSS, JavaScript, Node.js e JSON, o objetivo é oferecer uma experiência de usuário fluida e interativa, com design responsivo e boas práticas de desenvolvimento.

A interatividade do projeto é impulsionada pelo uso de JavaScript, que permite funcionalidades como a busca dinâmica de artistas e a atualização em tempo real da interface. Com o auxílio do JSON Server, simulamos uma API local que responde às requisições de pesquisa e exibe resultados, proporcionando uma experiência mais realista, como se estivéssemos realmente conectados ao Spotify.

![screenshot](src\assets\screenshot.png)

## 🚀 Tecnologias Utilizadas

-   HTML → Estruturação do conteúdo
-   CSS → Estilização e responsividade (Flexbox & Grid)
-   JavaScript → Manipulação do DOM e interatividade
-   Node.js → Ambiente para simulação de API local
-   JSON → Base de dados simulada

## 📌 Funcionalidades

✔ Recriação da interface inicial do Spotify \
✔ Design responsivo com Media Queries \
✔ Sidebar e menu superior estilizados \
✔ Layout flexível com Flexbox e CSS Grid \
✔ Simulação de API com JSON \
✔ Introdução ao JavaScript e manipulação do DOM

## 📂 Estrutura do Projeto

```plaintext
📦 SPOTIFY-IMERSAO-ALURA
├── .vscode/                # Configurações do VS Code
├── api-artists/            # Simulação de API com JSON
├── src/                    # Código-fonte
│   ├── assets/             # Ícones e playlists
│   ├── styles/             # Estilos CSS modulares
├── index.html              # Estrutura principal do site
├── script.js               # Funcionalidades interativas
├── artists.json            # Dados dos artistas
```

## 📚 Conteúdo das Aulas

1️⃣ HTML & CSS → Sidebar, atalhos do VSCode e estilização inicial \
2️⃣ CSS Avançado → Flexbox, posicionamento e melhorias no layout \
3️⃣ Estrutura & Responsividade → Refatoração, variáveis CSS e menu superior \
4️⃣ CSS Grid & JavaScript → Cards dinâmicos, media queries e introdução ao DOM \
5️⃣ Introdução ao React.js → Explicação teórica sobre o framework (implementação em outro [repositório](https://github.com/arielprovasi/spotify-react))

## 🔧 Como Rodar o Projeto

1. Clone o repositório:
    ```sh
    git clone https://github.com/seu-usuario/spotify-imersao-alura.git
    ```
2. Acesse a pasta do projeto:
    ```sh
    cd spotify-imersao-alura
    ```
3. Abra o `index.html` no navegador ou utilize a extensão **Live Server** no VSCode.

### 🔹 Rodando o JSON Server

Se o projeto precisar simular uma API local com JSON:

1. Instale o [**JSON Server**](https://www.npmjs.com/package/json-server) (caso ainda não tenha):
    ```sh
    npm install -g json-server
    ```
2. Navegue até a pasta do projeto e execute o servidor:
    ```sh
    json-server --watch api-artists/artists.json
    ```
3. O servidor estará disponível em:
    ```
    http://localhost:3000/artists
    ```

---

## 🤝 Contribuições

Se quiser contribuir, faça um fork do repositório, crie uma branch para suas alterações e envie um pull request. Toda ajuda é bem-vinda!

## 💡 Melhorias Futuras

-   Integração com a API oficial do Spotify
-   Implementação de um player funcional
-   Modo escuro e ajustes visuais adicionais

## 📜 Licença

Este projeto está licenciado sob a licença [MIT](https://choosealicense.com/licenses/mit/).
