
<a name="readme-top"></a>

<div align="center">

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

</div>
<!-- [![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url] -->



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/dr413677671/Quantflow-deep-learning-quant-framework-deep-learning-quant-framework">
    <img src="docs/logo.png" alt="Logo" width="384" height="216">
  </a>
</div>

  <h3 align="center">Quantflow Deep-learning Quant Framework</h3>
  <p align="center">
    A Light-weight Deep-learning Quant Framework
    <br />
    <!-- <a href="https://github.com/dr413677671/Quantflow-deep-learning-quant-framework/README.md"><strong>Play it »</strong></a> -->
    <br />
    <br />
    <!-- <a href="https://github.com/dr413677671/Quantflow-deep-learning-quant-framework/README.md">Explore the docs</a>
    · -->
    <a href="https://github.com/dr413677671/Quantflow-deep-learning-quant-framework/issues">Report Bug</a>
    ·
    <a href="https://github.com/dr413677671/Quantflow-deep-learning-quant-framework/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <!-- <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul> -->
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
        <ul>
        <li><a href="#Prerequisites">Prerequisites</a></li>
        <li><a href="#Installation">Installation</a></li>
        <li><a href="#Usage">Usage</a></li>
      </ul>
    </li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->

<!-- <div align=center>
<img src='./assets/screenshot.JPG'>
</div> -->

## About The Project

Homemade light-weight quant framework. Support Sliding windows, hyper-parameter search, backtesting, Reversing Trade and etc. See [LSTM stock price prediction demo](https://github.com/dr413677671/LSTM-stock-price-prediction/) 

自制量化框架。支持滑窗, 超参数搜索, 反向对冲, 回测等。查看基于Quantflow-deep-learning-quant-framework的 [LSTM 股票预测 Demo](https://github.com/dr413677671/LSTM-stock-price-prediction/)。

## Features:
- [x] Model
    - [x] LSTM
    - [x] Seq2seq
    - [x] Resnet50-1D
- [x] Prediction
    - [x] Signal Classification (Buy, Sell, Hold) 信号分类
    - [x] Regression (avg price in next window) 回归
- [x] Backtesting Metrics 回调指标
    - [x] Sharpe 夏普
    - [x] Maximum Drawdown 最大回撤
    - [x] Alpha (regression/annualized) (回归法/年化)
    - [x] Beta (regression/annualized) (回归法/年化)
    - [x] Interval rate of return 平均区间收益率
    - [x] Annualized rate of return (baseline/stretegy) 年化收益率 (基准/策略)
    - [x] backtesting rate of return 策略回测收益率
- [x] others
    - [x] Reversing Trade Support 反向对冲回调策略
    - [x] Sliding Window 滑窗生成器
    - [x] focal_loss
    - [x] class_weighed_sampling 分类权重采样 (抑制类别不均衡)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

<!-- * [![Python][python-img]][python-url] -->
* [![Tensorflow][Tensorflow]][Tensorflow-url]
* [![Keras][Keras]][Keras-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

1) Clone repo.

  ```sh
  git clone https://github.com/dr413677671/Quantflow-deep-learning-quant-framework.git
  ```

1) Install dependencies.

  ```sh
  pip install <repo-directory>/requirements.txt
  ```

## Usage

**See [LSTM stock price prediction demo](https://github.com/dr413677671/LSTM-stock-price-prediction/)**

<!-- CONTACT -->
## Contact

[<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg' alt='github' margin='10px' height='40'>](https://github.com/https://github.com/dr413677671) &nbsp;&nbsp; [<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/youtube.svg' alt='YouTube' height='40'>](https://www.youtube.com/channel/https://www.youtube.com/@randuan9718/videos) &nbsp;&nbsp; [<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/zhihu.svg' alt='zhihu' height='40'>](https://www.zhihu.com/people/kumonoue)  

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments
Based on these brilliant repos:
* [Seq2seq](https://github.com/google/seq2seq)
* [LSTM](https://www.tensorflow.org/api_docs/python/tf/keras/layers/LSTM)
* Logo genetrared by [Stable-Diffusion](https://github.com/CompVis/stable-diffusion)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/dr413677671/Quantflow-deep-learning-quant-framework.svg?style=for-the-badge
[contributors-url]: https://github.com/dr413677671/Quantflow-deep-learning-quant-framework/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/dr413677671/Quantflow-deep-learning-quant-framework.svg?style=for-the-badge
[forks-url]: https://github.com/dr413677671/Quantflow-deep-learning-quant-framework/network/members
[stars-shield]: https://img.shields.io/github/stars/dr413677671/Quantflow-deep-learning-quant-framework.svg?style=for-the-badge
[stars-url]: https://github.com/dr413677671/Quantflow-deep-learning-quant-framework/stargazers
[issues-shield]: https://img.shields.io/github/issues/dr413677671/Quantflow-deep-learning-quant-framework.svg?style=for-the-badge
[issues-url]: https://github.com/dr413677671/Quantflow-deep-learning-quant-framework/issues

[python-img]: https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue
[python-url]: https://www.python.org/
[Tensorflow]: https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white
[Tensorflow-url]: https://github.com/tensorflow/tensorflow
[Keras]: https://img.shields.io/badge/Keras-FF0000?style=for-the-badge&logo=keras&logoColor=white
[Keras-url]: https://github.com/keras-team/keras


<!-- [product-screenshot]: docs/screenshot.JPG -->
