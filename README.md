# HTML Stunde: XML, RSS, Atom und Podcasts

**tl;dr**

[Beispiel-HTML-Seite mit Links zu XML-Feeds](index.html)

- [RSS 2.0 Feed](rss.xml)
- [Atom Feed](atom.xml)
- [Podcast-Feed](podcast-episodes.xml)

Zusätzliche Informationen sind in den Dateien als Kommentare an den betreffenden Stellen untergebracht, können (und sollten) aber für echte Feeds entfernt werden.

## RSS

RSS ("Rich Site Summary") wird verwendet, um Artikel einer Website oder deren Kurzbeschreibungen, insbesondere Nachrichtenmeldungen, zu speichern und in maschinenlesbarer Form bereitzustellen. Ein sogenannter RSS-Feed oder Newsfeed besteht aus einer [XML-Datei](rss.xml), die den reinen strukturierten Inhalt – beispielsweise einer Nachrichtenseite – bereithält, aber keinerlei Layout, keine Navigation oder sonstige Zusatzinformationen beinhaltet. Zahlreiche Webangebote, die regelmäßig Artikel publizieren, stellen eine automatisch generierte RSS-Datei mit den neuesten Artikeln zur Verfügung. Das Format erlangte seine heutige Popularität vor allem durch den Einsatz in Blogs. Mittlerweile haben auch MP3-Portale begonnen, [RSS-Feeds mit Podcasting-Funktionalität](podcast-episodes.xml) einzusetzen.  
[Wikipedia: RSS](https://de.wikipedia.org/wiki/RSS_(Web-Feed))

## Atom

Atom entstand aus dem Bedürfnis heraus, die Vorteile der unterschiedlichen RSS-Formate ([0.9, 1.0, 2.0](https://de.wikipedia.org/wiki/RSS_(Web-Feed)#Versionen,_Alternativen_und_Erg%C3%A4nzungen)) in einem neuen Format zusammenzufassen und um neue Elemente zu ergänzen. Dabei haben die Entwickler – in überwiegender Mehrzahl Blogger – *Atom Syndication Format* auch so gestaltet, um den speziellen Bedürfnissen von Blogs und Nachrichtenseiten gerecht zu werden.  
[Wikipedia: Atom](https://de.wikipedia.org/wiki/Atom_(Format))

## Podcasts

Ein Podcast ist eine Serie von abonnierbaren Mediendateien (Audio oder Video) über das Internet. Er besteht aus einer Serie von Beiträgen (Episoden), die über einen Web-Feed (meistens RSS) automatisch bezogen werden können.
Der Podcasting-Client bietet dem Hörer die Möglichkeit, Listen von Web-Feeds von Podcasts zusammenzustellen. Viele Clients erlauben die regelmäßige Aktualisierung und den automatischen Download der abonnierten Podcast-Feeds.
Neben dem Abonnement durch spezielle Clients können Podcasts meistens auch über eine Website in Form eines Hyperlinks auf die Audiodatei publiziert und als gewöhnliche Audiodateien vom Nutzer mit dem Webbrowser heruntergeladen werden (Beispiel: [atp.fm](https://atp.fm/) und der [Feed](http://atp.fm/episodes?format=rss) dazu). Podcast-Feeds können auf einer HTML-Seite genau wie ein herkömmlicher RSS 2.0 Feed im `<head>` verknüpft werden.  
[Wikipedia: Podcast](https://de.wikipedia.org/wiki/Podcast)


