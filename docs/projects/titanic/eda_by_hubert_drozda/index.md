
# Analiza Demograficzna Przeżywalności na Titanicu

Fascynujące sekrety pasażerów Titanica!

Przeprowadzona analiza danych to nie tylko liczby, lecz podróż w czasie, ujawniająca zaskakujące zależności między przeżywalnością a cechami demograficznymi pasażerów. Dzięki zaawansowanym wizualizacjom i inteligentnemu grupowaniu danych ukazano, w jaki sposób płeć, klasa biletu i posiadanie rodziny wpływały na szanse przeżycia.

Dodatkowo, eksploracja kategorii wiekowych oraz analiza powiązań między pasażerami pozwoliły dostrzec intrygujące wzorce, które rzucają nowe światło na dobrze znaną historię.

Liczby opowiadają historię – warto sprawdzić, kto miał największe szanse przetrwania tej legendarnej katastrofy!

**Autor**: [Hubert Drozda](/od-zera-do-ai-portfolio/uczestnicy/hubert_drozda)

<a href="26_titanic_final.ipynb" class="md-button md-button--primary">Pobierz Notebook</a>

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
