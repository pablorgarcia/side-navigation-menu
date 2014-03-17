<h1>Side Navigation Menu</h1>

<p>CSS3 transition property & without JS.</p>
<a href="http://codepen.io/PableraShow/pen/HdJtv" target="_blank">Check out the demo page</a>.

<h2>How it works</h2>

<p>We have a &lt;nav&gt; tag on the left of the screen with <code>position: fixed;</code>, a width and a fixed height.</p>
<p>Then we have a list with &lt;svg&gt; images and hidden links with <code>display: none;</code>, when we do a <code>:hover</code> over &lt;nav&gt; tag we added more <code>with</code> to the &lt;nav&gt; and a <code>display: block;</code> so that the links appear.</p>

<p>Finally, we have to write on the &lt;nav&gt; tag the CSS3 <code>transition</code> property:</p>
<pre>
nav{
  transition-delay: 0s;
  transition-duration: 0.4s;
  transition-property: all;
  transition-timing-function: line;
  }
</pre>


<h2>Download, Fork, Commit.</h2>

<p>If you think you can make this better, please Download, Fork, &amp; Commit. I'd love to see your ideas.</p>

<h2>License</h2>

<p>You should add this comment to the beginning of the CSS code of this plugin:
<pre>
/*	
	Side Navigation Menu
	===================
	License:
	http://goo.gl/KC3XXj
	===================
	Author: @PableraShow

*/
</pre>
And add another comment when finish the CSS code plugin:
<pre>
/*	
	End of the Side Navigation Menu
	===================
	Author: @PableraShow

*/
</pre></p>

===================

<a href="http://pablogarciafernandez.com" title="Pablo García Fernández" target="_blank">Pablo García Fernández</a>
