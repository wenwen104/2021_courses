```
<!DOCTYPE html>
<head>
<title></title>
</head>
<body>
<h1>標題欄顯示當前日期</h1>
<script type="text/javascript">
    //定義月份的描述
    var isnMonth = new Array("1月","2月","3月","4月","5月","6月","7月","8月","9月","10月","11月","12月");
    //定義星期的描述
    var isnDay = new Array("星期日","星期一","星期二","星期三","星期四","星期五","星期六","星期日");

    today = new Date ();        //取得當前日期
    Year=today.getFullYear();	//取得日期的年份部分(四位年份2018)
    Date=today.getDate();	  //取得星期部分
    //定義需要顯示的字串
    titlestr="今天是: "+Year+"年"+isnMonth[today.getMonth()]+Date+"日"+isnDay[today.getDay()];
    //檢測瀏覽器相容性，如果是IE則可以顯示
    if (document.all)
        //改變標題，顯示日期。
        document.all
        document.title=titlestr;
</script>
</body>
</html>
```

```
選擇題
( B )1.	下列何者為HTML文件的根元素？
	A. <meta>  B. <html>	C. <head>	D. <body>
( B )2.	下列哪個全域屬性可以用來設定元素的標題？
		A. class	B. id	 C. style	D. title
(  )3.	下列哪個事件屬性可以用來設定當瀏覽器載入網頁時所要執行的Script？
		A. onload	B. onclick	C. onfocus	D. onblur
( D )4.	下列哪個元素可以放在 <head> 元素裡面？
		A. <p>	B. <h1>	 C. <body>	D. <title>
(  )5.	下列哪個元素可以用來設定HTML文件的內容類型 (content type)？
		A. <html>	B. <p>	C. <meta>	D. <link>
(  )6.	下列哪個元素可以用來設定HTML文件的聯絡資訊？
	A. <footer>  B. <title>	  C. <time>	D. <address>
(  )7.	下列哪個HTML5新增的元素最適合用來標示獨立的內容，例如部落格的一篇文章？
	A. <article>	B. <section>	C. <aside>	D. <nav>
(  )8.	下列哪個HTML5新增的元素最適合用來放置網頁的擁有者資訊、建議瀏覽器解析度、版權聲明、隱私權政策等內容？
	A. <header>	B. <footer>	C. <aside>	D. <address>
(  )9.	下列哪個元素預設的字體最大？
	A. <h1> 	B. <h2>	  C. <p>	D. <pre>
(  )10.下列哪個元素可以用來設定目前文件與其它資源之間的關聯？
	A. <base>	B. <meta>	C. <head>	D. <link>
```
```
( J )1. 標題5                               	A.<blockquote>
( S )2. 段落                                	B.<sup>
( A )3. 引述區塊                             	C.<u>
( M )4. 換行                                 	D.<strong>
( U )5. 預先格式化                           	E.<mark>
( O )6. 註解                                 	F.<hr>
( L )7. 粗體                                 	G.<ol>
( P )8. 上標                                 	H.<ruby>
( B )9. 下標                                 	I.<s>
( C )10. 加底線                              	J.<h5>
( V )11. 強調斜體                            	K.<dl>
( D )12. 強調粗體                            	L.<b>
( I )13. 刪除字                              	M.<br>
( T )14. 斜體                              		N.<span>
( E )15. 螢光標記                            	O.<!-- -->
( F )16. 水平線                              	P.<sub>
( Q )17. 項目符號                           	Q.<ul>
( G )18. 編號                                	R.<div>
( K )19. 定義清單                            	S.<p>
( H )20. 注音或拼音                          	T.<i>
( R )21. 群組成一個區塊                   		U.<pre>
( V )22. 群組成一行                      		V.<em>
( X )23. 超連結                          		W.<base>
( W )24. 相對URL的路徑資訊              		X.<a>
```
