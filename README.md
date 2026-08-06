# AppSupportDocs

Documenti di supporto (privacy policy, termini d'uso, ecc.) per le applicazioni di **FromPineSoft**.

I file di questo repository sono pubblicati tramite GitHub Pages e utilizzabili come URL pubblici (ad esempio nelle sottomissioni al Microsoft Store).

## Documenti disponibili

| App | Documento | URL pubblico |
|-----|-----------|--------------|
| WinUI-DJ | Privacy Policy (IT/EN/ES/FR) | https://dpcons.github.io/AppSupportDocs/WinUI-DJ-PrivacyPolicy.html |
| Viareggio Il Carnevale | Contenuti dell'app (JSON, schema v1) | https://dpcons.github.io/AppSupportDocs/carnevale-viareggio/contenuti-v1.json |

## Viareggio Il Carnevale — contenuti

Il file `carnevale-viareggio/contenuti-v1.json` alimenta l'app **Viareggio Il Carnevale**
(programma, luoghi, storia e biglietti). L'app lo scarica all'avvio, ne conserva
una copia locale per l'uso offline e include una copia di riserva nel pacchetto.

Regole di aggiornamento:

- il campo `versione` identifica lo schema: va incrementato solo per modifiche
  incompatibili, pubblicando il nuovo documento come `contenuti-v2.json`;
- aggiornare `aggiornatoIl` a ogni modifica;
- le informazioni provengono dal sito ufficiale del Carnevale di Viareggio
  (<https://viareggio.ilcarnevale.com/>), indicato nel campo `fonte`.

