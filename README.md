#About it
* 素人が作成したvimスクリプトです。
* latexテンプレートを出力し、コマンドの引数をテンプレートの中の任意の文字と置換してくれます。


#environment
* vim 7.4
* TeX Live 2013(このテンプレートでは)

#How it works
デフォルトの置換箇所は、下記の三つです。
<pre>
:LatexTemplate タイトル　名前 テンプレート 
</pre>

#install
neobundleとか
<pre>
NeoBundle 'kazuminn/latex_template.vim'
</pre>

#Setting
* ホームディレクトリーにtexテンプレートを置く
* テンプレートの中の置換したい場所をarg0,arg1...と書いてください。
* 0,1はコマンドの引数と対応しています。



#attention
* 何も書いてないバッファで使用すること
* テンプレートの中のargと引数の数が同じでないと挙動がおかしいです。
* Look at :help
