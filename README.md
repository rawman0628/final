# final
<!DOCTYPE HTML>
<!--
	Stellar by HTML5 UP
	html5up.net | @ajlkn
	Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)
-->
<html>
	<head>
		<title>Stellar by HTML5 UP</title>
		<meta charset="utf-8" />
		<meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no" />
		<link rel="stylesheet" href="assets/css/main.css" />
		<noscript><link rel="stylesheet" href="assets/css/noscript.css" /></noscript>
	</head>
	<body class="is-preload">

		<!-- Wrapper -->
			<div id="wrapper">

				<!-- Header -->
					<header id="header" class="alt">
						<span class="logo"><img src=https://cdn-icons-png.flaticon.com/512/3258/3258157.png
            " width="400" alt="" /></span>
						<h1>施驕陽</h1>
						<p>.資科四A 411025936.</p>
					</header>

				<!-- Nav -->
					<nav id="nav">
						<ul>
							<li><a href="#intro" class="active">簡介</a></li>
							<li><a href="#first">興趣愛好</a></li>
							<li><a href="#second">學習經歷</a></li>
							<li><a href="#cta">爬蟲展示</a></li>
						</ul>
					</nav>

				<!-- Main -->
					<div id="main">

						<!-- Introduction -->
							<section id="intro" class="main">
								<div class="spotlight">
									<div class="content">
										<header class="major">
											<h2>個人簡介</h2>
										</header>
										<p>大家好，我叫施驕陽，110學年入學靜宜大學資科系，在大學期間修習過許多課程都令我深有感觸，也希望在剩下的一年中可以更加鑽研提升自己的專業技能。</p>
										<ul class="actions">
										</ul>
									</div>
									<span class="image"><img src="https://upload.wikimedia.org/wikipedia/zh/thumb/8/8b/Providence_University_Emblem.svg/1200px-Providence_University_Emblem.svg.png" alt="" /></span>
								</div>
							</section>

						<!-- First Section -->
							<section id="first" class="main special">
								<header class="major">
									<h2>個人興趣</h2>
								</header>
								<ul class="features">
									<li>
										<span class="image"><img src="https://upload.wikimedia.org/wikipedia/commons/7/7a/Basketball.png"width="200" alt="" /></span>
										<h3>籃球</h3>
										<p>高強度的訓練鍛鍊爆發力，跟一群朋友一起打也是相當有趣</p>
									</li>
									<li>
										<span class="image"><img src="https://t.pimg.jp/088/686/439/1/88686439.jpg"width="200" alt="" /></span>
										<h3>羽球</h3>
										<p>不間段的跑跑跳跳鍛鍊心肺能力，適合兩到四個朋友一起訓練</p>
									</li>
									<li>
										<span class="image"><img src="https://www.shutterstock.com/image-vector/billiard-black-pool-ball-number-260nw-2495298859.jpg"width="200" alt="" /></span>

										<h3>撞球</h3>
										<p>靜下心擊出每一桿磨練自己的專注與冷靜，修身養性</p>
									</li>
								</ul>
								<footer class="major">
									<ul class="actions special">
										
									</ul>
								</footer>
							</section>

						<!-- Second Section -->
							<section id="second" class="main special">
								<header class="major">
									<h2>學系歷程</h2>
									<p>從大一到大四學習的課程每一科都是對自己的精進，從入門的微積分統計學，到POWERBI，資料庫系統，深度學習，智慧醫療等，每科都能學到不同的東西卻有些許關聯才能讓我在這個科系學到如此多的內容。</p>
								</header>
								<ul class="statistics">
									<li class="style1">
										<span class="icon solid fa-code-branch"></span>
										<strong>R studio</strong> Etiam
									</li>
									<li class="style2">
										<span class="icon fa-folder-open"></span>
										<strong>JAVA</strong> Magna
									</li>
									<li class="style3">
										<span class="icon solid fa-signal"></span>
										<strong>PYTHON</strong> Tempus
									</li>
									<li class="style4">
										<span class="icon solid fa-laptop"></span>
										<strong>POWER BI</strong> Aliquam
									</li>
									<li class="style5">
										<span class="icon fa-gem"></span>
										<strong>SQL</strong> Nullam
									</li>
								</ul>
								<p class="content">不同的程式語言有不同的適用環境根據自己的需求挑選合適的工具。<br>透過學習更多語言認識自己最感興趣的是哪一科並專精。</p>
								<footer class="major">
									<ul class="actions special">
										
									</ul>
								</footer>
							</section>

						<!-- Get Started -->
							<section id="cta" class="main special">
								<header class="major">
									<h2>爬蟲結果</h2>
							

									<p>載入必要套件<br>from selenium import webdriver<br>
