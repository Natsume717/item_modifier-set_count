# item_modifier-set_count
item_modifierのset_countに関するサンプルになります。

~詳しくはブログ記事『[]()』を参考にしてください。~<br>
現在執筆中

<h3>使い方</h3>

データパック導入後、itemコマンドを使ってitem_modifierを呼び出してください。

例えば手元のアイテムの数を10個に変更したい場合には

```copy
/item modify entity @s weapon.mainhand sample:set_count_add-false
```

と実行し<br>
手元のアイテムを+10個したい場合には

```copy
/item modify entity @s weapon.mainhand sample:set_count_add-true
```

と実行すればOKです。

指定した数に変更させるか、もともとの個数と合わせるのかはaddという項目によって決められています。

---

また、マイナスの値を指示することで、アイテムの個数を減らすことが出来ます。

本データパックでは

```copy
/item modify entity @s weapon.mainhand sample:set_count_remove
```
と実行することで、手元のアイテムを10個減らすことが可能です。
