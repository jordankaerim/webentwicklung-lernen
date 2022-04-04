# Einführung in die Web Entwicklung (Frontend)

Bei der Webentwicklung unterscheidet man grob zwischen Frontend und Backend. Das Frontend ist das was man als Benutzer sieht, also die Website von z.B. Airbnb. Das Backend läuft auf einem Server und verarbeitet Anfragen vom Frontend. Wenn also jemand auf Airbnb nach einer Unterkunft sucht, wird die Anfrage von der Website ans Backend geschickt. Das Backend sucht dann in der Datenbank und schickt das Ergebnis zurück ans Frontend im Browser. Es gibt Frontend Entwickler, Backend Entwickler und die, die sowohl am Frontend als auch Backend arbeiten, nennt man Fullstack Entwickler.

Das Frontend besteht im wesentlichen aus drei Sprachen -- HTML, CSS und JavaScript. HTML strukturiert das Webseiten Dokument und legt fest **was** auf einer Webseite **zu sehen** sein soll -- Überschriften, Textparagrafen, Bilder, Buttons, Eingabefelder etc. CSS definiert das **Optische**, d.h. welche Schriftart und Farbe z.B. die Überschrift hat oder ob der Button breit oder schmal ist und seine Farbe ändert wenn man die Maus darüber bewegt etc. JavaScript ist für die Interaktion zuständig. Damit programmiert man **was passieren** soll, wenn z.B. auf einen Button geklickt wird. Z.b. kann man in so einem Fall eine Login-Anfrage an das Backend senden. Es macht Sinn die drei Sprachen (HTML, CSS, JavaScript) in dieser Reihenfolge zu lernen und das geht schneller als man denkt. Der Rest ist dann nur noch Ausprobieren und Experimentieren.

Um mit der Frontend-Entwicklung zu beginnen, benötigt man nur einen Browser wie z.B. Chrome und einen Texteditor um den Code zu schreiben. Zu empfehlen ist dafür VSCode, da er viel Arbeit bei der Programmierung vereinfachen kann und für jedes Betriebssystem erhältlich ist. Der erste Schritt ist also [VSCode](https://code.visualstudio.com/) herunterzuladen und auf Deinem PC zu installieren. Mach dich mit dem Texteditor vertraut. Folge dann dem HTML Kurs auf [freeCodeCamp](https://www.freecodecamp.org/learn/responsive-web-design/basic-html-and-html5/say-hello-to-html-elements) und experimentiere selbst etwas herum. Dafür kannst Du deinen Code in eine `index.html` Datei schreiben und im Browser öffnen. Wichtig ist, dass man jeden Tag ein bischen daran arbeitet und ausprobiert. Die wichtihgsten Grundlagen von HTML erlernt man dann innerhalb von wenigen Tagen/Wochen. Wenn Du Fragen oder Probleme hast, schreib gerne in die Telegramgruppe und teile mit uns Deinen Fortschritt. Sobald Du Dich in einer Aufgabe sicher fühlst, können wir Dir dann für das Weitere Lernen neues Material geben.

## Ein einfaches Webeitendokument zum herumexperimentieren
Du kannst den folgenden Code in ein Textdokument kopieren und als Datei mit dem Name `template.html` auf deinem Computer speichern. Wenn du es in Deinem Browser öffnest siehst Du was passiert. Der untenstehende Code zeigt dir an welchen Stellen man den HTML, CSS und JavaScript Code schreiben kann und wie diese drei Sprachen zusammen arbeiten. Verwende dieses Template um zu lernen und herumzuexperimentieren.
```html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>

  <style>
    /* CSS */
    button {
      color: red;
      font-weight: bold;
    }
  </style>
</head>

<body>

  <!-- HTML -->
  <button onclick="greet()">Klick mich!</button>

  <script>
    /* JavaScript */
    function greet() {
      alert("Salam")
    }
  </script>
</body>

</html>
```

Unten sind noch weitere kostenlose und hilfreiche Quellen aufgelistet die man als Webentwickler zum Nachschlagen kennen sollte:

## Weitere Ressourcen
* [Mozilla HTML Dokumentation](https://developer.mozilla.org/en-US/docs/Learn/HTML)
* [MDN](https://developer.mozilla.org/de/docs/Learn)
* [CSS Tricks](https://css-tricks.com/)
* [CSS Reference](https://cssreference.io/)
* [freeCodeCamp](https://www.freecodecamp.org/learn)
* [CSS Kurs von Google](https://web.dev/learn/css/)
* [Svelte](https://svelte.dev/)
* [Smashing Magazine](https://www.smashingmagazine.com/)
