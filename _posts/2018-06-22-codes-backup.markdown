---
layout: post
title:  "Codes Backup"
date:   2018-06-22 00:01:00 -0300
categories: Codes
---

## Ajax
Um exemplo rápido de como usar o Ajax para trazer dados de um servidor.

{% highlight ruby %}
$.ajax({
    type: "GET",
    url: 'url-server',
    data: { 'var1': var1, 'var2': var2 },
    success: function (response) {

        data = JSON.parse(response);

    }
});
{% endhighlight %}

Check out the [Ajax docs][ajax-docs] for more info.

[ajax-docs]: http://api.jquery.com/category/ajax/