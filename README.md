# 📁 Projecte 02 – Consultoria EverPia

Benvingut al segon projecte del curs de **Sistemes Microinformàtics i Xarxes (SMX)**.  
Aquest projecte ens situa com a **consultors júnior** d’una consultora tecnològica anomenada **EverPia**, fundada per un equip de professors amb una visió clara: la tecnologia ha de servir per ajudar les persones i les organitzacions a créixer.

> *“Mai treballarem sols. Cada projecte serà una oportunitat per créixer junts.”* – Lema d’EverPia

L’objectiu és resoldre reptes tecnològics reals per a diferents clients, treballant amb metodologia àgil (Kanban), documentant tot el procés amb **Markdown** i utilitzant **GitHub** com a espai central de treball i control de versions.

---

## 📌 Índex

1. [Descripció del projecte](#-descripció-del-projecte)
2. [Metodologia de treball](#-metodologia-de-treball)
3. [Tasques realitzades](#-tasques-realitzades)
4. [Productes finals](#-productes-finals)
5. [Estructura del repositori](#-estructura-del-repositori)
6. [Tecnologies i eines](#-tecnologies-i-eines)
7. [Aprenentatges clau](#-aprenentatges-clau)
8. [Competències treballades](#-competències-treballades)
9. [Enllaços d’interès](#-enllaços-dinterès)
10. [Autor](#-autor)

---

## 📋 Descripció del projecte

**EverPia** és una consultora IT simulada que ens encarrega múltiples tasques per a diferents clients. Cada tasca pot semblar independent, però totes formen part d’un mateix repte: aprendre a funcionar com a consultors professionals, combinant habilitats tècniques (seguretat, xarxes, hosting, Linux) amb habilitats organitzatives (planificació, documentació, treball en equip).

Durant aquest projecte hem après a:

- Gestionar projectes amb **Kanban** i **Microsoft Planner**.
- Utilitzar **Git** i **GitHub** per al control de versions i documentació.
- Seleccionar un **SAI** per a una empresa client.
- Recuperar l’accés a un sistema Linux amb contrasenya oblidada.
- Configurar i administrar un **servidor Linux** (usuaris, grups, monitoratge).
- Instal·lar i configurar el servei **DHCP** en un servidor Ubuntu.
- Analitzar ofertes de **hosting** i **domini** per a diferents perfils de client.
- Instal·lar **WordPress** en local amb WP Local i en un hosting gratuït.
- Redactar documentació tècnica professional en **Markdown**.

---

## 🧭 Metodologia de treball

Tot el projecte s’ha gestionat amb la metodologia **Kanban** mitjançant **Microsoft Planner**, amb les següents columnes:

- **Backlog** – totes les tasques pendents (T00 a T11).
- **En curs** – tasques en desenvolupament.
- **En revisió** – tasques pendents de validació.
- **Fet** – tasques completades.

🔗 **Enllaç al tauler Kanban del projecte:**  
[https://planner.cloud.microsoft/webui/v1/plan/OnBXLzJLE06MPbkG3U9a65YAAOPj](https://planner.cloud.microsoft/webui/v1/plan/OnBXLzJLE06MPbkG3U9a65YAAOPj?tid=c7b5981a-7820-4ac8-ae65-03515ea81317)

---

## ✅ Tasques realitzades

A continuació es mostren les tasques desenvolupades al llarg del projecte, amb una breu descripció extreta del document d’instruccions.

| ID | Tasca | Descripció | Tipus |
|----|-------|-------------|-------|
| T00 | Presentació del projecte i inicialització del Kanban | Creació del tauler Planner i organització inicial del backlog. | Grup |
| T01 | Control de versions amb git i GitHub | Creació del compte de GitHub, repositori personal i README inicial. | Individual |
| T02 | Selecció d’un SAI per una empresa client | Inventari d’equips, càlcul de potència, autonomia i recerca de models SAI. | Grup |
| T03 | Seguretat Lògica: recuperant accés a sistemes | Recuperació de contrasenya en un Linux (Zorin OS) i protecció de l’accés al GRUB. | Grup |
| T04 | Configurant i administrant un servidor Linux | Gestió d’usuaris, grups, monitoratge i manteniment en un servidor Linux. | Grup |
| T05 | El servei de DHCP: introducció teòrica | Estudi del protocol DHCP, concessió, rang i reserva. Prova escrita. | Grup |
| T06 | El servei de DHCP: configuració pràctica | Instal·lació i configuració d’un servidor DHCP a Ubuntu Server, proves i captures Wireshark. | Grup |
| T07 | Idea de negoci responsable socialment | Elaboració de matriu DAFO personal, CANVAS personal i repte professional. | Individual |
| T08 | Assessorament de domini i hosting | Anàlisi de requeriments del client, taula comparativa de hostings i proposta de domini (en Markdown). | Grup |
| T09 | Donar-se d’alta en un hosting gratuït | Cerca d’un hosting gratuït, creació de compte i instal·lació de WordPress. | Individual |
| T10 | Màsterclass de Markdown | Aprenentatge del llenguatge Markdown per a documentació tècnica (títols, taules, llistes, imatges). | Individual |
| T11 | Instal·lació de WordPress en local amb WP Local | Creació d’un entorn WordPress local, configuració de pàgines, entrades i aprenentatge de la diferència entre pàgines i entrades. | Individual |
| T12 | Sostenibilitat | Reflexió sobre la sostenibilitat en el món TIC (3 pilars del desenvolupament sostenible). | Grup |

---

## 🏁 Productes finals

Els productes avaluables del projecte són tres. Cada un està documentat dins la seva carpeta corresponent al repositori.

| Codi | Nom del producte | Enllaç a la carpeta |
|------|------------------|---------------------|
| **P01** | Kanban & Compte de GitHub | [`Producte01`](./Producte01) |
| **P02** | Afegint la documentació de seguretat al repositori | [`Producte02`](./Producte02) |
| **P03** | Presentació d’elecció de hosting al nostre client | [`Producte03`](./Producte03) |

Cada carpeta conté el seu propi `README.md` amb la descripció detallada i les evidències.

---

## 📁 Estructura del repositori

El repositori està organitzat de la següent manera (segons es mostra a la captura):

````
Projecte-02-Consultoria-EverPia/
│
├── README.md # Aquest fitxer
│
├── Producto01/ # P01 – Kanban & GitHub
├── Producto02/ # P02 – Documentació de seguretat
├── Producto03/ # P03 – Presentació hosting
│
├── tasca02/ # Documentació de la T02 (SAI)
│ ├── README.md
│ ├── solucio.md
│ └── img/
├── tasca03/ # Documentació de la T03 (recuperació accés)
│ ├── README.md
│ ├── solucio.md
│ └── img/
├── tasca10/ # Documentació de la T10 (Markdown)
│ └── ...
└── (altres carpetes de tasques individuals o grupals)
````


Tota la documentació tècnica està redactada en **Markdown**, amb imatges allotjades a subcarpetes `img` i utilitzant text alternatiu per a l’accessibilitat.

---

## 🛠️ Tecnologies i eines utilitzades

- **Metodologia àgil:** Kanban amb Microsoft Planner.
- **Control de versions:** Git i GitHub.
- **Sistemes operatius:** Ubuntu Server, Zorin OS (Linux).
- **Serveis de xarxa:** DHCP (isc-dhcp-server), Wireshark.
- **Virtualització:** VirtualBox (màquines virtuals per a proves).
- **Web:** WordPress (local amb WP Local i en hosting gratuït), Markdown.
- **Seguretat:** Recuperació de contrasenyes, protecció del GRUB, SAI.
- **Documentació:** Markdown, captures PNG, enllaços relatius.

---

## 💡 Aprenentatges clau

- **Planificació i organització:** Seguiment del projecte amb Kanban, assignació de tasques i gestió del backlog.
- **Documentació professional:** Ús avançat de Markdown per crear informes tècnics, taules comparatives, llistes de verificació i insercions d’imatges.
- **Treball amb Linux:** Configuració d’un servidor Ubuntu (usuaris, grups, monitoratge), instal·lació de serveis (DHCP), i resolució d’incidències (recuperació de contrasenya).
- **Seguretat física i lògica:** Selecció d’un SAI, protecció de l’accés al GRUB, importància d’una bona política de contrasenyes.
- **Hosting i domini:** Anàlisi de requeriments, comparativa de proveïdors (Webempresa, Raiola, SiteGround), proposta de naming i presentació professional al client.
- **Eines col·laboratives:** Ús de Planner per a la coordinació de l’equip, i GitHub per a la documentació compartida.

---

## 🧰 Competències treballades

Extretes del document de projecte (mòduls 0224, 0226, 0227, 0228, 1708, 1710, 1713):

- Instal·lar i configurar programari bàsic i d’aplicació en entorns de xarxa.
- Aplicar mesures de seguretat passiva (SAI, política de contrasenyes, protecció física).
- Instal·lar serveis de configuració dinàmica (DHCP) i verificar-ne el funcionament.
- Instal·lar gestors de continguts (WordPress) en local i en hosting remot.
- Identificar aspectes ASG de sostenibilitat aplicats al sector TIC.
- Planificar, documentar i fer seguiment de les activitats d’un projecte.
- Transmetre informació tècnica amb claredat i professionalitat (presentació oral).
- Aplicar habilitats emprenedores i innovació en la resolució de problemes.

---

## 🔗 Enllaços d’interès

- 👤 **Perfil de GitHub:** [github.com/guillembarjuan](https://github.com/guillembarjuan)
- 📌 **Tauler Kanban (Planner):** [Accedir al Planner d’EverPia](https://planner.cloud.microsoft/webui/v1/plan/OnBXLzJLE06MPbkG3U9a65YAAOPj?tid=c7b5981a-7820-4ac8-ae65-03515ea81317)
- 📂 **Carpeta P01 (Kanban & GitHub):** [`./Producte01`](./Producte01)
- 📂 **Carpeta P02 (Documentació de seguretat):** [`./Producte02`](./Producte02)
- 📂 **Carpeta P03 (Presentació hosting):** [`./Producte03`](./Producte03)

---

## 👤 Autor

**Guillem Barjuan Alonso** – CFGM SMX  
Curs 2025-2026

---

*Aquest projecte representa la nostra primera experiència com a consultors IT reals: aprenent a resoldre problemes tècnics, a documentar cada pas i a comunicar solucions de manera professional. EverPia no és només una simulació; és la demostració que la tecnologia, quan s’explica i es planifica bé, pot transformar negocis.*
