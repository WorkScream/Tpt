<html class=" js no-touch svg no-firefox no-ie no-mac no-linux webkit safari  win"><head>
<title>Live preview for Website Template #52500</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta charset="utf-8"><script type="text/javascript" src="http://bam.nr-data.net/1/72d7dcce33?a=2939783,4702774&amp;pl=1429998465921&amp;v=632.2b17625&amp;to=ZV1TZ0FTVkFVWkwKXlwXckZARldfG11dDl4%3D&amp;ap=1&amp;be=1853&amp;fe=18178&amp;dc=567&amp;f=%5B%22err%22,%22xhr%22%5D&amp;perf=%7B%22timing%22:%7B%22of%22:1429998465921,%22n%22:0,%22dl%22:1804,%22di%22:2420,%22ds%22:2420,%22de%22:2542,%22dc%22:20031,%22l%22:20031,%22le%22:20040,%22f%22:0,%22dn%22:0,%22dne%22:0,%22c%22:0,%22ce%22:0,%22rq%22:4,%22rp%22:1803,%22rpe%22:1918%7D,%22navigation%22:%7B%7D%7D&amp;at=SRpQEQlJRU8%3D&amp;jsonp=NREUM.setToken"></script><script src="http://js-agent.newrelic.com/nr-632.min.js"></script><script type="text/javascript" async="" src="https://www.google-analytics.com/plugins/ua/linkid.js"></script><script type="text/javascript" async="" src="//www.googleadservices.com/pagead/conversion_async.js"></script><script async="" src="//connect.facebook.net/en_US/fbds.js"></script><script type="text/javascript" async="" src="https://www.google-analytics.com/analytics.js"></script><script type="text/javascript" async="" src="//www.googleadservices.com/pagead/conversion_async.js"></script><script type="text/javascript" async="" src="http://www.google-analytics.com/plugins/ga/inpage_linkid.js" id="undefined"></script><script type="text/javascript" async="" src="http://www.google-analytics.com/ga.js"></script><script async="" src="//www.googletagmanager.com/gtm.js?id=GTM-MS2BNB"></script><script type="text/javascript">(window.NREUM||(NREUM={})).loader_config={xpid:"VQQHVVRXGwEJV1hVDwI="};window.NREUM||(NREUM={}),__nr_require=function(t,e,n){function r(n){if(!e[n]){var o=e[n]={exports:{}};t[n][0].call(o.exports,function(e){var o=t[n][1][e];return r(o?o:e)},o,o.exports)}return e[n].exports}if("function"==typeof __nr_require)return __nr_require;for(var o=0;o<n.length;o++)r(n[o]);return r}({QJf3ax:[function(t,e){function n(t){function e(e,n,a){t&&t(e,n,a),a||(a={});for(var c=s(e),u=c.length,f=i(a,o,r),d=0;u>d;d++)c[d].apply(f,n);return f}function a(t,e){u[t]=s(t).concat(e)}function s(t){return u[t]||[]}function c(){return n(e)}var u={};return{on:a,emit:e,create:c,listeners:s,_events:u}}function r(){return{}}var o="nr@context",i=t("gos");e.exports=n()},{gos:"7eSDFh"}],ee:[function(t,e){e.exports=t("QJf3ax")},{}],3:[function(t){function e(t){try{i.console&&console.log(t)}catch(e){}}var n,r=t("ee"),o=t(1),i={};try{n=localStorage.getItem("__nr_flags").split(","),console&&"function"==typeof console.log&&(i.console=!0,-1!==n.indexOf("dev")&&(i.dev=!0),-1!==n.indexOf("nr_dev")&&(i.nrDev=!0))}catch(a){}i.nrDev&&r.on("internal-error",function(t){e(t.stack)}),i.dev&&r.on("fn-err",function(t,n,r){e(r.stack)}),i.dev&&(e("NR AGENT IN DEVELOPMENT MODE"),e("flags: "+o(i,function(t){return t}).join(", ")))},{1:20,ee:"QJf3ax"}],4:[function(t){function e(t,e,n,i,s){try{c?c-=1:r("err",[s||new UncaughtException(t,e,n)])}catch(u){try{r("ierr",[u,(new Date).getTime(),!0])}catch(f){}}return"function"==typeof a?a.apply(this,o(arguments)):!1}function UncaughtException(t,e,n){this.message=t||"Uncaught error with no additional information",this.sourceURL=e,this.line=n}function n(t){r("err",[t,(new Date).getTime()])}var r=t("handle"),o=t(6),i=t("ee"),a=window.onerror,s=!1,c=0;t("loader").features.err=!0,t(3),window.onerror=e;try{throw new Error}catch(u){"stack"in u&&(t(4),t(5),"addEventListener"in window&&t(1),window.XMLHttpRequest&&XMLHttpRequest.prototype&&XMLHttpRequest.prototype.addEventListener&&window.XMLHttpRequest&&XMLHttpRequest.prototype&&XMLHttpRequest.prototype.addEventListener&&!/CriOS/.test(navigator.userAgent)&&t(2),s=!0)}i.on("fn-start",function(){s&&(c+=1)}),i.on("fn-err",function(t,e,r){s&&(this.thrown=!0,n(r))}),i.on("fn-end",function(){s&&!this.thrown&&c>0&&(c-=1)}),i.on("internal-error",function(t){r("ierr",[t,(new Date).getTime(),!0])})},{1:5,2:8,3:3,4:7,5:6,6:21,ee:"QJf3ax",handle:"D5DuLP",loader:"G9z0Bl"}],5:[function(t,e){function n(t){i.inPlace(t,["addEventListener","removeEventListener"],"-",r)}function r(t){return t[1]}var o=(t(1),t("ee").create()),i=t(2)(o),a=t("gos");if(e.exports=o,n(window),"getPrototypeOf"in Object){for(var s=document;s&&!s.hasOwnProperty("addEventListener");)s=Object.getPrototypeOf(s);s&&n(s);for(var c=XMLHttpRequest.prototype;c&&!c.hasOwnProperty("addEventListener");)c=Object.getPrototypeOf(c);c&&n(c)}else XMLHttpRequest.prototype.hasOwnProperty("addEventListener")&&n(XMLHttpRequest.prototype);o.on("addEventListener-start",function(t){if(t[1]){var e=t[1];"function"==typeof e?this.wrapped=t[1]=a(e,"nr@wrapped",function(){return i(e,"fn-",null,e.name||"anonymous")}):"function"==typeof e.handleEvent&&i.inPlace(e,["handleEvent"],"fn-")}}),o.on("removeEventListener-start",function(t){var e=this.wrapped;e&&(t[1]=e)})},{1:21,2:22,ee:"QJf3ax",gos:"7eSDFh"}],6:[function(t,e){var n=(t(2),t("ee").create()),r=t(1)(n);e.exports=n,r.inPlace(window,["requestAnimationFrame","mozRequestAnimationFrame","webkitRequestAnimationFrame","msRequestAnimationFrame"],"raf-"),n.on("raf-start",function(t){t[0]=r(t[0],"fn-")})},{1:22,2:21,ee:"QJf3ax"}],7:[function(t,e){function n(t,e,n){t[0]=o(t[0],"fn-",null,n)}var r=(t(2),t("ee").create()),o=t(1)(r);e.exports=r,o.inPlace(window,["setTimeout","setInterval","setImmediate"],"setTimer-"),r.on("setTimer-start",n)},{1:22,2:21,ee:"QJf3ax"}],8:[function(t,e){function n(){u.inPlace(this,p,"fn-")}function r(t,e){u.inPlace(e,["onreadystatechange"],"fn-")}function o(t,e){return e}function i(t,e){for(var n in t)e[n]=t[n];return e}var a=t("ee").create(),s=t(1),c=t(2),u=c(a),f=c(s),d=window.XMLHttpRequest,p=["onload","onerror","onabort","onloadstart","onloadend","onprogress","ontimeout"];e.exports=a,window.XMLHttpRequest=function(t){var e=new d(t);try{a.emit("new-xhr",[],e),f.inPlace(e,["addEventListener","removeEventListener"],"-",o),e.addEventListener("readystatechange",n,!1)}catch(r){try{a.emit("internal-error",[r])}catch(i){}}return e},i(d,XMLHttpRequest),XMLHttpRequest.prototype=d.prototype,u.inPlace(XMLHttpRequest.prototype,["open","send"],"-xhr-",o),a.on("send-xhr-start",r),a.on("open-xhr-start",r)},{1:5,2:22,ee:"QJf3ax"}],9:[function(t){function e(t){var e=this.params,r=this.metrics;if(!this.ended){this.ended=!0;for(var i=0;c>i;i++)t.removeEventListener(s[i],this.listener,!1);if(!e.aborted){if(r.duration=(new Date).getTime()-this.startTime,4===t.readyState){e.status=t.status;var a=t.responseType,u="arraybuffer"===a||"blob"===a||"json"===a?t.response:t.responseText,f=n(u);if(f&&(r.rxSize=f),this.sameOrigin){var d=t.getResponseHeader("X-NewRelic-App-Data");d&&(e.cat=d.split(", ").pop())}}else e.status=0;r.cbTime=this.cbTime,o("xhr",[e,r,this.startTime])}}}function n(t){if("string"==typeof t&&t.length)return t.length;if("object"!=typeof t)return void 0;if("undefined"!=typeof ArrayBuffer&&t instanceof ArrayBuffer&&t.byteLength)return t.byteLength;if("undefined"!=typeof Blob&&t instanceof Blob&&t.size)return t.size;if("undefined"!=typeof FormData&&t instanceof FormData)return void 0;try{return JSON.stringify(t).length}catch(e){return void 0}}function r(t,e){var n=i(e),r=t.params;r.host=n.hostname+":"+n.port,r.pathname=n.pathname,t.sameOrigin=n.sameOrigin}if(window.XMLHttpRequest&&XMLHttpRequest.prototype&&XMLHttpRequest.prototype.addEventListener&&!/CriOS/.test(navigator.userAgent)){t("loader").features.xhr=!0;var o=t("handle"),i=t(2),a=t("ee"),s=["load","error","abort","timeout"],c=s.length,u=t(1);t(4),t(3),a.on("new-xhr",function(){this.totalCbs=0,this.called=0,this.cbTime=0,this.end=e,this.ended=!1,this.xhrGuids={}}),a.on("open-xhr-start",function(t){this.params={method:t[0]},r(this,t[1]),this.metrics={}}),a.on("open-xhr-end",function(t,e){"loader_config"in NREUM&&"xpid"in NREUM.loader_config&&this.sameOrigin&&e.setRequestHeader("X-NewRelic-ID",NREUM.loader_config.xpid)}),a.on("send-xhr-start",function(t,e){var r=this.metrics,o=t[0],i=this;if(r&&o){var u=n(o);u&&(r.txSize=u)}this.startTime=(new Date).getTime(),this.listener=function(t){try{"abort"===t.type&&(i.params.aborted=!0),("load"!==t.type||i.called===i.totalCbs&&(i.onloadCalled||"function"!=typeof e.onload))&&i.end(e)}catch(n){try{a.emit("internal-error",[n])}catch(r){}}};for(var f=0;c>f;f++)e.addEventListener(s[f],this.listener,!1)}),a.on("xhr-cb-time",function(t,e,n){this.cbTime+=t,e?this.onloadCalled=!0:this.called+=1,this.called!==this.totalCbs||!this.onloadCalled&&"function"==typeof n.onload||this.end(n)}),a.on("xhr-load-added",function(t,e){var n=""+u(t)+!!e;this.xhrGuids&&!this.xhrGuids[n]&&(this.xhrGuids[n]=!0,this.totalCbs+=1)}),a.on("xhr-load-removed",function(t,e){var n=""+u(t)+!!e;this.xhrGuids&&this.xhrGuids[n]&&(delete this.xhrGuids[n],this.totalCbs-=1)}),a.on("addEventListener-end",function(t,e){e instanceof XMLHttpRequest&&"load"===t[0]&&a.emit("xhr-load-added",[t[1],t[2]],e)}),a.on("removeEventListener-end",function(t,e){e instanceof XMLHttpRequest&&"load"===t[0]&&a.emit("xhr-load-removed",[t[1],t[2]],e)}),a.on("fn-start",function(t,e,n){e instanceof XMLHttpRequest&&("onload"===n&&(this.onload=!0),("load"===(t[0]&&t[0].type)||this.onload)&&(this.xhrCbStart=(new Date).getTime()))}),a.on("fn-end",function(t,e){this.xhrCbStart&&a.emit("xhr-cb-time",[(new Date).getTime()-this.xhrCbStart,this.onload,e],e)})}},{1:"XL7HBI",2:10,3:8,4:5,ee:"QJf3ax",handle:"D5DuLP",loader:"G9z0Bl"}],10:[function(t,e){e.exports=function(t){var e=document.createElement("a"),n=window.location,r={};e.href=t,r.port=e.port;var o=e.href.split("://");return!r.port&&o[1]&&(r.port=o[1].split("/")[0].split("@").pop().split(":")[1]),r.port&&"0"!==r.port||(r.port="https"===o[0]?"443":"80"),r.hostname=e.hostname||n.hostname,r.pathname=e.pathname,r.protocol=o[0],"/"!==r.pathname.charAt(0)&&(r.pathname="/"+r.pathname),r.sameOrigin=!e.hostname||e.hostname===document.domain&&e.port===n.port&&e.protocol===n.protocol,r}},{}],11:[function(t,e){function n(t){return function(){r(t,[(new Date).getTime()].concat(i(arguments)))}}var r=t("handle"),o=t(1),i=t(2);"undefined"==typeof window.newrelic&&(newrelic=window.NREUM);var a=["setPageViewName","addPageAction","setCustomAttribute","finished","addToTrace","inlineHit","noticeError"];o(a,function(t,e){window.NREUM[e]=n("api-"+e)}),e.exports=window.NREUM},{1:20,2:21,handle:"D5DuLP"}],"7eSDFh":[function(t,e){function n(t,e,n){if(r.call(t,e))return t[e];var o=n();if(Object.defineProperty&&Object.keys)try{return Object.defineProperty(t,e,{value:o,writable:!0,enumerable:!1}),o}catch(i){}return t[e]=o,o}var r=Object.prototype.hasOwnProperty;e.exports=n},{}],gos:[function(t,e){e.exports=t("7eSDFh")},{}],handle:[function(t,e){e.exports=t("D5DuLP")},{}],D5DuLP:[function(t,e){function n(t,e,n){return r.listeners(t).length?r.emit(t,e,n):(o[t]||(o[t]=[]),void o[t].push(e))}var r=t("ee").create(),o={};e.exports=n,n.ee=r,r.q=o},{ee:"QJf3ax"}],id:[function(t,e){e.exports=t("XL7HBI")},{}],XL7HBI:[function(t,e){function n(t){var e=typeof t;return!t||"object"!==e&&"function"!==e?-1:t===window?0:i(t,o,function(){return r++})}var r=1,o="nr@id",i=t("gos");e.exports=n},{gos:"7eSDFh"}],G9z0Bl:[function(t,e){function n(){var t=p.info=NREUM.info,e=u.getElementsByTagName("script")[0];if(t&&t.licenseKey&&t.applicationID&&e){s(d,function(e,n){e in t||(t[e]=n)});var n="https"===f.split(":")[0]||t.sslForHttp;p.proto=n?"https://":"http://",a("mark",["onload",i()]);var r=u.createElement("script");r.src=p.proto+t.agent,e.parentNode.insertBefore(r,e)}}function r(){"complete"===u.readyState&&o()}function o(){a("mark",["domContent",i()])}function i(){return(new Date).getTime()}var a=t("handle"),s=t(1),c=(t(2),window),u=c.document,f=(""+location).split("?")[0],d={beacon:"bam.nr-data.net",errorBeacon:"bam.nr-data.net",agent:"js-agent.newrelic.com/nr-632.min.js"},p=e.exports={offset:i(),origin:f,features:{}};u.addEventListener?(u.addEventListener("DOMContentLoaded",o,!1),c.addEventListener("load",n,!1)):(u.attachEvent("onreadystatechange",r),c.attachEvent("onload",n)),a("mark",["firstbyte",i()])},{1:20,2:11,handle:"D5DuLP"}],loader:[function(t,e){e.exports=t("G9z0Bl")},{}],20:[function(t,e){function n(t,e){var n=[],o="",i=0;for(o in t)r.call(t,o)&&(n[i]=e(o,t[o]),i+=1);return n}var r=Object.prototype.hasOwnProperty;e.exports=n},{}],21:[function(t,e){function n(t,e,n){e||(e=0),"undefined"==typeof n&&(n=t?t.length:0);for(var r=-1,o=n-e||0,i=Array(0>o?0:o);++r<o;)i[r]=t[e+r];return i}e.exports=n},{}],22:[function(t,e){function n(t){return!(t&&"function"==typeof t&&t.apply&&!t[i])}var r=t("ee"),o=t(1),i="nr@wrapper",a=Object.prototype.hasOwnProperty;e.exports=function(t){function e(t,e,r,a){function nrWrapper(){var n,i,s,u;try{i=this,n=o(arguments),s=r&&r(n,i)||{}}catch(d){f([d,"",[n,i,a],s])}c(e+"start",[n,i,a],s);try{return u=t.apply(i,n)}catch(p){throw c(e+"err",[n,i,p],s),p}finally{c(e+"end",[n,i,u],s)}}return n(t)?t:(e||(e=""),nrWrapper[i]=!0,u(t,nrWrapper),nrWrapper)}function s(t,r,o,i){o||(o="");var a,s,c,u="-"===o.charAt(0);for(c=0;c<r.length;c++)s=r[c],a=t[s],n(a)||(t[s]=e(a,u?s+o:o,i,s))}function c(e,n,r){try{t.emit(e,n,r)}catch(o){f([o,e,n,r])}}function u(t,e){if(Object.defineProperty&&Object.keys)try{var n=Object.keys(t);return n.forEach(function(n){Object.defineProperty(e,n,{get:function(){return t[n]},set:function(e){return t[n]=e,e}})}),e}catch(r){f([r])}for(var o in t)a.call(t,o)&&(e[o]=t[o]);return e}function f(e){try{t.emit("internal-error",e)}catch(n){}}return t||(t=r),e.inPlace=s,e.flag=i,e}},{1:21,ee:"QJf3ax"}]},{},["G9z0Bl",4,9]);</script>
<meta property="fb:admins" content="720898483">
<meta property="fb:admins" content="1129631948">
<meta property="fb:admins" content="100001777951090">
<link rel="publisher" href="https://plus.google.com/116173187155256042113">
<link rel="icon" href="http://static.templatemonster.com/img/favicon.ico?92f30db" type="image/x-icon">
<link rel="shortcut icon" href="http://static.templatemonster.com/img/favicon.ico?92f30db" type="image/x-icon">
<link href="//fonts.googleapis.com/css?family=PT+Sans:400,700" rel="stylesheet" type="text/css">
<!--[if lt IE 9]>
<link rel="stylesheet" href="http://static.templatemonster.com/css/ie.css?92f30db" media="screen">
<script src="http://static.templatemonster.com/js/html5shiv.js?6cd8a92"></script>
<![endif]-->
<!--[if IE 9]>
<link rel="stylesheet" href="http://static.templatemonster.com/css/compiledie9.css?92f30db" media="screen">
<![endif]-->
<!--[if (gt IE 9)|(!IE)]><!-->
<!--<![endif]-->
<link rel="stylesheet" href="http://static.templatemonster.com/css/livedemo/livedemo.css?92f30db">
<link rel="stylesheet" href="http://static.templatemonster.com/css/livedemo/bootstrap.css?92f30db">
<link rel="stylesheet" href="http://static.templatemonster.com/css/livedemo/responsive.css?92f30db">
<link rel="stylesheet" href="http://static.templatemonster.com/css/livedemo/style.css?92f30db">
<script type="text/javascript">
	window.template = {'id':52500 , 'price':116}
