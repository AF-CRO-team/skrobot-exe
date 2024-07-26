---
layout: post
title: CSS Selector test
subtitle: Testing page
---

<style>
        .menu {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        
        .quack {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        
        a[href="https://example.com"] {
            display: block;
            margin: 10px;
            padding: 10px;
            background-color: #4CAF50;
            color: white;
            text-align: center;
            text-decoration: none;
            border-radius: 5px;
        }
    </style>

<div class="menu">
   <a id="button1" href="https://example.com">Click Me</a>
    </div>
<div class="menu">
        <a data-button="3" href="https://example.com">Click Me</a>
    </div>
<div class="menu">
        <a class="quack" href="https://example.com">Click Me</a>
</div>
<div class="quack">
            <a href="https://example.com">Click Me</a>
</div> 
 
 