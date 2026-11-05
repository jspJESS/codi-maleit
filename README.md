# 🎃 El Codi Maleit - Investigació a la Casa dels Ecos

Són les 23.59 h de la nit de Halloween i la web de la Casa dels Ecos ha deixat de funcionar correctament. Algú ha deixat un rastre de pistes i canvis sospitosos al repositori que cal investigar urgentment.

## 🎯 Descripció i Objectius del Projecte
Aquest projecte consisteix en una pràctica de simulació d'incidències i control de versions orientada a l'aprenentatge de Git. Els objectius principals són:
* Clonar un repositori de GitHub i gestionar eficaçment les branques de treball.
* Consultar l'historial de commits per recuperar informació o fitxers modificats/esborrats.
* Investigar el codi font a la cerca de pistes ocultes.
* Desenvolupar una branca pròpia per documentar i deixar constància de la resolució del misteri.

## 💻 Tecnologies Utilitzades
* **Control de versions:** Git i GitHub.
* **Entorn de desenvolupament:** Visual Studio Code.
* **Llenguatges base:** HTML5 i CSS3 per a l'estructura i estils de la web.

## 🚀 Instruccions de Clonació i Obertura
Per descarregar el repositori a la teva màquina local i començar a investigar amb Visual Studio Code, executa les següents comandes a la terminal:

1. Clona el repositori oficial al teu ordinador:
   `git clone https://github.com/jspJESS/codi-maleit.git`

2. Entra a la carpeta del projecte:
   `cd codi-maleit`

3. Obre l'entorn de treball:
   `code .`

## 📂 Estructura de Fitxers i Carpetes
* `index.html`: Fitxer principal de la web que conté la estructura visible i missatges ocults als comentaris.
* `style.css`: Full d'estils per a la interfície visual.
* `README.md`: Documentació oficial del projecte i guia d'investigació.
* `pistes/`: Directori que conté fitxers addicionals amb notes i registres per analitzar.

## 🛠️ Aprenentatges i Pràctica de Git
Durant el desenvolupament d'aquesta pràctica s'han posat en pràctica les següents operacions essencials de Git:
* **Clonatge i navegació:** Ús de `git clone` per baixar el projecte i `git branch -a` / `git checkout` per explorar les diferents branques d'investigació.
* **Anàlisi d'historial:** Utilització de `git log --oneline` per revisar la línia temporal de canvis i `git show <HASH>` per inspeccionar el contingut de commits concrets.
* **Registre de solucions:** Creació de branques pròpies (`solucio-final`) i generació de commits de manera segura sense alterar la branca principal (`main`).