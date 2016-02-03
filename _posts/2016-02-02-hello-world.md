---
layout: base
title: 你好，世界
link: article.css
---
<section class="content">
	<div class="article sticker-pink">
		<h1>{{ page.title }}</h1>
		<p>我的第一篇文章</p>
		<p>PKC是猪猪猪</p>
		<p>{{ page.date | date_to_string }}</p>
	</div>
</section>