# スクリーンショットはWebPが良い

以下のグラフに示されるように、WebPはJPEGに対して優れた圧縮性能を発揮する。
WebPでは元となる画像によっては可逆圧縮のほうが非可逆圧縮よりも圧縮効率が良い。
したがって
**Lossy 70%クォリティのWebP**と**Lossless WebP**のうち、小さい方を採用するのが良い。

![WebP and JPEG Compression with Lossless](images/webp_jpeg_compression_with_lossless_graph.png)


### 目視による画像の比較
この記事で使用した2枚の元の画像は以下の通りです：

- ![neko.png](images/neko.png)
  *neko.png 195 KBのPNG画像*

- ![tenki.png](images/tenki.png)
  *tenki.png 109 KBのPNG画像*

変換前のオリジナルのPNG画像とWebP画像とJPEG画像を並べます。

## Quality 10のJPEGとWebP

<table><tr>
<td>
<img src="images/neko.png" alt="Original PNG">
<p align="center">Original PNG</p>
</td>
<td>
<img src="images/neko_quality_10.jpeg" alt="Quality 10 JPEG">
<p align="center">Quality 10 JPEG</p>
</td>
<td>
<img src="images/neko_quality_10.webp" alt="Quality 10 WebP">
<p align="center">Quality 10 WebP</p>
</td>
</tr>
<tr>
<td>
<img src="images/tenki.png" alt="Original PNG">
<p align="center">Original PNG</p>
</td>
<td>
<img src="images/tenki_quality_10.jpeg" alt="Quality 10 JPEG">
<p align="center">Quality 10 JPEG</p>
</td>
<td>
<img src="images/tenki_quality_10.webp" alt="Quality 10 WebP">
<p align="center">Quality 10 WebP</p>
</td>
</tr></table>

## Quality 20のJPEGとWebP

<table><tr>
<td>
<img src="images/neko.png" alt="Original PNG">
<p align="center">Original PNG</p>
</td>
<td>
<img src="images/neko_quality_20.jpeg" alt="Quality 20 JPEG">
<p align="center">Quality 20 JPEG</p>
</td>
<td>
<img src="images/neko_quality_20.webp" alt="Quality 20 WebP">
<p align="center">Quality 20 WebP</p>
</td>
</tr>
<tr>
<td>
<img src="images/tenki.png" alt="Original PNG">
<p align="center">Original PNG</p>
</td>
<td>
<img src="images/tenki_quality_20.jpeg" alt="Quality 20 JPEG">
<p align="center">Quality 20 JPEG</p>
</td>
<td>
<img src="images/tenki_quality_20.webp" alt="Quality 20 WebP">
<p align="center">Quality 20 WebP</p>
</td>
</tr></table>

<h2>Quality 30のJPEGとWebP</h2>

<table><tr>
<td>
<img src="images/neko.png" alt="Original PNG">
<p align="center">Original PNG</p>
</td>
<td>
<img src="images/neko_quality_30.jpeg" alt="Quality 30 JPEG">
<p align="center">Quality 30 JPEG</p>
</td>
<td>
<img src="images/neko_quality_30.webp" alt="Quality 30 WebP">
<p align="center">Quality 30 WebP</p>
</td>
</tr>
<tr>
<td>
<img src="images/tenki.png" alt="Original PNG">
<p align="center">Original PNG</p>
</td>
<td>
<img src="images/tenki_quality_30.jpeg" alt="Quality 30 JPEG">
<p align="center">Quality 30 JPEG</p>
</td>
<td>
<img src="images/tenki_quality_30.webp" alt="Quality 30 WebP">
<p align="center">Quality 30 WebP</p>
</td>
</tr></table>

<h2>Quality 40のJPEGとWebP</h2>

<table><tr>
<td>
<img src="images/neko.png" alt="Original PNG">
<p align="center">Original PNG</p>
</td>
<td>
<img src="images/neko_quality_40.jpeg" alt="Quality 40 JPEG">
<p align="center">Quality 40 JPEG</p>
</td>
<td>
<img src="images/neko_quality_40.webp" alt="Quality 40 WebP">
<p align="center">Quality 40 WebP</p>
</td>
</tr>
<tr>
<td>
<img src="images/tenki.png" alt="Original PNG">
<p align="center">Original PNG</p>
</td>
<td>
<img src="images/tenki_quality_40.jpeg" alt="Quality 40 JPEG">
<p align="center">Quality 40 JPEG</p>
</td>
<td>
<img src="images/tenki_quality_40.webp" alt="Quality 40 WebP">
<p align="center">Quality 40 WebP</p>
</td>
</tr></table>

<h2>Quality 50のJPEGとWebP</h2>

