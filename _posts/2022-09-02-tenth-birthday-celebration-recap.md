---
layout: post
title: "Trino's tenth birthday celebration recap"
author: "Brian Olsen"
excerpt_separator: <!--more-->
---

What an exciting month we had in August! August marked the ten-year birthday of
the Trino project! Don't worry if you missed all the excitment as we've
condensed it all in this post!

![](/assets/blog/trino-tenth-birthday/creators.jpeg)

<!--more-->

## Blog posts

We felt it necessary to chronicle the larger events that happened in the last
decade of the project through the lens of where we are today. Here are few of
the posts we wrote around this exciting occasion:

* [Why leaving Facebook/Meta was the best thing we could do for the Trino Community]({% post_url 2022-08-02-leaving-facebook-meta-best-for-trino %})
* [A decade of query engine innovation]({% post_url 2022-08-04-decade-innovation %})
* [Happy tenth birthday Trino!]({% post_url 2022-08-08-trino-tenth-birthday %})

Some exciting aspects to these blogs were sharing them on HackerNews. The
Facebook and the query innovation posts both hit the front page. This resulted
in one of the largest amount of page views on the Trino website in a given day
(>25k views).

![](/assets/blog/trino-tenth-birthday/hn-top.png)
![](/assets/blog/trino-tenth-birthday/hn-9.png)

## Trino ten-year timeline video

Another way we celebrated was creating an epic ten-year montage video that
chronicled the incredible journey starting with the Presto project's humble
beginnings and later evolved into the success that Trino is today.

<iframe src="https://www.youtube.com/embed/hPD95_-bZZw" width="800" height="500" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px;
margin-bottom:5px; max-width: 100%;" allowfullscreen="">
</iframe>

## Birthday celebration with the creators of Trino

To cap things off last month, we hosted a meetup with the creators to reflect
on the last ten years, laugh and listen to some stories from the early days,
talk about the exciting features currently launching, and speculate on the next
ten years of Trino. Here are some of the highlights you missed:

### Adding dynamic catalogs
<div class="three-column-grid">
<div class="three-column-grid-item">
<iframe src="https://www.youtube.com/embed/6TFLKcF24HM?clip=UgkxkYmwM6gmw9-GceMUb5IxqIKm0qNXt3fY&amp;clipt=ELDkAxjknQc" width="800" height="500" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px;
margin-bottom:5px; max-width: 100%;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="">
</iframe>
Dain discusses what dynamic catalogs could look like in Trino. There is still no
guarantee of exactly when this feature would arrive, but some of the foundations
are currently being added.
</div>
</div>

### Vectorization and performance
<div class="three-column-grid">
<div class="three-column-grid-item">
<iframe src="https://www.youtube.com/embed/6TFLKcF24HM?clip=UgkxmPAur8thP_D-_GpCcg-sqprEAqwWdyck&amp;clipt=EOrsGRjrtB0" width="800" height="500" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px;
margin-bottom:5px; max-width: 100%;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="">
</iframe>

Do modern workloads benefit from vectorization?
</div>

<div class="three-column-grid-item">
<iframe src="https://www.youtube.com/embed/6TFLKcF24HM?clip=UgkxmPAur8thP_D-_GpCcg-sqprEAqwWdyck&amp;clipt=EOrsGRjrtB0" width="800" height="500" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px;
margin-bottom:5px; max-width: 100%;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="">
</iframe>

Is there a benefit to vectorization over Java's auto-vectorization?
</div>

<div class="three-column-grid-item">
<iframe src="https://www.youtube.com/embed/6TFLKcF24HM?clip=UgkxQwDYDS6evVJelNVjWAgrIhzg_Q-cAEyq&amp;clipt=EJSUNxi_2Tk" width="800" height="500" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px;
margin-bottom:5px; max-width: 100%;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="">
</iframe>

If vectorization isn't always the answer, then what type of performance
improvements does Trino focus on?
</div>

<div class="three-column-grid-item">
<iframe src="https://www.youtube.com/embed/6TFLKcF24HM?clip=Ugkxt5ryTBP-EPEEo_OOcW2PKvNiJkj5n8UR&amp;clipt=EMiHrQEY_ZSwAQ" width="800" height="500" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px;
margin-bottom:5px; max-width: 100%;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="">
</iframe>

Much like the debate around compiler time vs runtime optimizations, a similar
debate for queries exists around query time optimization versus runtime
adaption.
</div>
</div>

### Polymorphic table functions

<div class="three-column-grid">
<div class="three-column-grid-item">
<iframe src="https://www.youtube.com/embed/6TFLKcF24HM?clip=Ugkx62IKgPd_v9eGBaPUHP2hyaRkWSXh8w8h&amp;clipt=EPi9Thin_lE" width="800" height="500" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px;
margin-bottom:5px; max-width: 100%;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="">
</iframe>

One feature that is top-of-mind for everyone in the Trino project are
[polymorphic table functions]({% post_url 2022-07-22-polymorphic-table-functions %})
or simply "table functions" as Dain prefers to call them.

In short, what is a table function?
</div>

<div class="three-column-grid-item">
<iframe src="https://www.youtube.com/embed/6TFLKcF24HM?clip=Ugkx62IKgPd_v9eGBaPUHP2hyaRkWSXh8w8h&amp;clipt=EPi9Thin_lE" width="800" height="500" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px;
margin-bottom:5px; max-width: 100%;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="">
</iframe>

