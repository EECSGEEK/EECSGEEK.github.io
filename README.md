<title>吴翱翔的博客</title>
<h1>吴翱翔的博客</h1>
<h2>文章列表</h2>
<h3>
	<a href="DIP-final-exam.html">数字图像处理期末考范围</a>
	<br />
	<a href="scrap-ocw-mp4.html">爬取交大「机器人学」全部视频地址</a>
	<br />
	<a href="computer-tricks.html">电脑小技巧【持续更新】</a>
</h3>
<h2>个人技能</h2>
<h4>别问我所获奖项，我参加比赛从来没过奖</h4>
<h3>技能.网页.JavaScript</h3>
<h3>网页搞得还是很烂，就像这个网站一样(这水平怎么当前端狗)</h3>
<img src="https://i.loli.net/2017/12/02/5a228738abe45.jpg" alt="cert-1024-4688288.jpg" title="cert-1024-4688288.jpg" />
<h3>技能.编程.Python(我的主力编程语言)</h3>
<img src="https://i.loli.net/2017/12/02/5a2287fbc7d43.jpg" alt="cert-1073-4688288.jpg" title="cert-1073-4688288.jpg" />
<h3>技能.编程.C++</h3>
<h4>(学C++是为了研究单片机程序,好像只有Arduino是用C++语法的)</h4>
<img src="https://i.loli.net/2017/12/02/5a2288673254b.jpg" alt="cert-1051-4688288.jpg" title="cert-1051-4688288.jpg" />
<h2>其它</h2>
<h3>
	<a href="https://github.com/EECSGEEK/EECSGEEK.github.io">网站源代码</a>
</h3>
<h4>网站的时间信息</h4>
<button onclick="lastModifiedTime()">点击显示俺上次提交更新博客的时间</button>
<p id="print_lastModified">
	<br />
</p>
<button onclick="copyToClipboard('print_lastModified')">Copy Timestamp</button>

<h5>Copyright&copy;2017 China </h5>

<!-- 脚本一般放在head或body最下面，加载顺序最好是HTML->CSS->JS
  This can improve page load, because HTML display is not blocked by scripts loading
-->
<script>
	function copyToClipboard(elementId) {
		var aux = document.createElement("input");
		aux.setAttribute("value", document.getElementById(elementId).innerHTML);
		document.body.appendChild(aux);
		aux.select();
		document.execCommand("copy");
		document.body.removeChild(aux);
	}

	function lastModifiedTime() {
		document.getElementById("print_lastModified").innerHTML = (document.lastModified);
	}
</script>