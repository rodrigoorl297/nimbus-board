# Nimbus Board

[![UI](https://img.shields.io/badge/UI-ops_console-22d3ee)](public/index.html)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

Console operacional para **logistica / tracking**. rastreio de envios, SLA e eventos de status em uma API unica.

## What recruiters should notice

- Interface de produto (sidebar, KPIs, grafico, fila de eventos), nao uma landing generica.
- Layout responsivo, tokens de design e atualizacao periodica de metricas.
- Documento de produto em `/docs` descrevendo o problema de negocio.

Problema: operacoes nao enxergam atrasos de entrega ate o cliente reclamar.

## Run

Abra `public/index.html` no navegador, ou:

```bash
python -m http.server 4173 --directory public
```

## Stack

HTML · CSS Grid · Canvas API · vanilla JS (zero dependencias)

## Next

- [ ] Ligar em uma API real (`nimbus-api` e um par natural)
- [ ] Filtro por ambiente e export CSV
