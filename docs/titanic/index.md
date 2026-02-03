
# Analiza eksploracyjna danych (EDA) – zbiór Titanic

W tym projekcie przedstawiam analizę eksploracyjną klasycznego zbioru danych **Titanic**, koncentrując się na identyfikacji czynników wpływających na przeżycie pasażerów. Analiza obejmuje czyszczenie danych, inżynierię cech oraz wizualizacje zależności pomiędzy zmiennymi demograficznymi i socjoekonomicznymi. Celem było nie tylko zrozumienie struktury danych, ale również wyciągnięcie wniosków, które mogą stanowić podstawę do budowy modeli predykcyjnych.

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
