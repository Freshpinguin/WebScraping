Dieses Projekt wird von Dave und Robin für die Vorlesung TextAnalytics im Sommersemester 2022 bearbeitet.

## Fragestellung

Können Methoden zur Textanalyse und Webscraping benutzt werden, um Unterschiede zwischen der Berichterstattung über den Ukraine-Russland Krieg in Deutschland und Russland zu finden? Wo sind diese Unterschiede besonders gravierend und wie lassen sich diese quantifizieren?  


## Methodik

Als Datenbasis sollen Veröffentlichungen der jeweils drei größten Nachrichtenwebsiten aus Russland und Deutschland herangezogen werden.
Die Methode zur Analyse der Texte wird im Laufe der Vorlesung entwickelt.

## WebScraping 

Wie in der Statistik von [Statista](https://www-statista-com.thn.idm.oclc.org/statistics/442988/most-visited-news-websites-germany/)(Aufgerufen 18.4.22) zu 
sehen ist sind die drei Nachrichten Websiten aus Deutschland mit der größten Reichweite für Februar 2022:

1. Bild.de
2. T-Online Contentangebot
3. n-tv.de

Wie in der Statistik von [Statista](https://www-statista-com.thn.idm.oclc.org/download/MTY1MDI3ODU2NSMjNjQ1MTMjIzExOTUyODAjIzEjI3BkZiMjU3RhdGlzdGlj)(Aufgerufen 18.4.22) zu 
sehen ist sind die drei Nachrichten Websiten aus Russland mit der größten Reichweite für August 2021:

1. Lenta.ru
2. Kp.ru
3. Rg.ru


### Deutsche News Websiten

Dateiformat:

Für jede Seite gibt es eine Funktion "get_article_content(url)"
Diese gibt:

 'title': title,
        'kicker': kicker,
        'author':author,
        'date':date,
        'text':text,
        'subheadlines': subheadline,
        'url': url
        
zurück. Wenn eines dieser Attribute nicht vorhanden ist: ''
(Auf Figcaption wird verzichtet _ Warum? _ Vielleicht doch noch)


### Bild.de

Bild hat ein sehr schönes Archiv, in dem sich alle älteren Artikel befinden. 

### T-Online Contentangebot

T-Online hat kein Archiv, allerdings sind ältere Artikel anscheinend über eine größeren Seitenindex abrufbar (muss noch getestet werden).

### n-tv.de

N-Tv hat kein Archiv, allerdings sind ältere Artikel anscheinend über eine größeren Seitenindex abrufbar (muss noch getestet werden).



### Russische Websiten

Fragen klären:

1. Ist es gefährlich?
2. Übersetzungsoftware besorgen
