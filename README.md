# Apunts_UF2_2

# ENTORNS DE DESENVOLUPAMENT

## Optimització
### Hediondez del Codi
  - També anomenat code smell en anglès.
  - És símptoma en el codi font que indica possiblement un problema més profund.
  - Usualment no són bug de programació (errors): no són tècnicament incorrectes i en realitat no impedeixen que el programa funcioni correctament.
  - Indica deficiències en el disseny que pot alentir el desenvolupament o augmenten el risc d'errors o fallades en el futur.
  - És un motiu important per a realitzar refactorització.
  - Ex:
    Codi duplicat.
    Massa paràmetres.
    Mètode llargs.
    Variables excessivament llargues o curtes.
    Enveja de classes.

### Anàlisi del Codi
  - Tipus:
    - **Anàlisi estàtic** (lint)
    - **Anàlisi dinàmic** (unit tests):

### Anàlisi estàtic:
    - S'utilitzen els "linters".
      Eines que fan la lectura d'el codi font per detectar errors, codi sospitós, etc...
      Ex:  
      - lint: C
      - sonar: Java
      - JSLint, ESLint: Javascript
    - O mitjançant llocs web per a inspecció de codi (Continuous Inspection)

### Refactorització
  - És el procés de reestructurar un codi font, alterant la seva estructura interna sense canviar el seu comportamen extern.
  - Tècniques:
    - Renom de variables
    - Passar codi duplicat a funcions
    - Eliminació de codi inabastable
    - Eliminació de codi redundant
    - Eliminació de codi mort

## Documentació
### Tipus de Documentació
  - Documentació de codi
  - Documentació tècnica
  - Documentació d'usuari

### Formats de Documentació
  - **HTML** (p. ej. Javadoc)  <img src="https://user-images.githubusercontent.com/74070913/110685413-87713c00-81de-11eb-86df-55c36cba99ec.png" alt="HTML-Logo" width="50"/>
  - **Markdown** (p. ej. Gitbook)  <img src="https://user-images.githubusercontent.com/74070913/110685482-9e179300-81de-11eb-9ea8-10792601fe4c.png" alt="Markdown-Logo" width="50"/>
  - **reStructuredText** (p. ej. Readthedocs)  <img src="https://user-images.githubusercontent.com/74070913/110685639-c99a7d80-81de-11eb-86bf-cbd996a83203.png" alt="reStructuredText-Logo" width="50"/>
  - **asciiDoc**  <img src="https://user-images.githubusercontent.com/74070913/110685727-e20a9800-81de-11eb-9ad8-2417bf36e426.png" alt="asciiDoc-Logo" width="50"/>
