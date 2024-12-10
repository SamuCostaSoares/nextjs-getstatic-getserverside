# nextjs-getstatic-getserverside

# Tecnologias Utilizadas

Next.js: Framework React para aplicações web.

Node.js: Ambiente de execução para JavaScript no servidor.

# Página Estática - getStaticProps

A página inicial utiliza getStaticProps para obter dados durante o build e renderizar uma página estática com esses dados. A página inclui um título, uma descrição e um link para uma página gerada no servidor.

getStaticProps é utilizado para páginas estáticas, ou seja, as páginas são geradas uma vez durante o build do Next.js.

Ideal para conteúdo que não muda frequentemente, como postagens de blogs ou páginas de produtos.

A página gerada com getStaticProps será reutilizada em todas as requisições.

## getStaticProps: Para gerar páginas estáticas durante o build.

# Página Gerada no Servidor - getServerSideProps

A página /server utiliza getServerSideProps para obter dados a cada requisição e renderizar uma página dinâmica. Esta página será gerada no servidor a cada vez que for acessada.

## getServerSideProps: Para gerar páginas dinâmicas no lado do servidor a cada requisição.





