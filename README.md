# JS -Oscar-meal-counter

<p>If you ever had troubles with stocking provision for an amount of time, this is useful tool. This example count how many portion of your favorite food you will have until you think you’ll leave this world.</p>

<p>I invite you to see how it works on: <a href="https://negrut112.github.io/JS-meal-counter/">https://negrut112.github.io/JS-meal-counter/</a><br>
  
<img src="https://i.imgur.com/idyNDOC.jpg">

## JavaScript

<p>On JS I made a <b>function</b> that is asking information stored in <b>variables</b> that will <b>alert</b> a message with the quantity of specific food until the specified age.</p>

<p>The quantity of need is calculated with the folowing formula using stored variables:</p>

<i>(enddate -age)<em>quantity</em>52;</i>

<pre><code>function oscarTheLifetimeSupplier(){<br>
var age=prompt(‘How old are you?’);<br>
var enddate=prompt(‘At what age do you think you will leave from this world?’);<br>
var food=prompt(‘What’s your favorite meal’);<br>
var quantity=prompt(‘How much of your favorite meal you eat per week?’);<br>
var quantityneed =(enddate -age)<em>quantity</em>52;<br>
alert(‘You will need ‘+quantityneed+’ of ‘+food+’ until ‘+enddate+’ years old’);<br>
return;}<br>
oscarTheLifetimeSupplier();</code></pre>
