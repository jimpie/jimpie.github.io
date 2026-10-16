# Van der Poel — persoonlijke website

Statische logo-only website voor GitHub Pages op `www.vanderpoel.org`. Het VDP-logo is een zelfgemaakt schaalbaar SVG-bestand. Geen buildstap, externe assets, tracking, cookies of backend.

## Lokaal bekijken

```sh
python3 -m http.server 8000
```

Open daarna `http://localhost:8000`.

De DNS-records van `vanderpoel.org` zijn niet onderdeel van deze repository. Voor het `www`-adres hoort bij TransIP een `CNAME`-record met naam `www` en waarde `jimpie.github.io` te staan (in plaats van het oude `www`-A-record). Laat het apex-`A`-record, de Google Workspace MX-records en overige mailrecords ongemoeid.
