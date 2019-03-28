---
layout: project
title: Inverted Pendulum Bot
description: 'A configurable, autonomous Segway-like robot. Currently in progress.'
image:
nav-menu: false
github-url: 'https://github.com/galensavidge/inverted-pendulum-bot'
---

<section id="one">
	<div class="inner">
		<div class="row">
			<div class="9u 12u$(medium)">
				<header class="major">
					<h3>About	</h3>
				</header>
				<p>The inverted pendulum is a classic feedback control problem. The coupled physical system exhibits complex behavior which can make it difficult to control. This project aims to tackle the problem from the ground up, using a derived kinematic model to simulate the effects of different feedback control techniques on the system. Eventually, feedback control will be tested on a custom-built physical bot.</p>
			</div>
			<div class="3u$ 12u$(medium)" align="right">
				<header class="major">
					<h3>Source Code	</h3>
				</header>
				<a href="{{ page.github-url }}" class="icon alt fa-github" target="_blank"><span class="label">GitHub</span></a>
			</div>
		</div>
	</div>
	
	<div class="inner">
		<div class="row">
			<div class="8u 12u$(medium)">
				<header class="major">
					<h3>Simulation</h3>
				</header>
				<p>A proof-of-concept Matlab simulation shows that two nested PID controllers can successfully drive the robot to a desired position.</p>
			</div>
			<div class="4u$ 12u$(medium)">
				<span class="image fit"><img src="assets/images/inverted-pendulum-side.gif" alt="assets/images/inverted-pendulum-thumb.PNG" /></span>
			</div>
		</div>
	</div>
</section>