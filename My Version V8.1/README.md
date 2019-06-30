# Platine und kap. Einleger V8.1

von einfachuli (ZOE-Aachen)

<pre>
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
!!!! OHNE GEWÄHR, ALLES AUF EIGENE GEFAHR, NUR ZU TESTZWECKEN !!!!
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
</pre>

##  Versionshinweise V8.1
  
  ### - kap. Display nur mit ioref 3V unterstützt ! keine PullDowns R4 und R7 auf dem I2C Bus, da Neue alle ioref haben
  ### - statt Lötbrücke SJ2 für die 5V Stromversorgung kap. Display über ESP USB Anschluss, Kodierbrücke bei Bedarf auf Jumper steckbar.(1)  
  ### - ich verwende Sockelleisten um den ESP und ggf auch das GPS zu sockeln. Sockelleisten sind dabei nur 5,7 mm hoch.
  ### - Das resistive Display wird bei mir direkt auf die Pinabstandsleiste des Displays gelötet und sitzt damit 1,6 mm tiefer im Einleger. 
        Dazu mussen die Lötstellen auf der Platine sauber geschnitten werden.
  ### - ggf. Reset- bzw. Ein-Aus-Schalter, als Unterbrecher vor der 12V+ Klemme.
  ### - resistives Display und Spannungsregler U2 Version OKI-78SR-5/1.5-W36-C ist von der Höhe ungünstig, wenn es in die Zoe Mulde passen soll. Besser ist hier eine niedrigere Bauform, wie z.B. bei Gaptec LMP78_05-1.5 DC/DC-Wandler
  
## Bilder sagen mehr als tausend Worte: https://github.com/einfachuli/ZOE-Display/tree/master/My%20Version%20V8.1/Bilder

## alles Weitere steht in der Bauanleitung Version Platine V8. siehe https://github.com/einfachuli/ZOE-Display/blob/master/Platine%20V8/README.md

## Bezugsquellen zusätzlich verwendete Bauteile:
  - Codierbrücke: https://www.conrad.de/de/p/codierbruecke-cab-pole-2-cab-9-g-r-fischer-elektronik-736318.html
  - niedrige Sockelleisten: https://www.reichelt.de/buchsenleiste-36-polig-vergoldet-2-54-bkl-10120802-p235673.html?
  - U2 Version flach: https://www.conrad.de/de/p/gaptec-lmp78-05-1-5-dc-dc-wandler-print-24-v-dc-5-v-dc-1500-ma-7-5-w-anzahl-ausgaenge-1-x-1603649.html
  - Reset Drucktaster: https://www.conrad.de/de/p/sci-r13-502b-05rt-drucktaster-250-v-ac-1-5-a-1-x-ein-aus-tastend-1-st-701100.html
  - 3D Drucke: https://www.s3dproducts.de/
