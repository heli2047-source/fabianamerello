# Fabiana Merello · Terapias Holísticas — Landing page

Landing page da terapeuta Fabiana Merello: Reiki, Energy Healing, Código HumanoSense e Humanoterapia, presencial ou à distância.

Visual "Santuário" (creme, areia e taupe com filetes dourados), escolhido pela cliente entre duas propostas, com elementos trazidos da segunda: "Para quem é", "Como começar" em 3 passos e o bloco de contato centralizado.

- `index.html`: a página, com CSS e JS embutidos.
- `assets/img/`: fotos.
- `versao-a/`: só redireciona para a raiz (link antigo enviado à cliente).

Os botões de WhatsApp usam a constante `WHATSAPP_NUMERO` no script da página.

## Publicação

GitHub Pages, branch `main`, pasta `/`, no domínio https://fabianamerello.com.br (arquivo `CNAME`). DNS no Registro.br: registros A/AAAA para os IPs do GitHub Pages e `www` como CNAME para `heli2047-source.github.io`.

Indexação liberada: `robots.txt` permite tudo e aponta para o `sitemap.xml`. Ao mudar a página, atualize o `lastmod` do sitemap.

## Pendências

- Fotos em resolução maior: `assets/img/fabiana1.jpg` (topo) e `assets/img/fabiana2.jpg` (retrato oval).

Projeto por [Pequeno Empresário](https://pequenoempresario.com.br/).
