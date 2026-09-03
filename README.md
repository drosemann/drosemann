# Hey, ich bin Daniel!

**Dev aus Leidenschaft | Umgebung Frankfurt am Main | FISI-Azubi 2. Lehrjahr | Hosting-Nerd & KI-Bastler**

Ich lebe für **Technik, IT-Infrastruktur und künstliche Intelligenz**. Learning by Doing ist mein Ding – ich baue lieber Server als Slides. Aktiv in der Minecraft- und Hosting-Community seit Jahren.

---

## Mein Stack
*Das ist mein privater Stack für eigene Projekte – im Betrieb nutze ich den dort vorgegebenen Stack.*

**Full-Stack:** `HTML` • `CSS` • `JavaScript` • `Java` • `PHP` • `Python`
**Infra & Server:** `Docker` • `Linux` • `NGINX` • `Apache` • `Proxmox` • `Velocity` • `KVM / libvirt`
**Panels (viel Erfahrung):** `Pterodactyl` • `Coolify` – aktuell nutze ich aber lieber pure Docker für meine Services, weniger Overhead, mehr Kontrolle
**Datenbanken:** `MariaDB` – sehr viel Erfahrung im produktiven Einsatz • `Supabase` – Cloud und Self-Hosted ausgiebig getestet
**Tools & Services:** `Cloudflare` (DNS) • `HetrixTools` (Monitoring) • `Trello` + `Notion` (Projektmanagement für ShadowUnity) • `Vercel` (Auto-Deploys)
**Client:** `Windows` – looking at you, Games Industry. Wechsel zu Linux geplant sobald der Anticheat-Support besser wird
**Fokus:** `Cybersecurity` • `KI / AI` • `Cloud & Virtualisierung` • `Automation mit Python`

## Aktuell
- Ausbildung zum **Fachinformatiker für Systemintegration** (2. Lehrjahr)
- Betreibe meinen Minecraft-Server **ShadowUnity** (seit 22.04.2018)

## Mein Weg: Vom Free-Hoster zur eigenen KVM
- **Aternos** → **Ploudos** → **Minehub** (geschlossen)
- **DeinServerHost** → **Strato** → **Host-Unlimited** → **LuxVPS** → **Mine-Hoster**
- **ST-Hosting** – nach 1 Monat gekündigt, LXC entsprach nicht meinen Ansprüchen
- **HT-Hosting** – insolvent gegangen, gelernt unter Zeitdruck zu migrieren
- **Index Hosting** – bis Mitte März genutzt, gekündigt wegen Einstellung der AMD EPYC-Reihe

Zwischendurch **Vercel** und **Kinsta** getestet – beste Dev-Experience mit Edge + CDN, aber Self-Hosting langfristig günstiger. Teilweise 3-4 Server parallel als Dev-, Failover- und Main-System betrieben.

<details>
<summary><b>🎮 Meine Minecraft Name History – von RTX-Laptop bis Tippfehler</b></summary>

| # | Name | Datum | Story |
| :--- | :--- | :--- | :--- |
| 12 | **d5_nel** | 03.09.2026 | Wollte `sewergratelifted` ändern weil es mir nicht gefallen hat und eh ausversehen war – und hab jetzt ausversehen `d5_nel` MIT RECHTSCHREIBFEHLER genommen, weil auf der Handy-Seite bei "Enter" direkt der Name genommen wird |
| 11 | **sewergratelifted** | 30.07.2026 | Ausversehen geändert weil MOJANG KEINE BESTÄTIGUNG FÜR NAMENSÄNDERUNGEN WILL. Inspiriert von YouTuber sewergratelifter |
| 10 | **DaaanielTV** | 26.06.2022 | Mein fester, jahrelanger Name – ~4 Jahre |
| 9 | **ShadowFoxStream** | 27.04.2022 | ShadowFox angepasst, weil ich früher viel gestreamt habe lol |
| 8 | **EinfachDanielYT** | 17.03.2022 | YouTube-Phase, imitiert von "EinfachEmmy" |
| 7 | **ShadowFoxxxx** | 24.05.2021 | ShadowFox ohne Nummern, einfach cooler |
| 6 | **DiamantSucht** | 23.04.2021 | GrieferGames-Phase, wollte ein Casino machen |
| 5 | **GrafDiamant** | 20.03.2021 | GrieferGames-Phase, wollte "GrafBonze" imitieren |
| 4 | **VulkanBot** | 18.02.2021 | GrieferGames-Phase, wollte einen Item-Verkauf-Bot aufmachen |
| 3 | **ShadowFox20201YT** | 01.10.2020 | Anfang meiner YouTube-Phase – daher kommt **ShadowUnity** |
| 2 | **HanauHoheTanne** | 27.08.2020 | Wohnort gedoxxt weil dummer Jugendlicher lol |
| 1 | **Raytracer2020** | 2020 | Mein Laptop hat eine RTX GPU – musste man ja zeigen |