</script><style type="text/css"></style>
<link rel="canonical" href="http://www.templatemonster.com/demo/52500.html">
<style></style>
<style type="text/css" id="vakata-stylesheet">#vakata-dragged { display:block; margin:0 0 0 0; padding:4px 4px 4px 24px; position:absolute; top:-2000px; line-height:16px; z-index:10000; } #vakata-contextmenu { display:block; visibility:hidden; left:0; top:-200px; position:absolute; margin:0; padding:0; min-width:180px; background:#ebebeb; border:1px solid silver; z-index:10000; *width:180px; } #vakata-contextmenu ul { min-width:180px; *width:180px; } #vakata-contextmenu ul, #vakata-contextmenu li { margin:0; padding:0; list-style-type:none; display:block; } #vakata-contextmenu li { line-height:20px; min-height:20px; position:relative; padding:0px; } #vakata-contextmenu li a { padding:1px 6px; line-height:17px; display:block; text-decoration:none; margin:1px 1px 0 1px; } #vakata-contextmenu li ins { float:left; width:16px; height:16px; text-decoration:none; margin-right:2px; } #vakata-contextmenu li a:hover, #vakata-contextmenu li.vakata-hover > a { background:gray; color:white; } #vakata-contextmenu li ul { display:none; position:absolute; top:-2px; left:100%; background:#ebebeb; border:1px solid gray; } #vakata-contextmenu .right { right:100%; left:auto; } #vakata-contextmenu .bottom { bottom:-1px; top:auto; } #vakata-contextmenu li.vakata-separator { min-height:0; height:1px; line-height:1px; font-size:1px; overflow:hidden; margin:0 2px; background:silver; /* border-top:1px solid #fefefe; */ padding:0; } </style><style type="text/css" id="jstree-stylesheet">.jstree ul, .jstree li { display:block; margin:0 0 0 0; padding:0 0 0 0; list-style-type:none; } .jstree li { display:block; min-height:18px; line-height:18px; white-space:nowrap; margin-left:18px; min-width:18px; } .jstree-rtl li { margin-left:0; margin-right:18px; } .jstree > ul > li { margin-left:0px; } .jstree-rtl > ul > li { margin-right:0px; } .jstree ins { display:inline-block; text-decoration:none; width:18px; height:18px; margin:0 0 0 0; padding:0; } .jstree a { display:inline-block; line-height:16px; height:16px; color:black; white-space:nowrap; text-decoration:none; padding:1px 2px; margin:0; } .jstree a:focus { outline: none; } .jstree a > ins { height:16px; width:16px; } .jstree a > .jstree-icon { margin-right:3px; } .jstree-rtl a > .jstree-icon { margin-left:3px; margin-right:0; } li.jstree-open > ul { display:block; } li.jstree-closed > ul { display:none; } #vakata-dragged ins { display:block; text-decoration:none; width:16px; height:16px; margin:0 0 0 0; padding:0; position:absolute; top:4px; left:4px;  -moz-border-radius:4px; border-radius:4px; -webkit-border-radius:4px; } #vakata-dragged .jstree-ok { background:green; } #vakata-dragged .jstree-invalid { background:red; } #jstree-marker { padding:0; margin:0; font-size:12px; overflow:hidden; height:12px; width:8px; position:absolute; top:-30px; z-index:10001; background-repeat:no-repeat; display:none; background-color:transparent; text-shadow:1px 1px 1px white; color:black; line-height:10px; } #jstree-marker-line { padding:0; margin:0; line-height:0%; font-size:1px; overflow:hidden; height:1px; width:100px; position:absolute; top:-30px; z-index:10000; background-repeat:no-repeat; display:none; background-color:#456c43;  cursor:pointer; border:1px solid #eeeeee; border-left:0; -moz-box-shadow: 0px 0px 2px #666; -webkit-box-shadow: 0px 0px 2px #666; box-shadow: 0px 0px 2px #666;  -moz-border-radius:1px; border-radius:1px; -webkit-border-radius:1px; }.jstree .jstree-real-checkbox { display:none; } .jstree-themeroller .ui-icon { overflow:visible; } .jstree-themeroller a { padding:0 2px; } .jstree-themeroller .jstree-no-icon { display:none; }.jstree .jstree-wholerow-real { position:relative; z-index:1; } .jstree .jstree-wholerow-real li { cursor:pointer; } .jstree .jstree-wholerow-real a { border-left-color:transparent !important; border-right-color:transparent !important; } .jstree .jstree-wholerow { position:relative; z-index:0; height:0; } .jstree .jstree-wholerow ul, .jstree .jstree-wholerow li { width:100%; } .jstree .jstree-wholerow, .jstree .jstree-wholerow ul, .jstree .jstree-wholerow li, .jstree .jstree-wholerow a { margin:0 !important; padding:0 !important; } .jstree .jstree-wholerow, .jstree .jstree-wholerow ul, .jstree .jstree-wholerow li { background:transparent !important; }.jstree .jstree-wholerow ins, .jstree .jstree-wholerow span, .jstree .jstree-wholerow input { display:none !important; }.jstree .jstree-wholerow a, .jstree .jstree-wholerow a:hover { text-indent:-9999px; !important; width:100%; padding:0 !important; border-right-width:0px !important; border-left-width:0px !important; } .jstree .jstree-wholerow-span { position:absolute; left:0; margin:0px; padding:0; height:18px; border-width:0; padding:0; z-index:0; }</style></head>
<body itemscope="" itemtype="http://schema.org/WebPage" id="demo-page">
<noscript>&lt;iframe src="//www.googletagmanager.com/ns.html?id=GTM-MS2BNB" height="0" width="0" style="display:none;visibility:hidden"&gt;&lt;/iframe&gt;</noscript>
<script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
            new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
            j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
            '//www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
    })(window,document,'script','dataLayer','GTM-MS2BNB');</script>
