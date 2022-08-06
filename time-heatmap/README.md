# time x heatmap

* 初めてのHeatmap、時系列変化で見たいと思い、やってみた。
  * <https://trial-viz.tviz.ninja/time-heatmap/demo.html>
* データはFIRMS(NASA)から、2021年のVIIRS SNPP、国単位のダウンロードを利用
  * <https://firms.modaps.eosdis.nasa.gov/country/>
* レンジスライダーで日付を変更
* 日付範囲(Windowing)を変更可能。ディフォルト7日で、その範囲に含まれるデータポイントをヒートマップで可視化
* map library は MapLibre
