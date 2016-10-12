---
layout: post
title: "boiling the ocean"
date: 2016-10-12 13:15:19 -0700
comments: true
categories:
---


{% highlight ruby %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}