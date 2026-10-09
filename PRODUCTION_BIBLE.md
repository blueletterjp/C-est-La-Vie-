# C'est la vie ― 一つの部屋、五つの朝
Newtake Creator Preview 制作バイブル(第1版)

期限: 付与日 + 10日 = ______(Newtake画面で確認して記入)
保有: 22,000 Credits / Max プラン
使用モデル: Seedance 2.5 / Seedance 2.0 VIP / MiniMax H3 / Midjourney V8.1 / GPT Image 2

---

## 0. 一行
屋根裏の部屋の窓辺に、縁の欠けた白いカップが残っている。
その欠けが「いつ、誰によって」生まれたのかを、5組の住人の朝を遡って見せる。セリフなし。

## 1. 仕様
- 画面: 16:9 / 目標尺 5:20(320秒) / 約61カット / 平均5.2秒
- 音楽: 先に作って尺を確定。66 BPM・4/4。1小節=3.64秒
  - Prologue 4小節(14.5秒) + 各幕16小節(58.2秒)×5 + Epilogue 4小節(14.5秒) = 88小節 = 320秒
- 音楽の内容: ソロピアノ+チェロ。4音のモチーフ(=カップのモチーフ)を時代ごとに編曲
  - 1幕: ピアノ単音(オルゴール的) / 2幕: ブラシドラムとラジオの断片が加わる
  - 3幕: ピアノが途中で消えて無音 / 4幕: 低いチェロと時計の秒針 / 5幕・Epilogue: モチーフ全開
- 環境音は音楽とは別に必ず入れる(窓の外の街、床の軋み、カップが石に触れる音)

## 2. 形式のルール(これが作者性の核)
1. **A-shot**: 全時代で同じ位置・同じ構図のカメラ(扉の位置から窓を見る、アイレベル、24mm)。各幕の最初と最後に必ず置く。時代の違いは部屋の飾り・光・色だけで見せる。
2. 幕間は**マッチカット**(カップ/ドアノブ)でつなぐ。煙・ホワイトアウト・黒味での遷移はしない。
3. カメラ移動は、ゆっくりした押し込み(Dolly In)とラックフォーカスだけ。手持ちは3幕の口論のみ。
4. 説明台詞・字幕・ナレーションなし。

## 3. ロック(全プロンプトの冒頭に貼る)

### ROOM LOCK
```
a small attic room in an old Paris building, sloped plaster ceiling on the left, one tall four-pane wooden casement window at the far end with a deep stone sill, narrow wooden floorboards running toward the window, bare plaster wall on the right, shot from the doorway at eye level (1.5m) looking straight at the window, 24mm lens
```

### CUP LOCK
```
a small white glazed ceramic cup, about 8cm tall, with one thin hand-painted cobalt-blue band just below the rim, rounded handle on the right side
```
- 3幕以降: 縁の左側(持ち手の反対)に、三日月形の欠け(約1cm)。青い線が欠けで途切れている。
- 3幕以降: 欠けた小さな破片(白、青い線の一部が残る)が、カップの左隣の窓辺に置かれたまま。**この破片は5幕まで動かさない。**

### DOOR LOCK
```
a wooden door with a round brass doorknob (new and shiny in 1962, worn and dull in the present)
```

### 人物ロック(幕ごとに参照画像を1枚作り、以降それだけを使う)
- **A1-W(1幕・1962)** 22歳の女性。あご下の黒髪ボブ・前髪は眉上、色白、細い眉。キャメルのウールコート(大きな丸い木ボタン3つ)、えんじ色のスカーフ、黒いストラップ靴。茶色の革トランク(真鍮の留め金2つ)。
- A2(2幕・1974)・A3(3幕・1991)・A4(4幕・2009)・A5(5幕・2026)は、各幕の前日に同じ手順で作る。シルエットと色が幕ごとに大きく違うこと(識別性を最優先)。

### 時代ごとのルック
| 幕 | 年 | 色・光 | 質感 |
|---|---|---|---|
| Prologue/5/Epilogue | 現在 | 埃の舞う金色の逆光、ハイキー | クリーンなデジタル |
| 1 | 1962 | 淡い緑の壁紙、朝の暖かい低い日差し | コダクローム調、細かい粒子 |
| 2 | 1974 | 茶とオレンジ、琥珀色の低い日差し | 粗めの粒子、柔らかい黒 |
| 3 | 1991 | 青灰色・雨・曇天・CRTの光 | 低彩度、やや硬い |
| 4 | 2009 | 白く平坦な朝の光、冷たい | デジタルの鮮明さ |

---

## 4. Script Node 投入用の脚本(全幕・セリフなし)

