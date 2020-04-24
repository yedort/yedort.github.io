<!doctype html>
<html>
<head>
<title>Yalcin Erdemir (yedort)</title>
<meta charset="utf-8"/>
<meta name="description" content="Yalcin Erdemir (yedort)"/>
<link rel="canonical" href="https://yedort.com"/>
<meta name="viewport" content="width=device-width,initial-scale=1,minimum-scale=1"/>
<meta name="HandheldFriendly" content="true"/>
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-127508830-1"></script>
<script>window.dataLayer = window.dataLayer || [];function gtag(){dataLayer.push(arguments);}gtag('js', new Date());gtag('config', 'UA-127508830-1');</script>
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css"/>
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css"/>
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Roboto:400,700"/>
<style>
body{cursor:default;background:#f1f1f1;color:#fff;text-shadow:#6a6a6a 1px 1px 2px;padding:35px 0;font-family:Roboto, sans-serif;font-weight:bold;font-size:19px}
a, a:hover, a:focus{cursor:pointer;color:#fff}
ul{margin-bottom:0}
.main-block{background:#dbdbdb;border:1px solid #c3c3c3;border-left:none;border-right:none;margin:0 auto;width:50%;height:220px;padding:40px;-webkit-border-top-left-radius: 15px;-moz-border-radius-topleft: 15px;border-top-left-radius: 15px;-webkit-border-bottom-right-radius: 15px;-moz-border-radius-bottomright: 15px;border-bottom-right-radius: 15px}
.info{float:left;width:62%}
.links{float:right;width:34%;line-height:35px;text-align:center}
.links li{margin:0 8px}
.links li a:hover{color:#efefef}
@media screen and (max-width:700px){
body{padding:0}
.main-block{width:100%;height:100%;-webkit-border-radius:0;-moz-border-radius:0;border-radius:0}
.info, .links{width:100%}
.links{margin-top:32px}
}
</style>
</head>
<body>
<div class="main-block">
	<div class="col-md-12 info">
		<div><span data-title="Name">Umut Yalçın Erdemir</span></div>
		<div><span data-title="Birth">4 Nov 1993, Manisa/Turkey</span></div>
		<div><span data-title="Languages">Turkish (TR), English (US)</span></div>
		<div><span data-title="Profession">Programmer</span></div>
		<div><span data-title="Nicknames"><del>y4lcin</del>, yedort</span></div>
	</div>
	<div class="col-md-12 links">
		<ul class="list-unstyled list-inline">
			<li><a href="http://facebook.com/yedort" target="_blank"><i class="fa fa-facebook"></i></a></li>
			<li><a href="http://instagram.com/yalcin.erdemir" target="_blank"><i class="fa fa-instagram"></i></a></li>
			<li><a href="http://soundcloud.com/yedort" target="_blank"><i class="fa fa-soundcloud"></i></a></li>
			<li><a href="http://open.spotify.com/user/11120219805" target="_blank"><i class="fa fa-spotify"></i></a></li>
			<li><a href="http://youtube.com/user/y4lcin" target="_blank"><i class="fa fa-youtube"></i></a></li>
			<li><a href="http://tunein.com/user/yedort" target="_blank"><i class="fa fa-podcast"></i></a></li>
			<li><a href="http://twitter.com/yedort" target="_blank"><i class="fa fa-twitter"></i></a></li>
			<li><a href="http://yedort.tumblr.com" target="_blank"><i class="fa fa-tumblr"></i></a></li>
			<li><a href="http://linkedin.com/in/yedort" target="_blank"><i class="fa fa-linkedin"></i></a></li>
			<li><a href="http://github.com/yedort" target="_blank"><i class="fa fa-github"></i></a></li>
			<li><a href="http://stackexchange.com/users/2825632/yedort?tab=accounts" target="_blank"><i class="fa fa-stack-exchange"></i></a></li>
			<li><a href="http://www.duolingo.com/profile/yedort" target="_blank"><i class="fa fa-language"></i></a></li>
		</ul>
	</div>
	<div class="clearfix"></div>
</div>
</body>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<script>
$(document).ready(function(){

	String.prototype.strip = function(text){
		return String(this).replace(/<|>/gi, 'ESCAPER$&').replace(new RegExp('^\\b' + text + '\\b|\\b' + text + '\\b$', 'gi'), '').replace(/ESCAPER/gi, '');
	}

	var text;

	$('.info span').hover(function(){
		text = $(this).data('title') + ': ';
		$(this).prepend(text);
	}, function(){
		$(this).html($(this).html().strip(text));
	});
	
});
</script>
</html>