<table><tr>
<td>
<img src="images/neko.png" alt="Original PNG">
<p align="center">Original PNG</p>
</td>
<td>
<img src="images/neko_quality_50.jpeg" alt="Quality 50 JPEG">
<p align="center">Quality 50 JPEG</p>
</td>
<td>
<img src="images/neko_quality_50.webp" alt="Quality 50 WebP">
<p align="center">Quality 50 WebP</p>
</td>
</tr>
<tr>
<td>
<img src="images/tenki.png" alt="Original PNG">
<p align="center">Original PNG</p>
</td>
<td>
<img src="images/tenki_quality_50.jpeg" alt="Quality 50 JPEG">
<p align="center">Quality 50 JPEG</p>
</td>
<td>
<img src="images/tenki_quality_50.webp" alt="Quality 50 WebP">
<p align="center">Quality 50 WebP</p>
</td>
</tr></table>

<h2>Quality 60 のJPEGとWebP</h2>

<table><tr>
<td>
<img src="images/neko.png" alt="Original PNG">
<p align="center">Original PNG</p>
</td>
<td>
<img src="images/neko_quality_60.jpeg" alt="Quality 60 JPEG">
<p align="center">Quality 60 JPEG</p>
</td>
<td>
<img src="images/neko_quality_60.webp" alt="Quality 60 WebP">
<p align="center">Quality 60 WebP</p>
</td>
</tr>
<tr>
<td>
<img src="images/tenki.png" alt="Original PNG">
<p align="center">Original PNG</p>
</td>
<td>
<img src="images/tenki_quality_60.jpeg" alt="Quality 60 JPEG">
<p align="center">Quality 60 JPEG</p>
</td>
<td>
<img src="images/tenki_quality_60.webp" alt="Quality 60 WebP">
<p align="center">Quality 60 WebP</p>
</td>
</tr></table>


<h2>Quality 70 のJPEGとWebP</h2>

<table><tr>
<td>
<img src="images/neko.png" alt="Original PNG">
<p align="center">Original PNG</p>
</td>
<td>
<img src="images/neko_quality_70.jpeg" alt="Quality 70 JPEG">
<p align="center">Quality 70 JPEG</p>
</td>
<td>
<img src="images/neko_quality_70.webp" alt="Quality 70 WebP">
<p align="center">Quality 70 WebP</p>
</td>
</tr>
<tr>
<td>
<img src="images/tenki.png" alt="Original PNG">
<p align="center">Original PNG</p>
</td>
<td>
<img src="images/tenki_quality_70.jpeg" alt="Quality 70 JPEG">
<p align="center">Quality 70 JPEG</p>
</td>
<td>
<img src="images/tenki_quality_70.webp" alt="Quality 70 WebP">
<p align="center">Quality 70 WebP</p>
</td>
</tr></table>


<h2>Quality 80 のJPEGとWebP</h2>

<table><tr>
<td>
<img src="images/neko.png" alt="Original PNG">
<p align="center">Original PNG</p>
</td>
<td>
<img src="images/neko_quality_80.jpeg" alt="Quality 80 JPEG">
<p align="center">Quality 80 JPEG</p>
</td>
<td>
<img src="images/neko_quality_80.webp" alt="Quality 80 WebP">
<p align="center">Quality 80 WebP</p>
</td>
</tr>
<tr>
<td>
<img src="images/tenki.png" alt="Original PNG">
<p align="center">Original PNG</p>
</td>
<td>
<img src="images/tenki_quality_80.jpeg" alt="Quality 80 JPEG">
<p align="center">Quality 80 JPEG</p>
</td>
<td>
<img src="images/tenki_quality_80.webp" alt="Quality 80 WebP">
<p align="center">Quality 80 WebP</p>
</td>
</tr></table>


<h2>Quality 90 のJPEGとWebP</h2>

<table><tr>
<td>
<img src="images/neko.png" alt="Original PNG">
<p align="center">Original PNG</p>
</td>
<td>
<img src="images/neko_quality_90.jpeg" alt="Quality 90 JPEG">
<p align="center">Quality 90 JPEG</p>
</td>
<td>
<img src="images/neko_quality_90.webp" alt="Quality 90 WebP">
<p align="center">Quality 90 WebP</p>
</td>
</tr>
<tr>
<td>
<img src="images/tenki.png" alt="Original PNG">
<p align="center">Original PNG</p>
</td>
<td>
<img src="images/tenki_quality_90.jpeg" alt="Quality 90 JPEG">
<p align="center">Quality 90 JPEG</p>
</td>
<td>
<img src="images/tenki_quality_90.webp" alt="Quality 90 WebP">
<p align="center">Quality 90 WebP</p>
</td>
</tr></table>


<h2>Quality 95 のJPEGとWebP</h2>

<table><tr>
<td>
<img src="images/neko.png" alt="Original PNG">
<p align="center">Original PNG</p>
</td>
<td>
<img src="images/neko_quality_95.jpeg" alt="Quality 95 JPEG">
<p align="center">Quality 95 JPEG</p>
</td>
<td>
<img src="images/neko_quality_95.webp" alt="Quality 95 WebP">
<p align="center">Quality 95 WebP</p>
</td>
</tr>
<tr>
<td>
<img src="images/tenki.png" alt="Original PNG">
<p align="center">Original PNG</p>
</td>
<td>
<img src="images/tenki_quality_95.jpeg" alt="Quality 95 JPEG">
<p align="center">Quality 95 JPEG</p>
</td>
<td>
<img src="images/tenki_quality_95.webp" alt="Quality 95 WebP">
<p align="center">Quality 95 WebP</p>
</td>
</tr></table>

