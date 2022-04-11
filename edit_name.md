---
layout: main
title:  "Edit"
permalink: /edit/name.html
---
<section>
    <article class="preview">
        <h1>
            John Doe: good person
            <a style="font-size: 1.2rem;" href="{{ '/edit/content' | relative_url }}"><i class="fa-solid fa-pen"></i></a>
        </h1>
        <article class="more">
            <header>
                <a class="secondary" style="float:right;" href="#"><i class="fa-solid fa-thumbtack"></i></a> 
                <input autofocus type="text" id="name" name="firstname" placeholder="name" required>
                <input type="text" id="name" name="firstname" placeholder="type" required>
            </header>
            <details open>
                <summary>Links (2)</summary>
                <input style="margin-bottom:0" autofocus type="search" id="search" name="search" placeholder="Add">
                <dl>
                    <dt>author</dt>
                    <dd>
                        <a href="#"> John Doe</a>
                        <a href="#" style="float: right; margin-left: 10px;">
                            <i class="fa-solid fa-copy"></i></a> <a href="#" style="float: right"> <i class="fa-solid fa-minus"></i>
                        </a>
                    </dd>
                    <dt>results</dt>
                    <dd>
                        <a href="#">Nice report</a>
                        <a href="#" style="float: right; margin-left: 10px;">
                            <i class="fa-solid fa-copy"></i></a> <a href="#" style="float: right"> <i class="fa-solid fa-minus"></i>
                        </a>
                    </dd>
                </dl>
            </details>
            <details open>
                <summary>Files (1)</summary>
                <ul>
                    <li style="list-style: none">
                        <a href="">pdf file.pdf</a>
                        <a href="#" style="float: right; margin-left: 10px;">
                            <i class="fa-solid fa-copy"></i></a> <a href="#" style="float: right"> <i class="fa-solid fa-minus"></i>
                        </a>
                    </li>
                </ul>
                <button class="outline">Add</button>
            </details>
        </article>
        <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad  minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in   voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia    deserunt mollit anim id est laborum.
        </p>
        <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad  minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in   voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia    deserunt mollit anim id est laborum.
        </p>
        <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad  minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in   voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia    deserunt mollit anim id est laborum.
        </p>
        <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad  minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in   voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia    deserunt mollit anim id est laborum.
        </p>
        <div style="max-width: 500px; margin:auto;" >
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e3/Che_ne_saj.jpg/2560px-Che_ne_saj.jpg">
        </div>
        <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad  minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in   voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia    deserunt mollit anim id est laborum.
        </p>
    </article>
    <article class="preview">
        <header>
            <a style="float:right;" href="#"><i class="fa-solid fa-thumbtack"></i></a> 
            <h2>John Doe <a style="font-size: 1.2rem;" href="{{ '/edit/name' | relative_url }}"><i class="fa-solid fa-pen"></i></a> </h2>
            <strong>person</strong>
        </header>
        <details open>
            <summary>Links (2)</summary>
            <dl>
                <dt>author</dt>
                <dd>
                    <a href="#"> John Doe</a>
                    <a href="#" style="float: right; margin-left: 10px;">
                    <i class="fa-solid fa-copy"></i></a> <a href="#" style="float: right">
                    <i class="fa-solid fa-minus"></i></a>
                </dd>
                <dt>results</dt>
                <dd>
                    <a href="#">Nice report</a>
                    <a href="#" style="float: right; margin-left: 10px;"> <i class="fa-solid fa-copy"></i></a>
                    <a href="#" style="float: right"> <i class="fa-solid fa-minus"></i></a>
                </dd>
            </dl>
            <button class="outline">Add</button>
        </details>
        <details>
            <summary>Files (1)</summary>
            <ul>
                <li style="list-style: none">
                    <a href="">pdf file.pdf</a>
                    <a href="#" style="float: right; margin-left: 10px;"> <i class="fa-solid fa-copy"></i></a>
                    <a href="#" style="float: right"> <i class="fa-solid fa-minus"></i></a>
                </li>
            </ul>
            <button class="outline">Add</button>
        </details>
        <div style="text-align: right">
            <a role="button" href="{{ '/edit/content' | relative_url }}">Add Content</a>
        </div>
    </article>
</section>  