</details>

## Erfahrung vor der Ausbildung
- **3 Helpdesk-Praktika** – 2 Schule + 1 freiwillig, unbezahlt aus Freude am Werk
- **YouTube & Streaming** – über 2000 Videos produziert, hunderte Stunden live gestreamt. Community-Aufbau, Live-Technik, Konstanz gelernt.

## Open Source – Meine 6 aktiven Repos

### 🚀 1. infra-pilot – Basis für meine Hosting-Firma
**Learning project: VPS management CLI + Dashboard** | TypeScript, Python, React/Express, Docker
> Ursprünglich `dmh-hosting` – first commit am 09.03.2025 nur mit `README.md` `# dmh-hosting`. Entstanden aus dem DMH Network. Wir wollten dann doch kein Public Hosting machen – zu viele Probleme mit Abuse, Cyberkriminellen, Fraud. Gepivotet zu einem internen Tool um eigene Infra zu managen. Weg von Pterodactyl/Coolify, hin zu purem Docker. Das ist heute die Basis für meine geplante IT-Firma.

`orchestrator-agent :8500 | management-panel :5173/:3001 | monitoring & discord profiles`

### 🧱 2. streuland – Mein Plot-System für ShadowUnity
**Paper Plugin Java/Maven für Paper 1.16.5**
> First commit `bfbadcb` am 01.02.2025 – 28 files. Entstanden weil ich ein Plotsystem machen wollte und "CB Nature" auf GrieferGames mochte, aber der CityBuild ziemlich tot war und nur für AFK Farmen genutzt wurde. Ich wusste, man kann Vanilla World-Gen mit besseren Plots als Standard-Grid verwenden. Kein hässliches Grid mehr, sondern zufällig verteilte Plots mit automatischen Pfaden, geschützt, mit District Progression, Markt und Clan Wars.

### 📝 3. forgecms – Weil ich immer bloggen wollte
**Flask + MariaDB Blog/CMS mit Docker**
> Ich wollte immer mal einen Blog machen, aber hatte keine Zeit und kein Impressum für eine Webseite (in DE = Abmahn-Risiko). Deshalb nie live gegangen. Bietet Auth, Draft/Scheduled/Published Workflow, Markdown, Media Uploads, Single-Server + Enterprise Mode (2 App Container hinter NGINX). Perfekt für `d5niel.de` und ShadowUnity News wenn Impressum steht.

### 🤖 4. ai-chat-webui – Lokal statt Cloud
**Privacy-focused Ollama WebUI – pure JavaScript, kein Framework**
> First commit `bc38708` am 14.03.2025, hieß noch `super-fast-ai-chat`. Früher dachte ich: "Lieber meinen $5 VPS auf 100% CPU haben als ein paar Cent an Inference Provider zu zahlen". Mittlerweile würde ich das meiste in der Cloud machen und nur lokale 4B Modelle (statt teurem VPS) für wirklich private Dinge nutzen. Genau dafür: `index.html` öffnen, `http://localhost:11434` – alles bleibt lokal.

### 🎮 5. stranded-horizons – Mein Browser-Game Traum
**Vanilla HTML/CSS/JS Survival Game – einziges Projekt mit Vercel Auto-Deploys**
> First commit `3a668c7` am 08.04.2025 – 18 files, `PROJECT-IDEA` war noch ein großes Multiplayer Survival RPG mit Character Creation. Ich wollte schon immer ein (Browser) Spiel (RPG vor allem), hatte nie die Zeit (jetzt noch weniger um kreativ zu sein). Einziges Repo mit Vercel Auto-Deploys – Free Tier wird um Weltjahre nicht genutzt, nur Hater die nie was probieren sagen das um nie etwas profen zu müssen. Nächstes Experiment: "Loop Engineering" – 3 KVM VMs (Worker/Production/Management) mit 3 OpenCode Agents die parallel an Audio/UI, Gameplay und Balancing schrauben, Puppeteer Tests, Dashboard.

