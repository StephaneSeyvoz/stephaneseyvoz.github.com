---
layout: post
title: "Implemented Formatting/Pretty Printing (Ctrl+Shift+F)"
description: ""
category: MindEd
tags: [MindEd, formatting, pretty printing, shortcuts]
---
{% include JB/setup %}

Implemented the ability to use Ctrl+Shift+F, using Xtext formatting API [Xtext & Formatting (Pretty Printing)] (http://www.eclipse.org/Xtext/documentation.html#formatting).

It mainly consisted of adding line wraps after all semi-columns, line wraps after opening curly brackets, before closing curly brackets, and finally setting automatic indentation between curly brackets.
