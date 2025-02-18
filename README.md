[//]: # (# enya-catalana)
<p align="center">
 <a href="https://github.com/eloicase/enya-catalana" target="_blank">
        <img alt="banner" src="./assets/banner.png" width="100%"></a>
</p>

[**Abstract**](#Abstract)
| [**Historial**](https://github.com/eloicase/enya-catalana#Historial) 
| [**Introducció**](#Introducció)
| [**Instal·lació**](#Instal·lació)
| [**Programari**](https://github.com/eloicase/enya-catalana#Programari)
| [**Maquinari**](https://github.com/eloicase/enya-catalana#Maquinari)
| [**Contacte**](https://github.com/eloicase/enya-catalana#Contacte)
| [**Agraïments**](https://github.com/eloicase/enya-catalana#Agraïments)


---
<a name="Highligts"></a>
## Abstract
El projecte **Enya Catalana** vol ser un repositori per centralitzar tots els recursos per customitzar els teclats QWERTY llatí castellà sustituïnt la lletra Ñ pel dígraf NY.



<a name="Historial"></a>
## What's New 🔥
- 2025/02: Primera versió del repositori amb versions per MacOS i Ubuntu Linux/Debian.

<a name="Introduction"></a>
## Introducció

_<p style="text-align: center;"></p>"     El senyor i la senyora Campmany dels Hostalets de Balenyà feia anys que anyoraven un bany a l'estany de la muntanya ja que tenien una cabanya feta de llenya amb vinyes i senyalitzada per un senyal amb una pinya amb pinyons i el text 'Seny i rauxa', dissenyat a gran tamany i que van comprar enganyats, tot i que era un bunyol i va costar un ronyó."</p>_


Els catalanoparlants i "catalanoescribents" ens hem acostumat a utilitzar "de facto" el teclat en castellà que inclou una lletra que MAI farem servir: la **ñ**.
En canvi, en català, la enya (ny) sempre ha estat a l'ombra de la ce trencada i de la ela geminada com a lletres insignes del català, tot i que es facin servir molt menys que la enya. Desde aqui es vol reinvindicar la enya catalana fins i tot en els nostres teclats.

En els dispositius actuals hi ha diferents alternatives per utilitzar diferents configuracions de teclat, ja que els sistemes més utilitzats (Mac, Linux, Windows) permeten canviar facilment de teclat a altres idiomes. Però malauradament no tenim una configuració de teclat ISO ni ANSI plenament en català. 
Una solució seria fer servir, per exemple, la configuració de teclat en anglès, però apart de que ens hem d'apendre de nou la ubicació de molts simbols i signes de puntuació, es perd la **ç** i el punt volat. La configuració de teclat portuguès té la **ç** enlloc de la **ñ** pero continuem perdent el punt volat de la el·la geminada.

Aixó, més que solucions, son pedaços a mitges i malauradament estem acostumats a saber on estan les tecles dels signes de puntuació, accents i altres simbols de sobre els números en el teclat en castellà.

Es per això que aquest repositori vol ser una solució que aglutini els recursos per posar remei als seguents punts:

- Utilitzar el teclat plenament en català.
- Desfer-se de la lletra **ñ** del teclat i utititzar el grafisme propi del català: **ny**.
- Que la resta de tecles del teclat funcionin com estem acostumats.


Per arreglar la situació s'ha d'afrontar el problema desde el punt de vista de programari i del maquinari.

<a name="Instal·lació"></a>
## Instal·lació

### Programari
Es proposa utilitzar una configuració de teclat customitzat que al premer la tecla **Ñ** el teclat generi directament **NY**.

### Maquinari
Substituïr la tecla en questió per una que mostri el que realment escriu un cop feta la modificació del programari (aplicable basicament a teclats mecànics).
En cas que no sigui factible substituir facilment la tecla es proposa com a pla B generar adhesius en forma de tecla que es pugui posar a sobre de la **Ñ**.


<a name="Programari"></a>
## Programari

### Entorn MacOS

- Descarregar el repositori

``` sh
git clone https://github.com/eloicase/enya-catalana.git

```

- Fer doble click en el teclat customitzat triat per instal·lar
``` sh
~/Users/username/enya-catalana/MacOS/Catalan-senyera

```

- o copiarlo manualment a
``` sh
~/Users/username/Library/Keyboard Layouts
```

- Activar el teclat desde
``` sh
Preferències del Sistema -> Teclat -> Dispositius d'entrada
```

Un cop activat ja es podrà fer servir desde el menú teclats de la barra superior.

### Entorn Linux Ubuntu/Debian

El procés és un xic més complicat però si es segueixen els passos és facil de seguir.

### Entorn Windows

> [!Note]
> Actualment no es té accés a una maquina windows i s'enten que hi ha d'haver una sol·lució similar per poder activar configuracions de teclat customitzades. Aquest repositori queda obert a la comunitat per afegir la versió Windows del teclat customitzat que generi NY enlloc de Ñ.

### Entorn iOS

El teclat dels iPhones i iPads és configurable en català, tot i que no es pot configurar facilment els teclats perque es generi el digraf 'ny'. 

### Entorn Android

> [!Note]
> Al igual que en Windows, no es té access a un dispositiu Android per provar. s'enten que tindrà un funcionament similar a iOS en quan als teclats.

