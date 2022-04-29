Overschakelen naar video
========================

Klik op het pionnetje in de taakbalk. Deze knop opent “VLC Player” met vooraf ingestelde opties (als er een update is mag je deze negeren).

.. image:: /images/taakbalk-vlc.png

Klik achtereenvolgens op :guilabel:`Media` en :guilabel:`bestand openen` en selecteer vervolgens het videobestand wat met de stappen eerder in de handleiding is gedownload.

.. image:: /images/vlc-bestand-openen.png

.. TIP::
  Je kunt ook het videobestand uit een map in het venster slepen, wellicht is dat sneller.

Als er meerdere video’s zijn, herhaal dan deze stappen totdat alle video’s in de lijst staan. Je kunt de lijst op eigen volgorde sorteren door video’s omhoog of omlaag te slepen.

Om de video af te spelen dubbelklik je op de titel. De video start op het beamerscherm. De besturingsknoppen blijven zichtbaar op het laptopscherm. Als de video is afgelopen stopt de speler automatisch. Om de volgende video af te spelen, dubbelklik op de titel van de volgende video.

Om de video vroegtijdig te stoppen, klik op het stopicoontje (vierkantje) onderin de balk, hiermee verdwijnt de video van het tweede scherm.
 
.. WARNING::
  Bij pauzeren blijft de video gepauzeerd op het tweede scherm staan.

.. image:: /images/vlc-video-besturing.png

.. TIP::
  - Als er geluid nodig is, geef dit dan tijdig door zodat het aangesloten kan worden. Waarschijnlijk vraagt de geluidsman voor de dienst of het geluid even getest kan worden. Start hiervoor het filmpje even en stop als aangegeven wordt dat de test geslaagd is.
  - Zorg dat het geluid van de laptop en van VLC op 100% staat, dit is voor het geluidsteam het makkelijkst.

Geavanceerd:
------------

Code voor achter het doel van de snelkoppling om automatisch op het tweede scherm te starten:

.. code-block:: console

   --video-x=1921 --video-y=1 --no-video-title-show --fullscreen --no-embedded-video --play-and-stop --width=1280 --height=720 --no-mouse-events --no-qt-fs-controller --no-osd --key-leave-fullscreen=