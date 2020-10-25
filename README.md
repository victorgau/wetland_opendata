# 濕地開放資料平台

> 這個平台是準備用來存放我們在茄萣濕地上蒐集的一些資料，我們計畫將資料開放出來做研究的用途。不過，目前感測器尚未佈署上濕地，所以數據尚未推上GitHub。

> 另外，我們也錄製了一些資料分析的教學，幫助大家上手簡單的資料分析。

資料整理：

* [台灣濕地GPS座標](wetlands.csv)

相關連結：

* [濕地的功能](https://wetland-tw.tcd.gov.tw/edu/Features.php)
* [國家重要濕地保育計畫](https://wetland-tw.tcd.gov.tw/tw/index.php)
* [濕地環境資料庫](https://wetland-db.tcd.gov.tw/)
* [交通部中央氣象局](https://www.cwb.gov.tw/V8/C/)

## 資料分析教學：

底下教學的程式語言以Python為主。

folium最新版本的中文顯示會出現亂碼，如果要用folium畫地圖並在地圖上標中文，請使用github上面修正後的版本。
```python
!pip install git+https://github.com/python-visualization/branca.git@master
```

<table>
<tr>
<td class="youtube" width="250px"><a href="https://www.youtube.com/watch?v=MwXoQpuR7X0"><img src="http://img.youtube.com/vi/MwXoQpuR7X0/0.jpg" width="240px"></a></td>
<td valign="top" width="400px">
<h3>水質感測器相關性分析</h3>

說明如何利用<a href="https://ksenlab.ksepb.gov.tw/wq/Default.aspx">河川水質連續自動監測站</a>的水質監測資料，簡單的觀察感測器的相關性。
</td>
</tr>
</table>

<table>
<tr>
<td class="youtube" width="250px"><a href="https://www.youtube.com/watch?v=PnDzBsHBbLc"><img src="http://img.youtube.com/vi/PnDzBsHBbLc/0.jpg" width="240px"></a></td>
<td valign="top" width="400px">
<h3>讀取濕地資料</h3>

簡單說明如何從<a href="https://wetland-db.tcd.gov.tw/">濕地環境資料庫</a>中讀取台灣的濕地資料。
</td>
</tr>
</table>

<table>
<tr>
<td class="youtube" width="250px"><a href="https://youtu.be/lLh2988i1g8"><img src="http://img.youtube.com/vi/lLh2988i1g8/0.jpg" width="240px"></a></td>
<td valign="top" width="400px">
<h3>在地圖上標出濕地位置</h3>

簡單說明如何使用folium在地圖上標出濕地的位置。
</td>
</tr>
</table>

<table>
<tr>
<td class="youtube" width="250px"><a href="https://youtu.be/8z7yM4ErRJQ"><img src="http://img.youtube.com/vi/8z7yM4ErRJQ/0.jpg" width="240px"></a></td>
<td valign="top" width="400px">
<h3>讀取濕地物種資料</h3>

<a href="https://wetland-db.tcd.gov.tw/">濕地環境資料庫</a>的<a href="https://wetland-db.tcd.gov.tw/#/wetlandAPIPage">介接服務</a>使用教學。

</td>
</tr>
</table>
