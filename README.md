# word-tokenizer-japanese
Splitting Japanese text into words so that [stopword](https://github.com/fergiemcdowall/stopword) removal can work. 

Will be based on [TinySegmenter](https://github.com/taku910/tinysegmenter)

## How to use

```javascript
<script type="text/javascript" src="tiny_segmenter.js" charset="UTF-8"></script>
<script>

var segmenter = new TinySegmenter();                 // インスタンス生成

var segs = segmenter.segment("私の名前は中野です");  // 単語の配列が返る

alert(segs.join(" | "));  // 表示

</script>
```