```
M0 屋根裏の部屋(現在)・朝
誰もいない。埃が光の中を漂う。窓辺の石の上に、縁の欠けた白いカップ。その左に、小さな白い欠片。
扉の外で鍵の音。ドアノブがゆっくり回り始める。

S1 同・1962年・朝
同じドアノブ(新品の真鍮)が回る。ドアが開く。キャメルのコートの若い女が、革のトランクを提げて入ってくる。
壁紙は淡い緑。鉄のベッドが一台あるだけ。彼女は窓を開ける。鳩が飛び立つ。
トランクから、新聞紙に包んだ白いカップを取り出す。無傷。窓辺に置く。石に触れる小さな音。
彼女は瓶の水をカップに注ぎ、飲む。壁に海の絵葉書をピンで留める。
午後、コートのままベッドで眠る。夜、ランプ。翌朝、ベッドは整えられ、彼女はいない。窓辺に、カップだけが残っている。

S2 同・1974年・朝
茶色の壁紙。ラジオが小さく鳴っている。若い夫婦が木箱を運び込む。
窓辺のカップを見つけ、男が拭く。女が笑う。二人は一つのカップを交互に回して飲む。
ラジオに合わせて、狭い床で少しだけ踊る。朝の光が二人の足元を横切る。
翌朝、また二人。カップは窓辺に戻される。

S3 同・1991年・雨の朝
青灰色の空。雨。壁紙は白に塗り替えられ、古いテレビ。女は黙ってスーツケースに服を詰めている。
男は窓辺でカップを持って立っている。女がコートを着る。男は何も言わない。
女が扉に向かう。男はカップを窓辺に置く――強く。縁が欠け、小さな破片が石の上に落ちる。
扉が閉まる音。男は破片を拾い、掌で見つめ、カップの隣に置く。そのまま、動かない。

S4 同・2009年・朝
白く平坦な光。老いた男が、毎朝同じ手順で湯を沸かす。欠けたカップを窓辺から取り、欠けを避けて口をつける。破片は触れない。
新聞。椅子。窓の外の街。何度目かの朝。
ある朝、椅子は空いている。カップの湯気が細くなり、消える。光だけが床を移動していく。

S5 同・現在・朝
扉が開く。若い人が段ボール箱を抱えて入ってくる。埃。
窓辺のカップと破片。若い人はゴミ袋を広げ、一度カップを入れかけて――止まる。
破片を欠けに当ててみる。合う。直しはしない。破片は元の場所に戻す。
カップを洗い、コーヒーを注ぎ、欠けた縁から飲む。窓の外が明るくなる。

E 同・朝(続き)
A-shotに戻る。部屋は暮らしの形になりつつある。窓辺に、カップと、破片。湯気。
カメラはゆっくり押し込み、カップに寄って終わる。
```

---

## 5. クレジット計画(22,000)
| 区分 | 配分 | 内容 |
|---|---|---|
| テスト | 1,500 | Day 1の単価実測 |
| 素材 | 3,000 | ROOMのA-shot基準画像、時代別の部屋、人物参照、キーフレーム |
| 動画本線 | 13,500 | 約61カット × 平均2.5回 = 約150回 → **1回あたり約90クレジット以下が目安** |
| 予備 | 4,000 | 最終日までのリテイク |

- 実測の結果、1回あたりの単価が90を超えるなら: ヒーローカット(15本程度)だけ高単価モデルで撮り、補助カット(約46本)は安いモデルに落とす。

### 実測メモ(Director Studio のスクリーンショットより)
- Director Engine / テキストから動画 / 自動・720P・5s の表示が **250クレジット**。
  - 50クレジット/秒 → 5:20(320秒)を1テイクずつ撮るだけで **16,000**。22,000では、リテイクは約24回しか残らない。
  - 22,000 ÷ 250 = **88回**。61カット × 2.5回(約150回)はこの設定では不可能。
- 上の想定(約90クレジット以下)に収めるには、次のどれか(または複数)が必要:
  1. 音声生成をオフにする(スピーカーのアイコン。音楽は別に作るので不要)
  2. より安いモデル(MiniMax H3 / Seedance 2.0 VIP など)で撮る
  3. 秒数・解像度を下げる(最終は編集側でアップスケールできるか確認)
  4. **動かないA-shotは「静止画+編集での微速Dolly In」にする**(画像生成のみ。1.9, 1.10 など、全体の約3割が該当)
  5. 長めのカット(8〜10秒)に統合して、総カット数を約40に減らす
- Director Studio は、ナラティブ/ビジュアル/撮影のプリセット(初期値は「アクション・ダイナミックなリズム」「クールブルー」「IMAXフィルム」)が効く。**この作品の静かなルックと衝突するので、使う場合は必ずプリセットをオフ/中立にする。**
- **ヒーローカット候補**: P2(欠けのラックフォーカス)、1.4(カップ登場)、2.4(カップの回し飲み)、3.7(欠ける瞬間)、4.9(湯気が消える)、5.5(破片が合う)、最後のカップへの押し込み。

