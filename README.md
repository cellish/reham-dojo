# リハモ道場 / Reharm Dojo

メロディにコードを付ける練習と、コードを付け替える（リハーモナイズする）練習のためのブラウザ用ツールです。ジャズ・ポップスのコードネームで考えます。

- **伴奏付け**：旋律だけからコードを付けます。区切りと終わり方 → コードを変える間隔 → I・IV・V で埋める → 流れを確かめる → ダイアトニック・コードを広げる → 向かうコードと色づけ、の6ステップのガイド付きです。
- **リハモ**：原曲のコードを付け替えます。原曲を読む → 4和音にする → 同じ機能で置き換える → ベースを動かす（分数コード） → 着地点へ向かう → 半音で近づく → 借りてくる → 見直す、の8ステップのガイドと、置き換え候補の一覧、着地点から手前へ組み立てる「逆算」があります。

楽譜の音符は、選んだコードに対する役割（和声音・テンション・アボイド・非和声音）で色分けされ、下に度数が表示されます。強拍でぶつかる所は印で知らせます。コード名はキーボードから打ち込めます（例：`Dm7`、`C/E` → Enter）。

## 収録曲

どの曲も好きな調に移調できます。

- **入門（I・IV・V）**：きらきら星、歓喜の歌、ジングルベル、聖者の行進
- **初級（3拍子・アウフタクト）**：ハッピーバースデー、赤とんぼ、アメイジング・グレイス、きよしこの夜
- **中級（ブルース・短調・ジャズ）**：ブルース（練習用オリジナル）、世の人忘るな、Tea for Two

旋律は日本と米国の両方で著作権の保護期間が終わったものだけを収めています。「曲を入力」から自分の曲も追加できます（ブラウザに保存されます）。

## 使っているもの

- 楽譜の描画：[VexFlow](https://github.com/vexflow/vexflow) 5.0.0（MIT License）。CDN（jsDelivr）から読み込みます。読み込めないときは簡易な描画に切り替わります。
- フォント：Google Fonts（Zen Kaku Gothic New、Barlow Condensed、Noto Music）
- 音はブラウザ内で合成しています。

## ファイル構成

- `index.html`：ページ本体（1ファイルで完結）

## English

Reharm Dojo is a browser tool for practising chord choice over a melody, in jazz/pop chord symbols. *Harmonize* mode walks you through adding chords to a bare melody in six steps; *Reharm* mode helps you substitute the original chords in eight steps (sevenths, functional substitutes, slash-chord bass lines, secondary dominants and II–Vs, tritone and diminished approaches, modal interchange). Melody notes are coloured by their role against the chosen chord, with the chord degree shown beneath. Every song can be transposed to any key. Notation is rendered with VexFlow.
