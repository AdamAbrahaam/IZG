<h2><span><a name="Redukce_barevného_prostoru">Redukce barevného prostoru</a></span></h2>

<h3><span><a name="Osnova_cvičení">Osnova cvičení</a></span></h3>

<ul>
<li class="level1">Organizace cvičení</li>
<li class="level1">Seznámení s kostrou aplikace používanou v IZG</li>
<li class="level1">Redukce barevného prostoru</li>
<li class="level1">Samostatná práce (bodované úkoly)</li>
</ul>

<h3><span><a name="Prerekvizita">Prerekvizita</a></span></h3>

<ul>
<li class="level1">Přednáška č. 2 - Redukce barevneho prostoru, barevný a monochromatický obraz</li>
</ul>

<h3><span><a name="Bodované_úkoly">Bodované úkoly</a></span></h3>

<ul>
<li class="level1">Implementací funkcí pro čtení a zápis do frame bufferu (0.5 bodu)</li>
<li class="level1">Implementace převodu barevného obrazu na šedotónový (0.5 bodu)</li>
<li class="level1">Implementace převodu na černobílý obraz pomocí maticového rozptýlení (1 bod)</li>
<li class="level1">Implementace distribuce chyby metodou Floyd-Steinberg (1 bod)</li>
</ul>

<h3><span><a name="Soubory_ke_stažení">Soubory ke stažení</a></span></h3>

<ul>
<li class="level1">Archiv s kostrou programu:</li>
</ul>

<p>

<a href="http://www.fit.vutbr.cz/study/courses/IZG/private/lab/01/izg_lab_01.zip" class="external" title="http://www.fit.vutbr.cz/study/courses/IZG/private/lab/01/izg_lab_01.zip"  rel="nofollow">www.fit.vutbr.cz/study/courses/IZG/private/lab/01/izg_lab_01.zip</a>
</p>

<ul>
<li class="level1">Prezentace/návod ke cvičení:</li>
</ul>

<p>

<a href="http://www.fit.vutbr.cz/study/courses/IZG/private/lab/01/izg_lab_01.pdf" class="external" title="http://www.fit.vutbr.cz/study/courses/IZG/private/lab/01/izg_lab_01.pdf"  rel="nofollow">www.fit.vutbr.cz/study/courses/IZG/private/lab/01/izg_lab_01.pdf</a>
</p>

<h2><span><a name="Ovládání_aplikace">Ovládání aplikace</a></span></h2>

<ul>
<li class="level1">Levé kliknutí myši
<ul>
<li class="level2">Vypíše na konzoli hodnotu daného pixelu</li>
<li class="level2">Závisí na funkci <b>getPixel()</b></li>
</ul>
</li>
<li class="level1">Klávesa <b>L</b>
<ul>
<li class="level2">Nahraje testovací obrázek umístěný v /data/image.bmp</li>
<li class="level2">Závisí na funkci <b>putPixel()</b></li>
</ul>
</li>
<li class="level1">Klávesa <b>S</b>
<ul>
<li class="level2">Uloží současné okno do souboru /data/out.bmp</li>
<li class="level2">Závisí na funkci <b>getPixel()</b></li>
</ul>
</li>
<li class="level1">Klávesa <b>G</b>
<ul>
<li class="level2">Převede obraz do stupňů šedi</li>
<li class="level2">Závisí na funkci <b>getPixel()</b> a <b>putPixel()</b></li>
</ul>
</li>
<li class="level1">Klávesy <b>1</b>..<b>4</b>
<ul>
<li class="level2">Převedou obraz na černobílý pomocí prahování s prahy (50, 100, 150, 200)</li>
<li class="level2">Závisí na funkci <b>getPixel()</b> a <b>putPixel()</b>, případně <b>greyScale()</b></li>
</ul>
</li>
<li class="level1">Klávesa <b>R</b>
<ul>
<li class="level2">Převede obraz na černobílý pomocí metody náhodného rozptýlení</li>
<li class="level2">Závisí na funkci <b>getPixel()</b>, <b>putPixel()</b> a <b>greyScale()</b></li>
</ul>
</li>
<li class="level1">Klávesa <b>M</b>
<ul>
<li class="level2">Převede obraz na černobílý pomocí maticového rozptýlení</li>
<li class="level2">Závisí na funkci <b>getPixel()</b> a <b>putPixel()</b>, případně <b>greyScale()</b></li>
</ul>
</li>
<li class="level1">Klávesa <b>D</b>
<ul>
<li class="level2">Převede obraz na černobílý pomocí prahování s distribucí chyby</li>
<li class="level2">Závisí na funkci <b>getPixel()</b> a <b>putPixel()</b>, případně <b>greyScale()</b></li>
</ul>
</li>
</ul>
