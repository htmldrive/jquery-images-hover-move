Image Hover Move- simple and practical navigation or featured image jQuery plugin
=======================

[![Image Hover Move- simple and practical navigation or featured image jQuery plugin](http://www.htmldrive.net/media/2010/9/19/1284901071.jpg "Image Hover Move- simple and practical navigation or featured image jQuery plugin")](http://www.htmldrive.net/items/demo/605/Image-Hover-Move-simple-and-practical-navigation-or-featured-image-jQuery-plugin "Image Hover Move- simple and practical navigation or featured image jQuery plugin")

[**Demo**](http://www.htmldrive.net/items/demo/605/Image-Hover-Move-simple-and-practical-navigation-or-featured-image-jQuery-plugin "Image Hover Move- simple and practical navigation or featured image jQuery plugin")

##Usage
**Include js and css files.**

    <link href="css/images_hover_move.css" rel="stylesheet" type="text/css" />
    <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.7.2/jquery.min.js"></script>
    <script src="js/images_hover_move.js"></script>
  
**Add html.**

    <div id="images_hover_move" class="images_hover_move">
        <ul>
            <li><a href="#"><img src="images/001.jpg" title="title1" /></a></li>
            <li><a href="#"><img src="images/003.jpg" title="title2" /></a></li>
            <li><a href="#"><img src="images/004.jpg" title="title3" /></a></li>
            <li><a href="#"><img src="images/006.jpg" title="title4" /></a></li>
        </ul>
    </div>
        
**Add startup script.**

    <script language="javascript" type="text/javascript">
        $(function() {
            $("#images_hover_move").images_hover_move({
                window_width: '600',
                window_height: '250',
                border_color: '#999',
                title_color: '#333',
                title_background_color: '#CCC',
                background_color: '#f5f5f5'
            });
        });
    </script>