---
title: "Com fer una applicació? Part 0: Introducció"
date: 2021-11-04T16:29:24+01:00
draft: false
tags:
    - CSharp
    - UnoPlatform
    - WinUI
    - Windows
    - XAML
    - WindowsAppSDK
categories:
    - Programació
    - Tutorials
---

# Com fer una aplicació? Part 0: Introducció 

A l'escola, a la feina, a casa... la tecnologia és a tot arreu i mou el món. Cada dia s'instal·len milers de milions d'aplicacions a milions de mòbils, tablets i ordinadors, fetes per programadors de tot el món que busquen sol·lucionar problemes i respondre a les necessitats dels usuaris mitjançant programari. 

Alguns internautes es preguntaran... com es fa una app? Un sistema operatiu? Com es programa? Aquestes són les preguntes que intentaré ajudar a respondre a qui vulgui seguir aquesta sèrie de tutorials. No són pocs aquells que volen aprendre el que passa darrere la pantalla, pero sovint la poca existència de documentació que no sigui en anglès ho fa difícil. 

**Lector, benvingut al curset d'introducció al desenvolupament d'apps! En català!**

## Què construïrem amb aquest curset?

L'objectiu d'aquestes guies és començar amb conceptes bàsics de programació i acabar fent una app que funcioni a Windows (7, 8, 10 i 11), macOS, Android i iOS alhora sense haver de fer-ne versions específiques. L'aplicació que farem plegats servirà per fer llistes de tasques i gestionar-les, com l'app de Recordatoris a l'iPhone o el Microsoft To-Do. 

Per fer-ho farem ús de la Plataforma Uno, un _SDK_ que permet fer apps per a molts sistemes alhora (i fins i tot fer que funcioni a la web) d'una manera fàcil i senzilla. Durant el transcurs de la guia s'anirà explicant més en profunditat com funciona tot plegat. 

Si aquest darrer paràgraf t'ha semblat que estava escrit en xinès, no t'hi capfiquis. Aqui sota hi ha un petit glossari amb diversos conceptes que cal tenir clars abans de començar a fer res. **T'espero a la part 1 del curset! 😄** Segueix-me al meu Twitter de programació [@martibravo04](https://twitter.com/martibravo04) i sigues el primer en saber quan es publica!


Si tens cap dubte, pregunta o comentari, envia'm un correu a [dev@martibravo.com](mailto:dev@martibravo.com) o deixa'm un missatge privat a la bústia de Twitter. 
****

### **Glossari**

**Sistema operatiu:** Conjunt de programari que controla el funcionament de l'ordinador i del seu maquinari. Són sistemes operatius, per exemple, la família de sistemes Windows, macOS, iOS (el de l'iPhone), Android o Ubuntu.

**Aplicació/Programa**: Seqüència d'instruccions que compleixen una tasca específica, o un conjunt de tasques. N'hi ha de molt bàsiques, com ara la Calculadora fins a algunes tan gegantesques com el Microsoft Office.

**Consola/Terminal** La millor amiga d'un programador. Si has vist qualsevol pel·lícula de hackers, hauràs vist que normalment no utilitzen els ordinadors amb el ratolí, sino que escriuen paraules i l'ordinador les interpreta. Això és una consola de comandaments. Li dones paraules (comandaments) i les interpreta. Si llegeixes això des d'un ordinador, és molt probable que hi puguis accedir tu també. 
- **Windows:** Obre el menú d'Inici, tecleja "cmd" i prem la tecla enter.
- **Mac:** prem ⌘ i la barra d'espai alhora. Et sotirà un quadre de cerca: tecleja "Terminal" i prem enter.

Pots donar-li el teu primer comandament escrivint "exit": es tancarà la terminal. 

**Llenguatge de programació:** El processador, el cervell de tots els ordinadors, funciona amb instruccions molt bàsiques i difícils de llegir per un humà. Per això, existeixen els llenguatges de programació, que són més fàcils de treballar per als humans i són traduibles a instruccions per al processador. Les instruccions escrites en un llenguatge de programació s'anomenen **codi**. 

**Compilar:** Per traduïr el codi a instruccions pel processador, cal compilar-lo: convertir-lo a un format que el processador pugui entendre. Hi ha llenguatges que es compilen al moment d'execució (Just-In-Time) i d'altres que es compilen un cop i se'n distribueix la compilació.

**Debug:** Literalment, "eliminar insectes". Significa executar el codi i veure quins errors té, identificar l'origen dels errors i sol·lucionar-los.

**IDE** Entorn integrat de desenvolupament, de l'anglès _Integrated Development Environment_. És un tipus de programari que serveix per facilitar el desenvolupament de programes, l'edició de codi i fer _debug_.

**Framework:** Un "marc de treball" sobre el qual construïr i distribuïr el nostre programari, que dona les eines necessàries als programadors per a fer més fàcil i eficient l'escritura de codi i el funcionament de l'app. Una applicació pot tenir més d'un framework, i hi ha frameworks que es construeixen dins d'altres frameworks. 

**SDK:** De l'anglès _Software Development Kit_, el Kit de Desenvolupament de Programari és un conjunt d'eines que permeten fer apps per un sistema en concret. macOS, Windows, iOS, Android... cadascun té els seus propis SDKs per ajudar els programadors a fer apps per a la seva plataforma.