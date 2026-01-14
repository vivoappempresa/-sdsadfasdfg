# Call Center Gamefication - GitHub Pages

Este projeto foi convertido para funcionar no GitHub Pages como um site estático.

## Funcionalidades

- **index.html**: Visualização principal do salão com vendedores, animações e ranking.
- **admin.html**: Painel para simular lançamentos de vendas (localmente, não salva no servidor).
- **editor.html**: Editor de layout para posicionar sprites (salva localmente no navegador).

## Limitações

Como é uma versão estática para GitHub Pages:
- Não há real-time via WebSockets; usa polling a cada 5 segundos para atualizar dados.
- Vendas e layouts são salvos localmente no navegador (localStorage), não no repositório.
- Para atualizar vendas reais, edite o arquivo `vendas.json` no repositório GitHub.
- Para atualizar layout, edite o arquivo `layout.json` no repositório.

## Como Usar

1. Faça upload desta pasta `docs/` para o seu repositório GitHub.
2. Vá para Settings > Pages e selecione "Deploy from a branch" > Branch: main > Folder: /docs.
3. Acesse a URL gerada pelo GitHub Pages.

## Arquivos

- `index.html`: Página principal.
- `admin.html`: Simulação de admin.
- `editor.html`: Editor de layout.
- `static/`: Imagens, sons e estilos.
- `layout.json`: Configuração do layout.
- `vendas.json`: Dados de vendas.

## Desenvolvimento Local

Abra `docs/index.html` no navegador para testar localmente.
