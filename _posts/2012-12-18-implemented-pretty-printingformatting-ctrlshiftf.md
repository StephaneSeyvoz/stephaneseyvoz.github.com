---
layout: post
title: "Implemented Formatting, aka Pretty Printing (Ctrl+Shift+F)"
description: ""
category: MindEd
tags: [MindEd, formatting, pretty printing, shortcuts]
---
{% include JB/setup %}

I used Xtext's formatting API, see: [Xtext & Formatting (Pretty Printing)] (http://www.eclipse.org/Xtext/documentation.html#formatting).

It mainly consisted of adding line wraps after all semi-columns, line wraps after opening curly brackets, before closing curly brackets, and finally setting automatic indentation between curly brackets.

For more detailed information, see: [My commit concerning ADL pretty printing] (https://github.com/StephaneSeyvoz/mindEd/commit/382219bb26f79130a9afab22dc037619541d4e5a).