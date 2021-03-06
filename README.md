# 濕地開放資料平台

> 這個平台是我們在2020聯發科【智在家鄉】競賽活動中，提出的六個計劃項目的其中一個，目的是要讓技術專家有溼地資料可以分析、領域專家可以學習技術分析，加速大家對全球暖化這個議題的研究。

> 我們的競賽的主題是【保護濕地、拯救地球】，一方面是希望透過智慧科技的協助維護濕地，群策群力的減緩地球的溫室效應，另一方面是希望從在地的茄萣濕地開始維護起，然後藉由茄萣濕地這個亮點，來`復興茄萣的產業`、`創造就業人口`、`促進人口回流`，達到地方創生的目的。

> 這個平台是準備用來存放一些簡單的技術教學，以及我們在茄萣濕地上蒐集的一些資料，我們計畫將資料開放出來做研究的用途。不過，目前感測器尚未佈署上濕地，所以數據尚未推上GitHub。

## Update

1. 以我個人的立場，我希望可以保護濕地；但是因為[高雄市政府已經通過環評](https://e-info.org.tw/node/228304)，茄萣濕地是可以被開路的，所以我已經有點放棄茄萣濕地這個場域，希望將技術應用在其他地方。濕地開路或許有少數人可以獲得短期的利益，但是長期來說保育濕地比較可以讓地方有更多的發展。所以... 雖然是家鄉... 但是殘念... 我沒辦法再做更多...
2. 對於物聯網跟AI，很多人是有疑慮的。打個比方說，對於濕地水質跟物種的採檢，政府是有編列預算給特定機構，然後由領域專家來執行的。我們在參加過的研討會中，有感受到領域專家害怕被系統取代的憂心；縱使我們覺得"定期健康檢查"(現行狀況)跟"使用血壓計、血糖計"(我們的提案)是兩個可以相輔相成的東西，但是還是有點擔心以後相關單位並不容易接受這一類系統。所以我們暫時把接下來的方向，放在技術分享，而不是系統開發上面。
3. 最後，我們已經將部分影片跟投影片上傳到這個 repo 裡面，希望對想要保護濕地的朋友們有幫助。

## 資料整理：

* [台灣濕地GPS座標](wetlands.csv)

## 相關連結：

* [濕地的功能](https://wetland-tw.tcd.gov.tw/edu/Features.php)
* [國家重要濕地保育計畫](https://wetland-tw.tcd.gov.tw/tw/index.php)
* [濕地環境資料庫](https://wetland-db.tcd.gov.tw/)
* [交通部中央氣象局](https://www.cwb.gov.tw/V8/C/)
* [氣象資料開放平台](https://opendata.cwb.gov.tw/index)

## 資料分析教學：

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/victorgau/wetland_opendata/)

底下教學的程式語言以Python為主。

如果對學習Python有興趣，可以參考我們的免費課程：[Python快速入門](https://khpy.teachable.com/p/simple-python-applications)。

folium是python繪製地圖的套件。folium最新版本的中文顯示會出現亂碼，如果要用folium畫地圖並在地圖上標中文，請使用github上面修正後的版本。
```python
!pip install git+https://github.com/python-visualization/branca.git@master
```

<table>
<tr>
<td class="youtube" width="250px"><a href="https://www.youtube.com/watch?v=MwXoQpuR7X0"><img src="http://img.youtube.com/vi/MwXoQpuR7X0/0.jpg" width="240px"></a></td>
<td valign="top" width="400px">
<h3>水質感測器相關性分析</h3>
<a href="https://colab.research.google.com/github/victorgau/wetland_opendata/blob/master/ipynb/%E6%B0%B4%E8%B3%AA%E6%84%9F%E6%B8%AC%E5%99%A8%E7%9B%B8%E9%97%9C%E6%80%A7%E5%88%86%E6%9E%90.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg"></a>

說明如何利用<a href="https://ksenlab.ksepb.gov.tw/wq/Default.aspx">河川水質連續自動監測站</a>的水質監測資料，簡單的觀察感測器的相關性。
</td>
</tr>
</table>

<table>
<tr>
<td class="youtube" width="250px"><a href="https://www.youtube.com/watch?v=PnDzBsHBbLc"><img src="http://img.youtube.com/vi/PnDzBsHBbLc/0.jpg" width="240px"></a></td>
<td valign="top" width="400px">
<h3>讀取濕地資料</h3>
<a href="https://colab.research.google.com/github/victorgau/wetland_opendata/blob/master/ipynb/%E8%AE%80%E5%8F%96%E6%BF%95%E5%9C%B0%E8%B3%87%E6%96%99.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg"></a>

簡單說明如何從<a href="https://wetland-db.tcd.gov.tw/">濕地環境資料庫</a>中讀取台灣的濕地資料。
</td>
</tr>
</table>

<table>
<tr>
<td class="youtube" width="250px"><a href="https://youtu.be/lLh2988i1g8"><img src="http://img.youtube.com/vi/lLh2988i1g8/0.jpg" width="240px"></a></td>
<td valign="top" width="400px">
<h3>在地圖上標出濕地位置</h3>
<a href="https://colab.research.google.com/github/victorgau/wetland_opendata/blob/master/ipynb/%E5%9C%A8%E5%9C%B0%E5%9C%96%E4%B8%8A%E6%A8%99%E5%87%BA%E6%BF%95%E5%9C%B0%E7%9A%84%E4%BD%8D%E7%BD%AE.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg"></a>

簡單說明如何使用folium在地圖上標出濕地的位置。
</td>
</tr>
</table>

<table>
<tr>
<td class="youtube" width="250px"><a href="https://youtu.be/8z7yM4ErRJQ"><img src="http://img.youtube.com/vi/8z7yM4ErRJQ/0.jpg" width="240px"></a></td>
<td valign="top" width="400px">
<h3>讀取濕地物種資料</h3>
<a href="https://colab.research.google.com/github/victorgau/wetland_opendata/blob/master/ipynb/%E8%AE%80%E5%8F%96%E6%BF%95%E5%9C%B0%E7%89%A9%E7%A8%AE%E8%B3%87%E6%96%99.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg"></a>

<a href="https://wetland-db.tcd.gov.tw/">濕地環境資料庫</a>的<a href="https://wetland-db.tcd.gov.tw/#/wetlandAPIPage">介接服務</a>使用教學。

</td>
</tr>
</table>

<table>
<tr>
<td class="youtube" width="250px"><a href="https://youtu.be/f1FpGgvxlPE"><img src="http://img.youtube.com/vi/f1FpGgvxlPE/0.jpg" width="240px"></a></td>
<td valign="top" width="400px">
<h3>讀取濕地水質資料</h3>
<a href="https://colab.research.google.com/github/victorgau/wetland_opendata/blob/master/ipynb/%E8%AE%80%E5%8F%96%E6%BF%95%E5%9C%B0%E6%B0%B4%E8%B3%AA%E8%B3%87%E6%96%99.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg"></a>

<a href="https://wetland-db.tcd.gov.tw/">濕地環境資料庫</a>的<a href="https://wetland-db.tcd.gov.tw/#/wetlandAPIPage">介接服務</a>使用教學。

</td>
</tr>
</table>


<table>
<tr>
<td class="youtube" width="250px"><a href="https://youtu.be/ivnA2b7fSGY"><img src="http://img.youtube.com/vi/ivnA2b7fSGY/0.jpg" width="240px"></a></td>
<td valign="top" width="400px">
<h3>讀取中央氣象局資料</h3>
<a href="https://colab.research.google.com/github/victorgau/wetland_opendata/blob/master/ipynb/%E8%AE%80%E5%8F%96%E4%B8%AD%E5%A4%AE%E6%B0%A3%E8%B1%A1%E5%B1%80%E8%B3%87%E6%96%99.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg"></a>

中央氣象局的<a href="https://opendata.cwb.gov.tw/index">氣象資料開放平台</a>的使用範例。

</td>
</tr>
</table>
