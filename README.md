# html-meta-tags

Inspired by/copied from http://code.lancepollard.com/complete-list-of-html-meta-tags/

Copied from https://gist.github.com/kevinSuttle/1997924  

## Basic HTML Meta Tags

```html
<meta charset="utf-8"/> <!-- declares the page"s character encoding -->
<meta charset="UTF-8">
<meta name="keywords" content="your, tags">
<meta name="description" content="160 words">
<meta name="subject" content="your website’s subject">
<meta name="copyright" content="company name">
<meta name="language" content="EN">
<meta name="robots" content="index,follow">
<meta name="revised" content="Sunday, July 18th, 2010, 5:15 pm">
<meta name="abstract" content="">
<meta name="topic" content="">
<meta name="summary" content="">
<meta name="Classification" content="Business">
<meta name="author" content="name, email@hotmail.com">
<meta name="designer" content="">
<meta name="reply-to" content="email@hotmail.com">
<meta name="owner" content="">
<meta name="url" content="http://www.websiteaddress.com">
<meta name="identifier-URL" content="http://www.websiteaddress.com">
<meta name="directory" content="submission">
<meta name="pagename" content="jQuery Tools, Tutorials and Resources - O’Reilly Media">
<meta name="category" content="">
<meta name="coverage" content="Worldwide">
<meta name="distribution" content="Global">
<meta name="rating" content="General">
<meta name="revisit-after" content="7 days">
<meta name="subtitle" content="This is my subtitle">
<meta name="target" content="all">
<meta name="HandheldFriendly" content="True">
<meta name="MobileOptimized" content="320">
<meta name="date" content="Sep. 27, 2010">
<meta name="search_date" content="2010-09-27">
<meta name="DC.title" content="Unstoppable Robot Ninja">
<meta name="ResourceLoaderDynamicStyles" content="">
<meta name="medium" content="blog">
<meta name="syndication-source" content="https://mashable.com/2008/12/24/free-brand-monitoring-tools/">
<meta name="original-source" content="https://mashable.com/2008/12/24/free-brand-monitoring-tools/">
<meta name="verify-v1" content="dV1r/ZJJdDEI++fKJ6iDEl6o+TMNtSu0kv18ONeqM0I=">
<meta name="y_key" content="1e39c508e0d87750">
<meta name="pageKey" content="guest-home">
<meta name="theme-color" content="#3c790a">
<meta itemprop="name" content="jQTouch">
<meta http-equiv="Expires" content="0">
<meta http-equiv="Pragma" content="no-cache">
<meta http-equiv="Cache-Control" content="no-cache">
<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
<meta http-equiv="imagetoolbar" content="no">
<meta http-equiv="x-dns-prefetch-control" content="off">
<meta http-equiv="X-UA-Compatible" content="chrome=1">
<meta name="viewport" content="width=320,initial-scale=1,user-scalable=no">
<meta name="viewport" content="width=device-width">
<meta name="viewport" content="initial-scale=1.0">
<meta name="viewport" content="initial-scale=2.3,user-scalable=no">
```

##  Meta Tags social

```html
<meta property="og:title" content="title of article">
<meta property="og:type" content="blog">
<meta property="og:image" content="image url">
<meta property="og:url" content="url">
<meta property="og:description" content="description">
```

## OpenGraph Meta Tags

```html
<meta property="og:title" content="The Rock"/>
<meta property="og:type" content="movie"/>
<meta property="og:url" content="http://www.imdb.com/title/tt0117500/"/>
<meta property="og:image" content="http://ia.media-imdb.com/rock.jpg"/>
<meta property="og:site_name" content="IMDb"/>
<meta property="og:description" content="A group of U.S. Marines, under command of..."/>

<meta property="fb:page_id" content="43929265776" />
<meta property="application-name" content="foursquare">
<meta property="og:email" content="me@example.com"/>
<meta property="og:phone_number" content="650-123-4567"/>
<meta property="og:fax_number" content="+1-415-123-4567"/>

<meta property="og:latitude" content="37.416343"/>
<meta property="og:longitude" content="-122.153013"/>
<meta property="og:street-address" content="1601 S California Ave"/>
<meta property="og:locality" content="Palo Alto"/>
<meta property="og:region" content="CA"/>
<meta property="og:postal-code" content="94304"/>
<meta property="og:country-name" content="USA"/>

<meta property="fb:admins" content="987654321">
<meta property="og:type" content="game.achievement">
<meta property="og:points" content="POINTS_FOR_ACHIEVEMENT">

<meta property="og:video" content="http://example.com/awesome.swf">
<meta property="og:video:height" content="640">
<meta property="og:video:width" content="385">
<meta property="og:video:type" content="application/x-shockwave-flash">
<meta property="og:video" content="http://example.com/html5.mp4">
<meta property="og:video:type" content="video/mp4">
<meta property="og:video" content="http://example.com/fallback.vid">
<meta property="og:video:type" content="text/html">

<meta property="og:audio" content="http://example.com/amazing.mp3">
<meta property="og:audio:title" content="Amazing Song">
<meta property="og:audio:artist" content="Amazing Band">
<meta property="og:audio:album" content="Amazing Album">
<meta property="og:audio:type" content="application/mp3">
```