<!--[if lt IE 9]>
<div style='clear: both; height: 112px; padding:0; position: relative;'><a href="http://www.theie8countdown.com/ie-users-info"><img src="http://www.theie8countdown.com/assets/badge_iecountdown.png" border="0" height="112" width="348" alt="" /></a></div>
<![endif]-->
<div class="relative js-demo-upper-menu" onmousewheel="SmoothSize; return false" id="headerlivedemo" data-template_id="52500">

</div>
<div id="iframelive" class="" style="height: 379px;">
<div id="frameWrapper">
<iframe id="frame" frameborder="0" src="http://livedemo00.template-help.com/wt_52500">
[Your user agent does not support frames or is currently configured not to display frames. However, you may visit the related document.]
</iframe>
</div>
</div>
<script src="http://static.templatemonster.com/js/application.compiled.js?6cd8a92"></script>
<script>
try {
	var _gaq = _gaq || [];
	_gaq.push(['a._setAccount', 'UA-1217838-2']);

	_gaq.push(['a._setDomainName', '.templatemonster.com']);
	_gaq.push(['a._setAllowLinker', true]);
	_gaq.push(['a._setAllowHash', false]);

	_gaq.push(['a._setSessionCookieTimeout', 180000000]);
	_gaq.push(['a._setVisitorCookieTimeout', 63072000000]);

	_gaq.push(['b._setAccount', 'UA-1217838-16']);


	_gaq.push(['b._setDomainName', '.templatemonster.com']);
	_gaq.push(['b._setAllowLinker', true]);
	_gaq.push(['b._setAllowHash', false]);

	_gaq.push(['b._setSessionCookieTimeout', 180000000]);
	_gaq.push(['b._setVisitorCookieTimeout', 63072000000]);

    _gaq.push(['a._setCustomVar', 3, "Beta", "Yes", 2]);
    _gaq.push(['b._setCustomVar', 3, "Beta", "Yes", 2]);

    
	_gaq.push(['a._require', 'inpage_linkid', '//www.google-analytics.com/plugins/ga/inpage_linkid.js']);

} catch (err) {}
(function() {
    var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
    ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
    var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
})();
</script>
<script type="text/javascript">
			$(function() {
				// IPad/IPhone
				var viewportmeta = document.querySelector && document.querySelector('meta[name="viewport"]'),
						ua = navigator.userAgent,
						gestureStart = function() {
					viewportmeta.content = "width=device-width, minimum-scale=0.25, maximum-scale=1.6";
				},
						scaleFix = function() {
					if (viewportmeta && /iPhone|iPad/.test(ua) && !/Opera Mini/.test(ua)) {
						viewportmeta.content = "width=device-width, minimum-scale=1.0, maximum-scale=1.0";
						document.addEventListener("gesturestart", gestureStart, false);
					}
				};
				scaleFix();
			});

