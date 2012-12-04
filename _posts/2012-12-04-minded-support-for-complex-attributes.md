---
layout: post
title: "MindEd support for complex attributes"
description: ""
category: MindEd
tags: [MindEd, Mind attributes, editor]
---
{% include JB/setup %}

Today I introduced basic support for the new "complex attributes" syntax.
Such attributes can be structures, unions or typedefs (but not enums yet !), and can be used in the ADL, e.g.:

	attribute attrTypes.h:struct s1 attr3 = {3, 4};

Where attrTypes.h is: 

	#ifndef ATTR_TYPES_H  
	#define ATTR_TYPES_H  
	  
	struct s1 {  
		int a, b;  
	};  
	
	#endif

The syntax is now supported in MindEd. You can __navigate__ from the file name to its content with the __F3__ or __CTRL+click__ standard hyperlink, when the file is in the same folder as its hosting component.

Note 1: Longer paths such as "my/api/file.h" are supported syntaxically but the hyperlink feature is __not__ available with them yet.

Note 2: The specified file is __not__ parsed to provide content suggestion in the right-hand expression.