## Twitter Meta Tags

```html
<meta name="twitter:card" content="summary_large_image" />
<meta name="twitter:site" content="@whoisryosuke" />
<meta name="twitter:title" content="Presentation Title" />
<meta name="twitter:description" content="A really great presentation" />
<meta name="twitter:image" content="https://pbs.twimg.com/profile_images/979408111868952576/yq2IUoGt_bigger.jpg" />
```

## Create Custom Meta Tags

Use custom meta tags to store data that you need in Javascript, instead of hard-coding that data into your Javascript.  I store my Google Analytics code in meta tags.  Here"s some examples:

```html
<meta name="google-analytics" content="1-AHFKALJ">
<meta name="google-site-verification" content=" ... GWT ID ... " />
<meta name="disqus" content="abcdefg">
<meta name="uservoice" content="asdfasdf">
<meta name="mixpanel" content="asdfasdf">
<meta name="google" content="notranslate">
```

## Company/Service Meta Tags

#### ClaimID

```html
<meta name="microid" content="mailto+http:sha1:e6058ed7fca4a1921cq91d7f1f3b8736cd3cc1g7">
<meta name="readability-verification" content="E7aEHvVQpWc8VHDqKvaB2Z58hek2EAv2HuLuegv7">
<meta name="google-site-verification" content="4SMIedO1X4IkYrYuhEC2VuovdQM36Xxb0btUjElqQyg">
<meta name="ICBM" content="40.746990, -73.980537">
<meta name="generator" content="WordPress 3.3.1">
<meta name="norton-safeweb-site-verification" content="tz8iotmk-pkhui406y41y5bfmfxdwmaa4a-yc0hm6r0fga7s6j0j27qmgqkmc7oovihzghbzhbdjk-uiyrz438nxsjdbj3fggwgl8oq2nf4ko8gi7j4z7t78kegbidl4">
```

#### Apple Meta Tags

```html
<meta name="apple-mobile-web-app-title" content="My App"> <!-- New in iOS6 -->
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-touch-fullscreen" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black">
<meta name="format-detection" content="telephone=no">
<meta name="viewport" content="width = 320;        initial-scale=1.0; maximum-scale=1.0; user-scalable=yes; target-densitydpi=160dpi">
<meta name="viewport" content="width=device-width; initial-scale=1.0; maximum-scale=1.0; user-scalable=yes; target-densitydpi=160dpi, minimal-ui">
<meta name="viewport" content="width = 320, initial-scale = 2.3, user-scalable = no">
<meta name="viewport" content="width = device-width">
<meta name="viewport" content="initial-scale = 1.0">
<meta name="viewport" content="initial-scale = 2.3, user-scalable = no">

<link rel="apple-touch-icon" sizes="144x144" href="assets/ico.apple-ipad@2x.png" />
<link rel="apple-touch-icon" sizes="72x72" href="assets/ico/apple-ipad.png" />
<link rel="apple-touch-icon" sizes="114x114" href="assets/ico/apple-iphone@2x.png" />
<link rel="apple-touch-icon" sizes="57x57" href="assets/ico/apple-iphone.png" />
<link rel="apple-touch-startup-image" href="assets/img/startup.png" />
<link rel="apple-touch-icon" href="touch-icon-iphone.png" type="image/png" />
<link rel="apple-touch-icon" type="image/png" href="/apple-touch-icon.png" />
<link href="http://github.com/images/touch-icon-iphone4.png" sizes="114x114" rel="apple-touch-icon-precomposed">
<link href="http://github.com/images/touch-icon-ipad.png" sizes="72x72" rel="apple-touch-icon-precomposed">
<link href="http://github.com/images/apple-touch-icon-57x57.png" sizes="57x57" rel="apple-touch-icon-precomposed">
```

##### Safari 9 Pinned tabs in El Capitan

```html
<link rel="mask-icon" href="website_icon.svg" color="red">
```

#### Internet Explorer Meta Tags

