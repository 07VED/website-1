---
layout: robot
title: MOOC QuickBot v2
description: "The Oringinal QuickBot"
modified: 2014-02-28
tags: [QuickBot]
published: true
---

<p align="center">
  <img src="{{ site.url }}/images/quickbot-red-icon.jpg" alt="QuickBot">
</p>

* Table of Contents
{:toc}

## Overview
The QuickBot was oringally designed by <a href="https://rowlandoflaherty.com" target="_blank">Rowland O'Flaherty</a> for the <a href="https://www.coursera.org/course/conrob" target="_blank">2014 Coursera MOOC "Control of Mobile Robots"</a>. The idea was to have a fairly cheap, easy to build, differential drive robot that the students of the course could use to apply the theory that they learn from the course to a real world robot. The name QuickBot was given because (in theory) it is quick to build and setup.

The QuickBot has a wheel encoder on each wheel to measure wheel rotations and five infrared (IR) distance sensors (proximity sensor) to measure the distance of obstacles to the robot. The processing on the QuickBot is preformed by a [BeagleBone Black (BBB)](http://beagleboard.org/products/beaglebone%20black) microcomputer. Wifi on board is used to connect the QuickBot to the world, which allows for onboard development as well as easy interfacing with simulation and visulization tools. The QuickBot is powered by 8 AA batteries.

<div id="disqus_thread"></div>
<script type="text/javascript">
    /* * * CONFIGURATION VARIABLES: EDIT BEFORE PASTING INTO YOUR WEBPAGE * * */
    {% if site.url == "http://o-botics.org" %}
      var disqus_shortname = 'o-botics'; // required: replace example with your forum shortname
    {% endif %}

    /* * * DON'T EDIT BELOW THIS LINE * * */
    (function() {
        var dsq = document.createElement('script'); dsq.type = 'text/javascript'; dsq.async = true;
        dsq.src = '//' + disqus_shortname + '.disqus.com/embed.js';
        (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(dsq);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="http://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
<a href="http://disqus.com" class="dsq-brlink">comments powered by <span class="logo-disqus">Disqus</span></a>


