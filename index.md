---
layout: home
title:  "AKS Workshop"
date:   2019-03-23 21:03:36 +0530
categories: AKS Azure Kubernetes Workshop
---

Diese Labs wurden für den Azure Kubernetes Service Workshop erstellt. Sie dienen als Lab für den 4-tägigen Workshop.

```javascript
const Razorpay = require('razorpay');

let rzp = Razorpay({
	key_id: 'KEY_ID',
	secret: 'name'
});

// capture request
rzp.capture(payment_id, cost)
	.then(function (data) {
		return 2;
	})
```
List with posts:
{% for post in site.posts %}
	{{ post.title}} - {{ post.url }}<br>
{% endfor %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
