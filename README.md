<img src="docs/images/unity-wide.png" align="middle" width="3000"/>

<img src="docs/images/image-banner.png" align="middle" width="3000"/>

# Unity ML-Agents Toolkit (Beta)

**Unity機器學習代理工具** (ML-Agents) 是一個開放原始碼的Unity插件
，讓遊戲和模擬器一個可以訓練出聰明的代理人的環境。代理人可以透過簡單易用的Python API，用強化學習、模仿學習、神經進化(neuroevolution)等其他機器學習的方法被訓練。我們也提供(以TensorFlow為基礎上)實現最新的演算法，讓遊戲開發者們和有興趣的人們可以輕鬆訓練出聰明的代理人在2D、3D和VR/AR遊戲上。 這些訓練好的代理人可以被用在多種目的，包含控制NPC(非玩家角色)行為 (像是多智能體(multi-agent)和對抗(adversarial)...等多樣的設置) 、自動測試遊戲建置和預先發布評估不同遊戲設計決策。 The ML-Agents
toolkit is mutually beneficial for both game developers and AI researchers as it
provides a central platform where advances in AI can be evaluated on Unity’s
rich environments and then made accessible to the wider research and game
developer communities.

## Features

* Unity environment control from Python
* 10+ sample Unity environments
* Support for multiple environment configurations and training scenarios
* Train memory-enhanced agents using deep reinforcement learning
* Easily definable Curriculum Learning scenarios
* Broadcasting of agent behavior for supervised learning
* Built-in support for Imitation Learning
* Flexible agent control with On Demand Decision Making
* Visualizing network outputs within the environment
* Simplified set-up with Docker
* Wrap learning environments as a gym

## Documentation

* For more information, in addition to installation and usage instructions, see
  our [documentation home](docs/Readme.md).
* If you are a researcher interested in a discussion of Unity as an AI platform, see a pre-print of our [reference paper on Unity and the ML-Agents Toolkit](https://arxiv.org/abs/1809.02627). Also, see below for instructions on citing this paper.
* If you have used an earlier version of the ML-Agents toolkit, we strongly
  recommend our [guide on migrating from earlier versions](docs/Migrating.md).

## Additional Resources

We have published a series of blog posts that are relevant for ML-Agents:

* Overviewing reinforcement learning concepts
  ([multi-armed bandit](https://blogs.unity3d.com/2017/06/26/unity-ai-themed-blog-entries/)
  and
  [Q-learning](https://blogs.unity3d.com/2017/08/22/unity-ai-reinforcement-learning-with-q-learning/))
* [Using Machine Learning Agents in a real game: a beginner’s guide](https://blogs.unity3d.com/2017/12/11/using-machine-learning-agents-in-a-real-game-a-beginners-guide/)
* [Post](https://blogs.unity3d.com/2018/02/28/introducing-the-winners-of-the-first-ml-agents-challenge/)
  announcing the winners of our
  [first ML-Agents Challenge](https://connect.unity.com/challenges/ml-agents-1)
* [Post](https://blogs.unity3d.com/2018/01/23/designing-safer-cities-through-simulations/)
  overviewing how Unity can be leveraged as a simulator to design safer cities.

In addition to our own documentation, here are some additional, relevant articles:

* [Unity AI - Unity 3D Artificial Intelligence](https://www.youtube.com/watch?v=bqsfkGbBU6k)
* [A Game Developer Learns Machine Learning](https://mikecann.co.uk/machine-learning/a-game-developer-learns-machine-learning-intent/)
* [Explore Unity Technologies ML-Agents Exclusively on Intel Architecture](https://software.intel.com/en-us/articles/explore-unity-technologies-ml-agents-exclusively-on-intel-architecture)

## Community and Feedback

The ML-Agents toolkit is an open-source project and we encourage and welcome
contributions. If you wish to contribute, be sure to review our
[contribution guidelines](CONTRIBUTING.md) and
[code of conduct](CODE_OF_CONDUCT.md).

If you run into any problems using the ML-Agents toolkit,
[submit an issue](https://github.com/Unity-Technologies/ml-agents/issues) and
make sure to include as much detail as possible.

Your opinion matters a great deal to us. Only by hearing your thoughts on the Unity ML-Agents Toolkit can we continue to improve and grow. Please take a few minutes to [let us know about it](https://github.com/Unity-Technologies/ml-agents/issues/1454). 


For any other questions or feedback, connect directly with the ML-Agents
team at ml-agents@unity3d.com. 

## Translations

To make the Unity ML-Agents toolkit accessible to the global research and
Unity developer communities, we're attempting to create and maintain
translations of our documentation. We've started with translating a subset
of the documentation to one language (Chinese), but we hope to continue
translating more pages and to other languages. Consequently,
we welcome any enhancements and improvements from the community.

* [Chinese](docs/localized/zh-CN/)

## License

[Apache License 2.0](LICENSE)

## Citation

If you use Unity or the ML-Agents Toolkit to conduct research, we ask that you cite the following paper as a reference:

Juliani, A., Berges, V., Vckay, E., Gao, Y., Henry, H., Mattar, M., Lange, D. (2018). Unity: A General Platform for Intelligent Agents. *arXiv preprint arXiv:1809.02627.* https://github.com/Unity-Technologies/ml-agents.
