# Presente de casamento — Morgana & Marco

Página estática com o Pix para o presente de casamento (07/11/2026).

- **Site publicado:** https://marcomartinssm.github.io/presente-morgana-marco
- Página única: [`index.html`](index.html)
- QR Code e código "copia e cola" embutidos direto no HTML (nada é carregado de fora).

## Como alterar a chave Pix / QR Code

1. No app do banco, gere um novo **"Pix copia e cola"**.
2. Substitua o texto dentro de `data-pix="..."` no `index.html` (botão "Copiar código Pix").
3. Gere o QR novo a partir desse mesmo texto e troque o `<svg>` dentro de `<div class="qr">`.
4. Faça o commit — o site atualiza sozinho em 1–2 minutos.

Só o dono do repositório consegue publicar alterações. A branch `main` está protegida.
