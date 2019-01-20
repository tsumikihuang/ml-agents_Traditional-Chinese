# Unity ML-Agents工具文件

## 安裝 & 建立

* [安裝](Installation.md)
  * [背景: Jupyter Notebooks](Background-Jupyter.md)
  * [Docker建立](Using-Docker.md)
* [基礎指南](Basic-Guide.md)

## 開始

* [ML-Agents工具概觀](ML-Agents-Overview.md)
  * [背景: Unity](Background-Unity.md)
  * [背景: 機器學習](Background-Machine-Learning.md)
  * [背景: TensorFlow](Background-TensorFlow.md)
* [從3D Balance Ball範例環境開始](Getting-Started-with-Balance-Ball.md)
* [學習環境範例](Learning-Environment-Examples.md)

## 創造學習環境

* [製造新的學習環境](Learning-Environment-Create-New.md)
* [設計一個學習環境](Learning-Environment-Design.md)
  * [Agents](Learning-Environment-Design-Agents.md)
  * [Academy](Learning-Environment-Design-Academy.md)
  * [Brains](Learning-Environment-Design-Brains.md):
    [Player](Learning-Environment-Design-Player-Brains.md),
    [Heuristic](Learning-Environment-Design-Heuristic-Brains.md),
    [Learning](Learning-Environment-Design-Learning-Brains.md)
* [學習環境最佳實踐](Learning-Environment-Best-Practices.md)
* [使用顯示器](Feature-Monitor.md)
* [使用可執行的環境](Learning-Environment-Executable.md)

## 訓練

* [訓練 ML-Agents](Training-ML-Agents.md)
* [訓練-使用Proximal Policy Optimization近端策略優化(PPO)](Training-PPO.md)
* [訓練-使用Curriculum Learning課程學習](Training-Curriculum-Learning.md)
* [訓練-使用Imitation Learning模仿學習](Training-Imitation-Learning.md)
* [訓練-使用LSTM長短期記憶](Feature-Memory.md)
* [雲端上訓練-使用Amazon Web Services](Training-on-Amazon-Web-Service.md)
* [雲端上訓練-使用Microsoft Azure](Training-on-Microsoft-Azure.md)
* [使用TensorBoard觀察Training](Using-Tensorboard.md)

## 推論Inference
//速度更快、效率更高的神經網路會按照訓練過的內容，猜想新資料的走向。在人工智慧圈的詞彙裡，這稱為「inference」（推論）<br/>
//TensorFlowSharp是Tensorflow的C#語言表
* [TensorFlowSharp in Unity (試驗)](Using-TensorFlow-Sharp-in-Unity.md)

## 幫助

* [ML-Agents早期版本遷移](Migrating.md)
* [常見問題](FAQ.md)
* [ML-Agents詞彙表](Glossary.md)
* [限制](Limitations.md)

## API文件

* [API Reference](API-Reference.md)
* [如何使用Python API](Python-API.md)
* [打包學習環境](../gym-unity/README.md)
