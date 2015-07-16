# myelinSlider
jquery slider plugin

# Code
```html
<div class="banner">
<ul class="m_banner_con">
  <li><a href="#" id="mb01" style="display:"><img src="1.jpg"></a></li>
  <li><a href="#" id="mb02" style="display:none"><img src="2.jpg"></a></li>
  <li><a href="#" id="mb03" style="display:none"><img src="3.jpg"></a></li>
  <li><a href="#" id="mb04" style="display:none"><img src="4.jpg"></a></li>
  <li><a href="#" id="mb05" style="display:none"><img src="5.jpg"></a></li>
</ul>
<ul class="m_banner_txt">
  <li><a href="#" class="mb01">Image01</a></li>
  <li><a href="#" class="mb02">Image02</a></li>
  <li><a href="#" class="mb03">Image03</a></li>
  <li><a href="#" class="mb04">Image04</a></li>
  <li><a href="#" class="mb05">Image05</a></li>
</ul>
</div>
```
``` css
.banner {
  overflow: hidden;
  width: 708px;
  height: 272px;
  margin: 250px auto 0;
  background: #FFF;
  border: 1px solid #ccc;
}
.banner ul.m_banner_con { float: left; }
.banner ul.m_banner_txt {
  float: right;
  text-align: left;
  width: 192px;
}
.banner ul.m_banner_txt > li {
  padding-left: 23px;
  padding-right: 1px;
  border-bottom: 1px solid #e3e5e6;
  line-height: 33px;
}
.banner ul.m_banner_txt > li:last-child { border-bottom: 0px; }
.banner ul.m_banner_txt > li.on {
  background: url(../img/icon_bullet.png) no-repeat 5px center;
  font-weight: bold;
}
```
```javascript
<script src="//code.jquery.com/jquery-1.11.2.min.js"></script>
<script src="path/to/jquery.myelinSilder.js"></script>
<script>
$('.banner').myelinSlider({
	mode : 'fade',
	item : 5,
	direction : 'down',
	// auto play
	auto : false,
	// transition speed
	speed : 3000
	});
</script>
```

# Sample
http://mokgoon.github.io/myelinSlider/demos/demo.html

#link 
http://www.jqueryscript.net/slider/Tiny-jQuery-Image-Slider-With-Side-Navigation-myelinSlider.html