from selenium.webdriver.chrome.service import Service<br>
from selenium.webdriver.common.by import By<br>
from selenium.webdriver.common.keys import Keys<br>
import time<br>
from webdriver_manager.chrome import ChromeDriverManager<br>
from selenium.common.exceptions import NoSuchElementException, ElementNotInteractableException
</p>
<span class="image"><img src="https://img.ixintu.com/download/jpg/20200910/1e885ccf87a205b6274de80dd9d47a3f_512_512.jpg!con"width="100" alt="" /></span>


<p># 啟動瀏覽器<br>
driver.get("https://data.taipei/")<br>
driver.maximize_window()</p>

<span class="image"><img src="https://img.ixintu.com/download/jpg/20200910/1e885ccf87a205b6274de80dd9d47a3f_512_512.jpg!con"width="100" alt="" /></span>
<p>
# 迴圈抓多頁<br>
count=0<br>
while count<3:<br>
    time.sleep(2)<br>
    extract_page_data()<br>
    try:<br>
        #next_button = driver.find_element(By.CSS_SELECTOR,'buttom[aria-labe="Next page"]') # Q?<br>
        next_button = driver.find_element(By.CLASS_NAME,'v-pagination__next') # Q?<br>

        if next_button.is_enabled():<br>
            next_button.click()<br>
        else:<br>
            break  # 已經是最後一頁<br>
    except (NoSuchElementException, ElementNotInteractableException):<br>
        break<br>
    count +=1<br>
    #time.sleep(2)<br>

driver.quit()

</p>
<span class="image"><img src="https://img.ixintu.com/download/jpg/20200910/1e885ccf87a205b6274de80dd9d47a3f_512_512.jpg!con"width="100" alt="" /></span>
<p>
# 轉為 DataFrame 並輸出成 CSV<br>
df = pd.DataFrame(data_list)<br>
df.to_csv(r"C:\Users\User\Desktop\411025936\taipei_bus_data.csv", index=False, encoding="utf-8-sig")
</p>

