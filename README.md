
## 0.※Gs卒業制作プロトタイプ<br>　※OSSであるOpen Web UI　を一部改変して作成したアプリケーションとなります。<br>
　　特徴<br>
　　　ⅰ.サーバー内でモデルをカスタマイズし、自社モデルを作成できるアプリケーション<br>
　　　ⅱ.モデルを開発するユーザーを管理者の承認制でサインアップ可能<br>
　　　ⅲ.公開されているLLMモデルをダウンロードし、サーバー内でファインチューニング可能<br>
　　　ⅳ.モデルの選択後、AIとのチャットが可能<br>
   

## 1.課題番号-プロダクト名

  - Model Refiner


## 2.課題内容（どんな作品か）

  - 企業内で活用する生成AIモデルの調整を行う社内アプリケーション

## 3.DEMO

- http://13.237.112.247:3000

## 4.作ったアプリケーション用のIDまたはPasswordがある場合

- 管理者アカウント
- - ID:test@test.com
- - PW:test00

- 一般アカウント
- - ID:test@test01.com
- - PW:testtest


## 5. 着想背景および現在の着地点
- 個人がLLMモデルを開発、チューニングし、自分用にカスタマイズされたAIを持つ世界をイメージしてアプリケーションの作成に着手した。
- 開発中、webアプリとしてリリースするにはLLMモデルを推論するために高品質なサーバースペックが必要であることがわかり、ローカル上で動作するプロダクトの検討を始めた。
- 調査の結果、「Open web UI」というローカル上で動作するOSSがリリースされていることを知り、そのツールを使って、LLMモデルを開発することとした。
- ※現在、Elyza;jp8bモデルを使用してモデルの検証をしている。https://huggingface.co/elyza/Llama-3-ELYZA-JP-8B


## 6. 今後の方針
-Webアプリケーションの開発は中止し、生成AIモデルを用いた企業向けの社内チャットボットの作成に切り替えることを検討中。
-既存のチャットボットとの違いは、質問に対し定型文を返すのではなく、モデルに社内情報を学習させることで、より具体的な回答をすることを目指したい。
