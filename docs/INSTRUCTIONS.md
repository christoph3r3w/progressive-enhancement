

# Progressive Enhancement

Ontwerp en bouw een website in lagen

## Context

Deze deeltaak hoort bij sprint 9 "The Web is for Everyone". Dit is een deeltaak die je individueel uitvoert.

In het college _S09W2-02-Progressive-Enhancement wordt behandeld wat Progressive Enhancement is.

Deze deeltaak hoort bij de leertaak:
- [the-web-is-for-everyone-interactive-functionality](https://github.com/fdnd-task/the-web-is-for-everyone-interactive-functionality)



## Doel van deze opdracht

Één van de mooiste [principes](https://www.w3.org/DesignIssues/Principles.html) van het web is dat iedereen met een computer en een browser het web kan gebruiken. [Het web is voor iedereen](https://www.youtube.com/watch?v=UMNFehJIi0E). 

Maar het web is geen gecontroleerde (programmeer) omgeving, je kan er gerust van uit gaan dat niemand precies hetzelfde te zien krijgt als wat jij in je browser ziet. Er zijn technische beperkingen, zoals afmetingen van de browser, type van de browser, versie van de browser, combinatie van browser extensies, grootte van het apparaat, manier van interactie, kwaliteit van de hardware, kwaliteit van het netwerk en er zijn mensen, allemaal verschillende mensen ...

Het doel van deze opdracht is te leren hoe je een website kan ontwerpen en maken met behulp van _Progressive Enhancement_ zodat het voor iedereen toegankelijk is.

### Progressive enhancement
Progressive Enhancement is een _(coding) strategy_ waarmee je er voor kan zorgen dat je website het altijd doet. 

1. Eerst bouw je de _core functionality_ van je website in HTML, zo nodig met server-side rendering. 
De _content layer_. 
Zo zorg je er voor dat je website het in de meest eenvoudige vorm goed doet.
2. Daarna voeg je CSS toe voor feedback voor de gebruiker en om de huisstijl toe te passen.
Dit noemen we de _presentation layer_.
3. Tot slot voeg je met CSS en JS extra enhancements toe om de _User Experience_ te verbeteren. 
Als een browser CSS en/of JS niet ondersteunt valt het terug naar laag 1 of 2, zodat de website altijd werkt.

![image](https://github.com/fdnd-task/progressive-enhancement/assets/1391509/f6d0490b-6748-4fc8-8a63-d33d2f2d0b68)
<br><small>_The skateboard may be a little slower, but it doesn’t stop the user getting to where they want to go. So, if the user’s browser doesn’t support JavaScript or modern CSS then it doesn’t break_ - Andy Bell
</small>



## Werkwijze

Voor deze opdracht ga je een aantal UI componenten ontwerpen, bouwen en testen in verschillende lagen, volgens het principe van _Progressive Enhancement_. 

Fork deze leertaak en ga aan de slag met de [files die klaar staan](https://fdnd-task.github.io/progressive-enhancement/).

Voor elk component staat een HTML-file klaar met een demo video van het eindresultaat. 
In de HTML van elk component staan wat hints en content die je nodig hebt.


### UI componenten

Maak minimaal 3 van onderstaande user interface componenten: 

- [Veelgestelde vragen](https://fdnd-task.github.io/progressive-enhancement/faq.html)
- [Switch control](https://fdnd-task.github.io/progressive-enhancement/switch.html)
- [Mobiel menu](https://fdnd-task.github.io/progressive-enhancement/menu.html)
- [Rating](https://fdnd-task.github.io/progressive-enhancement/rating.html)
- [Favorieten picker](https://fdnd-task.github.io/progressive-enhancement/pickers.html)
- [Carrousel](https://fdnd-task.github.io/progressive-enhancement/carrousel.html)
- [File upload met preview](https://fdnd-task.github.io/progressive-enhancement/file.html)
- [Tabbladen](https://fdnd-task.github.io/progressive-enhancement/tabs.html)


### Aanpak (per component)

1. Beschrijf in eigen woorden wat dit component is, en wat de _core functionaliteit_ is. Gebruik de demo video om een idee te krijgen.
2. Schets het component en de interactie 
3. Laag 1: Onderzoek welke HTML je voor de _core functionaliteit_ nodig hebt, maak hiervan een breakdownschets, en codeer je HTML (gebruik de hints en content in de code die klaarstaat, MDN en CanIUse).
4. Test deze HTML versie op verschillende browsers en devices.
5. Laag 2: Voeg CSS toe, aan de hand van MDN, CanIUse en `@supports`.
6. Test deze “enhanced” versie op verschillende browsers en devices.
7. Laag 3 en verder: Voeg eventueel meer CSS & JS toe, aan de hand van MDN, CanIUse, `@supports` en feature detection.
8. Test deze “enhanced” versie(s) op verschillende browsers en devices.
9. Documenteer je experiment.


### Bronnen bouwfase

* [Can I Use...](https://caniuse.com/)
* [Styling & Customizing File Inputs the Smart Way](https://tympanus.net/codrops/2015/09/15/styling-customizing-file-inputs-smart-way/)
* [It All Starts with a Humble `<textarea>`](https://24ways.org/2019/it-all-starts-with-a-humble-textarea/)
* [Making a Better Custom Select Element](https://24ways.org/2019/making-a-better-custom-select-element/)
* [Progressive Enhancement and Data Visualizations](https://css-tricks.com/progressive-enhancement-data-visualizations/)



## Criteria

Deze opdracht is done als:

- [ ] Je hebt minstens drie interactie componenten uitgewerkt en gedocumenteerd
- [ ] De breakdownschetsen zijn opgenomen in je wiki
- [ ] Bij elke schets staat een korte uitleg van de code
- [ ] Je werk is te bekijken via GitHub Pages