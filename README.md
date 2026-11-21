# Pipistrel Velis Electro – aandrijflijn in 3D

Interactief 3D-model voor lesmateriaal over elektrisch vliegen (luchtvaarttechniek, Vista College).
Toont de romp, beide accu's, de E-811-motor met H300C-controller, de twee koelcircuits en de HV-bekabeling,
met animaties van de energiestroom en de koelvloeistof.

Plaats en vorm van de aandrijfcomponenten zijn schematisch en niet op ware maat.

- `index.html` – interactieve 3D-versie (ook geschikt voor Electude en telefoon)
- `ar.html` – AR-versie (iPhone/iPad, Android, Apple Vision Pro): buitenkant, aandrijflijn, exploded view, opengewerkte motor E-811 en accu. Direct linken kan met `ar.html#motor`, `#accu`, `#expl`, `#xray`.
- Op Android (Chrome met ARCore) heeft `index.html` ook een interactieve AR-modus (knop *AR starten*): plaatsen, schalen en op onderdelen tikken voor uitleg.

## Herkomst en licentie

- **3D-model vliegtuig:** *Pipistrel Alpha/Velis Electro* voor FlightGear, door Bea Wolf (D-ECHO),
  Sven Seipp (D-SVEN) en Carsten Vogel (TeXnicer). Gepubliceerd onder de GNU General Public License
  versie 2 of later. Het FlightGear-model is uitgebracht zonder officiële goedkeuring van Pipistrel.
- **Aanpassingen (Vista College):** omgezet naar glTF (`velis.glb`), schematische aandrijfcomponenten
  toegevoegd, de belettering "VELIS"/"ELECTRO" op romp en vleugels vervangen door het VISTA-logo en een interactieve webpagina (`index.html`) gemaakt. Ook deze aanpassingen vallen onder de
  GNU GPL versie 2 of later.

Zie `COPYING` voor de volledige licentietekst.

Pipistrel, Velis en Velis Electro zijn merken van Pipistrel d.o.o. Dit project is geen uitgave van Pipistrel.
