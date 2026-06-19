# SyntaxWear - E-commerce de Tênis e Sneakers

## Visão geral

Projeto estático de landing page para uma loja de tênis fictícia chamada **SyntaxWear**. O site foi criado com HTML e CSS, trazendo um layout moderno e responsivo, com foco em uma experiência visual para venda de produtos de moda urbana.

## Estrutura do projeto

- `index.html` - página principal do site.
- `css/reset.css` - reset de estilos básico.
- `css/variabbles.css` - variáveis CSS e import de fontes Google.
- `css/base.css` - estilos globais, botões e responsividade geral.
- `css/components/header.css` - estilos do cabeçalho e navegação.
- `css/components/hero.css` - estilos da seção hero com imagem de destaque.
- `css/components/categories.css` - estilos das categorias de produtos.
- `css/components/products.css` - estilos do grid de produtos.
- `css/components/footer.css` - estilos do rodapé.
- `images/` - imagens de banners, ícones, logo e produtos.
- `fonts/` - pasta presente, atualmente sem arquivos.
- `docs/` - pasta presente, atualmente sem arquivos.

## Funcionalidades principais

- Layout estático moderno para e-commerce de calçados.
- Navegação principal com categorias e ações de conta/ajuda/carrinho.
- Seção hero com imagem de destaque e botões de CTA.
- Cards de categorias com efeito de hover e imagens de produto.
- Grid responsivo de produtos com destaque em área principal.
- Rodapé com formulário de newsletter e links de navegação.
- Menu mobile com toggle para exibição da navegação em telas menores.

## Tecnologias utilizadas

- HTML5
- CSS3
- Google Fonts (`Ubuntu`)

## Como executar

1. Abra a pasta do projeto no seu editor ou navegador.
2. Abra o arquivo `index.html` diretamente no navegador.
3. Para desenvolvimento local avançado, use uma extensão de servidor estático, como:
   - Live Server (VS Code)
   - Simple HTTP Server do Python

### Exemplo com Python

```bash
python -m http.server 8000
```

Em seguida, acesse `http://localhost:8000`.

## Observações

- O arquivo `index.html` referencia `css/layout.css`, mas este arquivo não está presente no repositório.
- As pastas `fonts/` e `docs/` existem, porém estão vazias no momento.
- As imagens utilizadas estão em `images/banners/`, `images/products/`, `images/icons/` e `images/logo/`.

## Melhorias possíveis

- Adicionar interações JavaScript para carrinho, filtro e menu mobile.
- Implementar uma página de produto ou catálogo completo.
- Ajustar perfis de acessibilidade, como estados de foco e descrições mais detalhadas.
- Incluir validação visual no formulário de newsletter.

## Contato

Este README foi gerado para documentar o site **SyntaxWear** e facilitar a continuação do desenvolvimento.
