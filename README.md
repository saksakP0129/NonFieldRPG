# アプリ名
NonFieldRPG

# 概要
ノンフィールドRPGゲームの基本的実装
街からボタンをクリックすることで遷移し進行していく

# 制作背景
ゲームが元々好きで、一度作成してみたいと思ったので

# DEMO
左の画面がTOPページ　
はじめるボタンを押すと右画像に遷移する
<img width="220" height="350" alt="top" src="https://user-images.githubusercontent.com/61728213/81072034-80273500-8f20-11ea-9200-59ba33e9bc8b.png"><img width="220" height="350" alt="map" src="https://user-images.githubusercontent.com/61728213/81071995-7271af80-8f20-11ea-8178-88082e72bb63.png">

ダンジョン内では右上に改装（クリックを押すごとに数字が加算）
進むボタンか街に戻るボタンを選ぶことができる
左下にはステーラスの表示をしている
<img width="220" height="350" alt="field" src="https://user-images.githubusercontent.com/61728213/81071943-60900c80-8f20-11ea-9316-df9795ce0a49.png">

敵とエンカウントした際には敵名前とHPを表示
敵を直接クリックすることで攻撃が実行され、プレイヤーの攻撃後に
モンスターからの攻撃の実装（右画面ログ参考）
受けたダメージ（プレイヤーモンスター双方のステータスも反映）
<img width="220" height="350" alt="battle" src="https://user-images.githubusercontent.com/61728213/81070419-2a518d80-8f1e-11ea-9171-12aba236f4ea.png"><img width="220" height="350" alt="battle2" src="https://user-images.githubusercontent.com/61728213/81071520-cd56d700-8f1f-11ea-9241-783b8e99dbe3.png">

WebGLでURL公開をした際に不具合があり現状画像だけでの表示になっていますが
解決できれば、URLも加える予定です。
その他、SE（遷移ボタンクリック時、敵攻撃時、ゲームクリア時）の実装
effect（モンスターに攻撃時にモンスターが揺れる、攻撃を受けた際に画面が揺れる、攻撃時にエフェクト）
場面でのBGM設定



# 使用技術（開発)
unity2019.3.9.f
C#

# 今後実装したい機能　
ランダムエンカウントの実装