<p>
標題,連結<br>
台北市指定藥癮戒治機構及替代治療機構及非鴉片類藥癮治療補助機構,https://data.taipei/
dataset/detail?id=0e28b90e-3372-4d18-b95e-7dfb4c870a69<br>
臺北市總預算與附屬單位預算及其決算編列情形,https://data.taipei/dataset/detail?
id=0911c648-f273-473a-9e5b-91d0eaf10d60<br>
臺北市都市計畫區人口及面積分區使用情形,https://data.taipei/dataset/detail?id=de85fbe3-
69db-4ddd-b6f6-68ec33ddc656<br>
─臺北市房屋稅稅源 按使用別,https://data.taipei/dataset/detail?id=197605fd-b822-470a-
b582-6bb9750e825b<br>
臺北市藥物檢查暨查獲違法情形,https://data.taipei/dataset/detail?id=852f6c10-dbe7-
445f-9419-816dab3d615d<br>
臺北市實施三七五減租成果,https://data.taipei/dataset/detail?id=7af22551-f55f-49b7-
b1e1-d09edabda462<br>
臺北市查緝經濟犯罪績效統計表,https://data.taipei/dataset/detail?id=6ac52059-2241-
4391-b649-5a2ec9523c33<br>
臺北市實施耕地三七五減租成果統計,https://data.taipei/dataset/detail?id=8a6031bb-88f2-
48b8-84f3-fcb77c59864c<br>
臺北市實施耕地三七五減租成果增減原因,https://data.taipei/dataset/detail?id=616b343e-
e15d-4e0a-97ac-fa0e406ea15e<br>
農林漁牧業普查臺北市概況(59 年至 74 年農林牧),https://data.taipei/dataset/detail?
id=d14a1a8e-acd3-4d4b-99b2-e9e7be62bea9<br>
緊急救護到院前心肺功能停止傷病患統計,https://data.taipei/dataset/detail?id=9c618632-
b143-4c90-bf76-8a7a61510d60<br>
公告臺北市政府最新公共債務情形,https://data.taipei/dataset/detail?id=b1e52a76-319a-
45f0-b029-3e83009406a7<br>
公告臺北市政府自 105 年 1 月起公共債務訊息,https://data.taipei/dataset/detail?
id=c4dd15fc-c828-4985-9469-fd54f0598c25<br>
臺北市地政人員人數異動統計,https://data.taipei/dataset/detail?id=adb5a280-3c12-48be-
888e-c11f0c45922f<br>
臺北市不動產消費爭議案件統計報表,https://data.taipei/dataset/detail?id=861a2ee4-e034-
41f8-ba11-4f62c48ef3be<br>
臺北市歷年性侵害案量統計,https://data.taipei/dataset/detail?id=13bef8d1-8129-4c28-
8750-cd1843830e2d<br>
臺北市直升機起降點點位資料,https://data.taipei/dataset/detail?id=2fe05f49-3007-489d-
993e-1e153c80210d<br>
臺北市生育補助合約醫院,https://data.taipei/dataset/detail?id=9ee72240-f9b3-42a7-
bcbe-e1bb1a28a2dc<br>
臺北市外籍移工人數,https://data.taipei/dataset/detail?id=ad0385fc-2c90-4009-9486-
194689641c93<br>
臺北市政府推介就業服務按就業者職業別(85 年至 104 年),https://data.taipei/dataset/detail?
id=1182dfb1-5bfc-4fd9-9107-976af15b7788<br>
臺北市政府推介就業服務按求職人職業需求別(85 年至 104 年),https://data.taipei/dataset/
detail?id=a800c85a-cd08-43c1-818a-b08e6d6d11d4<br>
人口及住宅普查臺北市概況,https://data.taipei/dataset/detail?id=df84a268-5a2c-4118-
89a6-9cb1ff6469de<br>
臺北市北投垃圾焚化廠營運管理及環境品質監測報告,https://data.taipei/dataset/detail?
id=8e183870-b695-473e-a161-c8e42b4d5aae<br>
臺北市職業安全衛生教育訓練機構,https://data.taipei/dataset/detail?id=94b90fd2-ecb0-
4763-9abb-94ef130a1552<br>
臺北市內湖垃圾焚化廠營運管理及環境品質監測報告,https://data.taipei/dataset/detail?
id=616cc4fa-80fb-431b-bd4d-ca5d83e378dd<br>
臺北市木柵垃圾焚化廠營運管理及環境品質監測報告,https://data.taipei/dataset/detail?
id=e20889a3-5d19-4828-8fc7-d2bc49db7ce8<br>
臺北市停車位數,https://data.taipei/dataset/detail?id=301a7699-75eb-4dff-8f3f-
362984b0581c<br>
臺北市兒童少年保護,https://data.taipei/dataset/detail?id=57f0c628-9e83-4bf0-9099-
15a2eeeee30d<br>
臺北市消防救護服務,https://data.taipei/dataset/detail?id=e48c7436-c5d3-4bd7-9c59-
69d96c45b85e<br>
112 學年度臺北市國民中小學餘裕空間情形一覽表,https://data.taipei/dataset/detail?
id=be069086-f70e-4e5b-a676-6edd614a76ff<br>
</p>
								</header>
								<footer class="major">
									<ul class="actions special">
										
										
									</ul>
								</footer>
							</section>

					</div>

				<!-- Footer -->
					<footer id="footer">
						<section>
							<h2></h2>
							<p></p>
							<ul class="actions">
								
							</ul>
						</section>
						<section>
							<h2>Etiam feugiat</h2>
							<dl class="alt">
								<dt>Phone</dt>
								<dd>(886) xxx-xxx-xxx</dd>
								<dt>Email</dt>
								<dd><a href="#">information@untitled.tld</a></dd>
							</dl>
							<ul class="icons">
								<li><a href="#" class="icon brands fa-twitter alt"><span class="label">Twitter</span></a></li>
								<li><a href="#" class="icon brands fa-facebook-f alt"><span class="label">Facebook</span></a></li>
								<li><a href="#" class="icon brands fa-instagram alt"><span class="label">Instagram</span></a></li>
								<li><a href="#" class="icon brands fa-github alt"><span class="label">GitHub</span></a></li>
								<li><a href="#" class="icon brands fa-dribbble alt"><span class="label">Dribbble</span></a></li>
							</ul>
						</section>
						<p class="copyright">&copy; Untitled. Design: <a href="https://html5up.net">HTML5 UP</a>.</p>
					</footer>

			</div>

		<!-- Scripts -->
			<script src="assets/js/jquery.min.js"></script>
			<script src="assets/js/jquery.scrollex.min.js"></script>
			<script src="assets/js/jquery.scrolly.min.js"></script>
			<script src="assets/js/browser.min.js"></script>
			<script src="assets/js/breakpoints.min.js"></script>
			<script src="assets/js/util.js"></script>
			<script src="assets/js/main.js"></script>

	</body>
</html>
