---
title: "Plot seasonal subseries of time series, generalization of list("stats::monthplot")"
rdname: "ggfreqplot"
date: "2015-04-25"
output: html_document
layout: article
category: "ggfortify"
images:
 - figure/source/2015-04-25-ggfreqplot//ggfreqplot-1.png
 - figure/source/2015-04-25-ggfreqplot//ggfreqplot-2.png
 - figure/source/2015-04-25-ggfreqplot//ggfreqplot-3.png
---




{% highlight r %}
ggfreqplot(AirPassengers)
{% endhighlight %}

![plot of chunk ggfreqplot](/allYourFigureAreBelongToUs/figure/source/2015-04-25-ggfreqplot/ggfreqplot-1.png) 

{% highlight r %}
ggfreqplot(AirPassengers, freq = 4)
{% endhighlight %}

![plot of chunk ggfreqplot](/allYourFigureAreBelongToUs/figure/source/2015-04-25-ggfreqplot/ggfreqplot-2.png) 

{% highlight r %}
ggfreqplot(AirPassengers, conf.int = TRUE)
{% endhighlight %}

![plot of chunk ggfreqplot](/allYourFigureAreBelongToUs/figure/source/2015-04-25-ggfreqplot/ggfreqplot-3.png) 