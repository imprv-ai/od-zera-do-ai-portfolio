
# Analiza Danych z Titanica: Odkryj Historię na Nowo

Zapraszamy do zapoznania się z fascynującym projektem analizy danych z legendarnego Titanica. Analiza Grzegorza oferuje unikalne spojrzenie na wydarzenia z 1912 roku poprzez różnorodne i ciekawe wykresy, które ożywiają historię. Odkryj na nowo perspektywy i zrozumienie tego, co wydarzyło się na pokładzie Titanica.

**Autor**: [Grzegorz Jaworucki](/od-zera-do-ai-portfolio/uczestnicy/grzegorz_jaworucki)

<a href="GrzegorzJa.ipynb" class="md-button md-button--primary">Pobierz Notebook</a>

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