```html
<meta http-equiv="Page-Enter" content="RevealTrans(Duration=2.0,Transition=2)">
<meta http-equiv="Page-Exit" content="RevealTrans(Duration=3.0,Transition=12)">
<meta name="mssmarttagspreventparsing" content="true">
<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />
<meta name="msapplication-starturl" content="http://blog.reybango.com/about/">
<meta name="msapplication-window" content="width=800;height=600">
<meta name="msapplication-navbutton-color" content="red">
<meta name="application-name" content="Rey Bango Front-end Developer">
<meta name="msapplication-tooltip" content="Launch Rey Bango’s Blog">
<meta name="msapplication-task" content="name=About;action-uri=/about/;icon-uri=/images/about.ico">
<meta name="msapplication-task" content="name=The Big List;action-uri=/the-big-list-of-javascript-css-and-html-development-tools-libraries-projects-and-books/;icon-uri=/images/list_links.ico">
<meta name="msapplication-task" content="name=jQuery Posts;action-uri=/category/jquery/;icon-uri=/images/jquery.ico">
<meta name="msapplication-task" content="name=Start Developing;action-uri=/category/javascript/;icon-uri=/images/script.ico">
<meta name="msvalidate.01" content="6E3AD52DC176461A3C81DD6E98003BC9">
<meta http-equiv="cleartype" content="on">
<link rel="shortcut icon" href="/images/favicon.ico" />
```

#### Windows 8 Meta Tags

``` html
<meta name="application-name" content="Contoso" />
<meta name="msapplication-TileColor" content="#009900" />
<meta name="msapplication-square70x70logo" content="images/smalltile.png" />
<meta name="msapplication-square150x150logo" content="images/mediumtile.png" />
<meta name="msapplication-wide310x150logo" content="images/widetile.png" />
<meta name="msapplication-square310x310logo" content="images/largetile.png" />
<meta name="msapplication-notification" content="frequency=30; polling-uri=notifications/contoso1.xml; polling-uri2=notifications/contoso2.xml; polling-uri3=notifications/contoso3.xml" />
```

#### Google Meta Tags

```html
<meta name="news_keywords" content="World Cup, Brazil 2014, Spain vs Netherlands, soccer, football">
```

#### Twitter Cards

```html
<meta name="twitter:card" content="summary" />
<meta name="twitter:site" content="@flickr" />
<meta name="twitter:site.id" content="@flickr" />
<meta name="twitter:creator" content="@flickr" />
<meta name="twitter:creator.id" content="@flickr" />
<meta name="twitter:title" content="Small Island Developing States Photo Submission" />
<meta name="twitter:description" content="View the album on Flickr." />
<meta name="twitter:image" content="https://farm6.staticflickr.com/5510/14338202952_93595258ff_z.jpg" />
<meta name="twitter:image.alt" content="A text description of the image conveying the essential nature of an image to users who are visually impaired." />

<meta name="twitter:player" content="https://urlofplayeriframe.com" />
<meta name="twitter:player" content="https://www.w3schools.com/html/mov_bbb.html">
<meta name="twitter:player:stream" content="https://www.w3schools.com/html/mov_bbb.mp4">
<meta name="twitter:player:height" content="320">
<meta name="twitter:player:width" content="600">
<meta name="twitter:domain" content="www.w3schools.com">

<meta name="twitter:app:country" content="US">
<meta name="twitter:app:name:iphone" content="Cannonball">
<meta name="twitter:app:id:iphone" content="929750075">
<meta name="twitter:app:url:iphone" content="cannonball://poem/5149e249222f9e600a7540ef">
<meta name="twitter:app:name:ipad" content="Cannonball">
<meta name="twitter:app:id:ipad" content="929750075">
<meta name="twitter:app:url:ipad" content="cannonball://poem/5149e249222f9e600a7540ef">
<meta name="twitter:app:name:googleplay" content="Cannonball">
<meta name="twitter:app:id:googleplay" content="io.fabric.samples.cannonball">
<meta name="twitter:app:url:googleplay" content="http://cannonball.fabric.io/poem/5149e249222f9e600a7540ef">
```

#### TweetMeme Meta Tags

```html
<meta name="tweetmeme-title" content="Retweet Button Explained">
```

#### Blog Catalog Meta Tags

```html
<meta name="blogcatalog">
```

#### Rails Meta Tags

```html
<meta name="csrf-param" content="authenticity_token">
<meta name="csrf-token" content="/bZVwvomkAnwAI1Qd37lFeewvpOIiackk9121fFwWwc=">
```

#### Apple Tags

