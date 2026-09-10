# cyberchef-recipes

Ready-to-use [CyberChef](https://gchq.github.io/CyberChef) recipes — encoding, hashing, JWT, compression, and data cleanup.

Receitas prontas para o CyberChef — encoding, hash, JWT, compressão e limpeza de dados.

Works online or locally. Open CyberChef, follow the steps, or import the JSON from `recipes/`.

Funciona online ou local. Abre o CyberChef, segue os passos, ou importa o JSON de `recipes/`.

## How to use / Como usar

1. Open https://gchq.github.io/CyberChef
2. Pick a recipe in [`recipes/`](./recipes/)
3. Drag operations in order, or paste the JSON via **Load recipe** (Load/Save menu)

1. Abre https://gchq.github.io/CyberChef  
2. Escolhe uma receita em [`recipes/`](./recipes/)  
3. Arrasta as operações na ordem, ou cola o JSON em **Load recipe**

## Index / Índice

| Recipe / Receita | File / Ficheiro | Purpose / Para quê |
|------------------|-----------------|--------------------|
| Base64 → text | [`decode-base64.json`](./recipes/decode-base64.json) | Decode Base64 |
| Text → Base64 | [`encode-base64.json`](./recipes/encode-base64.json) | Encode Base64 |
| SHA-256 | [`hash-sha256.json`](./recipes/hash-sha256.json) | SHA-256 hash |
| JWT decode | [`jwt-decode.json`](./recipes/jwt-decode.json) | JWT header + payload |
| URL decode | [`url-decode.json`](./recipes/url-decode.json) | Decode query strings |
| Gunzip | [`gunzip.json`](./recipes/gunzip.json) | Decompress gzip |
| Extract IPs | [`extract-ips.json`](./recipes/extract-ips.json) | Extract IPv4 from logs |
| JSON beautify | [`json-beautify.json`](./recipes/json-beautify.json) | Pretty-print JSON |

## Support / Apoio

Bitcoin donations welcome / Doações em Bitcoin bem-vindas:

```
bc1q0qfnlnxyum9u45stzxe0a7jnhtj4j0usfkqdjw
```

See [SUPPORT.md](./SUPPORT.md).

## Contributing / Contribuições

PRs with new recipes (JSON + table row) are welcome. Keep each recipe focused on one task.

PRs com novas receitas (JSON + linha na tabela) são bem-vindos. Mantém cada receita focada numa tarefa.

## License / Licença

[MIT](./LICENSE)
