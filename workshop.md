<!--

author:   Linda Zollitsch, Swantje Piotrowski
email:    zollitsch@ub.uni-kiel.de
version:  0.1.0
language: de
narrator: UK English Female

iicon:     /images/Logo_cau-norm-de-lilagrey-rgb-0720_2022.png

link: style_css.css

comment:   presentation for workshop: sharing is caring

-->


# Workshop Sharing is caring

Lehrmaterialien gemeinsam weiterentwickeln und miteinander teilen am Beispiel des Forschungsdatenmanagements
---



# Agenda

- Theoretische Einführung (ca. 09:00-10:30)
- Hinführung zur Anwendung (ca. 10:30-12:30)

Mittagspause

- Anwendungsteil / Praktische Anwendung (ca. 14:00-16:00)
- Abschluss (ca. 18:00-17:00)

## Beschreibung
Offene und nachnutzbare Lehr- und Lernmaterialien sind eine zentrale Voraussetzung für nachhaltige Kompetenzentwicklung im Forschungsdatenmanagement (FDM). Viele bereits erstellte Materialien stehen zwar als Open Educational Resources (OER) zur Verfügung, sind jedoch häufig noch nicht konsequent nach den FAIR-Prinzipien gestaltet und dadurch nur eingeschränkt nachnutzbar.

Der Workshop führt in zentrale Konzepte zu OER und FAIR ein und zeigt, wie sich Trainingsmaterialien (am Beispiel des Forschungsdatenmanagements) mit LiaScript offen, interaktiv und gemeinschaftlich weiterentwickeln lassen. Im praktischen Teil arbeiten die Teilnehmenden direkt an eigenen oder bereitgestellten Materialien und erproben, wie Inhalte gemeinsam in FAIRe, nachnutzbare OER überführt werden können. Ziel ist es, konkrete Ansätze und erste Materialien bzw. Überarbeitungen zu entwickeln, die in der FDM-Community weiter genutzt und ausgebaut werden können.


# Theoretische Einführung

## Open Educational Resources (OER)

![Fragezeichen](/images/FragezeichenTyp.jpg)

### Was ist das?

#### Definition


"Open Educational Resources (OER) sind Bildungsmaterialien jeglicher Art und in jedem Medium, die unter einer offenen Lizenz stehen. Eine solche Lizenz ermöglicht den kostenlosen Zugang sowie die kostenlose Nutzung, Bearbeitung und Weiterverbreitung durch Dritte ohne oder mit geringfügigen Einschränkungen."
"OER sind nicht nur kostenlos zugänglich, sondern können auch frei bearbeitet, geteilt, aktualisiert und vor allem an individuelle Lernbedürfnisse und -kontexte angepasst werden."
"Open Educational Resources können einzelne Materialien, aber auch komplette Kurse oder Bücher umfassen. Jedes Medium kann verwendet werden. Lehrpläne, Kursmaterialien, Lehrbücher, Streaming-Videos, Multimedia-Anwendungen, Podcasts – all diese Ressourcen sind OER, wenn sie unter einer offenen Lizenz veröffentlicht werden. Dabei bestimmen die Urhebenden selbst, welche Nutzungsrechte sie einräumen und welche Rechte sie sich vorbehalten."
https://www.unesco.de/themen/bildung/bildungsqualitaet/weltbildungsempfehlung/global-citizenship-education/friedens-und-menschen/open-educational-resources/

https://unesdoc.unesco.org/ark:/48223/pf0000392271.locale=en

https://www.oer-strategie.de/


"Eine offene Lizenz respektiert die geistigen Eigentumsrechte des Inhabers der Urheberrechte und gewährt der Öffentlichkeit das Recht auf Zugang, Weiterverwendung, Nutzung zu beliebigen Zwecken, Bearbeitung und Weiterverbreitung von Bildungsmaterialien."
https://www.oer-strategie.de/wp-content/uploads/691288_OER-Strategie.pdf


https://open-educational-resources.de/

