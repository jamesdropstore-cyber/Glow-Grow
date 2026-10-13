# Build-Notes – Glow & Grow Vorschau (06.10.2026)

Basis: Claude-Design-Variante 1. Statisches HTML/CSS, Netlify Forms.

## Genutzte Daten (von James bestätigt)
- Headline "Mehr Buchungen. Weniger DMs.", Unterzeile Variante C
- Über mich: Variante V1, Ich-Form, nur James sichtbar, Verlobte in der Geschichte
- Kein Preis auf der Seite; Antwortzeit 24–48 h; 2 Pilotstudios
- FAQ-Fakten aus Projekt: SEO/GEO 6–8 Wochen, live 14 Tage nach Unterlagen, Website/Domain/Hosting/Profil gehören der Kundin
- Impressum: Firma + Adresse laut Firmen-Tracker
- Instagram @glowandgrow.zh

## Bewusst offen
- WhatsApp-Button: kommt, sobald James die Nummer schickt
- Portrait: kommt, sobald hochgeladen
- E-Mail: erst nach Markenanwalt + Domain
- Favicon: provisorisches "GG" (Ele-Monogramm folgt)
- noindex (Meta, Header, robots.txt) bis Markenfrage geklärt
- Impressum/Datenschutz: vom Anwalt prüfen lassen

## v2 (13.10.2026) – Branch v2-landing-und-demo
- `/v2/` = neue Landingpage (Espresso-Hero, Vorher/Nachher DMs vs. Online-Buchung, 4 Bausteine, Ablauf, Reporting, Pilot, Über mich, FAQ, Check-Formular). Ersetzt index.html erst nach Go von James.
- `/demo/` = Master-Demo-Website "Maison Lumée" (fiktiv, alle Inhalte Beispiele), Layout-Konzept 3 "Seitenleisten-Magazin", Buchungs-Widget mit Daten in `const STUDIO = {…}`.
- Bilder: mit Higgsfield (Nano Banana Pro) generiert, lizenzfrei. Quelle der Artifact-Versionen: claude.ai/artifact/348LzygVz1suvp9NLosSC3 (Landing), claude.ai/artifact/SR58M9ma3zqjGvTBnvhMKj (Demo).
- Reviewer (separater Agent): Landing FREIGABE MIT HINWEISEN, Demo FREIGABE.

## v2.1 (13.10.2026 abends) – drei Demos
- `/demo-lash/` Demo 1 · Brow & Lash Studio „Maison Lumée“ (überarbeitet: Über uns mit Unschärfe-Hintergrund, keine Bogenrahmen, Cookie-Banner, Öffnungs-Badge, Schriften selbst gehostet).
- `/demo-aesthetik/` Demo 2 · Ästhetikpraxis „Praxis Solène“ (Anliegen-Finder, Sie-Form, Wording nach CH-Heilmittelwerbung).
- `/demo-laser/` Demo 3 · Laserpraxis „Klarwerk“ (Zonen-Preisrechner, V-NISSG-konform).
- `/v2/` Landingpage: Empfangsbild neu, drei Demo-Karten, Cookie-Hinweis, Texte rechtlich entschärft.
- Schriften als data-URI eingebettet (aus github.com/fontsource/font-files), keine Google-Fonts-Aufrufe.
- `_quellen/` = Artifact-Fassungen (ohne doctype) + Manager-Briefing. Netlify-Fassungen werden daraus erzeugt.
