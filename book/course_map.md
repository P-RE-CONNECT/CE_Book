(content:inter_curs_grafiek)=
# Interactieve Cursusgrafiek

Op deze pagina kan je de interactieve cursusgrafieken vinden per leerlijn. In deze grafieken kun je:

* **Klikken op een vak** (bijvoorbeeld CM2) om een korte toelichting te zien op de inhoud van dat vak.
* **Klikken op de pijlen** tussen de vakken om te ontdekken welke **voorkennis en vaardigheden** vereist zijn om het volgende vak succesvol te kunnen volgen.

Deze visualisatie is bedoeld om je inzicht te geven in de samenhang tussen de vakken, zodat je bewuster kunt reflecteren op je voorbereiding en studieaanpak. Gebruik dit overzicht als hulpmiddel om eventuele kennislacunes op tijd te signaleren en doelgericht aan te pakken.

## 🏗️ Constructiemechanica leerlijn

Onderstaande interactieve grafiek laat de opbouw zien van de cursusreeks **Constructiemechanica** binnen de bachelor Civiele Techniek. De vakken **CM1**, **CM2** en **CM3** bouwen logisch op elkaar voort en vormen samen een belangrijke leerlijn in het curriculum. 

<script>
  window.addEventListener('message', function(event) {
    if (event.data.type === 'setHeight') {
      const iframe = document.querySelector('iframe[src*="course_graph.html"]');
      if (iframe) {
        iframe.style.height = event.data.height + 'px';
      }
    }
  });
</script>

<iframe src="_static/course_graph.html" width="100%" frameborder="0" scrolling="no"></iframe>