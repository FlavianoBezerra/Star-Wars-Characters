# Projeto Personagens de Star Wars

Este projeto permite visualizar informações sobre personagens do universo de Star Wars, obtidas através de uma API pública. O objetivo é mostrar como integrar dados externos em uma aplicação web simples utilizando **HTML**, **CSS** e **JavaScript**.
- [Acessar projeto online](https://star-wars-characters-sepia.vercel.app/).

## Tecnologias Utilizadas

- **HTML**: Para estrutura e conteúdo das páginas.
- **CSS**: Para estilizar a página e melhorar a aparência visual.
- **JavaScript**: Para interagir com a API, exibir os dados e adicionar dinamismo à página.
- **API**: A API pública de Star Wars (SWAPI) retorna dados sobre os personagens, veículos e planetas do universo Star Wars.

## Estrutura de Diretórios

A estrutura do projeto é organizada da seguinte forma:


### Descrição dos Arquivos

- **assets/**: Contém recursos adicionais como imagens e ícones.
- **LICENSE**: Arquivo de licença do projeto (geralmente MIT ou outra).
- **index.html**: Página principal da aplicação onde os dados dos personagens de Star Wars são exibidos.
- **script.js**: Contém a lógica JavaScript para fazer as requisições à API e atualizar a interface com os dados dos personagens.
- **style.css**: Arquivo de estilos para a página.

## Como Rodar o Projeto

### Requisitos

- Um navegador da web (Chrome, Firefox, etc.)
- Conexão com a internet para fazer as requisições à API.

### Rodando localmente

1. Clone este repositório para o seu computador:
   ```bash
   git clone https://github.com/FlavianoBezerra/Star-Wars-Characters.git
Abra o projeto no VS Code (ou qualquer editor de sua preferência). Se estiver usando o VS Code, abra o arquivo index.html da página inicial e clique com o botão direito para "Open with Live Server". Isso permitirá que você veja o projeto em tempo real no navegador. Alternativamente, abra o arquivo index.html diretamente no navegador.

### Funcionalidades
A página exibe uma lista de personagens do universo Star Wars, como Luke Skywalker, Darth Vader, etc.
Os dados dos personagens são carregados dinamicamente a partir da SWAPI (Star Wars API) via requisições HTTP.
O usuário pode visualizar informações como nome, altura, cor de cabelo, entre outros detalhes dos personagens.
### Lógica de Integração com a API
A API utilizada neste projeto é a SWAPI (https://swapi.dev/), que fornece dados sobre o universo Star Wars. No projeto, usamos JavaScript para fazer uma requisição GET à API e retornar uma lista de personagens.

## Licença

Este projeto está licenciado sob a Licença MIT – veja o arquivo [LICENSE](LICENSE) para mais detalhes.

Criado por [Flaviano Bezerra](https://www.linkedin.com/in/flaviano-bezerra-5203bb333).
