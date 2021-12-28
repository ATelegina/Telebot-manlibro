# Telebot: manlibro
Ĉu vi volas krei propran telegraman roboton? Ĉi tiu kitabo helpos al vi!
Esperanta komputila vortaro: https://komputeko.net/

## Enhavo

  * [Antaŭparolo](#antaŭparolo)
    * [Kiel uzi ĉi tiun manlibron: du manieroj](#kieluzilibron)
    * [Kion povas kaj ne povas robotoj en Telegram ](#povo)
  * [0. Instali ilojn](#instaliilojn)
    * [Windows](#windows)
      * [Varianto 1: Anaconda](#anaconda)
      * [Varianto 2: Sublime Text](#sublime)
    * [Linux](#linux)
    * [Mac OS](#macos)
  * [1. Lernu Python-on!](#lernu-python-on-)
    * [Variabloj, print kaj input](#variabloj-print-kaj-input)
    * [Kalkulado](#kalkulado)
    * [Laboro kun alinioj](#alinioj)
    * [if kaj while](#if)
    * [Ciclo "for" kaj laboro kun listoj kaj vortaroj](#for)
    * [Funkcioj kaj esceptoj](#)
  * [2. Lernu telebot-on!](#lernutelebot)
    * [Kiel konektiĝi al via roboto](#konekto)
    * [Mesaĝaj traktiloj](#traktiloj)    
    * [Agoj](#agoj)
    * [Klavaro](#klavaro)
    * [Inline mode](#inlinemode)
  * [3. Pretaj kodaĵoj](#pretakodo)
    * [Roboto-papago](#papago)
    * [Diru version](#versio)
    * [Plusendi mesaĝojn en alia grupo](#anonimaroboto)
    * [Bonvena mesaĝo](#bonvenon)
    * [Iu forlasis la grupon](#forlasis)
    * [Kiel sendi longajn mesaĝojn](#longajmesaĝoj)
  * [4. Kiel subteni roboton](#kielsubteni)
    * [Kiel subteni roboton dum 27 horoj ĉiutage?](#24)
    * [Kion kaj kiel vi devas kaŝi...](#sekreto)
  * [Postparolo](#postparolo)

## 1. Lernu Python-on!

En ĉi tiu bloko vi ekscios pri bazaj operacioj en la plej ~pigriga~ facila programlingvo!
Kodo de ĉi tiu ĉapitro vi provas testi ĉi tie: https://www.programiz.com/python-programming/online-compiler/
(por lanĉi kodon, premu sur Run aŭ faru Ctrl+Enter (por Windows))

### Variabloj, print kaj input

Por testi, ĉu via interpretilo funkcias aŭ ne, lanĉu supran kodon:
```
print("Saluton, mondo!")
```
Nun rigardu konzolon. 
```
Saluton, mondo!
```
Se vi havas ĉi tiun rezulton, gratulon! Estas via unua programeto.

Funkcio print() montras tekston, kiun vi skribis en ĝi. 
```
print("Obeu min, stulta homo!") # Montras: Obeu min, stulta homo!
```
```#``` estas signo por komentoj. Ĉion, kio troviĝas post ĉi tiu signo, komputilo ne rigardas (escepte se ```#``` troviĝas inter citiloj):
```
print("Saluton!(1)")
#print("Saluton!(2)")
print("#Saluton!(3)")
```
Rezulto:
```
Saluton!(1)
#Saluton!(3)
```
