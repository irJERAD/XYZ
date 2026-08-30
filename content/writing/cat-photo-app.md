---
title: "Cat Photo App"
date: 2016-06-17
tags: ["html", "css", "front-end", "development"]
summary: "A small front-end development exercise from freeCodeCamp, built around HTML, CSS, and a delightfully direct cat-photo premise."
---

<p>A Cat Photo App page made while going through some front end development exercises at <a href="https://freecodecamp.com">freeCodeCamp</a></p>
<h4>Version using Kitty ipsum text</h4>
<p>&lt;link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css"&gt; &lt;style&gt; .red-text { color: red; }</p>
<p>h2 { font-family: Lobster, Monospace; }</p>
<p>p { font-size: 16px; font-family: Monospace; }</p>
<p>&lt;!-- .iphone-outline { border-color: black; border-width: 50px; width: 337px; height: 667px; } --&gt;</p>
<p>.thick-green-border { border-color: green; border-width: 10px; border-style: solid; border-radius: 50%; }</p>
<p>.smaller-image { width: 100px; } &lt;/style&gt; &lt;!-- &lt;div class ="iphone-outline"&gt; --&gt; &lt;h2 class="red-text"&gt;CatPhotoApp&lt;/h2&gt;</p>
<p>&lt;p&gt;Click here for &lt;a href="#"&gt;cat photos&lt;/a&gt;.&lt;/p&gt;</p>
<p>&lt;a href="#"&gt;&lt;img class="smaller-image thick-green-border" alt="A cute orange cat lying on its back" src="https://bit.ly/fcc-relaxing-cat"&gt;&lt;/a&gt;</p>
<p>&lt;p class="red-text"&gt;Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.&lt;/p&gt; &lt;p class="red-text"&gt;Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.&lt;/p&gt; &lt;!-- &lt;/div&gt; --&gt;</p>
<hr />
<h4>Cat lists and forms</h4>
<p>&lt;link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css"&gt; &lt;style&gt; .red-text { color: red; }</p>
<p>h2 { font-family: Lobster, Monospace; }</p>
<p>p { font-size: 16px; font-family: Monospace; }</p>
<p>.thick-green-border { border-color: green; border-width: 10px; border-style: solid; border-radius: 50%; }</p>
<p>.smaller-image { width: 100px; }</p>
<p>.gray-background { background-color: gray; }</p>
<p>#cat-photo-form { background-color: green; } &lt;/style&gt;</p>
<p>&lt;h2 class="red-text"&gt;CatPhotoApp&lt;/h2&gt;</p>
<p>&lt;p&gt;Click here for &lt;a href="#"&gt;cat photos&lt;/a&gt;.&lt;/p&gt;</p>
<p>&lt;a href="#"&gt;&lt;img class="smaller-image thick-green-border" alt="A cute orange cat lying on its back" src="https://bit.ly/fcc-relaxing-cat"&gt;&lt;/a&gt;</p>
<p>&lt;div&gt; &lt;p&gt;Things cats love:&lt;/p&gt; &lt;ul&gt; &lt;li&gt;cat nip&lt;/li&gt; &lt;li&gt;laser pointers&lt;/li&gt; &lt;li&gt;lasagna&lt;/li&gt; &lt;/ul&gt; &lt;p&gt;Top 3 things cats hate:&lt;/p&gt; &lt;ol&gt; &lt;li&gt;flea treatment&lt;/li&gt; &lt;li&gt;thunder&lt;/li&gt; &lt;li&gt;other cats&lt;/li&gt; &lt;/ol&gt; &lt;/div&gt;</p>
<p>&lt;form action="/submit-cat-photo" id="cat-photo-form"&gt; &lt;label&gt;&lt;input type="radio" name="indoor-outdoor" checked&gt; Indoor&lt;/label&gt; &lt;label&gt;&lt;input type="radio" name="indoor-outdoor"&gt; Outdoor&lt;/label&gt; &lt;label&gt;&lt;input type="checkbox" name="personality" checked&gt; Loving&lt;/label&gt; &lt;label&gt;&lt;input type="checkbox" name="personality"&gt; Lazy&lt;/label&gt; &lt;label&gt;&lt;input type="checkbox" name="personality"&gt; Energetic&lt;/label&gt; &lt;input type="text" placeholder="cat photo URL" required&gt; &lt;button type="submit"&gt;Submit&lt;/button&gt; &lt;/form&gt;</p>
