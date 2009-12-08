gitfollow 
=========

Gitfollow is a very simple JavaScript plugin that you can add to your websites to display your GitHub followers count.

By getting people to follow you, you'll drive more attention to your projects and get more people involved in contributing and commenting.

What does it look like?
-----------------------

The button uses beatiful and sexy CSS3 styling!

![Screenshot](http://cld.ly/5apc8)

How to use
----------

Place gitfollow in your header
	
	<script src="gitfollow.js" type="text/javascript"></script>

Place a link with `class="gitfollow"` wherever you want your GitHub count to be rendered

	<a href="http://github.com/rauchg" class="gitfollow"></a>
	
If you want a smaller one try

	<a href="http://github.com/rauchg" class="gitfollow small"></a>
	
and that's it!
	
How it works
------------

gitfollow utilizes the excellent GitHub API with the JSONP callback. Some neat things you can find in the code:

* data: URI usage for the logo injection (which is really small)

* HTML5 sessionStorage as a caching mechanism

* CSS3 gradients, box-shadow, border-radius
 
gitfollow has been tested in Safari 4, Google Chrome (mac) and Firefox 3.5. It displays best in webkit-based browsers.

Credits
-------

Authored by: [Guillermo Rauch](http://devthought.com)

GitHub logo: [found here](http://fi.github.com/images/modules/demo/github_logo.png)

Inspired by [Retweet](http://github.com/jeresig/retweet/) by John Resig