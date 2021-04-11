---
layout: post
title:  "Integrating Navigation Goals with AR detection"
date:   2021-04-10 22:28:00 -0700
categories: personal
---

This is very much a reminder to myself on what to run and what to check 

1. HARDWARE
make sure the nvidia is on
AND THE CAR batteries plugged in and esc turned on

2. ROS
gotta get the main ones down

{% highlight ruby %}
roscore
{% endhighlight %}

make sure in every terminal window you open, you 
{% highlight ruby %}
source devel/setup.bash
{% endhighlight %}

{% highlight ruby %}
rosrun i2cpwmboard beep boop
{% endhighlight %}

{% highlight ruby %}
rosrun donkeycar low_level_control.py
{% endhighlight %}
if you want to test if theyre working you can run the keyboard demo in teleop..

{% highlight ruby %}

{% endhighlight %}