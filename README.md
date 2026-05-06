kaggle competitions

Recruit-Restaurant-Visitor-Forecasting

時系列、回帰

評価指標：RMSLE 

補足

今回は複数デーブルのデータ結合をしています。
rolling features を使った、移動平均、移動標準偏差、店舗ごとに時系列順に並べて、rolling window 内で線形回帰して傾きを取る特徴量を作成しています。
学習関数内で、日付ベースの fold index を作成しています。
