# LP Distrito Fit

Landing page / catálogo da **Distrito Fitness**: roupas e acessórios fitness, com pedidos pelo WhatsApp.

![Prévia do site](preview/site-desktop.png)

## Como editar

- **Número do WhatsApp:** no `index.html`, troque `const WHATSAPP = "5500000000000"` (55 + DDD + número).
- **Oferta da Foto 5:** o texto e o preço ficam no `index.html`, no card `#suplementos`.
- **Fotos:** salve na pasta `fotos/` com os nomes indicados em [`fotos/LEIA-ME.txt`](fotos/LEIA-ME.txt).
- **Cores:** variáveis no topo do CSS (`--verde` da marca e o tema verde sálvia, `--fundo`, `--card`).

## Rodar localmente

```bash
npx http-server -p 5173 .
```
