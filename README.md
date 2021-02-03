# Restrizioni regionali COVID-19

Con il [DPCM del 3 novembre 2020](http://www.governo.it/it/articolo/dpcm-del-3-novembre-le-misure-suddivise-aree-di-criticit/15628) su tutto il territorio italiano sono state introdotte misure di contenimento suddivise per aree di criticità. 
Il diverso livello di rischio (o più informalmente il "colore") associato ad ogni regione e provincia autonoma è disponibile nel 
[repository della Protezione Civile](https://github.com/pcm-dpc/COVID-19), ma è rappresentato in un formato di difficile elaborazione [[#1012](https://github.com/pcm-dpc/COVID-19/issues/1012), [#1038](https://github.com/pcm-dpc/COVID-19/issues/1038), [#1045](https://github.com/pcm-dpc/COVID-19/issues/1045)].
Con l'obiettivo di facilitare l'accesso a tali informazioni questo repository le ripropone nei formati *csv* e *json*. 

Il dataset è aggiornato con periodicità giornaliera ed è basato su una rielaborazione delle informazioni pubblicate dalla Protezione Civile. 
Sto documentando la metodologia utilizzata, a breve la renderò pubblica.

| Nome Campo                | Descrizione                      | Formato                                        | Esempio    |
|---------------------------|----------------------------------|------------------------------------------------|------------|
| data                      | Data dell'informazione           | YYYY-MM-DD                                     | 2020-12-20 |
| denominazione_regione     | Denominazione della regione      | stringa                                        | Abruzzo    |
| colore                    | Livello di rischio della regione | 'rosso' \| 'arancione' \| 'giallo' \| 'bianco' | rosso      |

---

### English version

In Italy, the [DPCM of 3 November 2020](http://www.governo.it/it/articolo/dpcm-del-3-novembre-le-misure-suddivise-aree-di-criticit/15628) 
introduced containment measures divided into critical areas. 
The different level of risk (or more informally the "colour") associated to each region and autonomous province is available in the 
[Protezione Civile repository](https://github.com/pcm-dpc/COVID-19), but it is represented in a format that is difficult to process [[#1012](https://github.com/pcm-dpc/COVID-19/issues/1012), [#1038](https://github.com/pcm-dpc/COVID-19/issues/1038), [#1045](https://github.com/pcm-dpc/COVID-19/issues/1045)].
With the aim of facilitating access to this information, this repository makes it available in *csv* and *json* formats.

The dataset is updated on a daily basis and it's based on a reprocessing of the information published by the Protezione Civile. 
I am documenting the methodology used and I will soon make it public.

| Field name                | Description                      | Format                                         | Example    |
|---------------------------|----------------------------------|------------------------------------------------|------------|
| data                      | Date of notification             | YYYY-MM-DD                                     | 2020-12-20 |
| denominazione_regione     | Name of the Region               | string                                         | Abruzzo    |
| colore                    | Level of risk of the region      | 'rosso' \| 'arancione' \| 'giallo' \| 'bianco' | rosso      |
