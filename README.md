# KnappeKeuze open data: winkelprijzen van koptelefoons en oordopjes in Nederland

Dagelijkse winkelprijzen van draadloze koptelefoons en oordopjes bij Nederlandse winkels, gemeten door [KnappeKeuze](https://knappekeuze.nl), een onafhankelijke keuzehulp. Licentie: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

*Daily Dutch shop prices of wireless headphones and earbuds, measured by KnappeKeuze since September 2026. Includes a weekly price index and a per-model "is this discount real?" verdict based on our own price history, never on the shop's crossed-out reference price.*

## Bestanden

| Bestand | Inhoud | Actuele versie |
|---|---|---|
| `black-friday.csv` | Per model: prijs van de dag, laagste prijs die we zelf maten, sinds wanneer, en een oordeel (lager dan ooit gemeten, op de laagste prijs, dicht bij de laagste, gewone prijs, te kort gemeten). | https://knappekeuze.nl/pers/black-friday.csv |
| `prijsindex.csv` | De KnappeKeuze Prijsindex per week, met een vaste mand, per prijsgroep (eerste week = 100). | https://knappekeuze.nl/prijsindex.csv |
| catalogus (alleen live) | De catalogus: per model de KnappeKeuze score, deelscores, meetlat met marge en de prijs met tijdstip van controle. | https://knappekeuze.nl/api/v1/products |

De twee CSV-bestanden hier zijn een momentopname van 19 november 2026. De bron wordt elke dag (de meter elk uur) bijgewerkt.

Een doorgestreepte van-prijs van een winkel telt bij ons nooit mee: we vergelijken alleen met prijzen die we zelf hebben gemeten. Methode: https://knappekeuze.nl/methode en https://knappekeuze.nl/prijsindex#zo-rekenen-we

## Ook als koppeling voor AI-assistenten (MCP)

Alleen-lezen MCP-server, zonder sleutel: `https://knappekeuze.nl/mcp` (Streamable HTTP). Tools: `search_products`, `compare_products`, `price_check`, `deal_check`, `current_deals`.

- In Claude: [KnappeKeuze in de lijst met connectors](https://claude.ai/directory/connectors/knappekeuze)
- Officieel MCP-register: `nl.knappekeuze/catalogus`
- OpenAPI: https://knappekeuze.nl/api/v1/openapi.json

## Andere kopieën

- Zenodo (vaste DOI): https://doi.org/10.5281/zenodo.24291284
- Kaggle: https://www.kaggle.com/datasets/knappekeuze/winkelprijzen-koptelefoons-en-oordopjes-nederland
- Hugging Face: https://huggingface.co/datasets/Knappekeuze/winkelprijzen-koptelefoons-oordopjes-nl
- Wikidata: https://www.wikidata.org/wiki/Q142198281

## Citeren

KnappeKeuze (2026). *Dagelijkse winkelprijzen van koptelefoons en oordopjes in Nederland*. Zenodo. https://doi.org/10.5281/zenodo.24291284

Noem "KnappeKeuze (knappekeuze.nl)" en link naar https://knappekeuze.nl/open-data.
