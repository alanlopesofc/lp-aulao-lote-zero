# Aulão Lote Zero — página de vendas

Página estática (HTML, CSS e JS inline) do ingresso do Aulão Lote Zero (Alfa Prime).

- Abrir: `index.html` no navegador, ou servir a pasta com qualquer servidor estático.
- Imagens em `assets/` (WebP).
- Checkout: constante `CHECKOUT_URL` no fim do `index.html`. Os botões `[data-cta]` repassam os `utm_*` da URL.
- Fundo: grid interativo (port do CursorGrid, React Bits). Prova real: carrossel 3D (port do CircularCarousel, React Bits).
- Pendentes: IDs do Meta Pixel e do GA4 (placeholders comentados no `<head>`).
