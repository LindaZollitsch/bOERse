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

-----

Lehrmaterialien gemeinsam weiterentwickeln und miteinander teilen am Beispiel des Forschungsdatenmanagements
---



# Agenda

- Begrüßung
- Theoretische Einführung (ca. 09:30-10:30)
- Hinführung zur Anwendung (ca. 10:30-12:30)

Mittagspause

- Anwendungsteil / Praktische Anwendung (ca. 14:00-16:00)
- Abschluss (ca. 16:00-17:00)


## Kleinteilige Angenda für intern

- Begrüßung (ca. 09:00-09:30)
- Theoretische Einführung (ca. 09:30-10:25)
    - OER (15 Min)
    - Lizenzen (20 Min)
    - FAIR (20 Min)

- kurze Pause (15 Min) (ca. 10:25-10:40)

- Hinführung zur Anwendung (ca. 10:40-12:15)
    - Kriterienkatalog (20 Min)
    - Liascript / Markdown (40 Min)
    - Forschungsdatenmanagement (35 Min)

Mittagspause (12:15-13:45)

- Anwendungsteil / Praktische Anwendung (ca. 13:45-15:45)
- - kurze Pause (15 Min) (ca. 15:45-16:00)
- Abschluss (ca. 16:00-17:00)


## Beschreibung
Offene und nachnutzbare Lehr- und Lernmaterialien sind eine zentrale Voraussetzung für nachhaltige Kompetenzentwicklung im Forschungsdatenmanagement (FDM). Viele bereits erstellte Materialien stehen zwar als Open Educational Resources (OER) zur Verfügung, sind jedoch häufig noch nicht konsequent nach den FAIR-Prinzipien gestaltet und dadurch nur eingeschränkt nachnutzbar.

-----

Der Workshop führt in zentrale Konzepte zu OER und FAIR ein und zeigt, wie sich Trainingsmaterialien (am Beispiel des Forschungsdatenmanagements) mit LiaScript offen, interaktiv und gemeinschaftlich weiterentwickeln lassen. Im praktischen Teil arbeiten die Teilnehmenden direkt an eigenen oder bereitgestellten Materialien und erproben, wie Inhalte gemeinsam in FAIRe, nachnutzbare OER überführt werden können. Ziel ist es, konkrete Ansätze und erste Materialien bzw. Überarbeitungen zu entwickeln, die in der FDM-Community weiter genutzt und ausgebaut werden können.




## Limitation

- Es werden die Schritte 1 bis 3 im Workshop behandelt 

- Eine praktische Umsetzung an eigenen Materialien kann im Rahmen des 3stündigen Workshops nicht geleistet werden

- Wir fokussieren uns nur auf Teilaspekte der FAIR-Prinzipien

- Es ist erwünscht, eigene Beispiele in die Diskussion mit einzubringen


# Begrüßung 

Ankommen

Vorstellen und Kennenlernen - Vorwissen erfragen


# Überblick über den Prozess

<!--
style="
  display: block;
  margin-left: auto;
  margin-right: auto;
  max-width: 100%;
  background-color: lightblue;
  stroke: black;" -->
``` ascii

    .-------------------------------------------.  
    | 🏴 Step 1: Identifizieren von (Metadaten) |-----------------------------.
    | Lücken bezüglich der FAIR-Prinzipien      |                              \
    '-------------------------------------------'                               \
            .------------------------+----------------------.                    \
            | Überprüfung des eigenen Materials auf Lücken  |                     \
            |  z.B. mithilfe des Kriterienkatalogs          |               .------------------------------.
            '-----------------------------------------------'               | 🔎 Step 2: Festlegen der zu  |
                                                                            | schließende(n) Lücke(n)      |
                                                                            '------------------------------'
                                                                                       |  .-------------------------------.
                                                                                       |  | Setzen eines Schwerpunkts     |
                                                                                       |  | bezüglich der FAIR-Prinzipien |
                                                                                       |  '-------------------------------'
                                                                                       |
     .---------------------------------.                                               .     
     | 🏁 Step 5: FAIRe OER nachnutzen |                                              /
     '---------------------------------'                                             /
                           \                                   .----------------------------.
                            \                                  | 📝 Step 3: Lücke schließen |
                             \                                 '----------------------------'
                              \                                   /                 .-----------------+--------------.
                               \                                 /                  | Überarbeitung der Materialien  |
                               .--------------------------------------.             | um FAIRe OER zu erhalten       |
                               | 🔓 Step 4: FAIRe OER veröffentlichen |             '--------------------------------'
                               '--------------------------------------'
                          .-------------------+---------------.
                          | Veröffentlichung der Materialien  |
                          | in einem geeigneten Repositorium  |
                          '-----------------------------------'

```