//		    function to fix height of iframe!
			var calcHeight = function() {
				var headerDimensions = $('#headerlivedemo').height();
				var selector = '#iframelive';
				if ($('#advanced').hasClass('closed')) {
					$(selector).height($(window).height());
				} else {
					$(selector).height($(window).height() - headerDimensions);
				}
			}
			$(document).ready(function() {
				calcHeight();
			});
			$(window).resize(function() {
				calcHeight();
			}).load(function() {
				calcHeight();
			});
			</script>
<script type="text/javascript">
			$(function() {
				mobileCss = function() {
					if (navigator.userAgent.match(/iPhone/i) || navigator.userAgent.match(/iPod/i) || navigator.userAgent.match(/iPad/i) || navigator.userAgent.match(/Android/i) || navigator.userAgent.match(/Opera Mini/)) {
						$('#dropdown.box-drop ul.list-drop li .popover').css('top', '-1000px').css('display', 'none !important');
						$('.view_options').hide();
						$('body').css({'height': 'auto'});
						$('html').css({'height': 'auto'});
						$('#headerlivedemo').addClass('mobile');
					}
				};
				mobileCss();
			});
			</script>
<script type="text/javascript">/* responsive-views script-selector */
						$(document).ready(function() {
							if (!(navigator.userAgent.match(/iPhone/i) || navigator.userAgent.match(/iPod/i) || navigator.userAgent.match(/iPad/i) || navigator.userAgent.match(/Android/i) || navigator.userAgent.match(/Opera Mini/))) {

								var frame = document.getElementById('frame');

								$('ul#responsivator').show();

								$('ul#responsivator li.response').click(function() {

									$('ul#responsivator li').removeClass('active');
									$(this).addClass('active');
									var device = $(this).attr('id');
									$('#iframelive').removeClass().addClass(device);
									frame.src = frame.src;
								});

								$('ul#responsivator li#qr').unbind('click');

								$('.responsive-block').show();



							}

						});
						</script>