<h2>Quality 96 のJPEGとWebP</h2>

<table><tr>
<td>
<img src="images/neko.png" alt="Original PNG">
<p align="center">Original PNG</p>
</td>
<td>
<img src="images/neko_quality_96.jpeg" alt="Quality 96 JPEG">
<p align="center">Quality 96 JPEG</p>
</td>
<td>
<img src="images/neko_quality_96.webp" alt="Quality 96 WebP">
<p align="center">Quality 96 WebP</p>
</td>
</tr>
<tr>
<td>
<img src="images/tenki.png" alt="Original PNG">
<p align="center">Original PNG</p>
</td>
<td>
<img src="images/tenki_quality_96.jpeg" alt="Quality 96 JPEG">
<p align="center">Quality 96 JPEG</p>
</td>
<td>
<img src="images/tenki_quality_96.webp" alt="Quality 96 WebP">
<p align="center">Quality 96 WebP</p>
</td>
</tr></table>


<h2>Quality 97 のJPEGとWebP</h2>

<table><tr>
<td>
<img src="images/neko.png" alt="Original PNG">
<p align="center">Original PNG</p>
</td>
<td>
<img src="images/neko_quality_97.jpeg" alt="Quality 97 JPEG">
<p align="center">Quality 97 JPEG</p>
</td>
<td>
<img src="images/neko_quality_97.webp" alt="Quality 97 WebP">
<p align="center">Quality 97 WebP</p>
</td>
</tr>
<tr>
<td>
<img src="images/tenki.png" alt="Original PNG">
<p align="center">Original PNG</p>
</td>
<td>
<img src="images/tenki_quality_97.jpeg" alt="Quality 97 JPEG">
<p align="center">Quality 97 JPEG</p>
</td>
<td>
<img src="images/tenki_quality_97.webp" alt="Quality 97 WebP">
<p align="center">Quality 97 WebP</p>
</td>
</tr></table>

<h2>Quality 98 のJPEGとWebP</h2>

<table><tr>
<td>
<img src="images/neko.png" alt="Original PNG">
<p align="center">Original PNG</p>
</td>
<td>
<img src="images/neko_quality_98.jpeg" alt="Quality 98 JPEG">
<p align="center">Quality 98 JPEG</p>
</td>
<td>
<img src="images/neko_quality_98.webp" alt="Quality 98 WebP">
<p align="center">Quality 98 WebP</p>
</td>
</tr>
<tr>
<td>
<img src="images/tenki.png" alt="Original PNG">
<p align="center">Original PNG</p>
</td>
<td>
<img src="images/tenki_quality_98.jpeg" alt="Quality 98 JPEG">
<p align="center">Quality 98 JPEG</p>
</td>
<td>
<img src="images/tenki_quality_98.webp" alt="Quality 98 WebP">
<p align="center">Quality 98 WebP</p>
</td>
</tr></table>


<h2>Quality 99 のJPEGとWebP</h2>

<table><tr>
<td>
<img src="images/neko.png" alt="Original PNG">
<p align="center">Original PNG</p>
</td>
<td>
<img src="images/neko_quality_99.jpeg" alt="Quality 99 JPEG">
<p align="center">Quality 99 JPEG</p>
</td>
<td>
<img src="images/neko_quality_99.webp" alt="Quality 99 WebP">
<p align="center">Quality 99 WebP</p>
</td>
</tr>
<tr>
<td>
<img src="images/tenki.png" alt="Original PNG">
<p align="center">Original PNG</p>
</td>
<td>
<img src="images/tenki_quality_99.jpeg" alt="Quality 99 JPEG">
<p align="center">Quality 99 JPEG</p>
</td>
<td>
<img src="images/tenki_quality_99.webp" alt="Quality 99 WebP">
<p align="center">Quality 99 WebP</p>
</td>
</tr></table>

<h2>Quality 100 のJPEGとWebP</h2>

<table><tr>
<td>
<img src="images/neko.png" alt="Original PNG">
<p align="center">Original PNG</p>
</td>
<td>
<img src="images/neko_quality_100.jpeg" alt="Quality 100 JPEG">
<p align="center">Quality 100 JPEG</p>
</td>
<td>
<img src="images/neko_quality_100.webp" alt="Quality 100 WebP">
<p align="center">Quality 100 WebP</p>
</td>
</tr>
<tr>
<td>
<img src="images/tenki.png" alt="Original PNG">
<p align="center">Original PNG</p>
</td>
<td>
<img src="images/tenki_quality_100.jpeg" alt="Quality 100 JPEG">
<p align="center">Quality 100 JPEG</p>
</td>
<td>
<img src="images/tenki_quality_100.webp" alt="Quality 100 WebP">
<p align="center">Quality 100 WebP</p>
</td>
</tr></table>

