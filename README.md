traccia

Create un nuovo progetto utilizzando Vite: aiutatevi con le slide per ripercorrere i vari passaggi dell'installazione come visti a lezione.
Create e utilizzate un componente AppTitle, il quale contiene un titolo che recita "La mia prima app con Vite!"

Bonus:
Creare un secondo componente AppHero, che visualizza un jumbotron.

Svolgimento:

- Installare Vite
- Inserite nella componente AppTitle all'interno del tag template ciò che deve comparire nel dom
- Andare nella componente App e scrivere "import AppTitle from './components/AppTitle.vue'" nel tag script e sempre nello stesso scrivere: "export default { components: { AppTitle } }"
- Sempre in App inserire all'interno del tag templete un tag chiamato come l'elemento importato (in questo caso AppTitle)

Bonus:

- Nella cartella components creare un file .vue chiamato AppHero
- Al suo interno nel tag template inserire gli elementi che formeranno il jumbotron
- Nel file App.vue scrivere nel tag script "import AppHero from './components/AppHero.vue'" e nell'oggetto della proprietà components inserire AppHero
- Nel file App.vue inserire all'interno del tag templete un tag chiamato AppHero

