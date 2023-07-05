---
marp: true
theme: custom-default
paginate: true
class:
- invert
header: 'Developer Experience'
footer: 'Konrad Heimel 2023-07-04'
markdown.marp.enableHtml: true
inlineSVG: true
style: |
  .columns {  
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 1rem;
  }
---

# Developer Experience Workshop: Nutzerzentrierte Gestaltung im Platform Engineering

![bg opacity:.9](images/slide-1.png)

---

![bg right](images/slide-10.png)

## Workshop Agenda

- Einführung in das Konzept eines Platform Teams
- Erläuterung von Developer Experience und User Experience
- Einführung in User Personas
- Hands-on: Erstellung von User Personas

---

<!-- _class: default -->

# Die vier Team-Typen nach Team Topologies

- Stream-Aligned Team
- Complicated-Subsystem Team
- Enabling Team
- Platform Team

![bg left](images/slide-3.png)

---

![bg opacity:.3](images/slide-4.png)

## Was ist überhaupt ein Platform Team?

- Ein Platform Team hat die Aufgabe, Stream-Aligned Teams so zu unterstützen, dass diese weitestgehend autonom arbeiten können.
- Die Stream-Aligned Teams sind vollumfänglich verantwortlich für die Entwicklung, den Betrieb und die Wartung ihrer Anwendungen
- Ein Platform Team stellt interne Dienste bereit, die die kognitive Belastung der Stream-Aligned Teams bei der Entwicklung und dem Betrieb ihrer Anwendungen reduzieren.

<!-- _footer: Team Topologies, Matthew Skelton and Manuel Pais, Seite 151 -->

---

![bg opacity:.3](images/slide-5.png)

## Welches Verhalten wird von einem effizienten Platform Team erwartet?

- Enge Zusammenarbeit mit Stream-Aligned Teams, um deren Bedürfnisse zu verstehen.
- Anwendung von Fast-Prototyping-Methoden und Einbeziehung von Stream-Aligned Teams für schnelles Feedback zur Nützlichkeit der Dienstleistungen.
- Hochwertige, zuverlässige Dienstleistungen, die regelmäßig auf Aktualität und Nutzbarkeit überprüft werden.
- Nutzung der eigenen Dienstleistungen, um die Benutzererfahrung zu verstehen und zu verbessern.

<!-- _footer: Team Topologies, Matthew Skelton and Manuel Pais, Seite 152 -->

---

<!-- _class: default -->

![bg right](images/slide-2.png)

## _"I don't think, that you can ever do a good job of creating a platform unless you deeply understand the problem from the perspective of a stream aligned developer."_


<!-- _footer: Dave Farley, Co-Autor von Continuous Delivery -->

---

## Platform Engineering geht über reine technische Infrastruktur hinaus

<font size="5">

- **Plattform als Produkt**<br>
  Die Plattform ist nicht nur Infrastruktur, sie ist ein Produkt, das den Bedürfnissen ihrer Nutzer gerecht werden sollte.

- **Nutzung von Produktentwicklungsmethoden**<br>
  Platform Engineering nutzt Techniken der Produktentwicklung, einschließlich User Experience Design und User Research, um nutzerzentrierte Produkte zu schaffen.

- **Platform Thinking und Community-Building**<br>
  Eine Plattform wird als Gemeinschaft gesehen, nicht nur als technisches Produkt. Sie fördert Zusammenarbeit, Wissensaustausch und gegenseitige Unterstützung.

</font>

![bg opacity:.3](images/slide-6.png)

---

## Was ist Developer Experience?


- Developer Experience (DX) bezieht sich auf die Gesamterfahrung, die ein Entwickler hat, wenn er mit einem Produkt oder einer Plattform interagiert.
- Es ist ein Teilbereich der User Experience (UX), spezialisiert auf die Bedürfnisse und Anforderungen von Softwareentwicklern.
- Ziel ist es, Entwicklern eine reibungslose, intuitive und produktive Erfahrung zu bieten.

_"The Developer Experience (DX) describes the experience developers have while using or working on your product. It is a package of positive and also negative feelings."_

<!-- _footer: developerexperience.io -->

![bg opacity:.3](images/slide-12.png)

---

## Merkmale einer guten Developer Experience (DX) können sein:

<font size="5">

- **Dokumentation**:<br> Eine vollständige, klar strukturierte und leicht verständliche Dokumentation. Enthält beispielsweise eine gut gepflegte README-Datei, Tutorials, Anleitungen zur Fehlerbehebung und Beispiele für gängige Anwendungsfälle.

- **API-Design**:<br> Intuitive und konsistente APIs, die den Prinzipien des sauberen Designs folgen.

