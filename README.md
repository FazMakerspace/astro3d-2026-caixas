# Astro 2026 · Caixas de transporte

Visualizador 3D das três caixas de transporte do robô Astro (OS-2026-0821) na pose fixa: cabeça, corpo, e braços com pernas e peças soltas. Mostra o arranjo dentro do volume de transporte e a ficha técnica de cada caixa (MDF, isopor, massas estimadas, lista de corte).

Site: https://fazmakerspace.github.io/astro3d-2026-caixas/

- `index.html`: o app (three.js 0.128).
- `dados/pecas.json` e `dados/pecas.bin`: malhas das peças já orientadas para a viagem (vértices uint16 quantizados por peça e índices uint32).

Os dados vêm da pasta `pose-fixa/` do Drive da OS. São gerados por `t04_prep_app.py` no estudo local.