<script type="text/javascript">
							$(function() {



								$('.name_template .link-1').click(function() {

									var dd = $('.view_options  dt').siblings('dd');
									var pop = $('#popover2');
									var dropdown = $('#dropdown');
									if (pop.is(':visible')) {
										pop.fadeOut(100);
										return false;
									} else {
										pop.fadeIn(100);
										$('#dt').removeClass("active");
										if (dd.is(':visible')) {
											dd.fadeOut(100);
										}
										if (dropdown.is(':visible')) {
											dropdown.fadeOut(100);
											return false;
										}
										return false;
									}
								});

								$(window).scroll(function() {
									if ($(this).scrollTop() > 0) {
										$("#advanced").css({position: 'relative'});
									} else {
										$("#advanced").css({position: 'relative'});
									}
								});

								$("#advanced").css({marginTop: '0px'}).removeClass('closed');
								$("#advanced .trigger").toggle(function() {
									$(this).find('em').parent().parent('#advanced').addClass('closed').animate({marginTop: '-53px'}, "fast", function() {
										calcHeight();
									});
									strCookies2 = $.cookie("panel2", null);
									strCookies = $.cookie("panel", 'boo');
								},
										function() {
											$(this).find('em').parent().parent('#advanced').removeClass('closed').animate({marginTop: '0px'}, "fast", function() {
												calcHeight();
											})
											strCookies2 = $.cookie("panel2", 'opened');
											strCookies = $.cookie("panel", null);
										});

								if ($(window).scrollTop() > 0) {
									$("#advanced").css({position: 'relative'});
								} else {
									$("#advanced").css({position: 'relative'});
								}

								$('.trigger').click(function() {
									$('.view_options dd').fadeOut(100);
								})
								$('.trigger').click(function() {
									$('.buy_now').removeClass("open");
								})

								$('.view_options  dt')
										.click(function() {
									var dd = $(this).siblings('dd');
									var pop = $('#popover2');
									var dropdown = $('#dropdown');
									if (dd.is(':visible')) {
										dd.fadeOut(100);
										$(this).removeClass("active");
										return false;
									}
									else {
										$(this).addClass("active");
										dd.fadeIn(100);
										if (pop.is(':visible')) {
											pop.fadeOut(100);
											return false;
										}
										if (dropdown.is(':visible')) {
											dropdown.fadeOut(100);
											return false;
										}

										return false;
									}
								});

								$('#buy-button').click(function() {

									var dt = $('#dt');
									var dd = $('.view_options  dt').siblings('dd');
									var pop = $('#popover2');
									var dropdown = $('#dropdown');

									if (dropdown.is(':visible')) {
										dropdown.fadeOut(100);
										return false;
									} else {
										dt.removeClass('active');
										dropdown.fadeIn(100);
										if (pop.is(':visible')) {
											pop.fadeOut(100);
											return false;
										}
										if (dd.is(':visible')) {
											dd.fadeOut(100);
											return false;
										}
										return false;

									}

								});


								var ua = navigator.userAgent;


								$(document).click(function(e) {
									$('#dd').fadeOut(100);
									$('#dt').removeClass("active");
								});

								$('.link-1').hover(function() {
									$(this).find('span').css('background-position', '-188px -39px');
								}, function() {
									$(this).find('span').css('background-position', '-188px -6px');
								});
								$('#dt').hover(function() {
									$(this).find('span').css('background-position', '-193px -41px');
								}, function() {
									$(this).find('span').css('background-position', '-193px -8px');
								});

								$(document).click(function(e) {
									if ($('#popover2').is(':visible')) {
										$('#popover2').fadeOut(100);
									}
									if ($('#dropdown').is(':visible')) {
										$('#dropdown').fadeOut(100);
									}
								});
								if ($.browser.msie) {
									$('body').addClass('ie');
								}
								if (($.browser.msie) && ($.browser.version == '9.0')) {
									$('body').addClass('ie9');
								}




								$('.js-drop').hover(
										function() {
											$(this).siblings('.popover').css('opacity', '1').css('z-index', '999');
										}, function() {
									$('.list-drop li .popover').css('opacity', '0').css('z-index', '-999');
								});

								$('.trigger').click(function() {
									$('#popover2, #dd, #dropdown').hide();
								});



								var cssFix = function() {
									var u = navigator.userAgent.toLowerCase(),
											addClass = function(el, val) {
										if (!el.className) {
											el.className = val;
										} else {
											var newCl = el.className;
											newCl += (" " + val);
											el.className = newCl;
										}
									},
											is = function(t) {
										return (u.indexOf(t) != -1)
									};
									addClass(document.getElementsByTagName('html')[0], [
										(!(/opera|webtv/i.test(u)) && /msie (\d)/.test(u)) ? ('ie ie' + RegExp.$1)
												: is('firefox/2') ? 'gecko ff2'
												: is('firefox/3') ? 'gecko ff3'
												: is('gecko/') ? 'gecko'
												: is('opera/9') ? 'opera opera9' : /opera (\d)/.test(u) ? 'opera opera' + RegExp.$1
												: is('konqueror') ? 'konqueror'
												: is('safari/') ? 'webkit safari'
												: is('mozilla/') ? 'gecko' : '',
										(is('x11') || is('linux')) ? ' linux'
												: is('mac') ? ' mac'
												: is('win') ? ' win' : ''
									].join(" "));
								}();

							});
							</script>
