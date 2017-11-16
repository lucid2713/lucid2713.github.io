---
layout: post
title: MALMAL, ongoing project, 2017
description: Projection mapping test and MaxMSP
date: 2017-10-17 16:23:00
---

<br/>

MALMAL means 'bad word', combining the french adjective 'mal'(bad) with the same sounds word in Korean '말mal'(word or language).<br/>
I had worked for this idea before by making <a href="https://projectintheclass.github.io/MinApp/" target="blank">iOS application</a>, but now I keep working with this concept for another expression using another materials.
<br/><br/>

<div>
<img class="col three" src="/img/malmal-design-framework.jpg" alt="malmal-design-framework" title="malmal-design-framework"/>
</div>
<div class="col three caption">
Design framework for MalMal (MaxMSP version)
</div>

<br/><br/>

So the basic ideation is illustrated on the framework above, but still finding and thinking of more effective way of interaction and delivery of intention.
<br/><br/>
Until now I've working with MaxMSP to trigger sounds and videos, and tested a projection mapping with videos I made.  
<br/><br/>
<p align="middle">
<iframe width="560" height="315" src="https://www.youtube.com/embed/zbgwndtapbs" frameborder="0" allowfullscreen></iframe>
</p>
<div class="col three caption">
<i>MalMal(Bad words), practice with projection mapping</i>
</div>
<br/><br/><br/>

<h4>These are my to-do-list</h4>
<br/>
<ul>
<li>Devise more intuitive interaction of artwork with audience(participant)</li>
<li>Design sounds and videos(more or newly)</li>
<li>Figure out proper tools : still gonna use max? if so, for which interaction?</li>
<li>The way of presenting</li>
</ul>
<br/><br/>

<h4>Research for related (art)works</h4>
<br/>
There are several works which has similar subject as well as works that has really intuitive and effective interaction for delivering its meaning.
<br/><br/>
<ul>
<strong>Good reference for intuitive interaction</strong>
<li><a href="http://www.begomsantiago.com/LITTLE-BOXES" target="blank">Little Boxes</a>, Bego M. Santiago, 2011</li>
</ul>
<ul>
<strong>Toy button with similar idea(yelling to make shut up, funny way of delivery)</strong>
<li><a href="https://www.youtube.com/watch?v=bhiVtCewIJU" target="blank">Shut up Button</a></li>
<li><a href="https://www.youtube.com/watch?v=hww5LQ_-Cn4" target="blank">Donald Trump Button</a>, silly remarks of Donald Trump</li>
<li><a href="https://www.youtube.com/watch?v=EjrWipZ4g0g" target="blank">Another Trump Button</a></li>
</ul>
<ul>
<strong>Hacktivism (art)works with similar idea</strong>
<li><a href="https://twitter.com/burnedyourtweet" target="blank">Burned Your Tweet</a>, (physically) burning trump’s inflammatory tweets in real time</li>
<li><a href="https://www.behance.net/gallery/29128771/Demagogiaprotektor" target="blank">Demagogiaprotektor</a>, Daniel Cseh</li>
 : 3d printed middle finger skeleton which is responsive to (political bullshit)remarks, powered by servomotor and Google’s speech recognition capabilities
</ul>
<br/><br/>

***

<h4>Developed sketch of the design & process, 14.Nov</h4>
<br/><br/>
<div>
<img class="col three" src="/img/malmal-modified-design.jpg" alt="modified desing sketch" title="modified design sketch"/>
</div>
<div class="col three caption">
Modified design idea sketch using Kinect
</div>
<br/><br/>

Instead of the voice input with MaxMSP that I considered last idea sketch, I'll use Kinect for detecting depth & position in order to realize more intuitive interaction.<br/> I thought this way will be better to make audiences figure out to interact with my work as well as to deliver my intention - make bad words shut up and kick out.
<br/><br/>
<ul>
<strong>Control</strong>
<li>Processor : Processing(image/video), MaxMSP(sound)</li>
<li>Controller : Kinect(sensing depth and position)</li>
</ul>

<ol>
<strong>Task</strong>
<li>On the screen there is a big mouth with large sound, if there's no people nearby.</li>
<li>When someone is approaching to the screen, both the size and the volume of mouth are smaller.</li>
<li>Also, people can drive the mouth out of the screen, chasing it left or right side.</li>
</ol>

<br/><br/>
