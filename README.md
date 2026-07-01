# corcazzo.it

Sito statico anni '90 per dire "col cazzo" con un link personalizzato.

## File

- `index.html`: tutto il sito in un unico file HTML, con CSS e JavaScript incorporati.

## Come provarlo in locale

```bash
cd /Users/susannakayed/corcazzo.it
python3 -m http.server 8765
```

Poi apri:

```text
http://127.0.0.1:8765/index.html
```

Esempio link condivisibile:

```text
http://127.0.0.1:8765/index.html?a=prestarmi%2050%20euro&m=aziendale
```

## Modalità supportate

- normale
- diplomatica
- romana
- aziendale
- sentimentale
- definitiva

Esempio:

```text
https://corcazzo.it/?a=venire%20alla%20cena&m=romana
```

## Deploy

Essendo un sito statico, basta caricare `index.html` nella root del dominio `corcazzo.it` su qualunque hosting statico.
