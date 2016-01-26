# magento_training
```
http://connect20.magentocommerce.com/community/Mage_Locale_es_ES
<link href='https://fonts.googleapis.com/css?family=Montserrat' rel='stylesheet' type='text/css'>
http://connect20.magentocommerce.com/community/HelloWired_Free_Theme_1_4
```

```
<!--Image Slider Start-->
<div id="static-slide-home"><img alt="" /></div>
<script type="text/javascript">// <![CDATA[
var image1=new Image()
image1.src="{{skin url=images/media/slide1.jpg}}"
var image2=new Image()
image2.src="{{skin url=images/media/slide2.jpg}}"
var image3=new Image()
image3.src="{{skin url=images/media/slide3.jpg}}"
// ]]></script>
<script type="text/javascript">// <![CDATA[
//variable that will increment through the images
var step=1
function slideit(){
//if browser does not support the image object, exit.
if (!document.images)
return
jQuery('#static-slide-home img').attr('src', eval("image"+step+".src"))
if (step<3)
step++
else
step=1
//call function "slideit()" every 2.5 seconds
setTimeout("slideit()",5000)
}
slideit()
// ]]></script>
<!--Image Slider End-->
```
