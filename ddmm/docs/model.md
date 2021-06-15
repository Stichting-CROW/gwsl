## Informatiemodel

De meeste klassen in dit informatiemodel zijn niet verplicht.

| Sleutelwoord | Betekenis |
|--|--|
| `goedendag` | begin bericht |
| `tot-ziens` | einde bericht |

## Definities 

| CSS-klasse | Betekenis (Engels) | Opmerkingen
|--|--|--|
`.note`                | for informative notes         | (div, p, span, aside, details)
`.example`             | for informative examples      | (div, p, pre, span)
`.issue`               | for issues                    | (div, p, span)
`.advisement`          | for loud normative statements | (div, p, strong)
`.annoying-warning`    | for spec obsoletion notices   | (div, aside, details)
`.correction`          | for "candidate corrections"   | (div, aside, details, section)
`.addition`            | for "candidate additions"     | (div, aside, details, section)
`.correction.proposed` | for "proposed corrections"    | (div, aside, details, section)
`.addition.proposed`   | for "proposed additions"      | (div, aside, details, section)

<div class='def'>

Definitie: een <dfn>informatiemodel</dfn> maakt een representatie van de werkelijkheid die eenvoudig(er) door een systeem te verwerken is.

</div>

## Uitgangspunten

Uitgangspunt is het hanteren van de NEN2660; hierbij is gekozen voor een aantal elementen om de ontologie uit op te bouwen:

| NEN2660 | GWSL | |
|--|--|--|
| DiscreteObject | FysiekObject | Zichtbare objecten in het licht areaal |
| SpatialRegion | RuimtelijkObject | Ruimtes in het licht areaal, bijvoorbeeld gebieden |
| Interaction | Interactie | Activiteit uitgevoerd door fysieke objecten |
| Connection | VerbindingsObject | Manier waarop de activiteit uitgevoerd wordt |
| State | Toestand | Toestand van het fysieke object - dit kan zowel organisatorisch als fysiek zijn |
| Event | Gebeurtenis | Gebeurtenis welke een toestandsverandering (begin of einde) triggert |