- **Fehlermeldungen**:<br> Hilfreiche und präzise Fehlermeldungen, die Entwicklern dabei helfen, Probleme schnell zu identifizieren und zu beheben.

- **Tooling**: <br>Leistungsstarke und benutzerfreundliche Tools, die die Entwicklung erleichtern und beschleunigen.

- **Community und Support**:<br> Aktive Entwicklergemeinschaft und ansprechbarer Support. Möglichkeiten zur Interaktion und zum Austausch mit anderen Entwicklern.

</font>

![bg opacity:.3](images/slide-8.png)

---

![bg opacity:.3](images/slide-7.png)

## Zeichen von schlechter Developer Experience (DX) können sein:

<font size="5">

- **Fehlende oder veraltete Dokumentation**:<br>
  Fehlende Anleitungen, veraltete Informationen oder unklare Anweisungen, die die Entwickler im Stich lassen.

- **Unkonsistentes API-Design**:<br>
  APIs, die nicht intuitiv zu verwenden sind oder die gängige Prinzipien verletzen.

- **Nichtsaussagende Fehlermeldungen**:<br>
  Fehlermeldungen, die unklar sind oder die Ursache des Problems nicht genau identifizieren.

- **Komplexe Tools**:<br>
  Tools, die schwer zu erlernen und zu verwenden sind oder die nicht gut mit anderen Tools integrieren.

- **Mangelnder Support und Community**:<br>
  Fehlende Unterstützung und eine nicht engagierte Community, die nicht bei der Lösung von Problemen hilft.

</font>

---

## Was sind User Personas?

- User Personas sind fiktive Charaktere, die typische Nutzer und deren Eigenschaften, Bedürfnisse, Motivationen und Verhaltensweisen repräsentieren.
- Sie basieren auf den Erkenntnissen aus der Nutzerforschung und dienen als konkrete, greifbare Darstellungen von Nutzersegmenten.
- User Personas helfen, die Perspektive der Nutzer einzunehmen und Produktentscheidungen an ihren Bedürfnissen auszurichten.

![bg opacity:.3](images/slide-11.png)

---

## Nutzen von User Personas

<font size="5">

- **Klare Ausrichtung**<br>
  Helfen, ein gemeinsames Verständnis der Nutzer zu schaffen und sich besser auf deren Bedürfnisse auszurichten.
- **Empathie schaffen**<br>
  Errmöglichen es, sich besser in die Nutzer hineinzuversetzen und deren Perspektive einzunehmen.
- **Entscheidungshilfe**<br>
  Erleichtern Entscheidungen, indem sie dabei helfen, Optionen aus der Perspektive der Nutzer zu bewerten.
- **Kommunikation erleichtern**<br>
  Dienen als gemeinsame Referenzpunkte für die Kommunikation mit anderen Teammitgliedern und Stakeholdern.

</font>

![bg opacity:.3](images/slide-13.png)

---

<!-- _class: default -->
<font size="3">

## User Persona: Python Pete - Data Scientist

<div class="columns">

<div class="left">

<div align="center">

  ![width:200px](images/slide-14.png)

</div>

### Demografie

Leitender Data Scientist, 7 Jahre Erfahrung, spezialisiert auf Python und Maschinelles Lernen


### Bevorzugte Tools & Methoden

Python, TensorFlow, Jupyter Notebook, Scikit-learn, Spark, CI/CD.

### Zitat

"Ich möchte, dass meine Modelle mit hoher Geschwindigkeit und hoher Leistung laufen, ohne dass ich ein Kubernetes-Zertifikat benötige, um das zu erreichen."

</div>

<div class="right">

### Ziele und Bedürfnisse:

- Wünscht eine robuste Plattform, um Datenverarbeitungsjobs und ML-Modelle zu hosten.
- Sucht nach einer einfacheren Methode, um ML-Modelle zu trainieren, zu testen und zu implementieren.
- Macht sich Sorgen um die Performanz seiner Modelle und will dafür eine effiziente und zugleich zuverlässige Infrastruktur.

### Frustrationen:

- Hat mehr "Data" als "Science" im Job, da er viel Zeit damit verbringt, Infrastrukturprobleme zu beheben, anstatt Modelle zu trainieren.
- Leidet unter der Komplexität von Kubernetes und findet, dass es schwer ist, all die Details zu lernen und gleichzeitig ein vollzeit Data Scientist zu sein.
- Hat Schwierigkeiten, seine Modelle von der lokalen Entwicklungsumgebung in die Kubernetes-Umgebung zu übertragen.
- Sieht Kubernetes als eine notwendige Hürde auf dem Weg zur erfolgreichen Modellimplementierung.

</div>
</div>

</font>
