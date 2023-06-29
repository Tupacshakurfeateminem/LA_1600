

## Lern-Bericht
Cranberry: Leon Dakaj, Ava Hassani, John Broder

## Einleitung

In unserem Projekt haben wir eine Webseite programmiert, auf der Text ausgegeben wird, wenn man auf ein Logo klickt.
## Was habe ich gelernt?

Wir haben gelernt wie ein Logo beim Daraufklicken einen Text ausgibt.

## Beschreibung

Wir hatten drei Logos und wenn man über eines der drei Logos hovert, sollte es grösser werden. Anschliessend kann man auf das gewünschte Logo klicken, um dann einen Text ausgegeben bekommen. Dieser kann wieder eingeklappt werden, wenn man auf den Text klickt. Dies haben wir in css und HTML programmiert wir mussten viel Geduld haben da uns viele kleine Fehler passierten. Am Ende haben wir es dann doch noch Geschafft. 

![ezgif com-video-to-gif](https://github.com/Tupacshakurfeateminem/LA_1600/assets/111044137/7f4eca12-a619-4fff-acca-64ead8226738)

In diesem Video kann man erkennen, wie unser Programm funktioniert. Beim hovern über den Fussball wird er grösser und wenn man anschliessend darauf klickt, gibt er Text aus, diesen kann man allerdings wieder einklappen wenn man auf den ausgegebenen Text klickt.
```
   <div class="fussballContainer">
      <img class="fussball-logo" src="Fussball-logo.png" tabindex="0" />
      <p class="hidden-text" tabindex="0">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Optio quae iure
        qui. Ipsum quidem alias illo voluptate eligendi et! Quo praesentium
        beatae, et neque veritatis illum tempore pariatur reiciendis recusandae.
      </p>
    </div>
```
  ```.fussball-logo:hover {
  font-weight: 50px;
  border-width: 10px;
  transform: scale(1.1);
}

.fussballContainer {
  display: inline;
}

.fussballContainer .fussball-logo {
  cursor: pointer;
}

.fussballContainer .hidden-text {
  cursor: pointer;
  display: none;
}
```

![image](https://github.com/Tupacshakurfeateminem/LA_1600/assets/111044137/56ac6bd2-0cce-49ab-8fd2-4e9c55d836e9)

Auf dem oben gezeigten Code kann man sehen, wie wir vorgegangen sind. Wir haben zuerst auf HTML ein div Container erstellt, in dem wir das Fussball Logo und den gewünschten Text hatten. Dann haben wir den Hover Effekt programmiert, und zwar wird beim darüber Hovern wird das Logo grösser. Anschliessend haben wir den Text und die Ausgabe des Textes programmiert, dies gelang uns beim hidden Text.
## Verifikation
Der Text ganz oben erklärt den allgemein Vorgang wie wir vorgegangen sind in dem Video kann man das End Resultat sehen und im Code sieht man wie wir das gewünschte umgesetzt haben. 





# Reflexion zum Arbeitsprozess

+In diesem Projekt waren wir uns sehr schnell einig, was wir für eine Webseite machen und wie diese ungefähr aussehen könnte.

-In diesem Projekt waren wir leider sehr unorganisiert manchmal wurden gewisse Aufgaben teilweise erledigt oder gar nicht erledigt.

**VBV**: Nächstes Mal müssen wir unsere Aufgaben frühzeitig und gut lösen.
