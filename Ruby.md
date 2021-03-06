# Ruby
## バージョンについて
### 利用中のバージョンを確認する
`ruby -v`
### インストール可能なバージョンを確認する
`rbenv install --list`
### 指定したバージョンをインストールする
`rbenv install 2.5.1`
### 全体で利用するバージョンを指定する
`rbenv global 2.5.1`
### 特定のディレクトリのみで利用するバージョンを指定
`rbenv local 2.5.1`


---
## メソッド
### breakとreturnの違い
- break: `繰り返し処理`を中断する場合に使用する
- return: `メソッド自体`を中断する場合に使用する
#### シンボル
- `=>` の代わりと`:`書く
- 文字列としてではなく、`整数`として扱われるので処理が高速
#### ハッシュ
- 引数に`**`を記述すると、ハッシュのみを受け取れるようにできる
```ruby
def initialize(**params)
end
```
#### セッターとゲッター
- attr_reader : 読み取りメソッド
- attr_writer : 書き込みメソッド
- attr_accesor : 読み取りと書き込みメソッドの両方