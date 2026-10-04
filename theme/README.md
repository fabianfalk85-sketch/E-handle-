# bryda.se – temaändringar (utkast "bryda – ombyggnad (utkast)", id 205909819726)

- `backup-2026-10-04/` – originalfiler från utkastet innan ombyggnaden (identiska med live-temat 2026-10-03).
- `sections/bryda-varfor.liquid`, `sections/bryda-tidslinje.liquid` – nya sektioner.
- `templates/index.json`, `templates/product.json`, `sections/header-group.json` – nya versioner som laddats upp till utkastet.
- Övrigt i utkastet: `sections/image-banner.liquid` (textblockets limit 1 → 2), `templates/page.contact.json` och `templates/password.json` översatta till svenska.

## Uppdrag v2 (2026-10-04)

- `backup-v2-2026-10-04/` – `index.json`, `product.json` och `header-group.json` från utkastet innan v2.
- `sections/bryda-varfor.liquid` (nu "Bryda Text"), `bryda-how-it-works.liquid` (ny richtext-inställning `text`), `bryda-tidslinje.liquid`, `bryda-faq.liquid`, `bryda-paket.liquid` – omskrivna för mobil först, vänsterställd text, 60ch, 17px, samma padding 64/48.
- `templates/index.json`, `templates/product.json` – ny ordning och copy enligt v2-briefen. founder/igen/jämför är borttagna ur mallarna (filerna finns kvar).
- `sections/header-group.json` – land/språkväljare av, v2-CSS tillagd i bryda-besk-stil.

## Ny copy på live-mallen (2026-10-04)

Utkastet "bryda – ny copy (utkast)" (id 205916963150) är en exakt kopia av live-temat där bara textvärden i `templates/index.json` och `templates/product.json` är ändrade. Sektioner, ordning, design och bilder är identiska med live. Filerna ligger i `ny-copy-utkast/templates/`.
