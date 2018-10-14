# google_analytics

## analytics.jsからgtag.jsへ
<br><br><br>


###イベントトラッキング
##### 移行前
```
ga('send','event','カテゴリ','アクション','ラベル', '値');
```
##### 移行後
```
gtag('event', 'アクション', {'event_category': 'カテゴリ','event_label': 'ラベル', 'value': '値'});
```
[link] https://blog.siteanatomy.com/2017/11/gtag-js-migration.html
