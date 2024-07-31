# How to highlight the code using prism.js

Procedure:
1. Copy and paste the given CSS link below the <title>...</title> tag in your HTML theme source code. You can either copy the link from here or you can copy it from the official website www.https://prismjs.com/.

	    <link href='https://cdn.jsdelivr.net/gh/CDNSFree/PrismJS@latest/prism.min.css' rel='stylesheet'/>
2. Copy and paste the given Javascript link above the closing </body> tag in your HTML theme source code (open your blog dashboard-->click on theme-->then select "edit HTML" from the customise dropdown-menu-->here you can either search for the given tag by pressing ctrl + F buttton or directly look at the top most of the page to find the title tag and down most to find the clossing body tag).

	    <script src='https://cdn.jsdelivr.net/gh/CDNSFree/PrismJS@latest/prism.min.js'/>
3. Now insert your code in between <pre><code>...</code></pre> tags like this. Remember you have to do this step inside your blog post and write your blog post in HTML view. Another thing to remember is that always provide code tag a language class (<code class = "language-html">)or it will not execute in the expected manner.
      

        <pre>
            <code class = "language-html">
                //your codes here.....
       	    </code>
        </pre>        
      

      
The "html" inside class = "language-html" can be changed according to the code you want to display like markup, javascript, python, PHP, CSS, and etc. Check out the official website for more information.
Now you are ready to show your code in a nice clean and formatted manner. But do keep in mind that while working with special symbols like < and > in HTML, first convert them into their HTML entities or it will be executed and you will node be able to see your code.
Plugins:
To show line numbers, add a class called "line-numbers" to the pre-tag. Remember line-numbers plugin only works with blocks or whole body if you will use this plugin in inline-block elements it will not.
        

        <pre class = "line-numbers">
       	    <code class = "language-html">
                //your codes here.....
       	    </code>
		</pre>    
        
        
Themes:
Theme: Default

      <link rel="stylesheet" href="http://prismjs.com/themes/prism.css"/>
      
Theme: Dark

      <link rel="stylesheet" href="http://prismjs.com/themes/prism-dark.css"/>
      
Theme: Funky

      <link rel="stylesheet" href="http://prismjs.com/themes/prism-funky.css"/>
      
Theme: Okaidia

      <link rel="stylesheet" href="http://prismjs.com/themes/prism-okaidia.css"/>
      
Theme: Twilight

      <link rel="stylesheet" href="http://prismjs.com/themes/prism-twilight.css"/>
      
Theme: Coy

      <link rel="stylesheet" href="http://prismjs.com/themes/prism-coy.css"/>
      
Theme: Solarizedlight

      <link rel="stylesheet" href="http://prismjs.com/themes/prism-solarizedlight.css"/>
      
Theme: Tomorrownight      

      <link rel="stylesheet" href="http://prismjs.com/themes/prism-tomorrownight.css"/>
      

JavaScript file for themes: 

        <script type='text/javascript' src="http://prismjs.com/prism.js"></script>
  
