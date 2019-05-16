---
title: Tecnologia
type: docs
---

# Tecnologia
Questo che avete davanti **non è un nuovo libro di tecnologia** per la scuola media: ce ne sono già tanti! Vuole invece essere uno strumento didattico utile e versatile, una specie di *coltellino svizzero* da cui attingere argomenti, metodologie, approfondimenti, tutto ciò di cui potremmo aver bisogno per progettare la nostra lezione. Vogliamo affrontare difficoltà e proporre modalità che hanno avuto successo in base alla nostra esperienza di docenti.

## Suggerimenti
Ciascuno prenda il capitolo che preferisce e scriva direttamente in questo [pad condiviso](https://mensuel.framapad.org/p/tecnologia) e sostituisca l'etichetta **Chi ci vuole provare** con il proprio nome. Riportiamo quindi, in maniera pratica:

- come presento l'argomento ai ragazzi
- quali metodologie adotto
- un riferimento al materiale da utilizzare
- etc...

Volendo, chiunque può modificare anche direttamente questo sito cliccando l'apposito link presente in calce. Le pagine di cui è composto e l'indice per la navigazione si creano automaticamente partendo da **semplici file di testo**, con estensione .md anzichè .txt, ospitati sul cloud storage del mio account [Github](https://github.com/). Ad ogni capitolo corrisponde una cartella al cui interno si potrebbero inserire più pagine, una per ogni attività descritta.
Se sei collaboratore puoi creare file e cartelle proprio come avviene con Drive di Google, basta chiedermelo... prima però devi aver creato un account su github, è gratuito.

**STRUTTURA TIPO**

- Argomento trattato:
- Attività manuale:
- Attività a PC:
- Prodotto finale:

[Clicca qui](https://github.com/omartek/tecnologiadiclasse/tree/master/content/docs) per vedere la struttura delle cartelle del sito.

# Guida rapida al Markdown

Il **Markdown** è un linguaggio mark-up concettualmente simile all'HTML. Attraverso l'utilizzo di simboli marcatori, quali # (hashtag) o * (asterisco), si realizzano titoli, vocaboli in grassetto o corsivo, tebelle etc...

Una frase scritta in questo modo:

    Questa frase verrà visualizzata **in parte in grassetto** ed *in parte in corsivo*

verrà visualizzata così:

Questa frase verrà visualizzata **in parte in grassetto** ed in parte in *corsivo*.

In questo modo è più semplice sia scrivere che leggere testi all'interno delle pagine web, che diversamente sarebbero frammentati in mezzo ad una gran quantità <...> </...> tipici del codice HTML. In seguito, la pagina scritta in Markdown, viene tradotta automaticamente in codice HTML da un software intermediario.

Questo **bigino** fornisce una rapida panoramica di tutti gli elementi di sintassi di Markdown. Non può coprire ogni caso possibile, quindi se hai bisogno di maggiori informazioni, consulta le guide di riferimento per [sintassi di base] (https://www.markdownguide.org/basic-syntax) e [sintassi avanzata] (/ sintassi estesa).

## Sintassi di base

Questi sono gli elementi delineati nel documento di design originale di John Gruber. Tutte le applicazioni Markdown supportano questi elementi.

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Elemento</th>
      <th>Sintassi Markdown</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://www.markdownguide.org/basic-syntax/#headings">Titoli</a></td>
      <td><code># H1<br>
          ## H2<br>
          ### H3</code></td>
    </tr>
    <tr>
      <td><a href="https://www.markdownguide.org/basic-syntax/#bold">Grassetto</a></td>
      <td><code>**bold text**</code></td>
    </tr>
    <tr>
      <td><a href="https://www.markdownguide.org/basic-syntax/#italic">Corsivo</a></td>
      <td><code>*italicized text*</code></td>
    </tr>
    <tr>
      <td><a href="https://www.markdownguide.org/basic-syntax/#blockquotes-1">Citazione</a></td>
      <td><code>> blockquote</code></td>
    </tr>
    <tr>
      <td><a href="https://www.markdownguide.org/basic-syntax/#ordered-lists">Elenco numerato</a></td>
      <td><code>
        1. First item<br>
        2. Second item<br>
        3. Third item<br>
      </code></td>
    </tr>
    <tr>
      <td><a href="https://www.markdownguide.org/basic-syntax/#unordered-lists">Elenco puntato</a></td>
      <td>
        <code>
          - First item<br>
          - Second item<br>
          - Third item<br>
        </code>
      </td>
    </tr>
    <tr>
      <td><a href="https://www.markdownguide.org/basic-syntax/#code">Codice</a></td>
      <td><code>`code`</code></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#horizontal-rules">Linea orizzontale</a></td>
      <td><code>---</code></td>
    </tr>
    <tr>
      <td><a href="https://www.markdownguide.org/basic-syntax/#horizontal-rules">Link</a></td>
      <td><code>[title](https://www.example.com)</code></td>
    </tr>
    <tr>
      <td><a href="https://www.markdownguide.org/basic-syntax/#images-1">Immagine</a></td>
      <td><code>![alt text](image.jpg)</code></td>
    </tr>
  </tbody>
</table>

## Sintassi extra

Questi elementi estendono la sintassi di base aggiungendo funzionalità aggiuntive. Non tutte le applicazioni Markdown supportano questi elementi.

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Elemento</th>
      <th>Sintassi Markdown</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://www.markdownguide.org/extended-syntax/#tables">Tabella</a></td>
      <td><code>
          | Syntax      | Description |<br>
          | ----------- | ----------- |<br>
          | Header      | Title       |<br>
          | Paragraph   | Text        |
      </code></td>
    </tr>
    <tr>
      <td><a href="https://www.markdownguide.org/extended-syntax/#fenced-code-blocks">Fenced Code Block</a></td>
      <td><code>```<br>
      {<br>
      &nbsp;&nbsp;"firstName": "John",<br>
      &nbsp;&nbsp;"lastName": "Smith",<br>
      &nbsp;&nbsp;"age": 25<br>
      }<br>
      ```
      </code></td>
    </tr>
    <tr>
      <td><a href="https://www.markdownguide.org/extended-syntax/#footnotes">Note</a></td>
      <td><code>
        Here's a sentence with a footnote. [^1]<br><br>

        [^1]: This is the footnote.
      </code></td>
    </tr>
    <tr>
      <td><a href="https://www.markdownguide.org/extended-syntax/#heading-ids">Heading ID</a></td>
      <td><code>### My Great Heading {#custom-id}</code></td>
    </tr>
    <tr>
      <td><a href="https://www.markdownguide.org/extended-syntax/#definition-lists">Definizioni</a></td>
      <td><code>
        term<br>
        : definition
      </code></td>
    </tr>
    <tr>
      <td><a href="https://www.markdownguide.org/extended-syntax/#strikethrough">Barrato</a></td>
      <td><code>~~The world is flat.~~</code></td>
    </tr>
    <tr>
      <td><a href="https://www.markdownguide.org/extended-syntax/#task-lists">Lista attività</a></td>
      <td><code>
        - [x] Write the press release<br>
        - [ ] Update the website<br>
        - [ ] Contact the media
      </code></td>
    </tr>
  </tbody>
</table>

Buon lavoro!
