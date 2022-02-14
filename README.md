# PointCloudStreaming
## 4.4節 オンデマンド配信評価実験
・１フレームあたりの点群の描画にかかる処理時間を考慮して，再生レートを決め，ダウンロードするフレーム番号をスキップすることで，30fpsと同じ速さで再生させる．

・１フレームあたりの点群のダウンロードにかかる処理時間を考慮して，再生終了までバッファが枯渇しないように初期バッファサイズを決定する．

条件1 voxel size:0/initial buffer size:29/play frame rate:5fps

[デモ動画](https://waseda.box.com/s/j1j5r2h9y4u20q8sp215was04gda9xdw)

条件2 voxel size:0.003/initial buffer size:65/play frame rate:10fps

[デモ動画](https://waseda.box.com/s/y94tg5xyte84mzaf1dywkod5tw12j7pa)

条件3 voxel size:0.005/initial buffer size:79/play frame rate:15fps

[デモ動画](https://waseda.box.com/s/07o83jqg69dkn6p9dhgd95twe4whz925)

条件4 voxel size:0.01/initial buffer size:131/play frame rate:30fps

[デモ動画](https://waseda.box.com/s/8lx2g0xlujup4jwl3xk1y4qui5sl4bx0)

| ヘッダー | ヘッダー２ | ヘッダー３ |
| 要素１ | 要素２ | 要素３ |

| TH 左寄せ | TH 中央寄せ | TH 右寄せ |
| :--- | :---: | ---: |
| TD | TD | TD |
| TD | TD | TD |

表1　条件

| 条件 | voxel size | 初期バッファサイズ | 再生フレームレート(fps) | デモ動画リンク |
| :---: | :---: | :---: | :---: | :---: |
| 1 | 0 | 29 | 5 | [こちら](https://waseda.box.com/s/j1j5r2h9y4u20q8sp215was04gda9xdw) |
| 2 | 0.003 | 65 | 10 | [デモ動画](https://waseda.box.com/s/y94tg5xyte84mzaf1dywkod5tw12j7pa) |
| 3 | 0.005 | 79 | 15 | [デモ動画](https://waseda.box.com/s/07o83jqg69dkn6p9dhgd95twe4whz925) |
| 4 | 0.01 | 131 | 30 | [デモ動画](https://waseda.box.com/s/8lx2g0xlujup4jwl3xk1y4qui5sl4bx0) |
