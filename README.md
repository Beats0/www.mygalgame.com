# www.mygalgame.com
#### 代码替换中......
* [http替换](#http替换)
* [验证删除](#验证删除)
* [配置替换](#配置替换)
    * [1. Audio](#1-audio)
    * [2. css](#2-css)
    * [3. highslide](#3-highslide)
    * [4. images](#4-images)
    * [5. js](#5-js)
    * [6. page](#6-page)
    * [7. tag](#7-tag)
* [其他替换](#其他替换)
* [删除](#删除)

#### http替换
```
https://www.mygalgame.com
```
替换为：
```
https://beats0.github.io/www.mygalgame.com
```

#### 验证删除
```
<script type="text/javascript">/* <![CDATA[ */var favorites_data = {"ajaxurl":"https:\/\/www.mygalgame.com\/wp-admin\/admin-ajax.php","nonce":"06934cc10f","favorite":"\u6536\u85cf\u6587\u7ae0 <i class=\"sf-icon-star-empty\"><\/i>","favorited":"\u53d6\u6d88\u6536\u85cf <i class=\"sf-icon-star-full\"><\/i>","includecount":"1","indicate_loading":"","loading_text":"Loading","loading_image":"<img src=\"https:\/\/www.mygalgame.com\/wp-content\/plugins\/favorites\/assets\/images\/loading.gif\" class=\"simplefavorites-loading\" aria-hidden=\"true\" \/>","loading_image_active":"<img src=\"https:\/\/www.mygalgame.com\/wp-content\/plugins\/favorites\/assets\/images\/loading.gif\" class=\"simplefavorites-loading\" aria-hidden=\"true\" \/>","loading_image_preload":"","cache_enabled":"1","button_options":{"button_type":"custom","custom_colors":false,"box_shadow":false,"include_count":true,"default":{"background_default":false,"border_default":false,"text_default":false,"icon_default":false,"count_default":false},"active":{"background_active":false,"border_active":false,"text_active":false,"icon_active":false,"count_active":false}},"authentication_modal_content":"<p>Please login to add favorites.<\/p><p><a href=\"#\" data-favorites-modal-close>Dismiss this notice<\/a><\/p>","authentication_redirect":"","dev_mode":"","logged_in":"1","user_id":"53889","authentication_redirect_url":"https:\/\/www.mygalgame.com\/wp-login.php"};/* ]]> */</script>
```

#### 配置替换
```
wwww.galgame.com：
├─Audio
├─css
├─highslide
│       └─graphics
├─images
│       └─menu
├─js
├─page
└─tag
```

##### 1. Audio
```
https://www.mygalgame.com/wp-content/themes/mygalgame/ui/audio/oni.mp3
```
替换为：
```
https://beats0.github.io/www.mygalgame.com/Audio/oni.mp3
```

##### 2. css
1.
style.css 与 CDN.Bootstrap
```
<link rel='stylesheet' id='bootstrap-style-css' href='https://www.mygalgame.com/wp-content/themes/mygalgame/ui/css/bootstrap.css?ver=1.0.1' type='text/css' media='all' />
```
替换为：
```
<link rel='stylesheet' id='bootstrap-style-css' href='https://beats0.github.io/www.mygalgame.com/css/style.css' type='text/css' media='all' />
<link rel="stylesheet" type="text/css" href="https://cdn.bootcss.com/font-awesome/4.7.0/css/font-awesome.min.css">
```
2.
UI-Bootstrap-v-1.0.css
```
https://www.mygalgame.com/wp-content/themes/mygalgame/ui/css/bootstrap.css?ver=1.0.1
```
替换为：
```
https://beats0.github.io/www.mygalgame.com/css/UI-Bootstrap-v-1.0.css
```
3.
font-awesome.min.css
```
https://www.mygalgame.com/wp-content/themes/mygalgame/ui/font-awesome/css/font-awesome.min.css?ver=4.0.1
```
替换为：
```
https://cdn.bootcss.com/font-awesome/4.7.0/css/font-awesome.min.css
```
4.
myblog.css
```
https://www.mygalgame.com/wp-content/themes/mygalgame/ui/css/myblog.css?ver=1.0.25
```
替换为：
```
https://beats0.github.io/www.mygalgame.com/css/myblog.css
```

##### 3. highslide
1.
highslide.css
```
https://www.mygalgame.com/wp-content/themes/mygalgame/highslide/highslide.css
```
替换为：
```
https://beats0.github.io/www.mygalgame.com//highslide/highslide.css
```
2.
highslide.js
```
https://www.mygalgame.com/wp-content/themes/mygalgame/highslide/highslide.js
```
替换为：
```
https://beats0.github.io/www.mygalgame.com/highslide/highslide.js
```

##### 4. images
smilies
```
https://www.mygalgame.com/wp-content/themes/mygalgame/ui/images/smilies
```
替换为：
```
https://beats0.github.io/www.mygalgame.com/images/smilies
```


##### 5. js
1.
jquery=1.12.4.js
```
https://www.mygalgame.com/wp-includes/js/jquery/jquery.js?ver=1.12.4
```
替换为：
```
https://beats0.github.io/www.mygalgame.com/js/jquery=1.12.4.js
```
2.
jquery-migrate.min=1.4.1.js
```
https://www.mygalgame.com/wp-includes/js/jquery/jquery-migrate.min.js?ver=1.4.1
```
替换为：
```
https://beats0.github.io/www.mygalgame.com/js/jquery-migrate.min=1.4.1.js
```
3.
jquery.cookie.js=17.7.js
```
https://www.mygalgame.com/wp-content/plugins/advanced-browser-check/js/jquery.cookie.js?ver=17.7
```
替换为：
```
https://beats0.github.io/www.mygalgame.com/js/jquery.cookie.js=17.7.js
```
4.
script=17.7.js
```
https://www.mygalgame.com/wp-content/plugins/advanced-browser-check/js/script.js?ver=17.7
```
替换为：
```
https://beats0.github.io/www.mygalgame.com/js/script=17.7.js
```
5.
bootstrap=1.0.1.js
```
https://www.mygalgame.com/wp-content/themes/mygalgame/ui/js/bootstrap.js?ver=1.0.1
```
替换为：
```
https://beats0.github.io/www.mygalgame.com/js/bootstrap=1.0.1.js
```
6.
jquery.icheck=1.0.1.js
```
https://www.mygalgame.com/wp-content/themes/mygalgame/ui/js/jquery.icheck.js?ver=1.0.1
```
替换为：
```
https://beats0.github.io/www.mygalgame.com/js/jquery.icheck=1.0.1.js
```
7.
jquery.validate=1.9.0.js
```
https://www.mygalgame.com/wp-content/themes/mygalgame/ui/js/jquery.validate.js?ver=1.9.0
```
替换为：
```
https://beats0.github.io/www.mygalgame.com/js/jquery.validate=1.9.0.js
```
8.
jquery.lazyload.min=1.9.3.js
```
https://www.mygalgame.com/wp-content/themes/mygalgame/ui/js/jquery.lazyload.min.js?ver=1.9.3
```
替换为：
```
https://beats0.github.io/www.mygalgame.com/js/jquery.lazyload.min=1.9.3.js
```
9.
myblog=2.0.2.js
```
https://www.mygalgame.com/wp-content/themes/mygalgame/ui/js/myblog.js?ver=2.0.2
```
替换为：
```
https://beats0.github.io/www.mygalgame.com/js/myblog=2.0.2.js
```
10.
favorites.min=2.1.6.js
```
https://www.mygalgame.com/wp-content/plugins/favorites/assets/js/favorites.min.js?ver=2.1.6
```
替换为：
```
https://beats0.github.io/www.mygalgame.com/js/favorites.min=2.1.6.js
```
11.
favorites.min=2.1.6.js
```
https://www.mygalgame.com/wp-content/plugins/favorites/assets/js/favorites.min.js?ver=2.1.6
```
替换为：
```
https://beats0.github.io/www.mygalgame.com/js/favorites.min=2.1.6.js
```
12.
myblog_bd=1.0.3.js
```
https://www.mygalgame.com/wp-content/themes/mygalgame/ui/js/myblog_bd.js?ver=1.0.3
```
替换为：
```
https://beats0.github.io/www.mygalgame.com/js/myblog_bd=1.0.3.js
```
13.
myblog_min=1.1.1.js
```
https://www.mygalgame.com/wp-content/themes/mygalgame/ui/js/myblog_min.js?ver=1.1.1
```
替换为：
```
https://beats0.github.io/www.mygalgame.com/js/myblog_min=1.1.1.js
```

##### 6. page
##### 7. tag

#### 其他替换


##### 删除
1.
ajax
```
"ajaxurl": "https:\/\/www.mygalgame.com\/wp-admin\/admin-ajax.php",
```
```
"loading_image": "<img src=\"https:\/\/www.mygalgame.com\/wp-content\/plugins\/favorites\/assets\/images\/loading.gif\" class=\"simplefavorites-loading\" aria-hidden=\"true\" \/>",
```
```
"loading_image_active": "<img src=\"https:\/\/www.mygalgame.com\/wp-content\/plugins\/favorites\/assets\/images\/loading.gif\" class=\"simplefavorites-loading\" aria-hidden=\"true\" \/>",
```
```
"authentication_redirect_url": "https:\/\/www.mygalgame.com\/wp-login.php"
```
```
<div class='advanced-browser-check' style='display:none;'data-url='{"abc_url":"https:\/\/www.mygalgame.com\/wp-admin\/admin-ajax.php"}'></div>
```
2.


