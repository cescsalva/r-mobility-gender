
## Mobilitat interregional i gènere a Espanya

---

### 1 Descripció curta

**Anàlisi de la mobilitat interregional a Espanya amb perspectiva de gènere.**

---

### 2 Resum del projecte

Aquest projecte analitza les decisions de mobilitat interregional a Espanya amb perspectiva de gènere, utilitzant dades de l’**Enquesta d’Actituds i Expectatives de Mobilitat Espacial de la Població Activa** (Vidal & Busqueta, 2020, N = 3.889), recollida el 2019 entre població de 18 a 55 anys que treballava o buscava feina.

L’objectiu és identificar els factors que afavoreixen o limiten la mobilitat segons el gènere i explorar els obstacles percebuts que condicionen la presa de decisions.

**Objectius principals:**
- Identificar els factors que afavoreixen o limiten la mobilitat segons el gènere.
- Explorar els obstacles percebuts que condicionen la presa de decisions.

El treball s’articula al voltant de tres preguntes principals:

**Preguntes d’investigació:**
1. Els factors implicats en les decisions de mobilitat tenen efectes diferents per a homes i dones?  
2. Quins són els principals obstacles auto percebuts per a la mobilitat segons el gènere?  
3. Com s’associa la percepció d’obstacles amb les característiques sociodemogràfiques i les decisions de mobilitat o immobilitat?

El codi d’aquest repositori mostra tot el procés: **depuració i transformació de dades**, **anàlisi descriptiva** i **modelització estadística** mitjançant regressions logístiques multinomials diferenciades per sexe, amb càlcul i interpretació de **mitjanes dels efectes marginals**.

Els resultats indiquen que, mentre els factors econòmics i laborals incideixen de manera similar en homes i dones, els vincles familiars són especialment decisius per a les dones. La convivència en parella redueix la seva disposició a migrar, mentre que percebre oportunitats de millora en l’àmbit familiar la potencia. A més, les dones reporten amb més freqüència obstacles relacionats amb la xarxa familiar, mentre que els homes tendeixen a destacar restriccions laborals o financeres.

En conjunt, el projecte evidencia que per entendre la mobilitat interregional a Espanya no n’hi ha prou amb considerar els factors econòmics: cal incorporar també el paper central de la família i les dinàmiques de gènere en la configuració de les decisions de mobilitat i immobilitat.

**Resultats generals:**
- Els factors econòmics i laborals afecten homes i dones de manera similar.
- Els vincles familiars són determinants per a les dones.
- Cohabitar amb la parella redueix la predisposició a migrar de les dones.
- Obstacles familiars són percebuts més freqüentment per dones; obstacles laborals/financers més per homes.

---

### 3 Dades utilitzades

- **Font:** Enquesta Vidal & Busqueta, 2020  
- **Mida de mostra:** N = 3.889  
- **Població:** 18–55 anys, residents a Espanya, treballant o buscant feina  
- **Any de recollida:** 2019  
- Inclou preguntes sobre decisions de mobilitat, obstacles percebuts i característiques sociodemogràfiques.

---

### 4 Estructura del repositori

- **data/** → fitxers de dades (reals o simulats)  
- **scripts/** → scripts R per a depuració, anàlisi descriptiva i modelització  
- **output/** → resultats, gràfics, fitxers HTML  
- **README.md** → aquest document

---

### 5 Guia d'ús

- Obrir l’arxiu `.Rmd` amb **RStudio** i fer **Knit** per generar HTML o PDF.  
- R ≥ 4.2 amb paquets: `tidyverse`, `dplyr`, `ggplot2`, `margins`, `nnet` (i altres segons el codi).

---

### 6 Principals resultats



---

### 7 Llicència i crèdits

- **Codi:** MIT License  
- **Dades:** Vidal & Busqueta, 2020  
- Referències incloses dins del projecte

---

## 7 Llicència i crèdits

