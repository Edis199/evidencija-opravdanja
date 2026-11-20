# Evidencija izostanaka

Jednostavna web aplikacija za evidenciju dana i časova koje su roditelji opravdali u toku polugodišta.

- Podaci se čuvaju samo u pregledniku korisnika (localStorage). Ništa se ne šalje na server.
- U aplikaciji nema podataka o učenicima. Spisak učenika se unosi u "Datumi polugodišta".
- "Sigurnosna kopija" sprema podatke u datoteku, a "Učitaj kopiju" ih vraća.
- "Izvoz u Excel" pravi tabelu za štampu (A4, landscape).

## Instalacija kao aplikacija
Stranica je PWA (manifest.webmanifest, sw.js). U Chromeu/Edgeu se pojavi dugme "Instaliraj" u adresnoj liniji, a na mobitelu "Add to Home screen" / "Install app".
