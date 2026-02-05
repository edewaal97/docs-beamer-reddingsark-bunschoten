Video's downloaden van YouTube
==============================

Als er gevraagd wordt om video’s van YouTube af te spelen dan kan dit. Het staat echter een stuk netter om de video voorafgaand te downloaden. Daarnaast is er dan geen afhankelijkheid meer van de internetverbinding tijdens de dienst waardoor de video zou kunnen gaan haperen.

Voor het downloaden is de link van de YouTubevideo belangrijk. Neem bijvoorbeeld de video van de `Remix van het nummer Adembenemend van Marcel en Lydia Zimmer <https://www.youtube.com/watch?v=DaLolaYmX6g>`__. Kopieer de link boven uit de adresbalk: ``https://www.youtube.com/watch?v=DaLolaYmX6g``.

.. Danger::
  **Download geen afspeellijsten, alleen losse video's!**
  
  Als je een YouTube link ontvangt en deze plakt, zal deze starten met ``https://youtube.com/watch?=``. Daarna volgen 11 karakters met het video-ID. Als in de URL na het video-ID ``&list=`` staat, betekent dit dat de URL onderdeel is van een afspeellijst. Om alleen de video te downloaden, verwijder je alles uit de link na het video-ID. Alles wat volgt na het video-ID is informatie die niet belangrijk is. Dit kan je veilig verwijderen voordat je de link plakt in de downloadsoftware.

  * Goed: ``https://www.youtube.com/watch?v=RRFgtwQP8Qk``
  * Fout: ``https://www.youtube.com/watch?v=RRFgtwQP8Qk&list=RDRRFgtwQP8Qk&start_radio=1``

  Dit kan je ook zien als je de link opent in de webbrowser. Je ziet dan naast de play-knop een knop voor het volgende en vorige nummer. Aan de rechterkant, of direct onder de video staat de afspeellijst in een apart kader.
  
  .. image:: /images/youtube-video-in-playlist.png

Op de beamerlaptop staan twee applicaties om de video te downloaden. “Open Video Downloader” en “Stacher7”. Beide applicaties staan in het startmenu.

.. Tip::
  Kies in de meeste gevallen de hoogste kwaliteit. Het heeft echter geen zin om een video te downloaden met een kwaliteit hoger dan 1080p, dit neemt alleen maar onnodig ruimte in beslag. Als er dus een hogere kwaliteit beschikbaar is, kies dan voor 1080p.

Open Video Downloader
---------------------

.. image:: /images/open-video-downloader.png

Plak de link in de balk (1) en klik op de :guilabel:`+` (2).

De applicatie haalt op de achtergrond de informatie op waarna dit wordt weergegeven in de :guilabel:`queue`. Hier kan eventueel een keuze gemaakt worden naar het downloaden van de audio+video, of alleen de audio. Ook kan de kwaliteit geselecteerd worden. Klik op :guilabel:`Download` (3) om het downloadproces te starten.

Na het downloaden staat de video in de map ``D:\filmpjes`` (door windows weergegeven als ``Video's``).

`Downloadlocatie StefanLobbenmeier Open Video Downloader <https://github.com/StefanLobbenmeier/youtube-dl-gui/releases/latest>`_

.. Tip::
  Soms is het nodig om ook de ondertiteling te downloaden. Volg hiervoor de stappen onder de volgende afbeelding.
  
  .. image:: /images/open-video-downloader-subtitles.png

  Klik na het toevoegen van de video, maar voor het downloaden op het icoontje voor subtitles (1). Vink het vakje :guilabel:`Download subtitles` aan (2) en selecteer de gewenste subtitles (3). Klik op :guilabel:`Ok` (4) en vervolgens op :guilabel:`download`` (5).

  Naast het videobestand, worden de subtitles opgeslagen in een ``.vtt``-bestand. Zorg dat de naam van de video en de naam van het ondertitelingsbestand niet wijzigen en zorg dat beide bestanden in dezelfde map staan. VLC zal dan de ondertiteling automatisch oppakken bij het afspelen van de video. **Test of de ondertiteling werkt in VLC voorafgaand aan de dienst!**

Stacher7
--------

.. image:: /images/stacher7.png

Dit programma controleert na opstarten of alle componenten up-to-date zijn. Hierdoor kan het lijken alsof het programma vastloopt. Wacht dit even geduldig af. Als alles bijgewerkt is, staat rechtsboven in het scherm een klein een groen vinkje.

Plak de URL in het tekstvak (1) en klik op de downloadknop (2).

Na het downloaden staat de video in de map ``D:\filmpjes`` (door windows weergegeven als ``Video's``).

`Downloadlocatie Stacher7 <https://stacher.io/>`_