### 🖥️ 6. cooperating-screen – Nordee Urlaubsidee
**Cross-Device Screen Sharing – Flutter, WebRTC, Node.js Signaling**
> First commit `411edc7` am 15.01 – 3 files. Die Idee kam vor etlichen Jahren im Sommerurlaub auf der Insel Nordee mit meiner Schwester. Sie wollte Marketing Head werden und ich Dev/Infra/Implementierer/Sklave/etc. War zur Zeit als wir alle noch GPT 3.5 unlimited genutzt haben (crazy, heutzutage hat OpenAI Limit von 512 MB Speicher für Bilder/Dateien). Hatte einen Chat, finde ihn nicht mehr, lokale Kopie auch nicht – aber ein "Gemini Gem" hat alle meine ChatGPT Chats. Als OpenAI Codex gut genug und free wurde (zu geizig für $20) habe ich die Idee einfach in Codex eingegeben. Kurzzeitig hieß es mal "LinkScreen – Cross-Device Sharing", aber zurück umbenannt weil LinkScreen nach AI-generated Name klingt. Kein stumpfes Teams-Screensharing, sondern Multi-User Control auf App-Level.

## Weitere Projekte & Spielwiese
- **ShadowUnity** – play.shadowunity.de – Kein Reset seit 2022. Eigene Infra auf shadowunity.de mit Forum & Gästebuch. Fokus auf Qualität statt Quantität.

  <details>
  <summary>📜 Name History von ShadowUnity</summary>

    1. **GrieferPrinz** – Pocket Edition, inspiriert von GrieferKing + GrieferGames
    2. **MelonenGames** – erster Java Server, nur CityBuild
    3. **DiamantSucht** – weil ich ingame so hieß
    4. **DanielArmy** – persönliche Brand Phase
    5. **MineRush** – inspiriert von MineSucht von Abge & FloTastisch
    6. **ShadowUnity** – ShadowFox + Community = stabil seitdem.

  </details>

- **DMH Network** – 24.01.2025 bis 26.04.2025 mit Matti und Henry – verlassen für Ausbildung
- **SpigotMC Plugins** – unter altem Alias MineHub: https://www.spigotmc.org/resources/authors/minehub.1035036/
- **Emergency Response: Crestwood County** – Roblox-Roleplay seit 10.09.2023 mit Polizei, SWAT, Feuerwehr, Wanted-System, Fuel etc.
- **Raspberry Pi KI Pflanzen-Überwachung** – Sensorik + AI
- **Hardware-Hacking & KI-Sicherheit**

## Video Archive – Theo Browne Era
Nach über 2000 Gaming-Videos 15 Videos im Theo Browne Style – Tech-Takes schnell geschnitten. Offline genommen und hier archiviert um zu evaluieren was kommt.

**→ [`theo-browne-era-video-style/`](https://github.com/drosemann/drosemann/tree/main/theo-browne-era-video-style) – 15 Videos**

Enthalten: Cloud-Sicherheit, IT-Trends 2024, TikTok Drama USA, Warum Arc stirbt, Cloud-Gaming, KI-Agenten, World Labs 3D, Amazon Nova, China Open-Source KI, Ransomware NHS, OpenAI AGI, Uber Robotaxi Abu Dhabi etc.

## Eigene Domains
Alle bei netcup:
- **d5niel.de** – Portfolio (zukünftig mit ForgeCMS)
- **shadowunity.de** – Minecraft Server
- **hosting-club.de** – ehemaliges Hosting-Forum, nach 1 Jahr beendet für Fokus auf Ausbildung

## Meine 5-Jahres-Vision
> Nicht nur irgendein Job – eigenes Ding aufbauen.

- Gründung IT-Unternehmen für **Hosting, Infrastruktur & IT-Beratung** – Basis `infra-pilot`
- Skalierbare Cloud-Lösungen statt 0815-Rootserver – pure Docker, KVM
- Altes Haus kaufen und smart auf die günstige Weise machen – alles dokumentieren auf YouTube
- Wissen teilen – YouTube-Kanal zu IT & Hosting ist in Planung

## Let's build
Ich bin offen für Collabs in **IT, KI, Hosting, Gaming und Softwaredev**. Wenn du Bock hast, was Echtes zu bauen – meld dich!

In der Umgebung von Frankfurt am Main