## 6. Day 1 テスト(今日、最初の2時間)
| # | 内容 | 記録する項目 |
|---|---|---|
| 1 | ROOM LOCKでA-shot基準画像を、Midjourney V8.1とGPT Image 2で各4枚 | 1枚あたりのクレジット、部屋の再現性 |
| 2 | 気に入った1枚を起点画像にして、同じ動画プロンプトをSeedance 2.5 / 2.0 VIP / MiniMax H3で各1本(最短尺) | 単価、最大秒数、解像度、動きの安定、参照画像の枠数、音の有無 |
| 3 | Script Nodeに上の脚本(M0〜E)を全文貼る | シーンの分割のされ方、止まった点 |
| 4 | 1.4のカップ登場カットを各モデルで1本 | カップのロックが保たれるか |

テスト結果は下の表に書き込んでおく(アンケートにそのまま使える)。

| モデル | 画像/秒あたりクレジット | 最大秒数 | 良かった点 | 困った点 |
|---|---|---|---|---|
| Midjourney V8.1 | | | | |
| GPT Image 2 | | | | |
| Seedance 2.5 | | | | |
| Seedance 2.0 VIP | | | | |
| MiniMax H3 | | | | |

## 7. スケジュール(付与日=Day 1)
| Day | 内容 |
|---|---|
| 1 | テスト、A-shot基準画像、Act 1の人物参照、Prologue+Act 1の生成開始 |
| 2 | Act 1を完成(ここでワークフローを確定) |
| 3 | Act 2 |
| 4 | Act 3 |
| 5 | Act 4 |
| 6 | Act 5 + Epilogue |
| 7 | リテイク専用日 |
| 8 | 全体をつないで音をつける |
| 9 | 書き出し、**全素材をローカルに保存**、予備 |
| 10 | アンケート回答 |

幕ごとにその日のうちに完成させる。止まった場合でも、その時点の幕までで観られる形にしておく。

---

## 8. Prologue + Act 1 ショットリスト

生成は5〜8秒単位で撮り、編集で詰める。プロンプトは英語、冒頭にROOM/CUP/DOOR LOCKと時代ルックを貼る。

### 現在(Prologue / 14.5秒)
| # | 秒 | ショット | 内容 | プロンプト(LOCKに続けて) |
|---|---|---|---|---|
| P1 | 4.5 | A-shot / 24mm / Dolly In 5%以下 | 誰もいない埃の部屋、金色の逆光、窓辺に欠けたカップ。環境音のみ | `Empty dusty room, golden backlight from the window, floating dust motes in the light, the chipped cup and a tiny white shard on the stone sill, extremely slow push-in, still air, no people, cinematic, high-key` |
| P2 | 5 | 窓辺インサート / 100mm / ラックフォーカス | 背景の窓から、手前の欠けと破片へピントが移る | `Macro close-up of the chipped rim of the cup and the tiny shard on a stone sill, rack focus from the bright blurred window to the chip, one dust particle drifting through raking light, shallow depth of field` |
| P3 | 5 | ドアノブCU / 85mm / 固定 | 古い真鍮のドアノブが、ゆっくり回り始める。扉の下から光が漏れる | `Close-up of an old worn brass doorknob slowly beginning to turn, thin light leaking under the door, dust in the air, static camera, shallow depth of field` |

