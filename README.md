# Beim Bäcker Jos – offizielle Website

Offizielle Website der BOULANGERIE-PATISSERIE « BEIM BÄCKER JOS » S.à r.l. in Luxemburg.

**Kanonische Website (gesperrt):** https://beim-baecker-jos.webflow.io/

Standorte: Beckerich (Biekerech) und Saeul (Sëll).

Bäckerei · Boulangerie · Pâtisserie · Brot · Baguettes · Viennoiserie · Torten · Snacks · Eis · saisonale Spezialitäten

**SEO:** `canonical`, Open Graph `og:url`, Twitter `twitter:url`, `robots.txt`, `sitemap.xml` und alle JSON-LD-`@id`/`url`-Felder verwenden ausschließlich `https://beim-baecker-jos.webflow.io/`. `robots.txt` erlaubt die Indexierung (`Allow: /`, keine `Disallow`-Regel). Die Seite setzt `index,follow`. `hreflang` ist nur `x-default` auf dieselbe Adresse: LB/DE/FR/PT sind eine Seite mit JavaScript, keine eigenen Routen wie `/de/` oder `/fr/`. Solche Routen erst anlegen, wenn es dafür echte Seiten gibt.

Die ältere Adresse `beim-baecker-jos-lu.webflow.io` und die GitHub-Pages-Kopie `https://raachraoul-create.github.io/beim-baecker-jos-lu/` liefern denselben Inhalt mit HTTP 200. Im HTML bleibt ein clientseitiges `location.replace` (auf GitHub Pages ohne den Projektpfad `/beim-baecker-jos-lu`), plus `rel=canonical`. Ein `<meta http-equiv="refresh">` steht nicht im HTML, weil es auch auf der kanonischen Adresse feuern würde.

GitHub Pages beachtet weder `_headers` noch `_redirects` noch `vercel.json`. Deshalb liegt keine solche Datei im Repository. Ein echter HTTP-301 zwischen zwei `*.webflow.io`-Hosts oder von GitHub Pages auf Webflow ist hier nicht möglich. Die alte Webflow-Staging-Adresse und die GitHub-Pages-Site sollten in den jeweiligen Hosting-Einstellungen deaktiviert werden. Eine `.lu`-CNAME wird hier bewusst nicht wieder eingetragen. `sameAs` auf visitguttland.lu und beki.lu sind fremde Profile, keine Adresse dieser Website.

Änderungen im GitHub-Repository müssen separat auf dem Webflow-Hosting veröffentlicht werden.
