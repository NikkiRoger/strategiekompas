# OV+ Strategiekompas

Een platform voor het delen van good practices en het opvolgen van begeleidingsstrategieën volgens de Circle of Courage.

## Status
**Prototype**: `index.html` bevat een lokale demo met uitsluitend fictieve leerlingen. Invoer wordt alleen in de browser opgeslagen. Er is nog **geen** Google-login, Supabase-koppeling of productiehosting.

## Beveiliging
- Voeg nooit echte leerlinggegevens, observaties of credentials toe aan deze repository.
- De Supabase-databank is een afzonderlijk project; gebruik alleen een publieke publishable key in de browser, nooit een service-role/secret key.
- Voor gebruik door collega's zijn Google OAuth, een expliciete toegangscontrole en geteste RLS-regels vereist.
- Publiceer geen leerlinggegevens voordat de school de privacy- en beveiligingsafspraken heeft goedgekeurd.

## Volgende stappen
1. Google Workspace-login inrichten via Supabase Auth.
2. Toegang beperken tot expliciet goedgekeurde OV+-medewerkers.
3. Website verbinden met Supabase en RLS met testaccounts controleren.
4. Strategieën, evaluaties en good practices centraal opslaan.
5. Beveiligde hosting kiezen en testen.