<script type="text/javascript">window.NREUM||(NREUM={});NREUM.info={"beacon":"bam.nr-data.net","licenseKey":"72d7dcce33","applicationID":"2939783,4702774","transactionName":"ZV1TZ0FTVkFVWkwKXlwXckZARldfG11dDl4=","queueTime":0,"applicationTime":1,"atts":"SRpQEQlJRU8=","errorBeacon":"bam.nr-data.net","agent":"js-agent.newrelic.com\/nr-632.min.js"}</script>
<div id="jstree-marker" style="display: none;">»</div><div id="jstree-marker-line" style="display: none;"></div><div id="vakata-contextmenu"></div><div id="thubContent0" class="thumbContent"></div><div id="thubContent1" class="thumbContent"></div><script type="text/javascript" id="">(function(){var a=window._fbq||(window._fbq=[]);if(!a.loaded){var b=document.createElement("script");b.async=!0;b.src="//connect.facebook.net/en_US/fbds.js";var c=document.getElementsByTagName("script")[0];c.parentNode.insertBefore(b,c);a.loaded=!0}a.push(["addPixelId","679061212130215"]);a.push(["addPixelId","664222117030213"])})();window._fbq=window._fbq||[];window._fbq.push(["track","PixelInitialized",{}]);</script>
<noscript>&lt;img height="1" width="1" alt="" style="display:none" src="https://www.facebook.com/tr?id=679061212130215&amp;amp;ev=PixelInitialized"&gt;</noscript>
<noscript>&lt;img height="1" width="1" alt="" style="display:none" src="https://www.facebook.com/tr?id=664222117030213&amp;amp;ev=PixelInitialized"&gt;</noscript><script type="text/javascript" id="">(window.Image?new Image:document.createElement("img")).src=location.protocol+"//vk.com/rtrg?r\x3dRZqoKGTDKK03Gqe20CAwt78ixcjDqh0jM5IBpgOBVfikKQvop0nHpqMMqjpjpoMyGcL3IfO6JGcX6EdiF7yHlx/bWnnzmFZc*tiKPYf8BtI6qNbfQXy24d5q22d46922DHwhJpa7yJb1jvI2Xed90I19LAREHbEMUIK7Q6nvCaQ-";</script><div style="display: none; visibility: hidden;"><script type="text/javascript">(function(){try{dataLayer.push({event:"fireRemarketingTag",google_tag_params:{dynx_itemid:window.template.id,dynx_pagetype:"offerdetail",dynx_totalvalue:window.template.price}})}catch(a){}})();</script></div></body></html>