```html
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black">
<meta name="format-detection" content="telephone=no">
<link rel="apple-touch-icon" href="touch-icon-iphone.png" />
<link rel="apple-touch-icon" sizes="72x72" href="touch-icon-ipad.png" />
<link rel="apple-touch-icon" sizes="114x114" href="touch-icon-iphone4.png" />
<link rel="apple-touch-startup-image" href="/startup.png">

<link rel="apple-touch-icon" type="image/png" href="/apple-touch-icon.png" />
```
    
## HTML Link Tags

```html
<link rel="alternate" type="application/rss+xml" title="RSS" href="http://feeds.feedburner.com/martini">
<link rel="alternate" type="application/atom+xml" title="Atom 0.3" href="https://example.com/feed.atom">
<link rel="shortcut icon" type="image/ico" href="/favicon.ico">
<link rel="fluid-icon" type="image/png" href="/fluid-icon.png">
<link rel="me" type="text/html" href="http://google.com/profiles/thenextweb">
<link rel="shortlink" href="http://blog.unto.net/?p=353">
<link rel="archives" title="May 2003" href="http://blog.unto.net/2003/05/">
<link rel="index" title="DeWitt Clinton" href="http://blog.unto.net/">
<link rel="start" title="Pattern Recognition 1" href="http://blog.unto.net/photos/pattern_recognition_1_about/">
<link rel="bookmark" title="Styleguide" href="http://paulrobertlloyd.com/about/styleguide/">
<link rel="search" href="/search.xml" type="application/opensearchdescription+xml" title="Viatropos">

<link rel="self" type="application/atom+xml" href="http://www.syfyportal.com/atomFeed.php?page=3">
<link rel="first" href="http://www.syfyportal.com/atomFeed.php">
<link rel="next" title="Not blog" href="http://blog.unto.net/meta/not-blog/" />
<link rel="next" href="http://www.syfyportal.com/atomFeed.php?page=4">
<link rel="prev" title="OpenSearch and OpenID?  A sure way to get my attention." href="http://blog.unto.net/opensearch/opensearch-and-openid-a-sure-way-to-get-my-attention/" />
<link rel="previous" href="http://www.syfyportal.com/atomFeed.php?page=2">
<link rel="last" href="http://www.syfyportal.com/atomFeed.php?page=147">

<link rel="shortlink" href="http://smallbiztrends.com/?p=43625" />
<link rel="canonical" href="http://smallbiztrends.com/2010/06/9-things-to-do-before-entering-social-media.html">
<link rel="EditURI" type="application/rsd+xml" title="RSD" href="http://smallbiztrends.com/xmlrpc.php?rsd">
<link rel="pingback" href="http://smallbiztrends.com/xmlrpc.php">
<link rel="stylesheet" media="only screen and (max-device-width: 480px)" href="http://wordpress.org/style/iphone.css" type="text/css">
<link rel="wlwmanifest" href="http://www.example.com/wp-includes/wlwmanifest.xml" type="application/wlwmanifest+xml">

<link rel="manifest" href="/manifest.json" />

<link rel="help" title="FAQ" href="/faq">
<link rel="logo" type="image/svg" href="https://playfoursquare.s3.amazonaws.com/press/logo/foursquare-logo.svg">
<link rel="P3Pv1" href="/w3c/p3p.xml">
<link rel="publisher" href="https://plus.google.com/115081025762845243709/">
<link rel="image_src" href="http://du3itj18e4z0b.cloudfront.net/7b29fe/images/icon-facebook.gif" type="image/jpeg">

<link rel="author" href="humans.txt" type="text/plain">
<link rel="original-source" href="http://thenextweb.com/2009/01/08/how-to-snap-up-that-twitter-username-youve-always-wanted/">
<link rel="profile" title="Microformats" href="http://microformats.org/profile/specs/">
<link rel="profile" href="http://gmpg.org/xfn/11">
<link rel="chrome-webstore-item" href="https://chrome.google.com/webstore/detail/noojglkidnpfjbincgijbaiedldjfbhh">
```

#### Theme Color Meta Tags

```html
<meta name="theme-color" content="#202020"/>
```

## DNS Tags

```html
<link rel="dns-prefetch" href="https://www.gstatic.com/">
```

## Content Tags

```html
<link rel="canonical" href="originalMain.web.com" />
```

## Templates

### Article

