# PointCloudStreaming
## 実験4.2
・１フレームあたりの点群の描画にかかる処理時間を考慮して，再生レートを決め，ダウンロードするフレーム番号をスキップすることで，30fpsと同じ速さで再生させる．

・１フレームあたりの点群のダウンロードにかかる処理時間を考慮して，再生終了までバッファが枯渇しないように初期バッファサイズを決定する．

条件1 voxel size:0/initial buffer size:29/play frame rate:5fps

[デモ動画](https://waseda.app.box.com/file/918376727995)

条件2 voxel size:0.003/initial buffer size:65/play frame rate:10fps

[デモ動画](https://waseda.app.box.com/file/918391244594)

条件3 voxel size:0.005/initial buffer size:79/play frame rate:15fps

[デモ動画](https://waseda.app.box.com/file/918389052310)

条件4 voxel size:0.01/initial buffer size:131/play frame rate:30fps

[デモ動画](https://waseda.box.com/s/8lx2g0xlujup4jwl3xk1y4qui5sl4bx0)



