---
layout: fullwidth
title: '#MyAAPIVote | Thanks for Pledging!'
menutitle: 'Thanks for Pledging!'
permalink: /thankyou/
weight: 20
---

<h1>Thank You for Pledging to Vote!</h1>

<p>Let your friends and family know that you are making your vote count this election season. Add a badge your profile picture on Facebook, Twitter, and other social media and encourage your friends to register, pledge, and vote!</p>

<p>Use your badge to tell your friends and family why you vote -- you can fill in your issue below. Whether you vote for immigration reform, climate policy, or racial justice, let the world know that these issues are important to you as an AAPI.</p>

<div class="memer">
    <h2 class="thankyou">Create A Badge</h2>
    <div class="memer--inner-wrapper">
        <div class="canvas-wrapper">
            <canvas id="canvas"  width="900" height="900"></canvas>
            <div id="textarea-anchor"></div>
        </div>
            <label for="memer--input" id="memer--choose" class="button expand">Add your selfie&hellip;</label>
            <input type="file" id="memer--input" class="hide" />
            <span id="memer--add-text" class="button expand memer--button-off">Add your issue&hellip;</span>
            <a id="memer--save" class="button expand memer--button-off" href="#">Download</a>
    </div>
</div>

<script src="http://cdn.foundation5.zurb.com/foundation.js"></script>
<script src="/static/js/fabric.min.js"></script>
<script src="/static/js/jquery.scrollintoview.min.js"></script>
<script src="/static/js/exif.min.js"></script>
<script src="/static/js/memer.js"></script>
	
<h2 class="thankyou">Share your pledge to vote with friends on Twitter and Facebook!</h2>
	
<div class="share-page">
    <span><a href="https://twitter.com/intent/tweet?text={{ page.twittertext }}&url={{ site.url }}{{ page.sharelink | }}&via={{ site.twitter_username }}&related={{ site.twitter_username }}" rel="nofollow" target="_blank" title="Share on Twitter">Share on Twitter</a></span>
    <span><a href="https://www.facebook.com/sharer/sharer.php?u={{ site.url }}{{ page.sharelink }}">Share on Facebook</a></span>
</div>