# Lar Certo Imobiliária

Site de uma imobiliária em Moçambique, com listagem de imóveis (comprar e arrendar), filtros, imóveis guardados, agendamento de visitas por WhatsApp, "Sobre nós" e contacto.

## Ficheiros

- `index.html`: o site completo (HTML, CSS e JavaScript).
- `imagens/`: ilustrações por tipo de imóvel e o horizonte da página inicial.

## Como editar

No bloco `<script>` do `index.html`:

- `TELEFONE`: número de WhatsApp com indicativo (258), sem `+` nem espaços.
- `IMOVEIS`: lista de imóveis (título, bairro, cidade, preço em MT, quartos, WC, área, descrição).

Altere também a morada, o email e o texto de "Sobre nós".

## Fotografias reais

Carregue as fotos para `imagens/` e, no `index.html`, troque a linha `img.src = "imagens/" + ICONE[p.tipo] + ".svg"` por um campo `foto` em cada imóvel.

## Como publicar (GitHub Pages)

1. No repositório, vá a **Settings → Pages**.
2. Em **Branch**, escolha `main` e a pasta `/ (root)`. Guarde.
3. Após 1 a 2 minutos, o site fica em `https://SEU-UTILIZADOR.github.io/NOME-DO-REPOSITORIO/`.
