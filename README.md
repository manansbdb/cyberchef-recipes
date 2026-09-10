# cyberchef-recipes

Receitas prontas para o [CyberChef](https://gchq.github.io/CyberChef) — encoding, hash, JWT, compressão e limpeza de dados.

Funciona na versão online ou local. Abre o CyberChef, segue os passos (ou importa o JSON da pasta `recipes/`).

## Como usar

1. Abre https://gchq.github.io/CyberChef
2. Escolhe uma receita em [`recipes/`](./recipes/)
3. Arrasta as operações na ordem indicada, ou cola o JSON em **Load recipe** (menu Load/Save)

## Índice

| Receita | Ficheiro | Para quê |
|---------|----------|----------|
| Base64 → texto | [`decode-base64.json`](./recipes/decode-base64.json) | Decodificar Base64 |
| Texto → Base64 | [`encode-base64.json`](./recipes/encode-base64.json) | Codificar em Base64 |
| SHA-256 | [`hash-sha256.json`](./recipes/hash-sha256.json) | Hash SHA-256 do input |
| JWT decode | [`jwt-decode.json`](./recipes/jwt-decode.json) | Ver header + payload de um JWT |
| URL decode | [`url-decode.json`](./recipes/url-decode.json) | Decodificar query strings |
| Gunzip | [`gunzip.json`](./recipes/gunzip.json) | Descomprimir gzip |
| Extrair IPs | [`extract-ips.json`](./recipes/extract-ips.json) | Extrair endereços IPv4 de um log |
| JSON beautify | [`json-beautify.json`](./recipes/json-beautify.json) | Formatizar JSON |

## Contribuições

PRs com novas receitas (JSON + linha na tabela) são bem-vindos. Mantém cada receita focada numa tarefa.

## Licença

[MIT](./LICENSE)
