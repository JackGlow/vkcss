# VK CSS. Styling Guide

NavBar

```html
<div class="vkui_nav">
	<div class="navcon"> <!-- Container -->
		<span class="vkui_logo"></span> <!-- you can remove it -->
    <!-- your content here -->
		<input class="text ts_input" autocomplete="off" aria-label="Search" placeholder="Search" type="text"> <!-- Search Box -->
	</div>
</div>
```

### Buttons

```html
Primary Button:
<button class="flat_button">Primary Button</button>
Disabled Loading: <button class="flat_button button_lock button_disabled" disabled style="width: 128px;">&nbsp;</button>
Disabled Button: <button class="flat_button button_disabled">Disabled Button</button>
Secondary Button: <button class="flat_button secondary">Secondary Button</button>
Green Button: <button class="flat_button  ij_button">Green Button (IJ)</button>
Big Button: <button class="flat_button button_big_text">Big Button</button>
Link Button: <a href="#" onclick="return false;">Button Link</a>

```

### Post Element

```html
<div class="page_block" style="padding: 14px; width: 78%; margin: 0 auto;"> <!-- Container -->
	<img src="https://pp.userapi.com/c845121/v845121815/102b10/kASG1Fmhd9w.jpg?ava=1" class="vk_ava"> <!-- class "vk_ava" rounds and adds float to image -->
		<a href="#" class="post_author">User User</a><br> <!-- username -->
		<span class="post_date">today at 6:00 am</span> <!-- date -->

		<p>I love VKontakte and [id1|founder of this social network]!</p> <!-- content -->
		<p><input type="text" class="vk_input" placeholder="Leave your feedback..."> <button class="flat_button">Submit</button></p>
</div>
</p>

```

### Alerts

```html
<div class="page_block" style="padding: 14px; width: 78%; margin: 0 auto;">
	<h1>Alerts</h1>
<!-- Success -->	<div class="msg ok_msg"><div class="msg_text"><b>Changes saved.</b><br>Your profile has been successfully updated.</div></div>

<!-- Error -->	<div class="msg error"><div class="msg_text"><b>Changes update failed.</b><br>Your profile has been successfully updated.</div></div>

<!-- Info -->	<div class="msg info_msg"><div class="msg_text"><b>Changes saved.</b><br>Your profile has been successfully updated.</div></div>
<!-- NoIco -->	<div class="msg"><div class="msg_text"><b>Changes saved.</b><br>Your profile has been successfully updated.</div></div>
</div>
```
