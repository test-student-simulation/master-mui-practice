# master-mui-practice 作業記録（簡易版）

## 1. 実習の目的

Vite + React + TypeScriptで、MUI（Material UI）を使った管理アプリを作成し、UIデザインの基本を学ぶ。

## 2. 使用技術

- Vite / React / TypeScript
- MUI（Material UI）
- Material Design 3
- localStorage

下2つは二週目の応用編で使用する。

## 3. 基本アプリの作成

テキスト入力欄に名前を入力し、ボタンを押すと一覧に追加される管理アプリを作成。

主なMUIコンポーネント：

- Container / Box
- TextField / Button
- List / ListItem / ListItemText
- Card / CardContent


## 4. MUI応用編

基本アプリの完成後、Material Design 3を参考に、次の3要素を改善する。

**Color（色）**

`createTheme`と`ThemeProvider`を使用し、アプリ全体の配色を変更する。

例：

```ts
primary: { main: '#EF6C00' }
```

**Typography（文字）**

見出しや本文の文字サイズ・太さを調整し、情報の重要度を表現する。

**Layout（配置）**

カード間の余白、要素の配置、画面全体のバランスを調整する。

## 5. 作業中の確認事項

- MUIのデフォルトボタン色（青）
- テーマ設定によるオレンジ色への変更
- `CssBaseline`の役割
- カード背景や余白の調整
- テーマ設定を元に戻す方法

## 6. AI先生プロンプトへの展開

学生には次の順序で指導する。

1. MUIをインストールする
2. 管理アプリを作成する
3. データをlocalStorageに保存する
4. Material Design 3の考え方を学ぶ
5. Color・Typography・Layoutを改善する
6. 完成したアプリの見た目と操作性を確認する

基本編を終えた学生向けに、応用編を任意課題として提供する。
