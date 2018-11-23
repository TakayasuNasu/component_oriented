---?image=assets/images/github00.jpg
<h1 class="fc_white bold ta_center">Githubを使って<br>ワークフローを<br>進化させよう</h1>

<div class="fc_white ta_center">
企画制作部<br>
那須 毅康
</div>

---

## Agenda

- 「Githubってそもそもなに??」
- 「Githubってどうやって使うの???」

---

## **「Githubってそもそもなに??」**

---

例えばこんなことありませんか?

<h3 class="fc_white">仕様書を更新するたびに<br>バックアップファイルを共有ドライブに残す</h3>

<ul>
<li class="fragment visible" data-fragment-index="0">バックアップファイルがどんどん増える<i class="em em-cold_sweat"></i>  <!-- --></li>
<li class="fragment visible" data-fragment-index="1">どれが最新ファイルなのかわからない<i class="em em-cold_sweat"></i>  <!-- --></li>
<li class="fragment visible current-fragment" data-fragment-index="2">誰が、どのような目的で修正したのかわからない<i class="em em-cold_sweat"></i>  <!-- --></li>
</ul>

![github07](assets/images/github07.png)

---

<h3 class="fc_white">共有ドライブのファイルを間違えて<br>上書きしてしまった</h3>

<ul>
<li class="fragment visible" data-fragment-index="0">同じ名前のファイルが複数存在する(index.htmlとか)<i class="em em-confounded"></i>  <!-- --></li>
<li class="fragment visible current-fragment" data-fragment-index="1">一度上書きしたら元にもどせない<i class="em em-confounded"></i>  <!-- --></li>
</ul>

![github14](assets/images/github14.jpg)

---

<h3 class="fc_white">ファイルを上書きしたら実は別の人が先に更新していた</h3>

<ul>
<li class="fragment visible" data-fragment-index="0">普段ローカルにダウンロードしファイルを修正している<i class="em em-dizzy_face"></i>  <!-- --></li>
<li class="fragment visible current-fragment" data-fragment-index="1">アップロードのたびに更新されてないか確認するのは手間だ<i class="em em-dizzy_face"></i>  <!-- --></li>
</ul>

![github15](assets/images/github15.png)

---

## **「それGithubで解決できます!!」**

---

##### →仕様書を更新するたびに共有ドライブにバックアップファイルを残す

<ul>
<li class="fragment visible" data-fragment-index="0">ファイルの更新履歴をGithubが管理してくれます<i class="em em-smile"></i>  <!-- --></li>
<li class="fragment visible" data-fragment-index="1">しかも差分も簡単に確認できます<i class="em em-smile"></i>  <!-- --></li>
<li class="fragment visible current-fragment" data-fragment-index="2">誰が何の目的で変更したのかの記録も残せます<i class="em em-smile"></i>  <!-- --></li>
</ul>

---

##### →共有ドライブのファイルを間違えて上書きしてしまった

<ul>
<li class="fragment visible current-fragment" data-fragment-index="0">自分が編集したファイルのみ自動で更新してくれます<i class="em em-smiley"></i> <!-- --></li>
</ul>

---

##### →ファイルを上書きしたら実は別の人が先に更新していた

<ul>
<li class="fragment visible" data-fragment-index="0">他の人が編集した場合、差分を取り込むまで上書きできない仕組みです<i class="em em-blush"></i>  <!-- --></li>
<li class="fragment visible current-fragment" data-fragment-index="1">差分ファイルのみ自動で取り込んでくれます<i class="em em-blush"></i>  <!-- --><ul>
<li>どのファイルに差分があるかを探さなくてもいい<i class="em em-blush"></i>!</li>
</ul>
</li>
</ul>

---

## その結果

- **他の作業者に影響を与えずに、<br>自分の作業分を進めることができます** |
- **お互いの考えている経過が<br>見えるようになります** |
- **実物をみながら議論できます** |

---

## **「Githubってどうやって使うの???」**

---

### 「そもそも使いこなすのが難しんでしょ?」

- たしかにGithubを完全に使いこなすためには、それなりの学習コストが必要です
- でもコア機能であるファイル管理であれば簡単にはじめることができます

---

### Github Desktop
![github04](assets/images/github04.png)

[https://desktop.github.com/](https://desktop.github.com/)

---

Githubでアカウントを作りログインしてリポジトリを作ります

![github09](assets/images/github09.png)

---

![github10](assets/images/github10.png)

---

作ったリポジトリをローカルにクローンします
![github01](assets/images/github01.png)

---

![github02](assets/images/github02.png)

---

![github03](assets/images/github03.png)

---

ローカルでファイルを編集したらコミットします

![github11](assets/images/github11.png)

---

それをGithubにプッシュします

![github12](assets/images/github12.png)

---?image=assets/images/icarus.png

<h3 class="fc_white bold">ここでのポイントとして</h3>

- 編集したファイルのみ自動で更新されます |
- すでに他の人が更新していた場合は<br>差分を取り込むまでプッシュできません |

---?image=assets/images/icarus.png

<p class="fc_white">プッシュしようとすると以下の画面が表示されます</p>

![github16](assets/images/github16.png)

---?image=assets/images/icarus.png

<p class="fc_white">この場合、先にファイルを取り込む必要があります</p>

![github17](assets/images/github17.png)

---?image=assets/images/icarus.png

<p class="fc_white">他の人は更新されたファイルを取り込みます</p>

![github08](assets/images/github08.png)

---?image=assets/images/icarus.png

<p class="fc_white">そしてまたファイルを更新したらコミットしてプッシュします</p>

![github13](assets/images/github13.png)

<h3 class="fc_white bold">これが一連の流れになります</h3>

---

<h2 class="fc_white bold">その他の使い方</h3>

- 自作のsassやjsのコード置き場 |
- タスク管理やドキュメント管理 |
- プロダクト改善のアイデア出し |
- ちなみにこのスライドもGithubで管理しています |

---

<h2 class="fc_white bold">注意点</h2>

- リポジトリサイズは1GB以下(推奨) |
- 1ファイルのサイズ上限は100MB |
- wordやexcelなどのoffice製品は<br>差分の確認が不可能 |

---

<h2 class="fc_white bold">まとめ</h2>

### Githubは難しくありません。<br>まずはGithub Desktopを使ってドキュメントを管理しましよう
### プロジェクト管理ツールとしても使えます
### 何か不明点があればいつでも声をかけて下さい

---?image=assets/images/github00.jpg

<h1 class="fc_white bold">ありがとうございました</h1>
