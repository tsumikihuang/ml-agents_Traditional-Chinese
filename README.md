<img src="docs/images/unity-wide.png" align="middle" width="3000"/>

<img src="docs/images/image-banner.png" align="middle" width="3000"/>

# Unity ML-Agents 工具 (Beta測試版本)

**Unity機器學習代理工具** (ML-Agents) 是一個開放原始碼的Unity插件
，讓遊戲和模擬器一個可以訓練出聰明的代理人的環境。代理人可以透過簡單易用的Python API，用強化學習、模仿學習、神經進化(neuroevolution)等其他機器學習的方法被訓練。我們也提供(以TensorFlow為基礎上)實現最新的演算法，讓遊戲開發者們和有興趣的人們可以輕鬆訓練出聰明的代理人在2D、3D和VR/AR遊戲上。 這些訓練好的代理人可以被用在多種目的，包含控制NPC(非玩家角色)行為 (像是multi-agent多智能體和adversarial對抗...等多樣的設置) 、自動測試遊戲建置和預先發布評估不同遊戲設計決策。ML-Agents工具對於同事遊戲開發者和AI研究者是互利共贏的，因為它提供一個中央平台利於AI在Unity豐富的環境上運算，並且使之無障礙地擴展到更廣闊的研究和遊戲開發社群。

## 特色

* 從Python控制Unity環境
* 10多個Unity環境範例
* 支持多種環境配置和訓練場景
* 用深度強化學習訓練記憶增強代理
* 簡單可定義的課程式學習場景
* 廣播代理行為來達成監督式學習
* 內建資源給模仿學習
* 決策時彈性地控制代理人
* 在環境中視覺化網路輸出
* 簡單地使用Docker安裝
* 將學習環境打包成像是一個健身房

## 文件

* 安裝流程、常用指令...更多資訊，請看我們的[文件首頁](docs/Readme.md)。
* 如果你是一個對於討論AI平台有興趣的研究員，請看預先印製的[Unity和ML-Agents工具參考文件](https://arxiv.org/abs/1809.02627)，也可以看下方說明觀覽此文件。
* 如果你是使用早期ML-Agents工具的版本，我們強烈建議看[早期版本遷移指南](docs/Migrating.md)。

## 額外補充資源

我們有發佈一系列ML-Agents相關的部落格文章:

* 增強學習概念概觀
  ([multi-armed bandit](https://blogs.unity3d.com/2017/06/26/unity-ai-themed-blog-entries/)
  和
  [Q-learning](https://blogs.unity3d.com/2017/08/22/unity-ai-reinforcement-learning-with-q-learning/))
* [Using Machine Learning Agents in a real game: a beginner’s guide](https://blogs.unity3d.com/2017/12/11/using-machine-learning-agents-in-a-real-game-a-beginners-guide/)
* [文章](https://blogs.unity3d.com/2018/02/28/introducing-the-winners-of-the-first-ml-agents-challenge/)
  宣布我們
  [第一個ML-Agents挑戰](https://connect.unity.com/challenges/ml-agents-1)的贏家
* [文章](https://blogs.unity3d.com/2018/01/23/designing-safer-cities-through-simulations/)
  概觀為何Unity作為一個模擬器可以以小搏大設計出一個更安全的城市。

除了我們自己的文件外，這裡有一些其他額外的相關文章:

* [Unity AI - Unity 3D Artificial Intelligence](https://www.youtube.com/watch?v=bqsfkGbBU6k)
* [A Game Developer Learns Machine Learning](https://mikecann.co.uk/machine-learning/a-game-developer-learns-machine-learning-intent/)
* [Explore Unity Technologies ML-Agents Exclusively on Intel Architecture](https://software.intel.com/en-us/articles/explore-unity-technologies-ml-agents-exclusively-on-intel-architecture)

## 社區和回饋

ML-Agents工具是一個開源專案，我們鼓勵並歡迎各位的貢獻。如果你想要貢獻，請確認有讀過我們的
[貢獻準則](CONTRIBUTING.md) 和
[行為準則](CODE_OF_CONDUCT.md).

如果你使用ML-Agents工具有遇到任何問題可以
[提交問題](https://github.com/Unity-Technologies/ml-agents/issues) 並且確認盡可能地包含大量的細節。

你的意見對我們非常重要，聆聽你對於ML-Agents的想法可以讓我們持續進步和成長。請花一些時間來[讓我們知道](https://github.com/Unity-Technologies/ml-agents/issues/1454)。


有任何其他問題或回饋，請立即聯絡ML-Agent團隊 ml-agents@unity3d.com 

## 翻譯

為了使Unity ML-Agents工具無障礙地給全世界的研究和Unity開發者社群，我們新增並維護翻譯的文件。我們已經開始翻譯一個語言(簡體中文)，但我們希望持續翻譯更多文章和其他語言。因此，我們歡迎社群有任何加強和改進。

* [簡體中文](docs/localized/zh-CN/)

## 許可證

[Apache License 2.0](LICENSE)

## 引用

如果你使用Unity或ML-Agents工具進行研究，我們要求你引用以下文字當作參考:

Juliani, A., Berges, V., Vckay, E., Gao, Y., Henry, H., Mattar, M., Lange, D. (2018). Unity: A General Platform for Intelligent Agents. *arXiv preprint arXiv:1809.02627.* https://github.com/Unity-Technologies/ml-agents.
