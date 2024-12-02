---
aliases: 
tags:
  - periodicnote/daily
related:
---



***

up:: 
back:: <% tp.date.now("YYYY-MM-DD", -1, tp.file.title, "YYYY-MM-DD") %>
forward:: <% tp.date.now("YYYY-MM-DD", 1, tp.file.title, "YYYY-MM-DD") %>
layer:: [[arcofeternity|layer-359]]

***

year:: <% moment(tp.file.title, "YYYY-MM-DD").format("YYYY") %>
quarter:: [[timeblock-quarter-Q<% moment(tp.file.title, "YYYY-MM-DD").format("Q") %>
month:: <% moment(tp.file.title, "YYYY-MM-DD").format("MMMM") %>
week:: <% moment(tp.file.title, "YYYY-MM-DD").format("WW") %>
date:: <% moment(tp.file.title, "YYYY-MM-DD").format("MMM DD") %>
day:: <% moment(tp.file.title, "YYYY-MM-DD").format("dddd") %> ()

***