Rewriting the
[Google Sheets connector]({{site.url}}/docs/current/connector/googlesheets.html)
as a table function is one example to better understand what table functions
can achieve.
</div>

<div class="three-column-grid-item">
<iframe src="https://www.youtube.com/embed/6TFLKcF24HM?clip=UgkxQcokpdgPjiuMKMC5-3HwHvlbmZjxAvxe&amp;clipt=EIv7YRiixmQ" width="800" height="500" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px;
margin-bottom:5px; max-width: 100%;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="">
</iframe>

Why table functions are so incredibly powerful.
</div>
</div>
If you want to learn more about polymorphic table functions, check out the
recent [Trino Community Broadcast episode]({{site.url}}/episodes/38.html) that
covers the potential of these functions in much more detail!

### The early days of Presto and Trino
We wanted to get some insight into what the early days of the project looked
like, and how Martin, Dain, David, and Eric began the daunting task of designing
and building a distributed query engine from scratch. Some of the discussions
were interesting while others were downright hilarious.

<div class="three-column-grid">
<div class="three-column-grid-item">
<iframe src="https://www.youtube.com/embed/6TFLKcF24HM?clip=UgkxGjPYZRx8rhtAndyho7AZgsM4e9wG9Jt4&amp;clipt=EPbymQEYnN-cAQ" width="800" height="500" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px;
margin-bottom:5px; max-width: 100%;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="">
</iframe>

Step 1: Look up a bunch of research papers to see how others are doing this 📑:
</div>

<div class="three-column-grid-item">
<iframe src="https://www.youtube.com/embed/6TFLKcF24HM?clip=Ugkx6Hqe5iglsTgrR9hVo9U3ITi8LSxxMu4U&amp;clipt=EN_2pAEYpMSoAQ" width="800" height="500" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px;
margin-bottom:5px; max-width: 100%;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="">
</iframe>

Site note: Papers tend to be highly aspirational and skip important fundamentals:
</div>

<div class="three-column-grid-item">
<iframe src="https://www.youtube.com/embed/6TFLKcF24HM?clip=Ugkx57PezuXyRWHrxxxoLaKni6jqFZ-StwY-&amp;clipt=EMzJqAEYv5qqAQ" width="800" height="500" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px;
margin-bottom:5px; max-width: 100%;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="">
</iframe>

Step 2: Address the real challenges of making a query engine:
</div>

<div class="three-column-grid-item">
<iframe src="https://www.youtube.com/embed/6TFLKcF24HM?clip=UgkxJz7zve36QJZZDdtC3S29vI-Ak1jRifAH&amp;clipt=EJKolwEY_quZAQ" width="800" height="500" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px;
margin-bottom:5px; max-width: 100%;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="">
</iframe>

Step 3: Take your initial version and just throw it away 😂🗑🚮:
</div>

<div class="three-column-grid-item">
<iframe src="https://www.youtube.com/embed/6TFLKcF24HM?clip=UgkxQrBl0BzOrjvwDcEN4KAAyqehcRUc1tsf&amp;clipt=EO_9uAEYztK8AQ" width="800" height="500" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px;
margin-bottom:5px; max-width: 100%;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="">
</iframe>

Step 4: Expand outside the initial use cases at Facebook by learning from other
companies and building community 👥:
</div>

<div class="three-column-grid-item">
<iframe src="https://www.youtube.com/embed/6TFLKcF24HM?clip=Ugkx6SyQTFgwX_kdeH018VGt2pMUbldvuKtC&amp;clipt=EJuCvwEY39bCAQ" width="800" height="500" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px;
margin-bottom:5px; max-width: 100%;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="">
</iframe>

Step 5: Cause a [brownout](https://en.wikipedia.org/wiki/Brownout_(software_engineering))
on the Facebook network 📉:
</div>

<div class="three-column-grid-item">
<iframe src="https://www.youtube.com/embed/6TFLKcF24HM?clip=UgkxTqBY2nMAALn-OkglE5DT9dHlBuC18qf8&amp;clipt=EKaxzAEYhobQAQ" width="800" height="500" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px;
margin-bottom:5px; max-width: 100%;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="">
</iframe>

Step 6: Realize the system you replaced was actually faster in some cases, but
for all the wrong reasons ❌🙅:
</div>
</div>

From here, we know that the velocity of the project picked up and once the
project was independent of Facebook, the features took off even more. While
everything may seem calculated in hindsight, a lot of features we know today
happened organically through discussion by the community. If you're curious what
mindset the creators had when starting the project and if they ever expected the
project to become this widely adopted:

<iframe src="https://www.youtube.com/embed/6TFLKcF24HM?clip=Ugkxh2J-1bi1rUoBpuld_FAuXYZgz2bvqPPx&amp;clipt=ELPEkAEY64KTAQ" width="800" height="500" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px;
margin-bottom:5px; max-width: 100%;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="">
</iframe>

## Conclusion

We hoped you enjoyed all the fun we had celebrating these first ten years of the
Trino project. We are thrilled to think of what the following decades will
bring. We'd like to leave you with a closing though from Dain around what the
next ten years of Trino will look like:

<iframe src="https://www.youtube.com/embed/6TFLKcF24HM?clip=Ugkx5bFnjvRX0USjk8vgRJdqLwZQo7Ffg0xm&amp;clipt=ELfJ2gEY8o7eAQ" width="800" height="500" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px;
margin-bottom:5px; max-width: 100%;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="">
</iframe>
