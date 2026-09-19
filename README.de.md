# Dimensionsreise

🌐 [English](README.md) · **Deutsch** · [中文](README.zh-Hant.md)

**Gleicher Vorgang – verschiedene Welten – neue Perspektiven**

Eine interaktive, animierte Erklärseite zu Raumdimensionen von 1D bis 5D.
Eine Katze, ein Ball und fünf Welten: Derselbe Vorgang wird in jeder Dimension
gezeigt – einmal aus Sicht der Katze selbst und einmal aus Sicht eines Wesens
aus der nächsthöheren Dimension.

**➡️ Live-Seite: https://fco-mt.github.io/dimensionsreise/**

## Was die Seite zeigt

- **Fünf Welten nebeneinander:** Linie (1D), Fläche (2D), Raum (3D), 4D-Raum und 5D-Raum – in jeder Spalte läuft synchron dieselbe Geschichte.
- **Drei wählbare Vorgänge** (unter „Einstellungen“):
  - Ball über das Hindernis heben
  - Finger durch die Welt stecken
  - Nur Alltag (kein Eingriff)
- **Perspektivwechsel:** Was sieht die Katze wirklich? Immer nur ein Bild mit einer Dimension weniger als ihre Welt. Und was sähe das höhere Wesen?
- **Bedienung:** Animation abspielen, pausieren, zurücksetzen, Geschwindigkeit und Ablauf per Regler steuern; einzelne Dimensionen lassen sich groß hervorheben – praktisch für den Beamer im Unterricht.
- **Dreisprachig:** Deutsch · English · 中文 (per Knopfdruck umschaltbar)

## Das Prinzip dahinter

> Ein Wesen aus einer höheren Dimension kann Objekte in eine Richtung bewegen,
> die in der niedrigeren Dimension nicht existiert.

Was in einer Welt unmöglich ist (ein Ball verschwindet aus einer verschlossenen
Vitrine), ist eine Dimension höher ganz einfach.

## Technik

- Eine einzige Datei: [`index.html`](index.html) – ohne Build-Schritt, ohne Abhängigkeiten (nur Schriften von Google Fonts)
- Animationen mit reinem JavaScript auf HTML-Canvas
- Responsiv (Desktop bis Smartphone), berücksichtigt `prefers-reduced-motion`
- Gehostet über GitHub Pages (Branch `main`, Ordner `/`)

## Selbst hosten oder anpassen

Die Datei `index.html` genügt – einfach herunterladen und lokal im Browser
öffnen oder auf einen beliebigen Webserver legen. Alle Texte der drei Sprachen
stehen gesammelt im `T`-Objekt im Skriptteil der Datei.

## Autor und Lizenz

© 2026 Manfred Sablotny

Dieses Werk ist lizenziert unter einer [Creative-Commons-Lizenz „Namensnennung 4.0 International“ (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.de) – siehe [LICENSE](LICENSE). Du darfst die Seite frei teilen und bearbeiten (auch für den eigenen Unterricht), solange der Autor genannt wird.

---

*„Manchmal ist das Unmögliche nur eine Richtung weiter.“*
