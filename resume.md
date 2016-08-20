---
layout: page
title: My Resume
redirect_from: "/"
---

## Work Experience
-----
*   ***Branch8 Ltd ([YCombinator](https://www.ycombinator.com/) S15)*** (Hong Kong)

    *Software Engineer*, Feb 2016 - Present

    - Developed and maintained company websites [branch8.com](https://www.branch8.com/)
      - Over 3 million of products are managed by branch8
      - Find out more about us: [36kr (Chinese)](https://36kr.com/p/5036350.html), [Startupbeat (Chinese)](http://startupbeat.hkej.com/?p=20805), [TechCrunch](https://techcrunch.com/2015/08/11/branch8/)
		<div class="section group">
			<div class="col span_1_of_1">
				<img src="https://raw.githubusercontent.com/dyhpoon/dyhpoon.github.io/master/public/screenshots/branch8.png">
			</div>
		</div>

    - Developed a chrome extension “[8buy](https://chrome.google.com/webstore/detail/8buy-find-cheaper-prices/klmmacdelhgkpfhkifbcppibnbcpakhh?hl=en)” that finds cheaper price on Lazada
      - Stack: [React](https://github.com/facebook/react), [Redux](https://github.com/reactjs/redux), [material-ui](http://www.material-ui.com/#/), [bluebird](https://github.com/petkaantonov/bluebird), [AzureML](https://azure.microsoft.com/zh-tw/services/machine-learning/), and etc
		<div class="section group">
			<div class="col span_1_of_1">
				<img src="https://raw.githubusercontent.com/dyhpoon/dyhpoon.github.io/master/public/screenshots/eightbuy.png">
			</div>
		</div>
	- Developed other side projects.
		- [8Checkout](https://checkout.branch8.com/?url=http://www.lazada.sg/apple-iphone-6s-64gb-gold-6668152.html?offer_id=481&affiliate_id=104786&offer_name=SG+Data-feed_0&affiliate_name=Branch8+Limited&transaction_id=102ee5773344369da92f255d29de48)
			- ![](https://raw.githubusercontent.com/dyhpoon/dyhpoon.github.io/master/public/screenshots/8checkout.png)
		- Cadobox (chatbot)
			- ![](https://raw.githubusercontent.com/dyhpoon/dyhpoon.github.io/master/public/screenshots/cadobox.gif)

*   ***Premiumsoft Cybertech Ltd*** (Hong Kong)

    *Senior Software Developer*, Sep 2013 - Feb 2016

    - Develop "Grab for Instagram" in both Android and iOS version.
    	- Award the 19th Webby Awards Official Honoree — *MOBILE SITES & APPS "Best Use of Mobile Camera"* in 2015
    	- Over million of users have downloaded and rated 4+ in app store
    	- Over 100,000+ of active users are using daily
    	- <p style="color:red">The app has been taken down from app store due to <a href="http://developers.instagram.com/post/133424514006/instagram-platform-update">Instagram's API deprecation</a> 😞</p>
			<div class="section group">
				<div class="col span_1_of_3">
					<img src="https://raw.githubusercontent.com/dyhpoon/dyhpoon.github.io/master/public/screenshots/grab1.gif">
				</div>
				<div class="col span_1_of_3">
					<img src="https://raw.githubusercontent.com/dyhpoon/dyhpoon.github.io/master/public/screenshots/grab2.png">
				</div>
				<div class="col span_1_of_3">
					<img src="https://raw.githubusercontent.com/dyhpoon/dyhpoon.github.io/master/public/screenshots/grab3.png">
				</div>
			</div>

    - Automate tests and error reports by setting up a Jenkins CI server with other tools: [xctool](https://github.com/facebook/xctool), [docker](https://github.com/docker/docker) and [stf](https://github.com/openstf/stf).

    - Develop a restful Instagram-like backend server and a centralized authentication system using LAMP stack.

    - Some other internal side projects that I wrote:
		- Instagram SDK in both Android and iOS
		- Facebook paper like tutorial framework in iOS which is inspired by [Flow](https://github.com/OliverLetterer/Flow) and [Paper Team](https://www.youtube.com/watch?v=OiY1cheLpmI)
			- ![](https://raw.githubusercontent.com/dyhpoon/dyhpoon.github.io/master/public/screenshots/tutorial.png)
		- Bubble Search Bar
			- ![](https://raw.githubusercontent.com/dyhpoon/dyhpoon.github.io/master/public/screenshots/bubbleSearchBar.png)

*   ***Coffee Game*** (Hong Kong)

    *Game Developer*, Jun 2013 - Aug 2013

    - Developed a mobile game called "Attack on Pirates"
    - It is also open source on [here](https://github.com/dyhpoon/game-project)

*   ***Macsteel International Far East Ltd*** (Hong Kong)

    *Intern*, May 2009 - Jul 2009

    - Data analysis

## My Open Source Projects
-----
<div class="section group">
	<div class="col span_1_of_2 v-center text-left">
		<div class="display-block">
			<a href="https://github.com/dyhpoon/Fo.dex">Fo.dex</a>
			<br/>
			An Android application allows you to index photos at ease.
		</div>
	</div>
	<div class="col span_1_of_2">
		<img src="https://raw.githubusercontent.com/dyhpoon/dyhpoon.github.io/master/public/screenshots/fodex.gif">
	</div>
</div>
<br/>

<div class="section group">
	<div class="col span_1_of_2 v-center text-left">
		<div class="display-block">
			<a href="https://github.com/dyhpoon/Attack-on-Pirates">Attack on Pirates</a>
			<br/>
			A simple 2D puzzle game.
		</div>
	</div>
	<div class="col span_1_of_2">
		<img src="https://raw.githubusercontent.com/dyhpoon/dyhpoon.github.io/master/public/screenshots/aop.gif">
	</div>
</div>
<br/>

[Android Dockerfiles](https://github.com/dyhpoon/Android-Dockerfiles) - Containerized Android Emulator in docker.
<p class="italic small-text-size">Example usage:</p>
{% highlight js %}
	docker run --privileged -it \
	-v /Path/to/your/android/project/:/workspace \
	dyhpoon/android-emulator-21 start-emulator \
	"./gradlew connectedAndroidTest"
{% endhighlight %}
<br/>

[VotePlex](https://github.com/dyhpoon/voteplex) - A simple voting web application using MEAN stack.
<br/>
<br/>

## Education
-----
*   ***City University of Hong Kong*** (Hong Kong)

    *M.S. in Computer Science*, Sep 2012 - Jul 2013

    Overall GPA: 3.52/4.00 (Distinction)

    <div class="message tiny-text-size">
	    Related Courses:
	    <div class="italic">
			Software Engineering, Distributed System, Data Warehousing and Data Mining, Computer Graphic, Internet Application Development, Cryptography, Info Security of e-Commerce, Info Security Technology Management
		</div>
    </div>

*	***University of Waterloo*** (Ontario, Canada)

	*B.CS (Honour)*, Sep 2008 - Jun 2012

	Major Average: 72.93/100

	<div class="message tiny-text-size">
		Related Courses:
		<div class="italic">
			Object-Oriented Software Development, Computer Networks, Database Management, Algorithms, Operating Systems, Artificial Intelligence, Computer Security and Privacy, Data Structures and Data Management, Foundation of Sequential Programs, Logic and Computation, Numerical Computation
		</div>
	</div>

## Skills
-----
* Software, Frameworks and Others
	* Proficient: Android, iOS, MySQL, Git, Jenkins, Docker, Cocoapods, Gradle, scripting
	* Prior experience: HTML, Corona SDK, Node.js, Express.js, Angular.js, Bootstrap CSS, MongoDB, Memcache, AWS

* Languages
	* Proficient: Objective-C, Java
	* Prior experience: Javascript, PHP, Swift, Python, C++, Lua, Scheme, R
