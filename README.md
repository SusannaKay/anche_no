# corcazzo.it

Sito statico anni '90 per dire "col cazzo" con un link personalizzato.

## File

- `index.html`: tutto il sito in un unico file HTML, con CSS e JavaScript incorporati.
- `sitemap.xml`: sitemap da inviare a Google Search Console.
- `robots.txt`: consente la scansione e indica a Google dove trovare la sitemap.

## Come provarlo in locale

```bash
cd /Users/susannakayed/anche_no
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

Essendo un sito statico, basta caricare `index.html`, `sitemap.xml` e `robots.txt` nella root del dominio `corcazzo.it` su qualunque hosting statico.

Dopo il deploy devono rispondere questi URL:

```text
https://www.corcazzo.it/sitemap.xml
https://www.corcazzo.it/robots.txt
```

Su Google Search Console invia questa sitemap:

```text
https://www.corcazzo.it/sitemap.xml
```
