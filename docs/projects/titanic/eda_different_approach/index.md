
# Analiza Danych z Titanica: Wiek, Płeć i Szalupy Ratunkowe

Zapraszamy do zapoznania się z naszym projektem, który koncentruje się na szczegółowej analizie danych dotyczących pasażerów Titanica. Nasze badania skupiają się na wieku i płci pasażerów, ze szczególnym uwzględnieniem dzieci. Dodatkowo, przeprowadziliśmy analizę szalup ratunkowych i ich wypełnienia, aby lepiej zrozumieć, jak te czynniki wpłynęły na przeżywalność podczas katastrofy. Odkryj fascynujące wnioski i dowiedz się, jakie historie kryją się za liczbami.

**Autor**: [Maciej Lubaszka](/od-zera-do-ai-portfolio/uczestnicy/maciej_lubaszka)

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
