# Catálogo de Livros

Projeto de Desenvolvimento de Aplicações Multimédia — IPB / EsACT — 2026/2027
Entrega intermédia (30%)

## Elementos do grupo
- Lucas Souza
- Gonçalo Tavares

## Objetivo e público-alvo
Aplicação web para consultar um catálogo de livros e adicionar novos livros.
Destina-se a leitores que queiram descobrir e organizar livros de interesse.

## Funcionalidades previstas
**Já implementadas (entrega intermédia):**
- Lista de livros com capa, título e autor
- Mostrar/ocultar detalhes (ano e opinião) de cada livro
- Formulário para adicionar um novo livro, com atualização imediata da lista
- Seleção de uma imagem de capa a partir dos ficheiros do dispositivo

**Previstas para a entrega final:**
- Pesquisa e filtro por autor ou ano
- Marcar livros como favoritos
- Remover livros
- Estilos CSS e adaptação a diferentes ecrãs
- Dados de uma API externa

## Protótipo (esboço)
```
+-----------------------------+
|  Catálogo de Livros       |
+-----------------------------+
| [capa] Título               |
|        Autor                |
|        [Ver detalhes]       |
|        (ano + opinião)      |
| ...                         |
+-----------------------------+
| Adicionar novo livro        |
| Título [____] Autor [____]  |
| Ano [____] Imagem [Escolher]|
| Opinião [__________]        |
| [Adicionar livro]           |
+-----------------------------+
```

## Estrutura
```
src/
  main.jsx
  App.jsx
  components/
    BookList.jsx
    BookCard.jsx
    BookForm.jsx
```

## Como executar
```
npm install
npm run dev
```
Abrir o endereço indicado no terminal (normalmente http://localhost:5173).
