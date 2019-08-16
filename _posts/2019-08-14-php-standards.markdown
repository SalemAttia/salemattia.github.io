---
title: "PHP coding-standards-psr1-psr2 "
layout: post
date: 2019-08-14 22:44
image: /assets/images/markdown.jpg
headerImage: false
tag:
- PHP
- PSR-1 && PSR-2
star: true
category: blog
author: salem
description: Coding standards PSR-1 & PSR-2
---

## Coding standards PSR

{% highlight html %}
    PHP Standards Recommendation 
    PSR-0 - Autoloader Standard
    PSR-1 - Basic Coding Standard
    PSR-2 - Coding Style Guide
    PSR-3 - Logger Interface
    PSR-4 - Autoloader Standard
{% endhighlight %}

---

## PSR-1 Overview

{% highlight html %}
   - Files must use only <Strong><?php and <?=</strong>
   
   - Files must use only <Strong>UTF-8 without bom</strong>
   
   - Files SHOULD either declare symbols or cause side-effects but should not do both
   
   - Namespaces and classes must follow an "autoloading" PSR
   
   - Class names must be declared in <strong>StudlyCaps<?strong>
   
   - Method names must be declared in <strong>camelCase<?strong>
{% endhighlight %}

## PSR-2 Overview

{% highlight html %}
  - Code MUST follow a "coding style guide" PSR [PSR-1].
  
  - Code MUST use 4 spaces for indenting, not tabs.
  
  - There MUST NOT be a hard limit on line length; the soft limit MUST be 120 characters; lines SHOULD be 80 characters or less.
  
  - There MUST be one blank line after the namespace declaration, and there MUST be one blank line after the block of use declarations.
  
  - Opening braces for classes MUST go on the next line, and closing braces MUST go on the next line after the body.
  
  - Opening braces for methods MUST go on the next line, and closing braces MUST go on the next line after the body.
  
  - Visibility MUST be declared on all properties and methods; abstract and final MUST be declared before the visibility; static MUST be declared after the visibility.
  
  - Control structure keywords MUST have one space after them; method and function calls MUST NOT.
  
  - Opening braces for control structures MUST go on the same line, and closing braces MUST go on the next line after the body.

  - Opening parentheses for control structures MUST NOT have a space after them, and closing parentheses for control structures MUST NOT have a space before.
{% endhighlight %}

