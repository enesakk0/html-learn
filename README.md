<p align="center">
  <img src="1200px-Devicon-html5-plain.svg.png" width="110" height="110" alt="HTML5 Logo"/>
</p>

<h3 align="center">HTML Tutorial</h3>

<p align="center">HTML dilinde en çok sık kullanılan etiketler ve örnekler ile desteklenen bir proje çalışmasıdır.</p>

<div align="center" id="links">
  <span align="center"><strong><a href="https://developer.mozilla.org/en-US/docs/Web/HTML" target="_blank">MDN</a></strong></span>
  <span align="center"><strong><a href="https://www.w3schools.com/" target="_blank">W3Schools</a></strong></span>
</div>

## HTML Hakkında

<p>HTML dili açılım olarak Hyper Text Markup Language olarak olup, bir yazılım dili olmamakla beraber web sayfalarını oluşturulmak için kullanılan bir metin işaretleme dilidir ve en güncel sürümü <strong>HTML5</strong> sürümüdür.</p>

## Öğrenim içeriği

<p>Listeler üzerinde yer alan içeriklerin üzerine tıklayarak ilgili sayfa menüsüne ulaşabilirsiniz. Ek olarak ilgili içerik üzerinden örnek html dosyalarına ulaşabilirsiniz.</p>

<ul>
  <li><a href="#temel-html">Temel HTML etiketlerine genel bakış</a></li>
  <li>Semantic HTML etiketleri</li>
  <li>Blok ve inline elementler</li>
  <li>Liste etiketleri</li>
  <li>VS Code Emmet Kullanımı</li>
  <li>Tablo yapıları</li>
  <li>Form yapıları</li>
  <li>HTML Header Metatag yapıları</li>
</ul>

<h3 id="temel-html">Temel HTML Etiketleri</h3>
<hr>
<p>Bir web sayfası üzerinde sadece <strong>html</strong> etiketi yer almaz bunun haricinde <em>header,body</em> gibi etiketlerde yer almaktadır. 
<strong>html</strong> etiketi HTML dilinin root (temel) etiketi denebilir. Diğer etiketler <strong>html</strong> etiketinin içinde yer alan etiketlerdir.

İşaretleme sıraları aşağıdaki gibidir.</p>
  
 ├── html <br>
     &nbsp;  ├── <a href="#header">header</a> <br>
     &nbsp;  ├── <a href="#body">body</a>
     
<h3 id="header">Header Etiketi</h3>

<p>Web sitemizde özellike SEO ayarları veya sitenin metatagleri için kullanabileceğimiz alanı oluşturmaktadır. Burada girilen kodlar veya etiketler sitemiz içerisinde yer alan fakat görsellik anlamında bir değişiklik yapmazlar.</p>

<p>Metatag etiketleri sayı olarak biraz fazla olup genel bir HTML sayfasında genel olarak aşağıdaki Metatagler sık sık kullanılmaktadır.</p>

<p>Metatagleri kullanılırken aşağıdaki söz dizimi ile kullanılmaktadır.</p>

```md
<meta name="">
```

<table>
<thead>
  <td><strong>Metatag Etiketi</strong></td>
  <td><strong>Açıklama</strong></td>
</thead>
<tbody>
  <tr>
    <td>name="description"</td>
    <td>Arama motorlarında çıkan sonuçlarında sitelerin açıklaması olarak gözükmektedir.</td>
  </tr>
  <tr>
    <td>name="keywords"</td>
    <td>Arama motorları sorgulamaların sitelerin indexlenmesinde anahtar kelimelerini belirlemektedir.</td>
  </tr>
  <tr>
    <td>charset="UTF-8"</td>
    <td>Web sitesini emoji ve türkçe karaktere uygun olacak şekilde (utf-8) olarak kodlar.</td>
  </tr>
</tbody>
</table>

<h3 id="body">Body Etiketi</h3>

<p>Body etiketi ise sitemizde yer alan tüm içerikleri, görselleri, makaleleri vb. kısacası tüm içeriklerimizin yer aldığı etiket olarak yer almaktadır.</p>