```html
<!-- Update your html tag to include the itemscope and itemtype attributes. -->
<html itemscope itemtype="http://schema.org/Article">

<!-- Place this data between the <head> tags of your website -->
<title>Page Title. Maximum length 60-70 characters</title>
<meta name="description" content="Page description. No longer than 155 characters." />

<!-- Schema.org markup for Google+ -->
<meta itemprop="name" content="The Name or Title Here">
<meta itemprop="description" content="This is the page description">
<meta itemprop="image" content="http://www.example.com/image.jpg">

<!-- Twitter Card data -->
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:site" content="@publisher_handle">
<meta name="twitter:title" content="Page Title">
<meta name="twitter:description" content="Page description less than 200 characters">
<meta name="twitter:creator" content="@author_handle">
<!-- Twitter summary card with large image must be at least 280x150px -->
<meta name="twitter:image:src" content="http://www.example.com/image.jpg">

<!-- Open Graph data -->
<meta property="og:title" content="Title Here" />
<meta property="og:type" content="article" />
<meta property="og:url" content="http://www.example.com/" />
<meta property="og:image" content="http://example.com/image.jpg" />
<meta property="og:description" content="Description Here" />
<meta property="og:site_name" content="Site Name, i.e. Moz" />
<meta property="article:published_time" content="2013-09-17T05:59:00+01:00" />
<meta property="article:modified_time" content="2013-09-16T19:08:47+01:00" />
<meta property="article:section" content="Article Section" />
<meta property="article:tag" content="Article Tag" />
<meta property="fb:admins" content="Facebook numberic ID" />
```

### Product

```html
<!-- Update your html tag to include the itemscope and itemtype attributes. -->
<html itemscope itemtype="http://schema.org/Product">

<!-- Place this data between the <head> tags of your website -->
<title>Page Title. Maximum length 60-70 characters</title>
<meta name="description" content="Page description. No longer than 155 characters." />

<!-- Schema.org markup for Google+ -->
<meta itemprop="name" content="The Name or Title Here">
<meta itemprop="description" content="This is the page description">
<meta itemprop="image" content="http://www.example.com/image.jpg">

<!-- Twitter Card data -->
<meta name="twitter:card" content="product">
<meta name="twitter:site" content="@publisher_handle">
<meta name="twitter:title" content="Page Title">
<meta name="twitter:description" content="Page description less than 200 characters">
<meta name="twitter:creator" content="@author_handle">
<meta name="twitter:image" content="http://www.example.com/image.jpg">
<meta name="twitter:data1" content="$3">
<meta name="twitter:label1" content="Price">
<meta name="twitter:data2" content="Black">
<meta name="twitter:label2" content="Color">

<!-- Open Graph data -->
<meta property="og:title" content="Title Here" />
<meta property="og:type" content="article" />
<meta property="og:url" content="http://www.example.com/" />
<meta property="og:image" content="http://example.com/image.jpg" />
<meta property="og:description" content="Description Here" />
<meta property="og:site_name" content="Site Name, i.e. Moz" />
<meta property="og:price:amount" content="15.00" />
<meta property="og:price:currency" content="USD" />
```

## Testing

To test if your meta data is valid, there are several services:

- [Facebook Meta Tags](https://developers.facebook.com/tools/debug/)
- [Google Structured Data (Open Graph) Testing Tootl](https://search.google.com/structured-data/testing-tool/u/0/)
- [Twitter Card Validator](https://cards-dev.twitter.com/validator)

## Other Resources

- [Apple Meta Tags](https://developer.apple.com/library/archive/documentation/AppleApplications/Reference/SafariHTMLRef/Articles/MetaTags.html)
- [HTML5 Boilerplate explanations and suggestions of header tags](http://html5boilerplate.com/docs/head-Tips/)
- [Dublic Core Meta Tags](http://www.seoconsultants.com/meta-tags/dublin/)
- [Apple Meta Tags](http://developer.apple.com/safari/library/documentation/appleapplications/reference/safarihtmlref/articles/metatags.html)
- [OpenGraph Meta Tags](http://opengraphprotocol.org/)
- [Facebook Open Graph](https://developers.facebook.com/docs/sharing/webmasters)
- [Twitter Cards Markup Tag Reference](https://dev.twitter.com/cards/markup)
- [Link Tag Meaning](http://intertwingly.net/wiki/pie/LinkTagMeaning)
- [Google Chrome HTML5 Tags](http://www.html5rocks.com/)
- [HTML meta 详解](https://segmentfault.com/a/1190000009705754)
- [MDN The Document-level Metadata element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta)
- [移动前端开发之viewport的深入理解](https://www.cnblogs.com/2050/p/3877280.html)
- [A tale of two viewports ](https://www.quirksmode.org/mobile/viewports.html)
- [Theme Color](https://github.com/whatwg/meta-theme-color)

## Credits

- Originally copied from http://code.lancepollard.com/complete-list-of-html-meta-tags/
- Added templates from https://moz.com/blog/meta-data-templates-123


