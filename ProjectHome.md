This project is for developing an Urdu Editor Bookmarklet. When invoked, this bookmarklet converts the active edit area into an Urdu Editor. That makes it possible to conveniently input Urdu text using phonetic Urdu keyboard mapping.

Create a bookmarklet with the following address:

```
javascript:(webpad=window.webpad||function(){var%20t=webpad,d=document,o=d.body,c=&quot;createElement&quot;,a=&quot;appendChild&quot;,w=&quot;clientWidth&quot;,i=d[c](&quot;span&quot;),s=i.style,x=o[a](d[c](&quot;script&quot;));if(o){t.l=x.id=&quot;wpsc&quot;;o[a](i).id=&quot;wpst&quot;;i.innerHTML=&quot;Loading%20Urdu%20Editor...&quot;;s.cssText=&quot;z-index:99;font-size:18px;background:#FFF1A8;top:0&quot;;s.position=d.all?&quot;absolute&quot;:&quot;fixed&quot;;s.left=((o[w]-i[w])/2)+&quot;px&quot;;x.src=&quot;http://urdu-editor-bookmarklet.googlecode.com/svn/trunk/bklet/WebPad.js&quot;}else%20setTimeout(t,500)})()");
```

or the following address and use it to convert edit areas on web pages into Urdu editors.

```
javascript:(webpad=window.webpad||function(){var%20t=webpad,d=document,o=d.body,c=&quot;createElement&quot;,a=&quot;appendChild&quot;,w=&quot;clientWidth&quot;,i=d[c](&quot;span&quot;),s=i.style,x=o[a](d[c](&quot;script&quot;));if(o){t.l=x.id=&quot;wpsc&quot;;o[a](i).id=&quot;wpst&quot;;i.innerHTML=&quot;Loading%20Urdu%20Editor...&quot;;s.cssText=&quot;z-index:99;font-size:18px;background:#FFF1A8;top:0&quot;;s.position=d.all?&quot;absolute&quot;:&quot;fixed&quot;;s.left=((o[w]-i[w])/2)+&quot;px&quot;;x.src=&quot;http://urdu-editor-bookmarklet.googlecode.com/svn/trunk/bklet/WebPad.lite.js&quot;}else%20setTimeout(t,500)})()
```