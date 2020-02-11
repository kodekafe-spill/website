# Website (DEVELOPMENT)


[![Netlify Status](https://api.netlify.com/api/v1/badges/63bc5198-1b67-4dfe-b36b-22621469c564/deploy-status)](https://app.netlify.com/sites/boring-torvalds-37103a/deploys)

Development website!

## Development

Vi skal ha flere branches, dette er hvordan de skal funke:

[![Branch info](https://i.pinimg.com/originals/d6/06/ac/d606ac0eca71d6ead76c73d7aa08d51b.png)]()

`Master` skal være den som vises på nettsiden sitt root domain, (foreløpig er det [http://kodekafe.tk](http://kodekafe.tk)

`Hotfix`: Disse er for hotfixes. De skal bruke formatet `hotfix-<name på hotfix>`. Lag en ny branch pr. hotfix, og snakk før du merger.

`Release`: Brukes som et slags staging area for å gjøre ferdig changes. Når en versjon gjøres klar, skal ingen flere features merges inn

`Dev`: Alle merges og pushes for nye funksjoner skal hit.

`Feature`: Her skal nye funksjoner lages. Lages i formatet `feature-<feature name>`
