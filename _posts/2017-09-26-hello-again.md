---
layout: post
title: hello (again)
date: 2017-09-26
author: ckj
categories: news
---
# title 1
## title 2
### title 3
#### title 4
##### title 5
###### title 6

## text

It's very easy to make some words **bold** and some words *italic* with Markdown.  
And maybe also some `inline code` or some words ~~deleled~~.  
You can even [link to xdlinux](https://linux.xidian.edu.cn) !

## list

### unordered

* Item 1
* Item 2
  * Item 2a
  * Item 2b

### ordered

1. Item 1
2. Item 2
3. Item 3
   1. Item 3a
   2. Item 3b

## table

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

## code

{% highlight julia %}
function mandel(z)
    c = z
    maxiter = 80
    for n = 1:maxiter
        if abs(z) > 2
            return n-1
        end
        z = z^2 + c
    end
    return maxiter
end

function randmatstat(t)
    n = 5
    v = zeros(t)
    w = zeros(t)
    for i = 1:t
        a = randn(n,n)
        b = randn(n,n)
        c = randn(n,n)
        d = randn(n,n)
        P = [a b c d]
        Q = [a b; c d]
        v[i] = trace((P.'*P)^4)
        w[i] = trace((Q.'*Q)^4)
    end
    std(v)/mean(v), std(w)/mean(w)
end
{% endhighlight %}

## quote

> Those who do not understand Unix are condemned to reinvent it, poorly

