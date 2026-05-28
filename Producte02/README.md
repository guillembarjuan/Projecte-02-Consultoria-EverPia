# P02 – Afegint la documentació de seguretat al repositori

## 📌 Descripció del producte

Aquest producte consisteix a **organitzar i pujar al repositori GitHub la documentació tècnica** generada durant les tasques de seguretat del Projecte 02 (Consultoria EverPia). L’objectiu és evitar l’anomenat *data silo* (informació dispersa i inaccessible) i aprofitar el control de versions que ofereix Git i GitHub per centralitzar tota la documentació en format **Markdown**.

Amb aquesta estructura, qualsevol membre de l’equip o el client pot consultar fàcilment les guies, procediments i solucions tècniques des d’un sol lloc.

---

## 🎯 Objectius específics

- Crear un repositori anomenat `Projecte2` (o utilitzar el repositori existent del projecte).
- Elaborar un `README.md` principal que presenti el projecte de manera atractiva (utilitzant Markdown).
- Crear carpetes separades per a cada tasca (`tasca02` i `tasca03`).
- Dins de cada carpeta:
  - Un `README.md` explicant l’activitat i el contingut.
  - Un arxiu `solucion.md` amb la documentació detallada.
  - Una subcarpeta `img` amb les captures de pantalla en format PNG.
- Assegurar que cada imatge tingui una **descripció alternativa** (text alternatiu) per a l’accessibilitat.
- Incloure hiperenllaços dins dels README per accedir directament als arxius `solucion.md`.

---

## 📁 Estructura del repositori

La documentació s’ha organitzat de la següent manera:

````
Projecte02-Consultoria-EverPia/
│
├── README.md                    # Presentació general del projecte
│
├── tasca02/
│   ├── README.md                # Descripció de la Tasca 02
│   ├── solucion.md              # Documentació tècnica de la Tasca 02
│   └── img/                     # Captures de pantalla (PNG)
│       └── (imatges)
│
└── tasca03/
    ├── README.md                # Descripció de la Tasca 03
    ├── solucion.md              # Documentació tècnica de la Tasca 03
    └── img/                     # Captures de pantalla (PNG)
        └── (imatges)
````

---

## 🔗 Enllaços a les carpetes

A continuació es mostren els enllaços directes a cada tasca dins del repositori:

- [📂 Tasca 02 – Documentació de seguretat (part 1)](/./tasca02)
- [📂 Tasca 03 – Documentació de seguretat (part 2)](/./tasca03)

Dins de cada carpeta trobareu:
- El `README.md` amb l’explicació de l’activitat.
- L’arxiu `solucion.md` (accessible també per enllaç directe des del README).
- La carpeta `img` amb les captures.

---

## 🧠 Contingut de les tasques

### Tasca 02 – Introducció a la seguretat informàtica
- Conceptes bàsics: seguretat activa / passiva, física / lògica.
- Anàlisi d’incidents (inundació, robatori de dades, apagada, estafa CEO, malware).
- Relació amb els objectius de seguretat (CIDAV: Confidencialitat, Integritat, Disponibilitat, Autenticitat, No-repudi).

### Tasca 03 – Seguretat a l’entorn físic
- Visualització de vídeos sobre els centres de dades de Google (6 capes de seguretat).
- Identificació de mesures de protecció física: perímetre, control d’accés, vigilància 24/7, biometria, destrucció segura de discs.
- Reflexió sobre l’aplicabilitat d’aquestes mesures a la nostra escola o a petites empreses.



---

## 💡 Aprenentatges extrets

- Importància d’**evitar el data silo**: centralitzar tota la documentació en un repositori compartit.
- Ús avançat de **Markdown** per crear documentació tècnica atractiva (taules, llistes, enllaços, imatges).
- Organització clara de carpetes i fitxers perquè sigui fàcil de navegar per al client o l’equip.
- Pràctica de **control de versions** amb Git i GitHub: cada canvi queda registrat i es pot recuperar.
- Inclusió de **descripcions alternatives** a les imatges per a l’accessibilitat.

---

## 👤 Autor

**Guillem Barjuan Alonso** – CFGM SMX  
Projecte 02 – Consultoria EverPia  
Data de realització: primer trimestre del curs 2025-2026

Aquest README.md el pots situar a l’arrel del repositori **Projecte 02 – Consultoria EverPia** (o dins de la carpeta `Producte02` si ho prefereixes). Els enllaços a `./tasca02` i `./tasca03` funcionaran si les carpetes estan al mateix nivell que aquest README. Si vols que ajusti alguna ruta o afegeixi més detall, diga-m'ho.