### 1幕・1962(約58秒)
| # | 秒 | ショット | 内容 | プロンプト |
|---|---|---|---|---|
| 1.1 | 3.6 | ドアノブCU / 85mm / 固定 | **マッチカット**。P3と同じ角度で、新品の真鍮のノブが回る | `Close-up of a new shiny brass doorknob turning, same angle as before, warm morning light under the door, 1962, Kodachrome film look, fine grain` |
| 1.2 | 7.3 | A-shot / 24mm / ゆっくりDolly In | 開いた扉。女が背を向けてトランクを提げ、窓に向かって歩き、部屋の中ほどで止まる | `Doorway view into a bare pale-green-wallpapered attic room with one iron bed. A young woman (A1-W) seen from behind carries a leather trunk, walks toward the window and stops mid-room. Warm low morning sun, 1962, Kodachrome film look, fine grain, slow push-in` |
| 1.3 | 5.5 | 側面ミディアム / 50mm / 固定 | 窓の掛け金を外して開く。鳩が窓辺から飛び立つ | `Medium side shot of A1-W unlatching the tall wooden casement window and opening it; a pigeon bursts off the stone sill; curtain-less window, morning air, 1962, Kodachrome look` |
| 1.4 | 5.5 | 手元CU / 85mm / ゆっくりDolly In | **ヒーロー**。新聞紙を開くと、無傷のカップが現れる | `Close-up of A1-W's hands unwrapping an old French newspaper from a [CUP LOCK], revealing the intact cup, warm window light on the glaze, slow push-in, 1962 Kodachrome look` |
| 1.5 | 3.6 | 窓辺インサート / 100mm / ラックフォーカス | カップが石に置かれる。小さな音。ピントが手から窓の外へ | `Insert on the stone sill: A1-W's fingertips set the [CUP LOCK] down, rack focus from her hand to the cup to the blurred rooftops, warm light catching the rim, 1962` |
| 1.6 | 5.5 | ミディアムCU / 50mm / 固定 | 瓶の水をカップに注ぎ、一口飲む。息をつく | `Medium close-up of A1-W pouring water from a glass bottle into the [CUP LOCK] and drinking, soft exhale, warm window light, fine grain, 1962` |
| 1.7 | 5.5 | 背後OTS / 35mm / ゆっくりDolly In | トランクに座った彼女の背中越しに、何もない部屋と窓 | `Over-the-shoulder from behind A1-W sitting on her trunk, looking at the bare room and the bright open window, slow push-in, warm low sun, 1962` |
| 1.8 | 4.5 | 壁CU / 50mm / 固定 | 海の絵葉書を、ピンで壁に留める | `Close-up of A1-W's hands pinning a sea postcard to the pale-green wall, 1962` |
| 1.9 | 6.2 | A-shot(午後) / 24mm / 固定 | ベッドで眠る彼女。光が長く琥珀色に伸びる | `Doorway view of the same room, late afternoon, long amber light across the floor, A1-W asleep on the iron bed in her coat, trunk open, [CUP LOCK] on the sill, static camera, 1962` |
| 1.10 | 5.5 | A-shot(夜) / 24mm / 固定 | ランプの灯り、窓は青い夜。眠る彼女 | `Doorway view of the same room at night, a small lamp lit, window deep blue, A1-W asleep, the cup glinting on the sill, static camera, 1962` |
| 1.11 | 5.5 | A-shot(翌朝) / 24mm / Dolly In → カップへ | ベッドは整えられ、彼女はいない。カップだけが朝日の中に残る | `Doorway view of the same room, next morning, the iron bed made and empty, no people, warm sunrise on the [CUP LOCK] on the sill, slow push-in to the cup, 1962` |

接続: 1.11の窓辺のカップ(押し込み終わりの構図)=2.1の冒頭構図(マッチカット)。

### AI生成の注意と代替
- **1.4(新聞紙を開く)**は動作が複雑で崩れやすい。崩れたら代替: 「布に包まれたカップを両手で持ち、布が手から滑り落ちる」。
- 人物ロック: 毎回、A1-Wの参照画像を添付し、コート・スカーフ・ボブを文中に明記する。
- 避けるもの: 決めポーズ、意味のない歩行、過剰なスローモーション、黒画面、白飛び、煙での遷移、過剰なレンズフレア。
- 1つのクリップに入れる動作は、原則1〜2個まで。

## 9. Act 2〜5・Epilogue の主要カット(詳細は各幕の前日に作成)
- **2幕(1974)**: 2.1 マッチカット(カップ押し込み) / 夫婦入室 / 男がカップを拭く / **一つのカップを回し飲み** / ラジオで踊る(足元のロー) / 朝日が床を横切る / A-shot終わり
- **3幕(1991)**: 雨の窓 / 女が荷造り(手持ち) / コートを着る / 男がカップを持って立つ / **強く置く→欠け→破片が落ちる(ヒーロー)** / 扉が閉まる / 破片を掌に / カップの隣に置く / A-shotで静止
- **4幕(2009)**: 同じ手順の朝を3回反復(湯、カップ、新聞)/ 破片には触れない / 空の椅子 / **湯気が消える(ヒーロー)** / 光が床を移動 / 埃が積もり始める
- **5幕(現在)**: 扉が開く / 段ボール / ゴミ袋を広げる / 止まる / **破片を欠けに当てる(ヒーロー)** / 直さず戻す / カップを洗う / 欠けた縁から飲む
- **Epilogue**: A-shot(暮らしの気配) → カップへ押し込んで終わり

## 10. アンケート用ログ(作りながら書く)
| 時刻 | やろうとしたこと | 止まった/迷った点 | どうしたか | 改善案 |
|---|---|---|---|---|
| Day 1 | Director Studioを開く | 日本語UIなのに、ナラティブ/ビジュアルのプリセット名が韓国語のまま表示される | | 日本語化、または説明の追加 |
| Day 1 | Director Studioの生成 | ボタンに「250」とだけ表示。何の単価か(秒/解像度/音声込みか)が分かりにくい | | 内訳の表示 |
