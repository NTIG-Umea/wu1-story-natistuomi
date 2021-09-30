# wu1-story
En grundläggande övning i HTML och text.

## Uppgift

Du ska utifrån en historia/berättelse skapa ett HTML dokument.
Ett förslag är att använda Bram Stokers [Dracula](https://www.gutenberg.org/files/345/345-h/345-h.htm), den finns på projekt Gutenberg.
Det står dig dock fritt att hitta en annan berättelse eller historia (förutsatt att det inte tar dig mer än 5 minuter).
**Det är inte berättelsen i sig som är viktigt utan att det är en textmängd att arbeta med.**

HTML dokumentet ska finnas i en mapp, ```docs``` och heta ```index.html```.
Inga stilar behövs än så länge.

Element/taggar för text:
```html

<h1>Text</h1>
<h2>Text</h2>
<h3>Text</h3>
<p>Text</p>
<blockquote>Text</blockquote>
<q>Text</q>
<ul>
  <li>List item</li>
</ul>
```

Mer information om [grunden](https://jens-andreasson.gitbook.io/webbutveckling/html/html-start) i ett HTML-dokument finns i länkarna här nedan.
Hela uppgiften finns i [text avsnittet](https://jens-andreasson.gitbook.io/webbutveckling/html/text) med mer utförliga instruktioner.

Slå sedan på GitHub pages i settings och hosta från docs/.

### Mer utförligt

Börja med att välja en text på Projekt Gutenberg att jobba med.
Kopiera sedan texten och spara den till en textfil i detta repo.
Välj sedan ut en del av texten och börja formatera den med HTML.
Arbeta dig igenom textens delar och formattera den allteftersom.
Du behöver inte göra hela texten, men en del.

```html
<!-- skriv html:5 och tabba för grunden -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Alice’s Adventures in Wonderland</title>
</head>
<body>
    <main>
        <header>
            <h1>Alice’s Adventures in Wonderland</h1>
            <h2>by Lewis Carroll</h2>

            <p>THE MILLENNIUM FULCRUM EDITION 3.0</p>

        </header>
        <nav>
            <h3>Contents</h3>
        <!-- För att formatera en textlista, markera den och tryck ctrl+shift+p välj sedan -->
            <!-- emmet wrap ol>li*>a[href="#chapter-$"] -->
            <ol>
                <li>
                    <a href="#chapter-1">CHAPTER I. Down the Rabbit-Hole</a>
                </li>
            </ol>
        </nav>
        <section id="chapter-1">
            <header>
                <h1>CHAPTER I.</h1>
                <h2>Down the Rabbit-Hole</h2>
            </header>
            <p>
            Alice was beginning to get very tired of sitting by her sister on the
            bank, and of having nothing to do: once or twice she had peeped into the
            book her sister was reading, but it had no pictures or conversations in
            it, <q>and what is the use of a book,</q> thought Alice <q>without pictures or
            conversations?</q>
            </p>
        </section>
    </main>
</body>
</html>
```

## Material

* https://jens-andreasson.gitbook.io/webbutveckling/html/html-start
* https://jens-andreasson.gitbook.io/webbutveckling/html/text
* [Gutenberg top 25 downloads](https://www.gutenberg.org/ebooks/search/?sort_order=downloads)
* [Permission/License](https://www.gutenberg.org/policy/permission.html)
* [Public Domain](https://sv.wikipedia.org/wiki/Public_domain) USA, det finns en svensk motsvarighetish, läs mer. 
