
<img width="200" heigth="200" src="https://gitlab.com/mayan-edms/mayan-edms/raw/master/docs/_static/mayan_logo.png">

Nejjednodušší způsob, jak používat Mayam EDMS, je použití oficiálního
[Docker] (https://www.docker.com/) iamge. Docker musí být správně nainstalován
a funguje před pokusem o instalaci Mayam EDMS.

<h2 align="center">Hardware požadavky</h2>

- 2 GB RAM (1 GB pokud je  OCR vyplé).
- vícejádrový procesor (64 bit,  rychlejší než 1 GHz).

<div align="center">
  <a href="http://www.mayan-edms.com">
    
  <br>
  <br>
  <p>

    Mayan EDMS je systém správy dokumentů. Jeho hlavním účelem je skladovat,
    a kategorizovat soubory se silným důrazem na zachování kontextové a obchodní informace o dokumentech. Může 
    označit, podepsat, odesílat a přijímat tyto soubory.
<p>

<p align="center">
    <img src="https://gitlab.com/mayan-edms/mayan-edms/raw/master/docs/_static/overview.gif">
 
</p></div>





odkazy : 
https://docs.docker.com/engine/installation/linux/docker-ce/ubuntu/#install-docker-ce

https://www.mayan-edms.com/

https://github.com/soachishti/autoScanner

https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-16-04#step-4-%E2%80%94-working-with-docker-images

https://oauth.net/2/

## Časový harmonogram
1. nainstalovat a odzkoušet docker 
2. stahnuti autoscanneru, porozumění kodu a oprava
3. učení se Pythonu
4. zjištění jak funguje o2auth a zprovoznění
5. 






## poznamky:
pro "pushnuti" image se musím vytvořit tag image a repository
Z důvodu nefungujici proxy jsem musel změnit apt.conf (nano /etc/apt/apt.conf) a přepsat proxy

kvuli propojení musím zprovoznit o2auth

