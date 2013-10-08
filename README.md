<h1>Side Navigation Menu</h1>

<p>CSS3 transition technology & without JS.</p>
<a href="http://www.pablogarciafernandez.com/lab/demo/side-navigation-menu.html" target="_blank">Check out the demo page</a>.

<h2>How it works</h2>

<p>We have a &lt;nav&gt; label on the left of the screen with <code>position: fixed;</code>, a width and a fixed height.</p>
<p>Then we have a list with &lt;svg&gt; images and hidden links with  <code>display: none;</code>, when we do a <code>:hover</code> over &lt;nav&gt; label we added more <code>with</code> to the &lt;nav&gt; and a <code>display: block;</code> so that the links appear.</p>

<p>Finally, we have to write on the &lt;nav&gt; label the CSS3 <code>transition</code> property:</p>
<pre>
nav{
  transition-delay: 0s;
  transition-duration: 0.4s;
  transition-property: all;
  transition-timing-function: line;
  }
</pre>


<h2>Download, Fork, Commit.</h2>

<p>If you think you can make this better, please Download, Fork, & Commit. I'd love to see your ideas.</p>

<a href="http://www.pablogarciafernandez.com/lab/side-navigation-menu.html" target="_blank">Code on official site</a>

<a href="http://codepen.io/PableraShow/pen/HdJtv" target="_blank">Code on CodePen</a>

===================

<a href="http://pablogarciafernandez.com" title="Pablo García Fernández" target="_blank">Pablo García Fernández</a>
