# React Movie App 
## Sobre o Projeto
Este projeto é uma aplicação web de filmes construída com React, que permite aos usuários explorar filmes populares e obter detalhes completos. A aplicação consome dados da API TMDB (The Movie Database), demonstrando a implementação de conceitos modernos de desenvolvimento frontend, como roteamento client-side e gerenciamento de estado.

Acesse a versão final e veja como a aplicação funciona: [ Acessar a aplicação online](https://frolicking-boba-fb9192.netlify.app/)
  
##  Tecnologias e Conceitos

### Frontend
- React: Biblioteca principal para a construção da interface de usuário.

- HTML5 e CSS3: Usados para estruturação semântica e estilização completa, incluindo design responsivo para se adaptar a qualquer tamanho de tela.

### Gerenciamento de Dados
- Axios: Cliente HTTP para realizar requisições e consumir a API REST do TMDB.

- useState: Hook para gerenciar o estado local dos componentes, como a lista de filmes ou o status de carregamento.

- useEffect: Hook para lidar com efeitos colaterais, como a busca de dados da API ao carregar um componente.

### Navegação (Roteamento Client-Side)
- React Router: Biblioteca para criar uma navegação fluida de Single Page Application (SPA), sem recarregar a página a cada clique.

- useParams: Hook para capturar parâmetros da URL, como o ID de um filme, permitindo carregar a página de detalhes correta.

### Funcionalidades Adicionais
- React Toastify: Componente para exibir notificações elegantes de sucesso ou erro, melhorando o feedback ao usuário.

## Como Rodar o Projeto

```
# 1. Clone o repositório
git clone https://github.com/seu-usuario/seu-repositorio.git

# 2. Navegue até o diretório do projeto
cd seu-repositorio

# 3. Instale as dependências
npm install

# 4. Inicie a aplicação
npm start
```

## Funcionalidades

- Listagem de Filmes Populares: Exibe os filmes mais assistidos na página inicial.

- Detalhes Completos: Ao clicar em um filme, o usuário é redirecionado para uma página com sinopse, capa e outras informações.

- Adicionar aos Favoritos: Permite salvar filmes em uma lista local, utilizando o localStorage.

### Aprendizados Chave

Este projeto foi fundamental para consolidar o conhecimento em:

- Desenvolvimento com React e o uso de Hooks para gerenciar estado e efeitos.

- Integração com APIs REST para buscar e exibir dados dinâmicos.

- Roteamento client-side para uma experiência de usuário mais rápida e nativa.

- Deploy em plataformas cloud

<i><b>Desenvolvido por Lucas Herzinger Souza
