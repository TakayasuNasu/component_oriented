---?color=linear-gradient(to right, #021B79, #0575E6)
@title[Introduction]

@snap[west headline text-white span-70]
コンポーネント<br>指向で始める<br>*UI設計*
@snapend

@snap[south-west byline  text-white]
企画制作部<br>那須 毅康
@snapend

---?color=linear-gradient(to right, #021B79, #0575E6)
@title[Agenda]

@snap[west split-screen-heading text-pink span-50]
Agenda!
@snapend

@snap[east list-content-concise span-65]
@ul[](false)
- UI複雑化の背景
- そもそもコンポーネント指向とは?
- コンポーネント・ベースでUIを開発する場合のメリット
- コンポーネント・ベースでの設計の基本と分割基準
@ulend
@snapend

---?color=linear-gradient(to right, #021B79, #0575E6)
@title[Why UI be complicated?]

## @color[white](UI複雑化の背景)

---?color=linear-gradient(to right, #021B79, #0575E6)
@title[reason]

@snap[east list-content-concise text-white span-100]
@ul[list-bullets-circles]
- @color[pink](html5/css3の登場)
  - このことによりJavaScriptやcssで実現できることが増加
  - SPA(シングルページアプリケーション)やPWA(プログレッシブウェブアプリ)のように、web技術を使ったサービスの出現
- ユーザーが使う端末の種類が増加
  - 各デバイスの大きさに対応したUIを設計しなければならない
  - 今やiPhoneだけでも6種類の画面サイズがある<i class="em em-confounded"></i>
@ulend
@snapend

---?color=linear-gradient(to right, #021B79, #0575E6)
@title[result]

@snap[west text-white span-100]
## @color[white](複雑化することによって<br>開発期間の長期化や<br>不具合やデグレが起きる<br>リスクが高まります。)
@snapend

---?color=linear-gradient(to right, #021B79, #0575E6)
@title[result2]

@snap[east list-content-concise text-white span-100]
@ul[]
- そもそもコンポーネントとは、ある機能を実現するために部品化されたソフトウェアのこと
- それをwebの画面作成に応用し、各UIを部品かした状態。下記4つの特徴があります
  1. カプセル化されている
  2. 置換可能である
  3. 再利用可能である
  4. コンポーネントを別のコンポーネントに組み合わせて作成可能である
@ulend
@snapend


---?color=linear-gradient(to right, #021B79, #0575E6)
@title[result]

@snap[west text-white span-100]
### UIが持つ機能をカプセル化し、UI同士の置換や再利用が可能な状態にして、組み合わせることにより、より別の大きなUIを作ることができるように実装する
@snapend

---?color=linear-gradient(to right, #021B79, #0575E6)
@title[result]

@snap[west text-white span-70]
### Uコンポーネント・ベースで<br>UIを開発する場合のメリット
@snapend

---?color=linear-gradient(to right, #021B79, #0575E6)
@title[result2]

@snap[east list-content-concise text-white span-100]
@ul[]
- 再利用で実装量を減らす
- 平行開発で待ち時間を最小化する
- 仕様変更による手戻り作業を最小化する
- 新規参入開発メンバーを最短で戦力化する
- 複数のテスト・アプローチでテスト工数を下げる
- 複数アプリケーションの開発を容易にする
@ulend
@snapend

---?color=linear-gradient(to right, #021B79, #0575E6)
@title[result]

@snap[west text-white span-100]
### コンポーネント・ベースでの設計の基本と分割基準
@snapend


---?color=linear-gradient(to right, #021B79, #0575E6)
@title[result2]

@snap[east list-content-concise span-100]
@ul[](false)
- 依存関係の整理(小さなコンポーネントが大きなコンポーネントを含まない/その逆はOK)
- 一つのコンポーネントが責任を持つ問題は1つ
- コンポーネントが担当する目的別
@ulend
@snapend

---
@title[Tip! Fullscreen]

![TIP](template/img/tip.png)
<br>
For the best viewing experience, press F for fullscreen.
@css[template-note](We recommend using the *SPACE* key to navigate between slides.)

---?include=template/md/split-screen/PITCHME.md

---?include=template/md/sidebar/PITCHME.md

---?include=template/md/list-content/PITCHME.md

---?include=template/md/boxed-text/PITCHME.md

---?include=template/md/image/PITCHME.md

---?include=template/md/sidebox/PITCHME.md

---?include=template/md/code-presenting/PITCHME.md

---?include=template/md/header-footer/PITCHME.md

---?include=template/md/quotation/PITCHME.md

---?include=template/md/announcement/PITCHME.md

---?include=template/md/about/PITCHME.md

---?include=template/md/wrap-up/PITCHME.md

---
@title[The Template Docs]

@snap[west span-100]
### **Now it's @color[#E49436](your) turn.**

<br>

#### Use these templates to create custom slides.
#### **Then amaze your audience with a Git@color[#E49436](Pitch) slideshow @fa[smile-o]**
@snapend

@snap[south docslink span-100]
For supporting documentation see the [The Template Docs](https://gitpitch.com/docs/the-template)
@snapend