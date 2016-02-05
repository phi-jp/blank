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

<a href="javascript:(function(){;(function(url, title) {var base = 'http://phi-jp.github.io/blank/';var euc = encodeURIComponent;var q = ['url=' + euc(url), 'title=' + euc(title)].join('&amp;');location.href = [base, q].join('?');})(document.URL, document.title);})();">blank</a>
