<p align="center">
  <img src="./assets/banner.svg" alt="XXD Panel 023 プロジェクトバナー" width="1200">
</p>

<div align="center">

# 🦁 XXD Panel 023

### 写真自身が選ぶ東洋の窓と柔らかな光で、静かな框景へ

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Four Modes](https://img.shields.io/badge/Modes-4-d75d32?style=flat-square)](#4つの出力を支えるひとつの東洋窓景ロジック)
[![Raster Output](https://img.shields.io/badge/Output-PNG-3c6f67?style=flat-square)](#境界と信頼性)

<a href="README.md">简体中文</a> · <a href="README.en.md">English</a> · <strong>日本語</strong> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

> 元写真が選ぶ窓 · 淡く呼吸する背景 · 柔らかな色光 · スプレー粒子 · 虚実の投影と小文字

XXD Panel 023 は、Codex と互換 Agent のための画像生成 Skill です。写真の輪郭、動き、開口、重心、空間関係に応じて、円窓、花窓、漏窓、月洞、扇形窓、六角窓、簡略格子から一つを選び、主体、枝影、光斑、抽象投影を窓の内側に現し、通し、遮らせ、または少し溢れさせます。

背景は元写真から取った極めて淡い低彩度色、最も生命感のある色は柔らかな光になります。一つの主光域、一つの静かな余白、少数のぼけた投影が三角形を作り、細かなスプレー粒子、パステル粉、空気の柔焦点、小さな編集文字が、窓格子の光を記憶の中へ溶かします。

## なぜ 023 が必要なのか

一般的な「東洋の窓景」は、いつも同じ中央の月洞、濃紺背景、硬い中華枠、安価な懐古フィルターへ崩れがちです。

023 は順序を逆にします。

```text
輪郭／動き／開口／方向／光色／関係を固定 → 最適な伝統窓を一つ選ぶ → 主体や投影を現す／通す／遮る／溢れさせる → 主光域一つ＋静かな余白一つ＋少数の柔投影 → 元写真から淡い背景と生命の光色を取る → 粒子、粉、拡散境界で柔らげる → 極短い題と小文字を窓縁、弧、軸、光の余白へ置く
```

無関係な写真に替えても窓形、主体と窓の関係、主光域、静かな余白、投影、背景色、光色、文字経路がほぼ成立するなら、それは 023 ではありません。

## 023 のビジュアル契約

- **元写真が窓を選ぶ：** 三つ以上の固有手掛かりで窓形を一つ決め、月洞を機械的に使いません。
- **窓と主体が作用する：** 主体、枝影、光斑、投影が窓内に現れ、通り、遮り、溢れ、秩序と奥行きを作ります。
- **一つの視覚三角形：** 主光域一つ、静かな余白一つ、少数の柔投影。窓は偏置、裁切、浮遊できます。
- **淡い元写真色：** 元写真に根拠のある低彩度背景と、そこから抽出した生命の光色を使います。
- **空気の素材：** スプレー粒子、パステル粉、粉塵、柔焦点、拡散境界。格子は少し明瞭でも硬くしません。
- **静かな小文字：** 極短い題と少数の微小語を、窓縁、弧、軸、光の余白へ置きます。

## 作例 · X より

> [小小東（@xiaoxiaodong01）](https://x.com/xiaoxiaodong01/status/2090381352025854206) · 2026-08-20<br>
> GPT2 x 中式美学 x 窗景 x 朦胧 x 美学提示词<br>
> 元の投稿には VOL 表記がありませんが、作者が本対話で XXD Panel 023 の作例であると確認しました。

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090381352025854206"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 023 作例 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090381352025854206"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 023 作例 2"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2090381352025854206">元の投稿と完全なプロンプトを見る →</a></p>

これらの作例は 023 の美的意図を示すものであり、作例の被写体、構図、配色、コピー、旧キャンバス比率が生成時の参照や現在の既定値になることはありません。

## 4つの出力を支えるひとつの東洋窓景ロジック

4つのモードは単独でも複数でも選択できます。`1`、`1+3`、`1、2、4`、`全部` と返信すると、Skill が重複を除き 1→4 の順で実行します。各モードは別々のタスクフォルダに独立出力され、一覧画像にはまとめません。`全部` は元写真1枚につき7点（通常3モード各1点＋壁紙4点）です。サイズはモード名付きで同時指定でき、未指定の通常モードは元画像に適応します。文案は既定で選択モード間に共通し、モード別指定も可能です。

| モード | サイズ方針 | 成果物 |
| --- | --- | --- |
| `top-bottom` | 元画像適応 | 上に完全な元写真、下に 023 の東洋窓形と柔光の框景。両パネルは元画像サイズを保ち、厳密に 50/50 |
| `left-right` | 元画像適応 | 左に完全な元写真、右に 023 の東洋窓形と柔光の框景。両パネルは元画像サイズを保ち、厳密に 50/50 |
| `design-only` | 元画像適応 | 元写真を見せず、変化デザインだけを表示。元画像の比率と寸法を維持 |
| `wallpaper-pack` | 端末別4サイズ | スマートフォン、iPad、デスクトップ、子ども用ウォッチの PNG を個別出力 |

優先順位は、正確な指定ピクセル > 指定比率／用途 > 通常モードの元画像適応です。原稿 `023.md` の 3:4 は初期の制作画角であり、現在の暗黙の既定値ではありません。

ペアモードの写真は、抑制した調色と必要最小限の環境拡張だけで忠実さを保ちます。デザイン単独と壁紙では写真を根拠として使いますが、原片は表示しません。

### 壁紙セット：連動または独立

壁紙に暗黙のサイズ既定値はありません。一般プリセットはスマートフォン `1440×3200`、iPad `2048×2732`、デスクトップ `3840×2160`、ウォッチ `1024×1024`。端末別のカスタムサイズも指定できます。

- **連動セット（推奨）：** まず iPad の基準作品を生成・承認し、残り3枚は元写真＋同じ基準作品を参照して各画面に再構成します。
- **独立4作品：** 各端末は元写真だけを参照し、窓形、主体との関係、光域、余白、柔投影、文字経路を別々に探れます。

連動は切り抜きではありません。4枚を個別に生成、構成、検査し、iPad→スマートフォン→デスクトップ→ウォッチの順に参照を連鎖させません。

## 文字は窓と光の静かな秩序に沿う

生成前に、自動文案、カスタム文案、文字なしを選びます。文字を入れる場合は対象言語または地域も指定します。

自動文案は、写真の感情、時間、動き、温度、比喩から極短い題を作り、必要な時だけ少数の場所語、状態語、微小短句を加えます。文字は窓縁、弧、軸、光の余白に沿います。

場所、日付、出典、事実的な番号はユーザー提供または確かな根拠が必要で、洗練を装うために捏造しません。ユーザー確定文はそのまま保ちます。

ユーザーが完成稿を渡した場合は一字一句保ちます。方向や編集可能な草稿の場合だけ、対象、目的、必須語、語調、含意を守りながら磨きます。

言語は命令文ではなく、想定する読者に従います。

```text
対象市場・読者 > 指定された成果物言語 > 方向指示の言語；不明なら生成前に確認
```

日本版は自然な現代日本語、韓国向けは自然な韓国語と正しい分かち書き、英国版は英国英語、アラビア語版は原則として自然な現代標準アラビア語と正しい右から左の組版を使います。外見、服装、風景、看板から国籍を推測せず、雰囲気づくりの偽外国語も使いません。

## 正確な構成はコード、作品は画像生成

画像モデルが元写真に適応する伝統窓、主体との奥行き、淡い背景、生命の色光、粒子、パステル粉、柔焦点、拡散投影、静かな小文字を作ります。`scripts/compose_panel.py` は画布計画、厳密な 50/50 ラスター合成、最終寸法、監査だけを担当し、プログラム描画で作品を偽装しません。

```bash
python3 scripts/compose_panel.py --plan --layout top-bottom --source photo.png
python3 scripts/compose_panel.py --plan --layout left-right --size 2560x1440
python3 scripts/compose_panel.py --audit result.png --layout design-only --size 2048x2048
```

正確な上下構成は総高さ、左右構成は総幅が偶数である必要があります。指定ピクセルは勝手に変更されません。

## 使い始める

```bash
git clone https://github.com/nevertoday/xxd-panel-023.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-023" ~/.codex/skills/xxd-panel-023
```

Claude Code では同じフォルダを `~/.claude/skills/xxd-panel-023` にリンクできます。インストール後に Agent セッションを再起動してください。

```text
$xxd-panel-023
この写真を左右二連にしてください。文案は写真の意味から作り、自然な韓国語を使ってください。
```

写真だけでも呼び出せます。番号付きの複数行メニューでモードと文字設定を確認し、壁紙では連動／独立と端末サイズも確認します。

詳細仕様：

- [Skill ワークフロー](SKILL.md)
- [中国語の完全プロンプト](references/xxd-panel-023-prompt.zh-CN.md)
- [英語の完全プロンプト](references/xxd-panel-023-prompt.en.md)
- [元のスタイル指示](references/023-source.md)

## 境界と信頼性

- 各写真は独立したタスク内だけで使い、他の入力、旧成果物、作例の主題、色、文案、構図を借りません。
- 呼び出すたびに新しいタスクフォルダを作り、同じ原画像と条件でも新たに生成します。
- 成果物は PNG ビットマップであり、SVG、HTML、Canvas、プログラム描画の代替物ではありません。
- 設定済みビットマップブリッジは匿名化した状態だけを返し、プロバイダー、エンドポイント、ヘッダー、認証情報、プロンプト、応答本文を表示しません。
- 選択した通常モードごとに1点を返し、`wallpaper-pack` を選ぶと独立壁紙4点を追加します。`全部` は元写真1枚につき7点を4つの同階層モードフォルダへ出力し、一覧コラージュにはまとめません。

ローカル合成には Python 3 と Pillow が必要です。安全なビットマップブリッジは Python 3.11+ の `tomllib` を使用します。画像生成には、ホスト Agent の内蔵ラスター生成機能または設定済みの互換ルートが必要です。

## リポジトリ

```text
xxd-panel-023/
├── SKILL.md
├── README.md / README.en.md / README.ja.md / README.ko.md / README.ar.md
├── agents/openai.yaml
├── assets/banner.svg + examples/（今後のローカル作例用）
├── scripts/compose_panel.py + configured_imagegen.py
└── references/xxd-panel-023-prompt.zh-CN.md + xxd-panel-023-prompt.en.md + 023-source.md
```

## XXD について

XXD は小小東（Xiaoxiaodong）のブランド名の略称です。このプロジェクトは [@xiaoxiaodong01](https://x.com/xiaoxiaodong01) が制作・管理しています。

## サポートと会員制度

### 個別深度相談 · 1時間 CNY 299

Skills 利用に関する一対一相談は1時間 CNY 299です。下の WeChat QR コードから予約してください。

### Xiaoxiaodong Skills ユーザー交流グループ · CNY 99

一度 CNY 99 を支払うと、ワークフロー共有、作品相談、ユーザー同士の支援を行う交流グループに参加できます。時間制の個別相談は含まれません。

### 知識星球＋会員プロンプトライブラリ · 年額 CNY 699

[知識星球](https://wx.zsxq.com/group/15554814142882)と[XXD 会員プロンプトライブラリ](https://vip.xiaoxiaodong.ai/)は同じ会員権です。**一度の年額決済で両方を利用でき、二重の購入は不要です。**

1. 知識星球で加入後、WeChat でプロンプトライブラリの交換コードを受け取る。
2. プロンプトライブラリで加入後、WeChat で知識星球への招待を受け取る。

<p align="center">
  <a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD 有料サービス WeChat QR コード" width="320"></a>
</p>

<div align="center">

**窓は飾りではなく、主体、光、余白が同時に起こる場所。**

</div>

---

<div align="center">
  <h2>☕ オープンソースプロジェクトを支援</h2>
  <p>このプロジェクトが時間の節約になったなら、Star、共有、コーヒー一杯で継続を支援できます。</p>
  <table><tr><td align="center" width="240">
    <a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee で Xiaoxiaodong を支援" width="180"></a><br>
    <strong>Buy me a coffee</strong><br><sub>QR コードを読み取るか開いて支援できます</sub>
  </td></tr></table>
  <p><sub>支援は任意であり、このオープンソースプロジェクトの利用権には影響しません。</sub></p>
</div>
