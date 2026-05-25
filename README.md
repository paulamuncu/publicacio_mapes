# Fonts de dades per l'avaluació de Publicació de Cartografia

Fitxers de dades i geometries utilitzats per a la visualització de mapes amb Leaflet.

## Fitxers

### `divisions-administratives-v2r2-municipis-50000-20260120.json`
Límits municipals de Catalunya a escala 1:50000 en format GeoJSON.  
Font: Institut Cartogràfic i Geològic de Catalunya (ICGC).
URL: https://www.icgc.cat/ca/Geoinformacio-i-mapes/Dades-i-productes/Geoinformacio-cartografica/Divisions-administratives

### `censph-17092-20490-mun.csv`
Habitatges per tipus d'ús d'intensitat elèctrica. Municipis de Catalunya, 2021.  
Font: Idescat, a partir del Cens de població i habitatges de l'INE.  
URL: https://www.idescat.cat/pub/?id=censph&n=30&geo=mun

**Categories:**
- `EMPT_DW_EL_C_MIN` — Habitatges buits: consum elèctric inferior al llindar mínim
- `LWU_DW_EL_C_UND_250` — Ús molt baix: consum elèctric entre el llindar mínim i 250 kWh
- `OCCU_DW_EL_C_250_750` — Ús esporàdic: consum elèctric de 251 a 750 kWh
- `REGU_DW_EL_C_MORE_750` — Ús habitual: consum elèctric de més de 750 kWh
- `TOTAL` — Total habitatges familiars