# Theoretische Einführung (60 Min)

<!--
style="
  display: block;
  margin-left: auto;
  margin-right: auto;
  max-width: 100%;
  background-color: lightblue;
  stroke: black;" -->
``` ascii

        
            .------.                                  .--------.
            | OER  |----------------------------------|  FAIR  |
            '------'  \                            /  '--------'       
                       \                          /
                        \                        /
                         \                      /
                          \                    /
                           \                  /
                            \                /
                             \              /
                              \            /
                              .------------.
                              | FAIRe OER  |
                              '------------'
      

```

{{1}}
********************
OER und FAIR stehen thematisch nebeneinander

| Jahr    | OER                                             | FAIR                                                    |
| ------- | ----------------------------------------------- |-------------------------------------------------------- |
| 2002    | UNESCO verwendet  den Begriff erstmalig         |                                                         |
| 2006    | OER werden durch ein EU-Projekt gefördert       |                                                         |
| 2007    | Stuttgarter Erklärung und Cape Town Declaration |
| 2009    | OER-Plattform "OpenLearnWare"                   |
| 2012    | OER Policy Registry, Paris Declaration          |
| 2015    | Neue OER Definition der UNESCO                  |

********************

## Open Educational Resources (OER)

![OER Logo](/images/OER.png)

^This logo is a CC0/Public Domain OER logo which can be used and adapted freely. It is based on an original design from "leomaria", Berlin.^

### Was ist das?

*~~Lernziel~~: Lernende können den Begriff OER erläutern.*

offene Fragerunde:

- Welche Berührungspunkte hatten Sie bisher mit OER?

- Was wissen Sie bereits über OER?

{{1}}
********************

Definition
---

"Open Educational Resources (OER) sind Bildungsmaterialien jeglicher Art und in jedem Medium, die unter einer offenen Lizenz stehen. Eine solche Lizenz ermöglicht den kostenlosen Zugang sowie die kostenlose Nutzung, Bearbeitung und Weiterverbreitung durch Dritte ohne oder mit geringfügigen Einschränkungen."
"OER sind nicht nur kostenlos zugänglich, sondern können auch frei bearbeitet, geteilt, aktualisiert und vor allem an individuelle Lernbedürfnisse und -kontexte angepasst werden."

"Open Educational Resources können einzelne Materialien, aber auch komplette Kurse oder Bücher umfassen. Jedes Medium kann verwendet werden. Lehrpläne, Kursmaterialien, Lehrbücher, Streaming-Videos, Multimedia-Anwendungen, Podcasts – all diese Ressourcen sind OER, wenn sie unter einer offenen Lizenz veröffentlicht werden. Dabei bestimmen die Urhebenden selbst, welche Nutzungsrechte sie einräumen und welche Rechte sie sich vorbehalten."

https://www.unesco.de/themen/bildung/bildungsqualitaet/weltbildungsempfehlung/global-citizenship-education/friedens-und-menschen/open-educational-resources/

-----

"Eine offene Lizenz respektiert die geistigen Eigentumsrechte des Inhabers der Urheberrechte und gewährt der Öffentlichkeit das Recht auf Zugang, Weiterverwendung, Nutzung zu beliebigen Zwecken, Bearbeitung und Weiterverbreitung von Bildungsmaterialien."

https://www.oer-strategie.de/wp-content/uploads/691288_OER-Strategie.pdf


********************

{{2}}
********************

Weiterführende Informationen
---

https://unesdoc.unesco.org/ark:/48223/pf0000392271.locale=en

https://www.oer-strategie.de/

https://open-educational-resources.de/

https://www.unesco.de/dokumente-und-hintergruende/publikationen/detail/was-sind-open-educational-resources/

********************

## OER als genereller Lösungsansatz?

