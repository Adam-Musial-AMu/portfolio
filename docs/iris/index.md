
# Analiza eksploracyjna danych (EDA) – zbiór Iris

W tym projekcie prezentuję analizę eksploracyjną zbioru danych **Iris**, jednego z najbardziej klasycznych zestawów danych wykorzystywanych w uczeniu maszynowym. Analiza koncentruje się na zależnościach pomiędzy cechami morfologicznymi kwiatów oraz ich wpływie na rozróżnianie poszczególnych gatunków. W ramach pracy wykonano wstępne przygotowanie danych oraz wizualizacje, które pozwalają lepiej zrozumieć strukturę zbioru i jego potencjał do zastosowań klasyfikacyjnych.

<a href="iris.ipynb" class="md-button md-button--primary">Pobierz Notebook</a>

<iframe
    id="content"
    src="iris.html"
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
