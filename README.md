# practice02
ブランチを作って、変更を登録できるようにする。  
## ブランチを作成する
左上にあるBranchのボタンをクリックして名前を入力し、任意のブランチを作成する。  
![branch](https://user-images.githubusercontent.com/61729632/78203311-a09f4200-74d1-11ea-8a08-71ac070b5c83.jpg)  

※日本語可。Branch:「～～～」の～～～と同じ内容のコピーが作られる。  
Branch:「～～～」の～～～部分が入力した内容に変わっていたら、ブランチ作成・移動しています。  
（これで元となるマスターブランチから、作業用のブランチが複製できました。）  
## ダウンロード・編集・アップロード
右上にある緑のClone or downloadのボタンをクリックして、zipファイルをダウンロードする。  
![branch](https://user-images.githubusercontent.com/61729632/78203311-a09f4200-74d1-11ea-8a08-71ac070b5c83.jpg)
  
html等はエディターで編集しておく。画像は用意しておく。  
アップロードは、該当のブランチでUpload filesボタンをクリックして、ドラッグ＆ドロップする。（同名の場合、上書きされる）  
Commit changesの欄に変更内容などを記入し、緑のCommit changesボタンをクリック、アップロードされる。  
![commit](https://user-images.githubusercontent.com/61729632/78203541-405cd000-74d2-11ea-894b-44a0f70ecd82.jpg)
  
html等テキストファイルの場合は、右上にあるペンのアイコン（Edit this file）をクリックしてコピペしても編集できる。  
![edit](https://user-images.githubusercontent.com/61729632/78203604-64b8ac80-74d2-11ea-87a5-66c1c70e9003.jpg)
## 変更した箇所を確認する
Codeタブ → 作業用のブランチ → Compare をクリックすると、マスターブランチとの差分が表示されます。  
![compare](https://user-images.githubusercontent.com/61729632/78203659-84e86b80-74d2-11ea-8492-7b651b552a16.jpg)
あるいは、URLに直接コミットIDを入力します。  
Codeタブ → commits → Branch から各コミットの右側にある7桁の英数字がIDで、ピリオド3つでつなげた下記URLで比較します。  
https://github.com/ishima-t/practice02/compare/a71380f...7e9408d  
### これを記録することでどの段階でどこを変更したか、ファイル管理がクラウドでできるようになります。変更（コミット）はすべて記録されるので、修正や戻すことも容易になります。