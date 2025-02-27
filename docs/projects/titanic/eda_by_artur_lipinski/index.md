
# Titanic: Co Mówią Dane?

Zapraszamy do odkrycia fascynującej analizy danych z legendarnego Titanica, przygotowanej przez Artura. W projekcie znajdziesz szczegółowe spojrzenie na poszczególne zmienne i ich wpływ na losy pasażerów, co pozwala lepiej zrozumieć tę historyczną katastrofę. Dzięki rzetelnemu podejściu do analizy oraz fenomenalnemu podsumowaniu wyników, projekt ten stanowi wartościowe źródło wiedzy. Dodatkowo, przepiękne wizualizacje danych sprawiają, że odkrywanie tajemnic Titanica staje się nie tylko pouczające, ale i wizualnie atrakcyjne.

**Autor**: [Artur Lipiński](/od-zera-do-ai-portfolio/uczestnicy/artur_lipinski)

<a href="titanic.ipynb" class="md-button md-button--primary">Pobierz Notebook</a>

<iframe
    id="content"
    src="titanic.html"
    width="100%"
    style="border:1px solid black;overflow:hidden;"
></iframe>
<script>
function resizeIframeToFitContent(iframe) {
    iframe.style.height = (iframe.contentWindow.document.documentElement.scrollHeight + 50) + "px";
    iframe.contentDocument.body.style["overflow"] = 'hidden';
}
window.addEventListener('load', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
window.addEventListener('resize', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
</script>