**Open Courseware / Open Educational Resources** ... teaching, learning and
research materials in any medium, digital or otherwise,that reside in the
**public domain** or have been released under an open license that permits
no-cost access, use, **adaptation** and **redistribution** by others with no or 4
limited restrictions. Open licensing is built within the existing framework of
intellectual property rights as defined by relevant international conventions
and respects the authorship of the work

-- UNESCO 2002 Forum on the Impact of Open Courseware for Higher Education in Developing Countries [(Link)](https://unesdoc.unesco.org/ark:/48223/pf0000128515)

           {{0-1}}
********************************************************************************

| Anforderung                  | Bedeutung                                  |
| ---------------------------- | ------------------------------------------ |
| `verwahren/vervielfältigen ` | Download, Speicherung und Vervielfältigung |
| `verwenden`                  | Nutzung im Lernkontext                     |
| `verarbeiten`                | Umgestaltung und Adaption                  |
| `vermischen`                 | Kombination und Extraktion                 |
| `verbreiten`                 | (digitale) Publikation                     |


*_5 V-Freiheiten für Offenheit_ von Jöran Muuß-Merholz und Jörg Lohrer für [open-educational-ressources](https://open-educational-resources.de) - Transferstelle für OER*

_OER können der Auslöser für Innovation und neue Lenrformen des 21. Jahrhunderts sein._

-- _Handreichung OER - Der Einstieg in den Umgang mit Open Educational Ressources_, Bericht des Projektes OERsax, 2018

********************************************************************************

### Kritik am OER-Ansatz

Welche Probleme sehen Sie im OER-Ansatz?

-----

| Ebene                               | Kernaussage                                                                             |
| ----------------------------------- | --------------------------------------------------------------------------------------- |
| Emotionale Einordnung               | "_Da kann ja jeder meine Arbeit für sich nutzen!_"                                      |
|                                     | "_Da kann mich ja jeder kontrollieren!_"                                                |
| Rechtliche Herausforderungen        | "_Ich verwende viele Grafiken, die bei deren Urheberrecht ich mir im besten Fall unsicher bin!_"                                                                                        |
| Auffindbarkeit                      | "_Ich finde keine Inhalte, die ich in meiner Lehre gewinnbringend integrieren kann!_"   |
| <!-- Style="color:red" --> Aufwand  | <!-- Style="color:red" --> "_Da muss man ja Informatik studiert haben!_"                |
| <!-- Style="color:red" -->Abdeckung | <!-- Style="color:red" -->"_Da fehlen mir aber die Schnittstellen für meine Tools XY!_" |

### OER in a nutshell

Es ist ein Framework, mit dem man arbeiten kann
---

- Lehrmaterialien bauen und los geht es!

- Dabei die Grundlagen von OER beachten:

    - Zugänglichkeit
    
    - offene Lizenz

-----

Was Lizenzen sind und wie man damit umgeht, schauen wir uns nach dem folgenden Abschnitt an


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

![FAIR-Prinzipien](./images/fair_beispiele.png) 

"Lehmann, Sebastian B. C.; Altemeier, Franziska; Nina, Düvel, 2026, Nachhaltige Wissenschaft mit Forschungsdatenmanagement - Eine Einführung für Betreuende von Qualifizierungsarbeiten, doi.org/10.25625/EKEEFB, GRO.data, V2"

##  FAIRe OER

- es gibt nicht die Erwartung, dass alle Aspekte der FAIR-Prinzipien sofort umgesetzt sein müssen

- Schritt für Schritt beginnen, Aspekte umsetzen

- es muss nicht von Anfang an alles perfekt sein

- einfach anfangen



# FAIRe OER

- Findable (zum Beispiel über einen persistenten Identifier)

- Accessible (zum Beispiel durch Metadaten und Informationen über die Zugänglichkeit)

- Interoperable (zum Beispiel durch ein offenes, nicht-proprietäres Dateiformat, in dem das Material vorliegt)

- Reusable (Wiederverwendung durch Lizenzierung)

## Am Beispiel des R: Lizenzen 

![Fragezeichen](/images/FragezeichenTyp.jpg)

Lizenzen? Welche Lizenzen oder Lizenzsysteme kennen Sie?

- Sammlung der Teilnehmenden durch reinrufen in den Raum auf einem Flipchart

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

#### Was für Lizenzen gibt es?

Creative Commons (CC) Lizenzen:

CC0

CC-BY

CC-BY-SA

alle weiteren CC-Lizenzen gelten nicht als offene Lizenzen!

CC-BY-SA-NC

CC-BY-ND

### Wozu brauche ich das?

"Eine offene Lizenz respektiert die geistigen Eigentumsrechte des Inhabers der Urheberrechte und gewährt der Öffentlichkeit das Recht auf Zugang, Weiterverwendung, Nutzung zu beliebigen Zwecken, Bearbeitung und Weiterverbreitung von Bildungsmaterialien."
https://www.oer-strategie.de/wp-content/uploads/691288_OER-Strategie.pdf

- damit können die Bedingungen sichtbar gemacht werden, unter denen das Material nachgenutzt werden kann

- es herrscht Klarheit und Eindeutigkeit (Rechtssicherheit)

### Lizenzen in a nutshell

- es ist hilfreich, sich mit Lizenzsystemen und Lizenzen vertraut zu machen

- mehr Sicherheit bei der Nachnutzung von 'fremden' Materialien

- eigene Materialien durch eine Lizenz kennzeichnen 

    - für die eigene Nachnutzung

    - für die Nachnutzung durch Andere

# Hinführung zur Anwendung (120 Min)


# How to FAIRify your OER

## Step 1: Identifizieren von (Metadaten) Lücken bezüglich der FAIR-Prinzipien

Eigene, bereits produzierte Materialien überprüfen auf Lücken bezüglich der FAIR-Prinzipien

Mögliches Hilfsmittel: Der Kriterienkatalog für Materialien aus dem Themenbereich Forschungsdatenmanagement

 Zollitsch, L., & Piotrowski, S. (2026). Kriterienkatalog für Materialien aus dem Themenbereich Forschungsdatenmanagement (2.0). Zenodo. https://doi.org/10.5281/zenodo.18537803

 -----
 
Andere Hilfsmittel:

- FAIR-Prinzipien (Wilkinson, M., Dumontier, M., Aalbersberg, I. et al. The FAIR Guiding Principles for scientific data management and stewardship. Sci Data 3, 160018 (2016). https://doi.org/10.1038/sdata.2016.18)

- Metadatenschemata (Beispiele nennen)

    RDA Recommendations for a minimal metadata set (Hoebelheinrich, N. J., Biernacka, K., Brazas, M., Castro, L. J., Fiore, N., Hellström, M., Lazzeri, E., Leenarts, E., Martinez Lavanchy, P. M., Newbold, E., Nurnberger, A., Plomp, E., Vaira, L., van Gelder, C. W. G., & Whyte, A. (2022). Recommendations for a minimal metadata set to aid harmonised discovery of learning resources (1.0). Zenodo. https://doi.org/10.15497/RDA00073)

    Metadatenschema für Schulungsmaterialien (Biernacka, K., Haase, C., Löhde, B., Murcia Serra, J., Neumann, J., Scherreiks, P., Schneemann, C., Schranzhofer, H., Senft, M., Voigt, A., & Wiljes, C. (2025). Metadatenschema für Schulungsmaterialien zum Thema Forschungsdatenmanagement. Zenodo. https://doi.org/10.5281/zenodo.14800610)

### Der Kriterienkatalog

Zollitsch, L., & Piotrowski, S. (2026). Kriterienkatalog für Materialien aus dem Themenbereich Forschungsdatenmanagement (2.0). Zenodo. https://doi.org/10.5281/zenodo.18537803

-----

- Hilfestellung beim Identifizieren von Lücken in Bezug auf die FAIR-Prinzipien

- Überblick über mögliche Aspekte, die für die Nachnutzung von Materialien eine Rolle spielen

- Hinweise zur Verbesserung der Qualität der eigenen Materialien

- Bietet Möglichkeit zur Reflexion des eigenen Materials



- Materialien werden mit dem Kriterienkatalog überprüft

- jeder hat 20 Minuten Zeit, sich schonmal dazu vertraut zu machen und die eigenen Materialien daraufhin zu überprüfen

- jeder stellt kurz vor, welche Lücken gefunden wurden

-----

![Fragezeichen](/images/FragezeichenTyp.jpg)



## Step 2: Festlegen der zu schließende(n) Lücke(n)

Empfehlung, einen Schwerpunkt zu setzen. 

Die FAIR-Prinzipien in ihrer Gesamtheit vollständig umzusetzen ist ein Prozess, der sehr komplex ist und in einigen Fällen möglicherweise auch nie ganz erfüllt werden kann. Es empfiehlt sich daher, zunächst einen Schwerpunkt zu setzen, welchen oder welche Aspekt(e) vorrangig umgesetzt werden sollen.

- Findable (zum Beispiel über einen persistenten Identifier)

- Accessible (zum Beispiel durch Metadaten und Dokumentation des Zugangsweges)

- Interoperable (zum Beispiel durch ein offenes, nicht-proprietäres Dateiformat, in dem das Material vorliegt)

- Reusable (Wiederverwendung durch Lizenzierung für die Veröffentlichung)

-----

Fokus auf I und R!

----

Methode überlegen

mit einem Partner die Lücken besprechen und eine zu schließende Lücke identifizieren


## Step 3: Lücke schließen

Nachdem Lücken identifiziert (wurden) und entschieden wurde, welche Lücken geschlossen werden sollen, geht es an die Umsetzung. 

zu Findable: Veröffentlichung der Materialien nicht eingebunden auf einer Homepage, sondern über ein Respositorium und mit einem digital object identifier (DOI). Eine Empfehlung für ein entsprechendes Repositorium wäre Zenodo.

zu Accessible: Es sollte auf eine möglichst umfassende Beschreibung durch Metadaten geachtet werden (z. B. Zielgruppe, Lernziele, Kontext und Version), sodass andere Nutzende die Inhalte verstehen und sinnvoll weiterverwenden können; Insbesondere aber Beschreibung des Wegs, um Zugang zu dem Material zu bekommen.

zu Interoperable: Bei Veröffentlichung des Materials ein Dateiformat wählen, das möglichst offen und nicht proprietär ist. Falls das nicht möglich sein sollte, unter den proprietären Formaten eines wählen, das dennoch auch von anderen Programmen geöffnet werden kann. Eine Empfehlung wären .md, .odt, .csv

zu Reusable: Bei Veröffentlichung des Materials eine entsprechende Lizenz mit angeben, die es den Nachnutzenden leicht macht zu erfahren, wie das Material nachgenutzt werden darf. Mögliche Lizenzen wären hier die CC-0 sowie die CC-BY Lizenzen.


## Step 4: FAIRe OER veröffentlichen

Teilen Sie ihre Materialien mit anderen! (Hausaufgabe)

Zeigen von Beispielen, wie aus pdf eine Markdown-Datei wurde

Beispiel LiaScript

#### LiaScript

- https://liascript.github.io/

- https://liascript.github.io/course/?https://raw.githubusercontent.com/liaScript/docs/master/README.md#1

LiaScript ist ein Markdown-Dialekt für interaktive Kurse und datengesteuertes Publizieren,

- alles ist in Elm/JavaScript implementiert und läuft direkt im Browser (online),

- der Interpreter selbst ist gleichzeitig ein Reader, der sowohl das Speichern von Dokumenten als auch den Fortschritt ermöglicht,

- alles ist privat, es werden keine Daten über die Kurse, Nutzer oder deren Fortschritte gespeichert. 



## Step 5: FAIRe OER nachnutzen

Nutzen Sie die eigenen aber auch die Materialien von anderen nach!

(könnte in diesem Step nicht auch auf die Box 2 aus Wilkinson et al. 2016, S. 4 verwiesen werden, in der die Inhalte der jeweiligen FAIR-Prinzipien kurz runtergebrochen werden?) 







## Warum FAIRe OER?!

Video:

https://www.youtube.com/watch?v=66oNv_DJuPc

-----

Haben Sie selbst schon einmal im (Arbeits)Alltag ähnliche Situationen erlebt?

Wie können FAIRe OER helfen, die im Video gezeigten Probleme zu reduzieren?


## Reflexion der Anwendungsphase

- Was lief gut?

- Wo gab es Herausforderungen?

- Wie war es allgemein?

## Zusammenfassung

- Wo gibt es die Materialien

- An wen kann ich mich bei weiteren Fragen oder für Kontakt wenden?
















