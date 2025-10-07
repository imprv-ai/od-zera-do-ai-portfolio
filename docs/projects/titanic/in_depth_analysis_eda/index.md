
# Wnikliwa Analiza Danych z Titanica

Zapraszamy do zapoznania się z wspaniałą, gruntownie wykonaną analizą eksploracyjną danych (EDA) z Titanica. Nasz projekt zawiera wiele ciekawych wniosków, które mogą być niezwykle przydatne w modelowaniu danych. Odkryjemy zależności pomiędzy różnymi kolumnami oraz zidentyfikujemy najważniejsze cechy w naszym zbiorze danych. Dodatkowo, nasza analiza wyróżnia się kreatywnością, na przykład poprzez skonstruowanie unikalnego 'survival score'.

**Autor**: [Natalia Swojak](/od-zera-do-ai-portfolio/uczestnicy/natalia_swojak)

<a href="titanic.ipynb" class="md-button md-button--primary" download>Pobierz Notebook</a>

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
