# M241 – Framework Vergleich mit Astro

Dieses Projekt wurde im Rahmen des Moduls 241 (Tech Innovation – Frameworks) erstellt. Ziel war es, ein modernes Web-Framework praktisch auszuprobieren, zu analysieren und anhand verschiedener Kriterien zu bewerten.

Als Framework wurde **Astro** gewählt und ein einfacher Blog umgesetzt.

---

##  Projektbeschreibung

Im Projekt wurde mit dem Framework Astro eine kleine Blog-Webseite entwickelt.  
Dabei wurden folgende Anforderungen erfüllt:

- Erstellung eines funktionierenden Webprojekts (Blog)
- Verwaltung des Projekts mit GitHub
- Deployment der Anwendung auf einer PaaS-Plattform
- Analyse und Bewertung des Frameworks

 Die Website ist online verfügbar:
https://m241-astro-framework-comparison.vercel.app

---

##  Umsetzung

Die Umsetzung erfolgte in mehreren Schritten:

1. **Projekt Setup**
   - Erstellung eines Astro-Projekts mit dem Blog-Template
   - Installation der benötigten Dependencies mit npm

2. **Entwicklung**
   - Anpassung der bestehenden Seiten
   - Erstellung von Blog-Inhalten
   - Verständnis der Projektstruktur (pages, components, layouts)

3. **Versionsverwaltung**
   - Nutzung von Git und GitHub
   - Commit und Push des Projekts ins Repository

4. **Deployment**
   - Deployment mit Vercel
   - Automatische Veröffentlichung der Website

---

##  Analyse des Frameworks

### 1. Ecosystem

| Name  | Alter | Nutzung | Dokumentation | Bugs & Fixes | Migration |
|------|------|--------|--------------|-------------|----------|
| Astro | seit 2021 | wachsend | sehr gut | aktive Community | einfach |

---

### 2. Performance

| Name | SSR | SPA | Static | Serverless |
|------|----|----|--------|-----------|
| Astro | ja | teilweise | ja | ja |

 Astro ist besonders schnell, da standardmässig statische Seiten generiert werden.

---

### 3. Business Model & Kosten

| Name | Infrastrukturkosten | Lizenz | Ø Kosten/Monat | Kleine App | Grosse App |
|------|------------------|--------|---------------|-----------|-----------|
| Astro | gering | MIT | 0–20$ | günstig | skalierbar |

---

### 4. Skalierbarkeit

| Name | Horizontale Skalierung | Hosting | Reserven | Notizen |
|------|----------------------|--------|---------|--------|
| Astro | ja | Vercel | hoch | statische Seiten sind leicht skalierbar |

---

##  Projektspezifische Anforderungen

Für dieses Projekt (Blog) waren folgende Punkte wichtig:

- schnelle Ladezeiten
- einfache Entwicklung
- geringe Kosten
- einfache Deployment-Möglichkeiten

 Astro erfüllt diese Anforderungen sehr gut durch statische Generierung und einfache Integration mit Hosting-Plattformen.

---

##  Fazit / Takeaways

- Astro ist ein modernes und performantes Framework
- Besonders geeignet für Blogs und statische Webseiten
- Sehr gute Dokumentation und einfache Nutzung
- Deployment ist schnell und unkompliziert

 Insgesamt ist Astro eine sehr gute Wahl für einfache bis mittelgrosse Webprojekte.

---

##  Deployment

https://m241-astro-framework-comparison.vercel.app