https://www.unesco.de/dokumente-und-hintergruende/publikationen/detail/was-sind-open-educational-resources/



### Was kann das?

### Kann ich das auch?


## FAIR-Prinzipien

![Fragezeichen](/images/FragezeichenTyp.jpg)

### Was ist das?

{{0-1}}
****************
<img src="../images/fair2.jpg" width="450" align="right"> 

Ein wichtiges Ziel des strukturierten Foschungsdatenmanagements ist es, Daten langfristig und personenunabhängig zugänglich, nachnutzbar und nachprüfbar zu halten.

Die [**FAIR-Prinzpien**](https://www.nature.com/articles/sdata201618) dienen als Leitfaden für die Auswahl von Handlungsoptionen, die sicherstellen sollen, dass die im Rahmen von Forschung geschaffenen digitalen Artefakte auffindbar, zugänglich, interoperabel und wiederverwendbar sind.

<small>Illustration: Patrick Hochstenbach in Engelhardt, Claudia et. al. (2021).</small>

****************

<div style="page-break-after: always;"></div>

{{1}}
>**F**indable

{{2-3}}
****************
Der erste Schritt bei der (Wieder-)Verwendung von Daten besteht darin, sie zu finden. Metadaten und Daten sollten sowohl für Menschen als auch für Computer leicht zu finden sein.

F1. (Meta)data are assigned a globally unique and persistent identifier

F2. Data are described with rich metadata (defined by R1 below)

F3. Metadata clearly and explicitly include the identifier of the data they describe

F4. (Meta)data are registered or indexed in a searchable resource

***************


{{1}}
>**A**ccessible

{{3-4}}
***********************
Sobald der Nutzer die gewünschten Daten gefunden hat, muss er wissen, wie er auf sie zugreifen kann, möglicherweise einschließlich Authentifizierung und Autorisierung.

A1. (Meta)data are retrievable by their identifier using a standardised communications protocol

A1.1 The protocol is open, free, and universally implementable

A1.2 The protocol allows for an authentication and authorisation procedure, where necessary

A2. Metadata are accessible, even when the data are no longer available

******************

<div style="page-break-after: always;"></div>

{{1}}
>**I**nteroperable

{{4-5}}
**********************
Daten sollten in einer Form vorliegen, die die Nutzung mit diversen Anwendungen oder Arbeitsabläufen für die Analyse, Speicherung und Verarbeitung ermöglichen.

I1. (Meta)data use a formal, accessible, shared, and broadly applicable language for knowledge representation.

I2. (Meta)data use vocabularies that follow FAIR principles

I3. (Meta)data include qualified references to other (meta)data

**********************

{{1}}
>**R**eusable

{{5-6}}
***************
Das Ziel von FAIR ist es, die Wiederverwendung von Daten zu optimieren. Um dies zu erreichen, sollten Metadaten und Daten gut dokumentiert und beschrieben sowie mit einer eindeutigen Angabe bzgl. der Nutzungsbedingungen (Lizenzen) versehen sein.

R1. Meta(data) are richly described with a plurality of accurate and relevant attributes

R1.1. (Meta)data are released with a clear and accessible data usage license

R1.2. (Meta)data are associated with detailed provenance

R1.3. (Meta)data meet domain-relevant community standards

**************

### Was kann das? FAIR-Prinzipien im Überblick

![FAIR-Prinzipien](../images/fair_beispiele.png "Lehmann, Sebastian B. C.; Altemeier, Franziska; Nina, Düvel, 2026, Nachhaltige Wissenschaft mit Forschungsdatenmanagement - Eine Einführung für Betreuende von Qualifizierungsarbeiten, doi.org/10.25625/EKEEFB, GRO.data, V2")


### Kann ich das auch?

JA!
---

- es gibt nicht die Erwartung, dass alle Aspekte der FAIR-Prinzipien sofort umgesetzt sein müssen

- Schritt für Schritt beginnen, Aspekte umsetzen

- es muss nicht von Anfang an alles perfekt sein


## Lizenzen und offene Formate

![Fragezeichen](/images/FragezeichenTyp.jpg)


### Was ist das?

{{0-1}}
********************
Um einschätzen zu können, ob und in welcher Form Datensätze und sonstige Materialien nachgenutzt werden dürfen, sollten Lizenzsysteme bekannt sein.

*~~Lernziel~~: Lernende können Lizenssysteme benennen, erläutern und anwenden.*
********************

{{1-2}}
********************
Durch freie Lizenzen wird die Nutzung eines urheberrechtlich geschützten Inhalts Nachnutzenden erlaubt. Dabei können Einschränkungen in Hinblick auf den die Verbreitung von Bearbeitungen und Veränderungen oder in Bezug auf die Modalitäten einer weiteren Veröffentlichung bestehen.

Die am häufigsten verwendeten Lizenzensysteme sind:

- Creative Commons (CC) / für Texte, Abbildungen und Daten geeignet
- GNU General Public License (GPL) / für Software konzipiert
- Open Data Commons (ODC) / für Datenbanken konzipiert
- Community Data License Agreement / für Daten konzipiert

Das hierunter bekannteste Lizenzsystem sind die [Creative Commons Lizenzen](https://de.creativecommons.net/was-ist-cc/):

https://www.ub.uni-kiel.de/de/publizieren/publizieren/bilder/cc-lizenzen-im-ueberblick

Weitere Informationen auf forschungsdaten.info: https://forschungsdaten.info/themen/rechte-und-pflichten/forschungsdaten-veroeffentlichen/creative-commons-lizenzen/

********************

### Was kann das?

offene Lizenzen?

"Eine offene Lizenz respektiert die geistigen Eigentumsrechte des Inhabers der Urheberrechte und gewährt der Öffentlichkeit das Recht auf Zugang, Weiterverwendung, Nutzung zu beliebigen Zwecken, Bearbeitung und Weiterverbreitung von Bildungsmaterialien."
https://www.oer-strategie.de/wp-content/uploads/691288_OER-Strategie.pdf

### Kann ich das auch?

JA!
---

- sich mit Lizenzsystemen und Lizenzen vertraut machen

- mehr Sicherheit bei der Nachnutzung von 'fremden' Materialien

- eigene Materialien durch eine Lizenz kennzeichnen 
    - für die eigene Nachnutzung
    - für die Nachnutzung durch Andere


# Hinführung zur Anwendung

## Der Kriterienkatalog v2

![Fragezeichen](/images/FragezeichenTyp.jpg)

### Was ist das?

Der Kriterienkatalog

Zollitsch, L., & Piotrowski, S. (2026). Kriterienkatalog für Materialien aus dem Themenbereich Forschungsdatenmanagement (2.0). Zenodo. https://doi.org/10.5281/zenodo.18537803

### Was kann das?

Überblick über Inhalte und Aufbau des Kriterienkatalogs

### Kann ich das auch?

JA!
---

- Hilfestellung beim Identifizieren von Lücken in Bezug auf die FAIR-Prinzipien

- Überblick über mögliche Aspekte, die für die Nachnutzung von Materialien eine Rolle spielen

- Hinweise zur Verbesserung der Qualität der eigenen Materialien

- Bietet Möglichkeit zur Reflexion des eigenen Materials

## LiaScript und Markdown

![Fragezeichen](/images/FragezeichenTyp.jpg)

### Was ist das?

### Was kann das?

### Kann ich das auch?

# Mittagspause

# Anwendungsteil



## Praktische Anwendung von LiaScript

## Anwendungsphase mit Überarbeitung bestehender Materialien

Erstellung neuer Materialien ist natürlich auch möglich

# Abschluss

## Präsentation der Ergebnisse

## Reflexion der Anwendungsphase

Und? Wie wars?

## Zusammenfassung

Wo gibt es die Materialien

An wen kann ich mich bei weiteren Fragen oder für Kontakt wenden?
