# LDC-Skeletonize-Sample
[LDC: Lightweight Dense CNN for Edge Detection](https://github.com/xavysp/LDC)でエッジ抽出を行い、その結果を細線化するサンプルです。<bR>
LDCの推論は[LDC-ONNX-Sample](https://github.com/Kazuhito00/LDC-ONNX-Sample)にてONNX化したものを利用しています。

■オリジナル画像<br>
　<img src="https://user-images.githubusercontent.com/37477845/233829548-ea2941b7-afa8-4bbf-ace4-f6d65cea8dce.png" loading="lazy" width="800px"><br>
■LDC(Average Image)<br>
　<img src="https://user-images.githubusercontent.com/37477845/233829554-4f490fa4-3c2c-471e-96b0-b4c4449c728c.png" loading="lazy" width="800px"><br>
■細線化(ZHANGSUEN)<br>
　<img src="https://user-images.githubusercontent.com/37477845/233829559-d309b048-7da6-4447-baec-ab46416632f7.png" loading="lazy" width="800px"><br>
■細線化(GUOHALL)<br>
　<img src="https://user-images.githubusercontent.com/37477845/233829579-9d3b47ab-acdc-4957-9303-ccfa20723cd1.png" loading="lazy" width="800px"><br>

# Requirement 
* OpenCV 4.5.3.56 or later
* onnxruntime 1.13.0 or later

# Usage
[LDC-Skeletonize-Sample.ipynb](LDC-Skeletonize-Sample.ipynb)をColaboratoryで上から実行してください。

# Reference
* [xavysp/LDC](https://github.com/xavysp/LDC)
* [Kazuhito00/LDC-ONNX-Sample](https://github.com/Kazuhito00/LDC-ONNX-Sample)

# Author
高橋かずひと(https://twitter.com/KzhtTkhs)
 
# License 
LDC-Skeletonize-Sample is under [CC-BY-NC 4.0](LICENSE).

# License(Image)
サンプル動画は[NHKクリエイティブ・ライブラリー](https://www.nhk.or.jp/archives/creative/)の[イギリス オックスフォードのクライスト・チャーチ学生寮外観](https://www2.nhk.or.jp/archives/movies/?id=D0002011220_00000&ref=search)を使用しています。
