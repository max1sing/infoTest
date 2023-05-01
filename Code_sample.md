<h1 id="code-sample">Code Sample</h1>
<h1 id="this-code-sample-was-written-by-me">This code sample was written by me</h1>
<p>def cone_numbers():
    &quot;&quot;&quot;
    This function multiplies by pi and radius, and divides height by 3
    &quot;&quot;&quot;</p>
<pre><code><span class="hljs-comment">#prompt the user for the numbers</span>
number1 = <span class="hljs-built_in">float</span>(input(<span class="hljs-string">"Please enter the radius of the cone: "</span>))
number2 = <span class="hljs-built_in">float</span>(input(<span class="hljs-string">"Please enter the height of the cone: "</span>))
number3 = <span class="hljs-number">3</span>.<span class="hljs-number">14159265359</span>
<span class="hljs-comment"># calculate the numbers to make the cone</span>
<span class="hljs-literal">result</span> = number3 * number1 * number1 * number2 / <span class="hljs-number">3</span>

<span class="hljs-keyword">return</span> <span class="hljs-literal">result</span>
</code></pre><p>def cube_numbers():
    &quot;&quot;&quot;
    This function multiplies the length of the cube
    &quot;&quot;&quot;</p>
<pre><code><span class="hljs-comment">#prompt the user for the number</span>
number1 = <span class="hljs-built_in">float</span>(input(<span class="hljs-string">"Please enter the length of the cube: "</span>))

<span class="hljs-comment"># calculate the numbers to make the cube</span>
<span class="hljs-literal">result</span> = number1 * number1 * number1

<span class="hljs-keyword">return</span> <span class="hljs-literal">result</span>
</code></pre><p>def cylinder_numbers():
    &quot;&quot;&quot;
    This function multiplies the radius, height, and pi
    &quot;&quot;&quot;</p>
<pre><code><span class="hljs-comment">#prompt the user for two numbers</span>
number1 = <span class="hljs-built_in">float</span>(input(<span class="hljs-string">"Please enter the radius of the cylinder: "</span>))
number2 = <span class="hljs-built_in">float</span>(input(<span class="hljs-string">"Please enter the height of the cylinder: "</span>))
number3 = <span class="hljs-number">3</span>.<span class="hljs-number">14159265359</span>
<span class="hljs-comment"># calculate the numbers to make a cylinder</span>
<span class="hljs-literal">result</span> = number3 * number1 * number1 * number2

<span class="hljs-keyword">return</span> <span class="hljs-literal">result</span>
</code></pre><h1 id="print-a-menu-for-the-user">print a menu for the user</h1>
<p>print(&quot;Choose an option below&quot;)
print(&quot;1. Calculate volume of a cone&quot;)
print(&quot;2. Calculate volume of a cube&quot;)
print(&quot;3. Calculate volume of a cylinder&quot;)</p>
<h1 id="get-the-user-s-menu-choice">get the user&#39;s menu choice</h1>
<p>print()
user_choice = input(&quot;Enter your menu choice: &quot;)</p>
<h1 id="call-the-function-and-get-the-result">call the function and get the result</h1>
<p>if (user_choice == &quot;1&quot;):
    total = cone_numbers()
elif(user_choice == &quot;2&quot;):
    total = cube_numbers()
elif(user_choice == &quot;3&quot;):
    total = cylinder_numbers()
else:
    print(&quot;Error: You entered a horrific value, goodbye!&quot;)
    exit()</p>
<p>#print the result<br>print()
print(&quot;The result is: &quot; + str(total))</p>
<p><a href="./README.md">return to home page</a></p>
