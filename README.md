# Gridding v1.0

Gridding uses maximum 12 columns and five media breakpoints to build layouts (mobile first layout) 

<b>Instructions:</b><br>

Gridding seperated into two files "grid-wide.css" and "grid-box.css"
Both uses same method to make your site responsive. The only difference is "grid-wide.css" containing the maximum with 1180 pixels and "grid-box" containing the maximum with 1100 pixels. "grid-box.css" is recommended for boxed web page layout

<b>The grid system ( with minimum width ):</b><br>

<ul>
<li>.tm-lg-* ( Desktop screen: 1224px )</li>
<li>.tm-md-* ( Mini-Desktop screen: 1024px )</li>
<li>.tm-sm-* ( Tablet screen: 768px )</li>
<li>.tm-ss-* ( Large-Mobile screen: 480px )</li>
<li>.tm-xs-* ( Small-Mobile screen: 320px )</li>
<li>.tm-xx-* ( Small-Mobile screen: 320px maximum width)</li>
</ul>

<b>CSS selector classes and their width:</b><br>

<ul>
<li>.tm-*-1 = 8.33333333%</li>
<li>.tm-*-2 = 16.66666667%</li>
<li>.tm-*-3 = 25%</li>
<li>.tm-*-4 = 33.33333333%</li>
<li>.tm-*-5 = 41.66666667%</li>
<li>.tm-*-6 = 50%</li>
<li>.tm-*-7 = 58.33333333%</li>
<li>.tm-*-8 = 66.66666667%</li>
<li>.tm-*-9 = 75%</li>
<li>.tm-*-10 = 83.33333333%</li>
<li>.tm-*-11 = 91.66666667%</li>
<li>.tm-*-12 = 100%</li>
</ul>

<b>CSS selector classes for page offset distance from left and right</b><br>

<ul>
<li>.tm-*-edge-1 = 8.33333333%</li>
<li>.tm-*-edge-2 = 16.66666667%</li>
<li>.tm-*-edge-3 = 25%</li>
<li>.tm-*-edge-4 = 33.33333333%</li>
<li>.tm-*-edge-5 = 41.66666667%</li>
<li>.tm-*-edge-6 = 50%</li>
<li>.tm-*-edge-7 = 58.33333333%</li>
<li>.tm-*-edge-8 = 66.66666667%</li>
<li>.tm-*-edge-9 = 75%</li>
<li>.tm-*-edge-10 = 83.33333333%</li>
<li>.tm-*-edge-11 = 91.66666667%</li>
<li>.tm-*-edge-12 = 100%</li>
</ul>

<b>Make something hidden or visible in defferent width</b><br>
<ul>
<li>To hide: .hide-*</li>
<li>To show: .show-*</li>
</ul>

For example: <br>
Hide on desktop device: <code>&lt;nav class="hide-lg"&gt;&lt;/nav&gt;</code><br>
Show on mobile device: <code>&lt;nav class="show-xs"&gt;&lt;/nav&gt;</code> ( By default the &lt;nav&gt; element will show on mobile without "show-xs" )

<b>Make clearfix before and after element using " .fix "</b><br>
For example: <br>
    <code>&lt;div class="fix"&gt; </code> <br> 
        &nbsp;&nbsp;<code>&lt;p style="float:left;"&gt;This is a floating text inside div&lt;/p&gt;</code> <br> 
    <code>&lt;/div&gt;</code><br>
    </code>
  
<b>For circles use " .circle "</b><br>
<b>To hide, use "  .hide "</b>

Enjoy !
