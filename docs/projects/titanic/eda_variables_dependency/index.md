
# Analiza Danych z Titanica: Odkrywanie Pojedynczych Zmiennych

Zapraszamy do zapoznania się z fascynującą analizą danych z legendarnego rejsu Titanica. Nasz projekt koncentruje się na szczegółowej analizie pojedynczych zmiennych, takich jak wiek, płeć, klasa podróży i inne, aby odkryć interesujące wnioski i wzorce. Dowiedz się, jakie czynniki miały największy wpływ na przeżywalność pasażerów i jakie historie kryją się za suchymi danymi. Zanurz się w świat statystyki i historii, gdzie każda liczba opowiada swoją unikalną opowieść.

**Autor**: [Patryk](/od-zera-do-ai-portfolio/uczestnicy/patryk)

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
