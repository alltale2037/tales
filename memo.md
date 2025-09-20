github ブラウザ上でファイルをリモートに直接 Add してしまった後、commit するには：

リモートの変更内容を取得
```
% git fetch 
```
取得した変更を現在のブランチ（main）にマージする
```
% git merge origin/main
```
あとは普通に add + commit
