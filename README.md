# Lucas Lusni — portfólio

Site pessoal com foco em desenvolvimento full stack usando JavaScript, TypeScript, Node.js e Angular.

## Conteúdo

- Apresentação profissional e tecnologias.
- Projetos reais: Vexel, Controle de Acervo Racnegê, concorrência em Node.js e Monsten.
- Links para os repositórios, LinkedIn e e-mail.
- Layout responsivo, navegação por teclado e respeito à preferência de movimento reduzido.

O site é estático: HTML, CSS e JavaScript, sem dependências de build.

## Executar

Abra `Portifolio/index.html` no navegador ou sirva a raiz com Python 3:

```sh
git clone https://github.com/lucaslusni/Portfolio.git
cd Portfolio
python -m http.server 8000
```

Abra http://localhost:8000. O arquivo da raiz redireciona para `Portifolio/`.

## Estrutura

- `index.html`: entrada da raiz.
- `Portifolio/index.html`: página completa.
- `Portifolio/styles.css`: layout e responsividade.
- `Portifolio/script.js`: ano exibido no rodapé.
- `Portifolio/img/`: arquivos anteriores preservados; não são necessários para o layout atual.

## Publicação

A raiz pode ser servida por uma hospedagem estática. Para GitHub Pages, selecione a branch desejada e a pasta raiz nas configurações do repositório. A configuração de hospedagem não é ativada por estes arquivos.

Os links dos projetos apontam para o código-fonte, não para demonstrações públicas que ainda não foram verificadas. O [Controle de Acervo Racnegê](https://github.com/lucaslusni/Tcc-Controle-acervo-racnege) inclui backend Fastify/Prisma, frontend React e migrações PostgreSQL.

