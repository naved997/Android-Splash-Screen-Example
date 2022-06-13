# Android-Splash-Screen-Example
<h4>This is a simple example for Android Splash Screen.</h4>

<h3>Splash Screen</h3>
<p>A Splash Screen is a introductory screen which is a first startup screen and appears when application opened. It is also appears when application fetches the relevant content such as Network Calls and Database.</p>


<h3>Use of Splash Screen</h3>
<ol>
<li>It is used to beautify and animate startup screen for an application.</li>
  <li>It is used to load Network Calls and Database in background.</li>
</ol>

<h3>Concept</h3>
<p>
<pre>
new Handler().postDelayed(new Runnable() {<br>
  @Override<br>
  public void run() {<br>
  Intent i=new Intent(MainActivity.this,Home.class);<br>
  startActivity(i);<br>
  finish();<br>
  }<br>
  },5000);<br>
  </pre>
</p>
<br>
<br>
<br>

<div class="row">

<img src="https://user-images.githubusercontent.com/42957042/173415781-8529442d-50b6-4f6f-85aa-14ebed768f4c.png" width=200px/>
&nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp
<img src="https://user-images.githubusercontent.com/42957042/173415793-f8a00eb9-8bce-4ab5-8b75-83593859d851.png" width=200px/>

</div>

<br>
<br>

<hr>

<a href="https://www.flaticon.com/free-icons/splash" title="Splash icons" align="justify"> <sup>Splash icons created by AbtoCreative - Flaticon</sup> </a>
