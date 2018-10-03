---
layout: fullwidth
title: '#OurAAPIVote | Pledge to Vote'
menutitle: 'Pledge to Vote'
permalink: /pledge/
featured-image: /static/images/featured/pledge2016.png
description: "I just pledged to vote and created a #MYAAPIVOTE badge to share the issue I’m most passionate about. Join me by pledging to vote and create a badge about why YOU vote!"
weight: 15
---

<link href='https://actionnetwork.org/css/style-embed-whitelabel.css' rel='stylesheet' type='text/css' /><script>window.yepnope || document.write('<script src="https://actionnetwork.org/includes/js/yepnope154-min.js"><\/script>');</script><script src='https://actionnetwork.org/widgets/v2/petition/join-18mr-in-pledging-to-vote-myaapivote?format=js&source=vote-widget&style=full'></script><div id='can-petition-area-join-18mr-in-pledging-to-vote-myaapivote' style='width: 100%; margin-top: 15px;'><!-- this div is the target for our HTML insertion --></div>
<script>
	$(document).ready(function() {
		$('#can-petition-area-join-18mr-in-pledging-to-vote-myaapivote').on('can_embed_loaded', function() {
			document.getElementsByName("commit")[0].value = "Pledge to Vote";
			$(".action_sidebar h4").text("Pledge to Vote");
			var str = document.getElementsByClassName("action_status_running_total")[0].innerHTML;
			var txt = str.replace("Signatures Collected", "Pledges Made");
			document.getElementsByClassName("action_status_running_total")[0].innerHTML = txt;
			document.getElementById('form-comments').style.display="none";
			});
	});
</script>