HTMLとCSSをのみで内容を書き込む部分と送信ボタンがあるシンプルなフォームを制作した。



■HTML
・ヘッダー要素以外をformタグで括る。その中にname,label,button要素を記述。
・送信ボタンの位置を手軽に変更できるようにspanタグを記述。



■CSS
・配色ツール（coolors）を用いてフォントカラー、フォームカラーの色彩を調整。
・コーディングルールを決め、第三者が手を加えやすいようにした。


［コーディングルール］

CSSの優先度を記述。
位置情報系＝position, top, right, z-index, display, float
サイズ＝width, height, padding, margin
文字系＝font, line-height, letter-spacing, color- text-align
背景＝background, border等
その他＝animation, transition等

■疑問点
・<input type="name" id="name" ="name">を多様したが、ループ設定などで短くできるのでは？


■その他
Gitの環境設定に苦戦した。転んだ所を
をhttp://qiita.com/14ta98
に記述。