---
title: |
  Random swatch colour
rdname: random_swatch_colour
date: 2015-05-12
output: html_document
layout: article
category: ggthemr
images:
 - /allYourFigureAreBelongToUs/figure/source/2015-05-12-random_swatch_colour//random_swatch_colour-1.png
 - /allYourFigureAreBelongToUs/figure/source/2015-05-12-random_swatch_colour//random_swatch_colour-2.png
---




{% highlight r %}
ggthemr('dust')
ggplot(diamonds, aes(carat, price)) +
  geom_point(colour = random_swatch_colour())
{% endhighlight %}

![plot of chunk random_swatch_colour](/allYourFigureAreBelongToUs/figure/source/2015-05-12-random_swatch_colour/random_swatch_colour-1.png) 

{% highlight r %}
colorem <- random_swatch_colour()
ggplot(diamonds, aes(color, price)) +
  geom_boxplot(fill = colorem, outlier.colour = colorem)
{% endhighlight %}

![plot of chunk random_swatch_colour](/allYourFigureAreBelongToUs/figure/source/2015-05-12-random_swatch_colour/random_swatch_colour-2.png) 