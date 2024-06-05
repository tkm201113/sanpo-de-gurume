■サービス概要
「散歩 de グルメ」は、指定した時間内に歩いて行けるお店をピックアップするアプリです。

現在地からの距離と時間を考慮して、おすすめのグルメスポットを表示します。

■ このサービスへの思い・作りたい理由
僕がこのサービスを思いついたのは、毎日の散歩中に新しいお店を発見する楽しさを感じたからです。

お気に入りのカフェやレストランを見つけた時の喜びを、もっと多くの人と共有したいと思いました。

また、健康のために散歩をする人が増えている中で、ただ歩くだけでなく新しい楽しみを提供したいという思いがあります。

■ ユーザー層について
【地元住民】
普段通り過ぎてしまう近所のお店を再発見し、食事のバリエーションを増やしたい

【ビジネスマン・ビジネスウーマン】
ランチタイムや仕事帰りに短時間で食事を済ませたいが、新しいお店も試してみたい

【観光客】
限られた時間で、地元の美味しいお店を効率的に見つけたい

【子育て中の主婦・主夫】
子供と一緒に短時間で安心して行けるお店を見つけたい

【高齢者】
健康のために散歩を楽しむ中で、安全に歩いて行ける範囲で新しいお店を発見したい

■サービスの利用イメージ
1.ユーザーがアプリを開き、指定した時間（例えば15分、30分）内で歩いて行けるお店を検索します。

2.アプリは現在地と時間を元に、最適なルートとおすすめのお店を表示します。

3.ユーザーはその中から気になるお店を選び、口コミや写真を見て訪れるかどうかを決めます。

4.食事後、レビューを投稿して他のユーザーと共有します。

■ ユーザーの獲得について
Runteqコミュニティ、Xでの宣伝

■ サービスの差別化ポイント・推しポイント
【時間指定機能】
指定した時間内で歩いて行けるお店をピックアップする

【リアルタイムの位置情報連動】
現在地に基づいてリアルタイムでおすすめのお店を表示する

【ユーザーレビューと写真】
実際に訪れたユーザーのレビューと写真を掲載

■ 機能候補
MVPリリース時に作っていたいもの:

・現在地周辺のお店表示

・指定時間内で行けるお店検索機能

・ユーザーレビューと写真の投稿機能

・お気に入り登録機能


本リリースまでに作っていたいもの:

・お店の詳細情報（営業時間、メニューなど）

・カスタム散歩ルート作成機能

・ソーシャルシェア機能

・リアルタイム混雑情報

■ 機能の実装方針予定
【指定時間内で行けるお店検索機能】
Google Maps APIを利用して現在地を取得し、指定した時間内で歩いて行ける範囲を計算する

【リアルタイムの位置情報連動】
同じくGoogle Maps APIを使って、周辺のお店情報を表示する

【ユーザーレビューと写真の投稿機能】
AWS S3を使って写真を保存し、RailsのActive Storageで管理する

【リアルタイム混雑情報】
外部API（例えば、Google Places API）を使って、お店のリアルタイム混雑