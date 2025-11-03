# Blog do Asdrubal 

Um blog pessoal desenvolvido em React com design responsivo, criado nas aulas de Web 2. O projeto conta a história de Asdrubal Topolinsk e apresenta um sistema de postagens dinâmico.

## Sobre o Projeto

Este projeto foi desenvolvido como parte das aulas de Web 2 e apresenta:

- **Página Inicial**: Listagem de posts em layout de grid responsivo
- **Página Sobre Mim**: Biografia completa de Asdrubal Topolinsk
- **Páginas de Postagem**: Visualização individual de posts com suporte a markdown
- **Página 404**: Página personalizada para rotas não encontradas
- **Design Responsivo**: Adaptável para desktop, tablet e mobile

## Objetivos de Aprendizado

- Desenvolvimento de Single Page Application (SPA) com React
- Implementação de roteamento com React Router
- Utilização de CSS Modules para estilização
- Trabalho com componentes reutilizáveis
- Manipulação de dados JSON estáticos
- Implementação de design responsivo
- Uso do React Markdown para renderização de conteúdo

## Tecnologias Utilizadas

- **React** - Biblioteca principal para construção da interface
- **React Router** - Gerenciamento de rotas e navegação
- **React Markdown** - Renderização de conteúdo em markdown
- **CSS Modules** - Estilização modularizada e escopada
- **Vite** - Build tool e dev server para desenvolvimento rápido
- **JSON** - Armazenamento estático dos dados dos posts

## Estrutura do Projeto

```
src/
├── assets/              # Imagens e recursos estáticos
│   ├── erro_404.png
│   ├── sobre_mim_capa.png
│   └── sobre_mim_foto.jpeg
├── componentes/         # Componentes reutilizáveis
│   └── PostModelo/     # Componente base para páginas de conteúdo
├── json/               # Dados estáticos
│   └── posts.json      # Lista de posts do blog
├── paginas/            # Páginas da aplicação
│   ├── Inicio/         # Página inicial com listagem de posts
│   ├── Postagem/       # Página individual de post
│   ├── SobreMim/       # Página "Sobre mim"
│   └── NaoEncontrada/  # Página 404
├── App.css             # Estilos globais
└── main.jsx            # Ponto de entrada da aplicação
```

## Componentes Principais

### PostModelo
Componente base que fornece layout consistente para páginas de conteúdo, incluindo capa e título.

### Post
Componente para exibição de cards de posts na página inicial.

### Páginas
- **Inicio**: Exibe grid responsivo com todos os posts
- **Postagem**: Renderiza conteúdo completo do post em markdown
- **SobreMim**: Apresenta biografia com layout de texto envolvente
- **NaoEncontrada**: Página 404 personalizada com ilustração

## Funcionalidades

- **Navegação entre páginas** sem recarregamento
- **Layout responsivo** que se adapta a diferentes tamanhos de tela
- **Sistema de posts** com conteúdo em markdown
- **Design consistente** com variáveis CSS para cores e fontes
- **Tratamento de erros** com página 404 personalizada

## Como Executar

```bash
# Instalar dependências
npm install

# Executar em modo desenvolvimento
npm run dev

# Build para produção
npm run build
```
