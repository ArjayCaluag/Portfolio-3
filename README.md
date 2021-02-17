# **Updated Portfolio**

For this portfolio assignment I chose to stick with the Bulma library but implemented features that I havent used prior. I've since implemented a skills section and made some changes to certain sections of my website.

<br><br>

![image](https://user-images.githubusercontent.com/52800632/108153314-c6085080-708f-11eb-802a-aca8bcba623f.png)


# **Installation**


Link javascript,jQuery, and bulma to html file
```html
<script src="script.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bulma@0.9.1/css/bulma.min.css">

```

# **Built With**

<ul>
    <li> Bulma - Bulma framework based on Flexbox
    <li> Javascript - scripting language that allows implementation of complex web features
    <li> jQuery - Javascript library that simplifies javascript programming.
    <li> HTML - The standard markup language for web pages 
    <li> CSS - used to describe the presentation of markup langauges such as HTML </li>
</ul>

# **Code Snippet**
Here I utulized a Bulma card feature that allowed me to provide each card a Project Title, tags relevant to the project, an image, and links to both deployed and repo sites.

```js
 <!-- Project card 1 -->
                    <div class="card">
                        <header class="card-header">
                            <p class="card-header-title">
                                <span>Project 2</span>
                                <span class="is-pulled-right">

                                    <span class="tag is-default">Sequelize Database</span>
                                    <span class="tag is-default">Html/Api Routing</span>

                                </span>
                            </p>
                        </header>
                        <div class="card-content" id="projectCard">
                            <figure class="image is-4by3">
                                <img src="./assets/Project2Snip.PNG" alt="Project2">
                            </figure>
                        </div>
                        <footer class="card-footer">
                            <a href="https://party-x.herokuapp.com/" class="card-footer-item">Deployed Site</a>
                            <a href="https://github.com/ArjayCaluag/Project-2" class="card-footer-item">Github
                                Repo</a>
                        </footer>
                    </div>
```
# **Deployed Link**

https://arjaycaluag.github.io/Portfolio-3/
# **Authors**

Ron-Arjay Caluag<br>
[Linkedin](https://www.linkedin.com/in/ron-arjay-caluag-00b29b182/)<br>
[Github](https://github.com/ArjayCaluag)


The MIT License (MIT)

Copyright (c) 2011-2020 Twitter, Inc.

Copyright (c) 2011-2020 The Bootstrap Authors

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
