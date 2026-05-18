# ecommerce-sintaxwear

Bem-vindo ao repositório do projeto **ecommerce-sintaxwear** — um site estático de exemplo para uma loja de roupas e tênis. Este README descreve a estrutura do projeto, como testar localmente, como contribuir e outras informações úteis.

## Descrição

Projeto front-end estático criado com HTML e CSS, contendo páginas de catálogo e recursos visuais (imagens, ícones e banners). Ideal para estudos e demonstração de layouts responsivos e componentes visuais.

## Tecnologias

- HTML5
- CSS3 (arquivos em `src/`)

## Como visualizar o projeto

1. Abra o arquivo [index.html](index.html) no seu navegador (duplo clique ou arraste para uma aba do navegador).
2. Para testes de responsividade, use as ferramentas de desenvolvedor do navegador (ex.: F12) e altere o tamanho da janela.

Não há dependências ou servidor necessário — o site é totalmente estático.

## Estrutura de pastas

- [index.html](index.html) — página inicial do site
- [pages/tenis_feminino.html](pages/tenis_feminino.html) — página categoria feminina
- [pages/tenis_masculino.html](pages/tenis_masculino.html) — página categoria masculina
- [pages/outlet.html](pages/outlet.html) — página de outlet/promos
- [src/reset.css](src/reset.css) — reset de estilos
- [src/style.css](src/style.css) — estilos principais
- [src/variables.css](src/variables.css) — variáveis e tokens de design
- [images/](images/) — ativos de imagem organizados em subpastas:
	- `banner/` — imagens de banner e hero
	- `favicon/` — ícone do site
	- `icons/` — ícones SVG (redes sociais, menu, etc.)
	- `logo/` — logo do projeto
	- `products/` — imagens de produtos (inclui `clothes/`)

## Observações sobre imagens

Algumas imagens possuem espaços no nome do arquivo (ex.: `shoes nike.jpg`). Ao referenciá-las no código ou publicar, recomenda-se renomear os arquivos sem espaços (ex.: `shoes-nike.jpg`) para evitar problemas em servidores ou URLs.

## Boas práticas para desenvolvimento

- Edite os estilos em [src/style.css](src/style.css) e variáveis em [src/variables.css](src/variables.css).
- Utilize `src/reset.css` para ajustar estilos base antes de modificar componentes.
- Mantenha os ativos de imagem em pastas organizadas e com nomes amigáveis para URLs.

## Como contribuir

1. Faça um fork ou copie o repositório para sua máquina.
2. Faça alterações em uma branch separada.
3. Teste os arquivos localmente abrindo `index.html`.
4. Envie um pull request com uma descrição clara das mudanças.

## Licença

Este projeto de exemplo não possui uma licença explícita no repositório. Se desejar, adicione uma licença (ex.: MIT) criando um arquivo `LICENSE` na raiz.

## Contato

Se precisar de ajuda com o projeto ou quiser solicitar alterações, responda a esta solicitação ou abra uma issue no repositório.

---

Arquivo gerado/atualizado automaticamente: README em Português com documentação básica do projeto.