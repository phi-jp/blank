# blank
空ページ生成. 超軽量にする. タブによるメモリ専有を節約


## bookmarklet

```
;(function(url, title) {
  var base = 'http://phi-jp.github.io/blank/';
  var euc = encodeURIComponent;
  var q = ['url=' + euc(url), 'title=' + euc(title)].join('&');

  location.href = [base, q].join('?');
})(document.URL, document.title);
```

<a href='javascript:(function()%7B%3B(function(url, title) %7Bvar base %3D %27http://phi-jp.github.io/blank/%27%3Bvar euc %3D encodeURIComponent%3Bvar q %3D %5B%27url%3D%27 %2B euc(url), %27title%3D%27 %2B euc(title)%5D.join(%27%26%27)%3Blocation.href %3D %5Bbase, q%5D.join(%27%3F%27)%3B%7D)(document.URL, document.title)%3B%7D)()%3B'>blank</a>
