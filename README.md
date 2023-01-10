[![Python Versions](https://img.shields.io/pypi/pyversions/pyqlib.svg?logo=python&logoColor=white)](https://pypi.org/project/pyqlib/#files)
[![Platform](https://img.shields.io/badge/platform-linux%20%7C%20windows%20%7C%20macos-lightgrey)](https://pypi.org/project/pyqlib/#files)
[![PypI Versions](https://img.shields.io/pypi/v/pyqlib)](https://pypi.org/project/pyqlib/#history)
[![Upload Python Package](https://github.com/microsoft/qlib/workflows/Upload%20Python%20Package/badge.svg)](https://pypi.org/project/pyqlib/)
[![Github Actions Test Status](https://github.com/microsoft/qlib/workflows/Test/badge.svg?branch=main)](https://github.com/microsoft/qlib/actions)
[![Documentation Status](https://readthedocs.org/projects/qlib/badge/?version=latest)](https://qlib.readthedocs.io/en/latest/?badge=latest)
[![License](https://img.shields.io/pypi/l/pyqlib)](LICENSE)
[![Join the chat at https://gitter.im/Microsoft/qlib](https://badges.gitter.im/Microsoft/qlib.svg)](https://gitter.im/Microsoft/qlib?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## :newspaper: **What's NEW!** &nbsp;   :sparkling_heart: 
Recent released features
| Feature | Status |
| --                      | ------    |
| Release Qlib v0.9.0 | :octocat: [Released](https://github.com/microsoft/qlib/releases/tag/v0.9.0) on Dec 9, 2022 |
| RL Learning Framework | :hammer: :chart_with_upwards_trend: Released on Nov 10, 2022. [#1332](https://github.com/microsoft/qlib/pull/1332), [#1322](https://github.com/microsoft/qlib/pull/1322), [#1316](https://github.com/microsoft/qlib/pull/1316),[#1299](https://github.com/microsoft/qlib/pull/1299),[#1263](https://github.com/microsoft/qlib/pull/1263), [#1244](https://github.com/microsoft/qlib/pull/1244), [#1169](https://github.com/microsoft/qlib/pull/1169), [#1125](https://github.com/microsoft/qlib/pull/1125), [#1076](https://github.com/microsoft/qlib/pull/1076)|
| HIST and IGMTF models | :chart_with_upwards_trend: [Released](https://github.com/microsoft/qlib/pull/1040) on Apr 10, 2022 |
| Qlib [notebook tutorial](https://github.com/microsoft/qlib/tree/main/examples/tutorial) | 📖 [Released](https://github.com/microsoft/qlib/pull/1037) on Apr 7, 2022 | 
| Ibovespa index data | :rice: [Released](https://github.com/microsoft/qlib/pull/990) on Apr 6, 2022 |
| Point-in-Time database | :hammer: [Released](https://github.com/microsoft/qlib/pull/343) on Mar 10, 2022 |
| Arctic Provider Backend & Orderbook data example | :hammer: [Released](https://github.com/microsoft/qlib/pull/744) on Jan 17, 2022 |
| Meta-Learning-based framework & DDG-DA  | :chart_with_upwards_trend:  :hammer: [Released](https://github.com/microsoft/qlib/pull/743) on Jan 10, 2022 | 
| Planning-based portfolio optimization | :hammer: [Released](https://github.com/microsoft/qlib/pull/754) on Dec 28, 2021 | 
| Release Qlib v0.8.0 | :octocat: [Released](https://github.com/microsoft/qlib/releases/tag/v0.8.0) on Dec 8, 2021 |
| ADD model | :chart_with_upwards_trend: [Released](https://github.com/microsoft/qlib/pull/704) on Nov 22, 2021 |
| ADARNN  model | :chart_with_upwards_trend: [Released](https://github.com/microsoft/qlib/pull/689) on Nov 14, 2021 |
| TCN  model | :chart_with_upwards_trend: [Released](https://github.com/microsoft/qlib/pull/668) on Nov 4, 2021 |
| Nested Decision Framework | :hammer: [Released](https://github.com/microsoft/qlib/pull/438) on Oct 1, 2021. [Example](https://github.com/microsoft/qlib/blob/main/examples/nested_decision_execution/workflow.py) and [Doc](https://qlib.readthedocs.io/en/latest/component/highfreq.html) |
| Temporal Routing Adaptor (TRA) | :chart_with_upwards_trend: [Released](https://github.com/microsoft/qlib/pull/531) on July 30, 2021 |
| Transformer & Localformer | :chart_with_upwards_trend: [Released](https://github.com/microsoft/qlib/pull/508) on July 22, 2021 |
| Release Qlib v0.7.0 | :octocat: [Released](https://github.com/microsoft/qlib/releases/tag/v0.7.0) on July 12, 2021 |
| TCTS Model | :chart_with_upwards_trend: [Released](https://github.com/microsoft/qlib/pull/491) on July 1, 2021 |
| Online serving and automatic model rolling | :hammer:  [Released](https://github.com/microsoft/qlib/pull/290) on May 17, 2021 | 
| DoubleEnsemble Model | :chart_with_upwards_trend: [Released](https://github.com/microsoft/qlib/pull/286) on Mar 2, 2021 | 
| High-frequency data processing example | :hammer: [Released](https://github.com/microsoft/qlib/pull/257) on Feb 5, 2021  |
| High-frequency trading example | :chart_with_upwards_trend: [Part of code released](https://github.com/microsoft/qlib/pull/227) on Jan 28, 2021  | 
| High-frequency data(1min) | :rice: [Released](https://github.com/microsoft/qlib/pull/221) on Jan 27, 2021 |
| Tabnet Model | :chart_with_upwards_trend: [Released](https://github.com/microsoft/qlib/pull/205) on Jan 22, 2021 |

Features released before 2021 are not listed here.

<p align="center">
  <img src="http://fintech.msra.cn/images_v070/logo/1.png" />
</p>


Qlib是一个面向人工智能的量化投资平台，旨在实现人工智能技术在量化投资中的潜力、赋能研究、创造价值。

它包含了数据处理、模型训练、回测等完整的ML pipeline；并涵盖了量化投资的整个链条：寻求阿尔法、风险建模、组合优化和订单执行。

通过Qlib，用户可以轻松地尝试创造更好的量化投资策略的想法。


更多信息参考: ["Qlib: An AI-oriented Quantitative Investment Platform"](https://arxiv.org/abs/2009.11189).


<table>
  <tbody>
    <tr>
      <th>Frameworks, Tutorial, Data & DevOps</th>
      <th>Main Challenges & Solutions in Quant Research</th>
    </tr>
    <tr>
      <td>
        <li><a href="#plans"><strong>Plans</strong></a></li>
        <li><a href="#framework-of-qlib">Framework of Qlib</a></li>
        <li><a href="#quick-start">Quick Start</a></li>
          <ul dir="auto">
            <li type="circle"><a href="#installation">Installation</a> </li>
            <li type="circle"><a href="#data-preparation">Data Preparation</a></li>
            <li type="circle"><a href="#auto-quant-research-workflow">Auto Quant Research Workflow</a></li>
            <li type="circle"><a href="#building-customized-quant-research-workflow-by-code">Building Customized Quant Research Workflow by Code</a></li></ul>
        <li><a href="#quant-dataset-zoo"><strong>Quant Dataset Zoo</strong></a></li>
        <li><a href="#learning-framework">Learning Framework</a></li>
        <li><a href="#more-about-qlib">More About Qlib</a></li>
        <li><a href="#offline-mode-and-online-mode">Offline Mode and Online Mode</a>
        <ul>
          <li type="circle"><a href="#performance-of-qlib-data-server">Performance of Qlib Data Server</a></li></ul>
        <li><a href="#related-reports">Related Reports</a></li>
        <li><a href="#contact-us">Contact Us</a></li>
        <li><a href="#contributing">Contributing</a></li>
      </td>
      <td valign="baseline">
        <li><a href="#main-challenges--solutions-in-quant-research">Main Challenges &amp; Solutions in Quant Research</a>
          <ul>
            <li type="circle"><a href="#forecasting-finding-valuable-signalspatterns">Forecasting: Finding Valuable Signals/Patterns</a>
              <ul>
                <li type="disc"><a href="#quant-model-paper-zoo"><strong>Quant Model (Paper) Zoo</strong></a>
                  <ul>
                    <li type="circle"><a href="#run-a-single-model">Run a Single Model</a></li>
                    <li type="circle"><a href="#run-multiple-models">Run Multiple Models</a></li>
                  </ul>
                </li>
              </ul>
            </li>
          <li type="circle"><a href="#adapting-to-market-dynamics">Adapting to Market Dynamics</a></li>
          </ul>
        </li>
      </td>
    </tr>
  </tbody>
</table>

# Plans
正在开发的新功能（按预计发布时间排序）。
你对这些功能的反馈是非常重要的。

<!-- | Feature                        | Status      | -->
<!-- | --                      | ------    | -->

# Framework of Qlib

<div style="align: center">
<img src="docs/_static/img/framework-abstract.jpg" />
</div>

Qlib的高层框架可以在上面找到（用户可以在深入了解Qlib设计的[详细框架]（https://qlib.readthedocs.io/en/latest/introduction/introduction.html#framework））。
这些组件被设计成松散耦合的模块，每个组件都可以独立使用。


Qlib提供了一个强大的基础设施来支持Quant研究。[数据](https://qlib.readthedocs.io/en/latest/component/data.html)始终是一个重要的部分。
一个强大的学习框架旨在支持不同的学习范式（如[强化学习](https://qlib.readthedocs.io/en/latest/component/rl.html)，[监督学习](https://qlib.readthedocs.io/en/latest/component/workflow.html#model-section)）和不同层次的模式（如[市场动态建模](https://qlib.readthedocs.io/en/latest/component/meta.html)）。
通过对市场进行建模，[交易策略](https://qlib.readthedocs.io/en/latest/component/strategy.html)将产生将被执行的交易决策。不同级别或粒度的多个交易策略和执行者可以[嵌套在一起进行优化和运行](https://qlib.readthedocs.io/en/latest/component/highfreq.html)。
最后，将提供一个全面的[分析](https://qlib.readthedocs.io/en/latest/component/report.html)，该模型可以以较低的成本[在线服务](https://qlib.readthedocs.io/en/latest/component/online.html)。


# Quick Start
本快速入门指南试图证明
1. 用_Qlib_建立一个完整的Quant研究工作流程并尝试你的想法是非常容易的。
2. 2.虽然有了*公共数据*和*简单的模型，但机器学习技术在实际的量化投资中**效果非常好。

这里有一个快速的**[演示](https://terminalizer.com/view/3f24561a4470)**显示了如何安装``Qlib``，并使用``qrun``运行LightGBM。**但是***，请确保你已经按照[说明](#data-preparation)准备好数据。


## 安装

下表展示了支持的 Python 版本的“Qlib”：
|               | install with pip           | install from source  | plot |
| ------------- |:---------------------:|:--------------------:|:----:|
| Python 3.7    | :heavy_check_mark:    | :heavy_check_mark:   | :heavy_check_mark: |
| Python 3.8    | :heavy_check_mark:    | :heavy_check_mark:   | :heavy_check_mark: |
| Python 3.9    | :x:                   | :heavy_check_mark:   | :x: |

**Note**: 
1. 建议使用 **Conda** 来管理您的 Python 环境。
1. 请注意，在 Python 3.6 中安装 cython 从源代码安装 ``Qlib`` 时会出现一些错误。如果用户在他们的机器上使用 Python 3.6，建议*升级* Python 到 3.7 版或使用 `conda` 的 Python 从源代码安装 ``Qlib``。
1. 对于 Python 3.9，`Qlib` 支持运行工作流，例如训练模型、进行回测和绘制大部分相关数据（包含在 [notebook](examples/workflow_by_code.ipynb) 中的数据）。但是，目前不支持*模型性能*的绘图，我们将在未来升级依赖包时修复此问题。
1. `Qlib`需要`tables`包，tables中的`hdf5`不支持python3.9。


### Install with pip
用户可以根据以下命令通过 pip 轻松安装``Qlib``。

```bash
  pip install pyqlib
```

**注意**：pip 将安装最新的稳定 qlib。但是，qlib 的主要分支正在积极开发中。如果你想在主分支测试最新的脚本或功能。请使用以下方法安装 qlib。

### Install from source
另外，用户可以按照以下步骤通过源代码安装最新的开发版本``Qlib``：

* 在从源代码安装 ``Qlib`` 之前，用户需要安装一些依赖项：

  ```bash
  pip install numpy
  pip install --upgrade  cython
  ```

* 克隆repository并按如下方式安装“Qlib”。
    ```bash
    git clone https://github.com/microsoft/qlib.git && cd qlib
    pip install .
    ```
  **注意**：您也可以使用 `python setup.py install` 安装 Qlib。但这不是推荐的方法。它会跳过 `pip` 并导致难以理解的问题。例如，**只有**命令``pip install .`` **可以**覆盖``pip install pyqlib``安装的稳定版本，而命令``python setup.py install`` **不能**。

**提示**：如果您无法安装 `Qlib` 或在您的环境中运行样本，比较您的步骤和 [CI 工作流程](.github/workflows/test_qlib_from_source.yml) 可能会帮助您找到问题所在。


## 数据准备
通过运行以下代码加载和准备数据：

### Get with module
  ```bash
  # get 1d data
  python -m qlib.run.get_data qlib_data --target_dir ~/.qlib/qlib_data/cn_data --region cn

  # get 1min data
  python -m qlib.run.get_data qlib_data --target_dir ~/.qlib/qlib_data/cn_data_1min --region cn --interval 1min

  ```

### Get from source

  ```bash
  # get 1d data
  python scripts/get_data.py qlib_data --target_dir ~/.qlib/qlib_data/cn_data --region cn

  # get 1min data
  python scripts/get_data.py qlib_data --target_dir ~/.qlib/qlib_data/cn_data_1min --region cn --interval 1min

  ```
该数据集由[爬虫脚本](scripts/data_collector/)收集的公共数据创建，这些数据已在同一repository中发布。
用户可以用它创建相同的数据集。 [数据集说明](https://github.com/microsoft/qlib/tree/main/scripts/data_collector#description-of-dataset)


请注意，数据是来自 [Yahoo Finance](https://finance.yahoo.com/lookup), 并且数据可能并不完美。
如果用户有高质量的数据集，我们建议他们准备自己的数据。更多信息，用户可以参考[相关文档](https://qlib.readthedocs.io/en/latest/component/data.html#converting-csv-format-into-qlib-format)*。

### 自动更新每天的频率数据（来自雅虎财经）。
  > 如果用户只想在历史数据上尝试他们的模型和策略，这一步是可选的。
  > 建议用户手动更新一次数据（--trading_date 2021-05-25），然后将其设置为自动更新。>
  > **注意**。用户不能根据Qlib提供的离线数据来增量更新数据（一些字段被删除以减少数据的大小）。用户应该使用[yahoo collector](https://github.com/microsoft/qlib/tree/main/scripts/data_collector/yahoo#automatic-update-of-daily-frequency-datafrom-yahoo-finance)从头开始下载雅虎数据，然后增量更新它。
  > 
  > For more information, please refer to: [yahoo collector](https://github.com/microsoft/qlib/tree/main/scripts/data_collector/yahoo#automatic-update-of-daily-frequency-datafrom-yahoo-finance)

  * 每个交易日自动更新数据到 "qlib "目录(Linux)
      * use *crontab*: `crontab -e`
      * set up timed tasks:

        ```
        * * * * 1-5 python <script path> update_data_to_bin --qlib_data_1d_dir <user data dir>
        ```
        * **script path**: *scripts/data_collector/yahoo/collector.py*

  * Manual update of data
      ```
      python scripts/data_collector/yahoo/collector.py update_data_to_bin --qlib_data_1d_dir <user data dir> --trading_date <start date> --end_date <end date>
      ```
      * *trading_date*: start of trading day
      * *end_date*: end of trading day(not included)


<!-- 
- 运行初始化代码并获得股票数据。

  ```python
  import qlib
  from qlib.data import D
  from qlib.constant import REG_CN

  # Initialization
  mount_path = "~/.qlib/qlib_data/cn_data"  # target_dir
  qlib.init(mount_path=mount_path, region=REG_CN)

  # Get stock data by Qlib
  # Load trading calendar with the given time range and frequency
  print(D.calendar(start_time='2010-01-01', end_time='2017-12-31', freq='day')[:2])

  # 将一个给定的市场名称解析为一个股票池配置
  instruments = D.instruments('csi500')
  print(D.list_instruments(instruments=instruments, start_time='2010-01-01', end_time='2017-12-31', as_list=True)[:6])

  # 在给定的时间范围内加载某些股票的特征
  instruments = ['SH600000']
  fields = ['$close', '$volume', 'Ref($close, 1)', 'Mean($close, 3)', '$high-$low']
  print(D.features(instruments, fields, start_time='2010-01-01', end_time='2017-12-31', freq='day').head())
  ```
 -->

## 自动定量研究工作流程
Qlib提供了一个名为`qrun`的工具来自动运行整个工作流程（包括建立数据集，训练模型，回测和评估）。你可以启动一个自动量化研究的工作流程，并根据以下步骤进行图形化的报告分析。

1. Quant Research Workflow: Run  `qrun` with lightgbm workflow config ([workflow_config_lightgbm_Alpha158.yaml](examples/benchmarks/LightGBM/workflow_config_lightgbm_Alpha158.yaml) as following.
    ```bash
      cd examples  # Avoid running program under the directory contains `qlib`
      qrun benchmarks/LightGBM/workflow_config_lightgbm_Alpha158.yaml
    ```
    如果用户想在调试模式下使用`qrun`，请使用以下命令。
    ```bash
    python -m pdb qlib/workflow/cli.py examples/benchmarks/LightGBM/workflow_config_lightgbm_Alpha158.yaml
    ```
    The result of `qrun` is as follows, please refer to [Intraday Trading](https://qlib.readthedocs.io/en/latest/component/backtest.html) for more details about the result. 

    ```bash

    'The following are analysis results of the excess return without cost.'
                           risk
    mean               0.000708
    std                0.005626
    annualized_return  0.178316
    information_ratio  1.996555
    max_drawdown      -0.081806
    'The following are analysis results of the excess return with cost.'
                           risk
    mean               0.000512
    std                0.005626
    annualized_return  0.128982
    information_ratio  1.444287
    max_drawdown      -0.091078
    ```
    Here are detailed documents for `qrun` and [workflow](https://qlib.readthedocs.io/en/latest/component/workflow.html).

2. Graphical Reports Analysis: Run `examples/workflow_by_code.ipynb` with `jupyter notebook` to get graphical reports
    - Forecasting signal (model prediction) analysis
      - Cumulative Return of groups
      ![Cumulative Return](http://fintech.msra.cn/images_v070/analysis/analysis_model_cumulative_return.png?v=0.1)
      - Return distribution
      ![long_short](http://fintech.msra.cn/images_v070/analysis/analysis_model_long_short.png?v=0.1)
      - Information Coefficient (IC)
      ![Information Coefficient](http://fintech.msra.cn/images_v070/analysis/analysis_model_IC.png?v=0.1)
      ![Monthly IC](http://fintech.msra.cn/images_v070/analysis/analysis_model_monthly_IC.png?v=0.1)
      ![IC](http://fintech.msra.cn/images_v070/analysis/analysis_model_NDQ.png?v=0.1)
      - Auto Correlation of forecasting signal (model prediction)
      ![Auto Correlation](http://fintech.msra.cn/images_v070/analysis/analysis_model_auto_correlation.png?v=0.1)

    - Portfolio analysis
      - Backtest return
      ![Report](http://fintech.msra.cn/images_v070/analysis/report.png?v=0.1)
      <!-- 
      - Score IC
      ![Score IC](docs/_static/img/score_ic.png)
      - Cumulative Return
      ![Cumulative Return](docs/_static/img/cumulative_return.png)
      - Risk Analysis
      ![Risk Analysis](docs/_static/img/risk_analysis.png)
      - Rank Label
      ![Rank Label](docs/_static/img/rank_label.png)
      -->
   - [Explanation](https://qlib.readthedocs.io/en/latest/component/report.html) of above results

## 通过代码构建定制的量化研究工作流程
自动工作流程可能不适合所有Quant研究人员的研究工作流程。为了支持灵活的Quant研究工作流程，Qlib还提供了一个模块化的接口，允许研究人员通过代码建立自己的工作流程。[这里](examples/workflow_by_code.ipynb)是一个通过代码定制量子研究工作流程的演示。

# 量化研究的主要挑战和解决方案
量子投资是一个非常独特的场景，有很多关键的挑战需要解决。
目前，Qlib为其中的几个问题提供了一些解决方案。

## 预测。寻找有价值的信号/模式
对股票价格趋势的准确预测是构建盈利投资组合的一个非常重要的部分。
然而，金融市场上各种格式的海量数据，使建立预测模型成为挑战。

越来越多的SOTA量子研究工作/论文，主要是建立预测模型，在复杂的金融数据中挖掘有价值的信号/模式，在`Qlib`中发布。

### [Quant Model (Paper) Zoo](examples/benchmarks)

这里有一个建立在`Qlib`上的模型列表。
- [GBDT based on XGBoost (Tianqi Chen, et al. KDD 2016)](examples/benchmarks/XGBoost/)
- [GBDT based on LightGBM (Guolin Ke, et al. NIPS 2017)](examples/benchmarks/LightGBM/)
- [GBDT based on Catboost (Liudmila Prokhorenkova, et al. NIPS 2018)](examples/benchmarks/CatBoost/)
- [MLP based on pytorch](examples/benchmarks/MLP/)
- [LSTM based on pytorch (Sepp Hochreiter, et al. Neural computation 1997)](examples/benchmarks/LSTM/)
- [GRU based on pytorch (Kyunghyun Cho, et al. 2014)](examples/benchmarks/GRU/)
- [ALSTM based on pytorch (Yao Qin, et al. IJCAI 2017)](examples/benchmarks/ALSTM)
- [GATs based on pytorch (Petar Velickovic, et al. 2017)](examples/benchmarks/GATs/)
- [SFM based on pytorch (Liheng Zhang, et al. KDD 2017)](examples/benchmarks/SFM/)
- [TFT based on tensorflow (Bryan Lim, et al. International Journal of Forecasting 2019)](examples/benchmarks/TFT/)
- [TabNet based on pytorch (Sercan O. Arik, et al. AAAI 2019)](examples/benchmarks/TabNet/)
- [DoubleEnsemble based on LightGBM (Chuheng Zhang, et al. ICDM 2020)](examples/benchmarks/DoubleEnsemble/)
- [TCTS based on pytorch (Xueqing Wu, et al. ICML 2021)](examples/benchmarks/TCTS/)
- [Transformer based on pytorch (Ashish Vaswani, et al. NeurIPS 2017)](examples/benchmarks/Transformer/)
- [Localformer based on pytorch (Juyong Jiang, et al.)](examples/benchmarks/Localformer/)
- [TRA based on pytorch (Hengxu, Dong, et al. KDD 2021)](examples/benchmarks/TRA/)
- [TCN based on pytorch (Shaojie Bai, et al. 2018)](examples/benchmarks/TCN/)
- [ADARNN based on pytorch (YunTao Du, et al. 2021)](examples/benchmarks/ADARNN/)
- [ADD based on pytorch (Hongshun Tang, et al.2020)](examples/benchmarks/ADD/)
- [IGMTF based on pytorch (Wentao Xu, et al.2021)](examples/benchmarks/IGMTF/)
- [HIST based on pytorch (Wentao Xu, et al.2021)](examples/benchmarks/HIST/)

我们非常欢迎你对新的量子模型进行PR。
每个模型在 "Alpha158 "和 "Alpha360 "数据集上的表现可以在[这里]（examples/benchmarks/README.md）找到。

### 运行一个单一的模型
上面列出的所有模型都可以用``Qlib``运行。用户可以通过[benchmarks](examples/benchmarks)文件夹找到我们提供的配置文件和关于模型的一些细节。更多信息可以在上面列出的模型文件中检索到。

`Qlib`提供了三种不同的方式来运行一个模型，用户可以选择最适合自己情况的方式。
- 用户可以使用上面提到的工具`qrun`，根据配置文件来运行一个模型的工作流。
- 用户可以根据`examples'文件夹中列出的[one](examples/workflow_by_code.py)创建一个`workflow_by_code'的python脚本。

- 用户可以使用`examples`文件夹中列出的脚本[`run_all_model.py`]（examples/run_all_model.py）来运行一个模型。下面是一个要使用的具体shell命令的例子。`python run_all_model.py run --models=lightgbm`，其中`--models`参数可以取上面列出的任何数量的模型（可用的模型可以在[benchmarks]（examples/benchmarks/）中找到）。更多的使用案例，请参考该文件的[docstrings](examples/run_all_model.py)。
    - **注意**。每个基线都有不同的环境依赖，请确保你的python版本符合要求（例如，由于`tensorflow==1.15.0'的限制，TFT只支持Python 3.6~3.7）。
    
### Run multiple models
`Qlib`还提供了一个脚本[`run_all_model.py`](examples/run_all_model.py)，可以运行多个模型进行多次迭代。(**注意**：该脚本目前只支持*Linux*。其他操作系统将在未来被支持。此外，它也不支持多次并行运行同一个模型，这一点在未来的开发中也会被修复）。
该脚本将为每个模型创建一个独特的虚拟环境，并在训练结束后删除这些环境。因此，只有实验结果，如 "IC "和 "backtest "结果将被生成和存储。
下面是一个运行所有模型进行10次迭代的例子。

```python
python run_all_model.py run 10
```
它还提供了一次性运行特定模型的API。对于更多的使用案例，请参考文件的[docstrings](examples/run_all_model.py)。

## [Adapting to Market Dynamics](examples/benchmarks_dynamic)

由于金融市场环境的非平稳性，数据分布在不同时期可能会发生变化，这使得建立在训练数据上的模型在未来的测试数据中的性能会下降。
因此，使预测模型/策略适应市场动态，对模型/策略的性能非常重要。

这里有一个建立在`Qlib`上的解决方案列表。
- [Rolling Retraining](examples/benchmarks_dynamic/baseline/)
- [DDG-DA on pytorch (Wendi, et al. AAAI 2022)](examples/benchmarks_dynamic/DDG-DA/)

# Quant Dataset Zoo
数据集在Quant中起着非常重要的作用。下面是建立在`Qlib`上的数据集列表。

| Dataset                                    | US Market | China Market |
| --                                         | --        | --           |
| [Alpha360](./qlib/contrib/data/handler.py) |  √        |  √           |
| [Alpha158](./qlib/contrib/data/handler.py) |  √        |  √           |

[Here](https://qlib.readthedocs.io/en/latest/advanced/alpha.html) is a tutorial to build dataset with `Qlib`.
我们非常欢迎你建立新的定量数据集的公关。


# Learning Framework
Qlib是高度可定制的，它的许多组件是可学习的。
可学习的组件是 "预测模型 "和 "交易agent "的实例。它们是基于 "学习框架 "层的学习，然后应用于 "工作流 "层的多个场景。
学习框架也利用了 "工作流 "层（例如，共享 "信息提取器"，基于 "执行环境 "创建环境）。

根据学习范式，它们可以被分为强化学习和监督学习。
- 对于监督学习，详细的文件可以在[这里](https://qlib.readthedocs.io/en/latest/component/model.html)找到。
- 对于强化学习，详细的文档可以找到[这里](https://qlib.readthedocs.io/en/latest/component/rl.html)。Qlib的RL学习框架利用`Workflow`层中的`Execution Env`来创建环境。 值得注意的是，"NestedExecutor "也被支持。这使用户能够一起优化不同级别的策略/模型/agent（例如，为一个特定的投资组合管理策略优化订单执行策略）。


# More About Qlib
如果你想快速浏览一下qlib中最常用的组件，你可以试试笔记本[here](examples/tutorial/)。

The detailed documents are organized in [docs](docs/).
[Sphinx](http://www.sphinx-doc.org) and the readthedocs theme is required to build the documentation in html formats. 
```bash
cd docs/
conda install sphinx sphinx_rtd_theme -y
# Otherwise, you can install them with pip
# pip install sphinx sphinx_rtd_theme
make html
```
你也可以直接在线查看[最新文件](http://qlib.readthedocs.io/)。
Qlib正处于积极和持续的开发中。我们的计划在路线图中，它作为一个[github项目]管理（https://github.com/microsoft/qlib/projects/1）。


# Offline Mode and Online Mode
Qlib的数据服务器可以部署为 "Offline"模式或 "Online "模式。默认模式是offline模式。
在 "Offline "模式下，数据将被部署在本地。

在 "Online "模式下，数据将被部署为一个共享的数据服务。数据和它们的缓存将由所有客户共享。由于更高的缓存点击率，数据检索性能有望得到改善。它也将消耗更少的磁盘空间。在线模式的文件可以在[Qlib-Server]（https://qlib-server.readthedocs.io/）中找到。在线模式可以通过[Azure CLI based scripts]（https://qlib-server.readthedocs.io/en/latest/build.html#one-click-deployment-in-azure）自动部署。在线数据服务器的源代码可以在[Qlib-Serverrepository](https://github.com/microsoft/qlib-server)中找到。

## Performance of Qlib Data Server
数据处理的性能对于像AI技术这样的数据驱动的方法是很重要的。作为一个面向AI的平台，Qlib提供了一个数据存储和数据处理的解决方案。为了证明Qlib数据服务器的性能，我们
将其与其他几个数据存储解决方案进行比较。
我们通过完成相同的任务来评估几个存储解决方案的性能。
该任务从股票市场的基本OHLCV每日数据（从2007年到2020年每天800只股票）中创建一个数据集（14个特征/因素）。该任务涉及数据查询和处理。

|                         | HDF5      | MySQL     | MongoDB   | InfluxDB  | Qlib -E -D  | Qlib +E -D   | Qlib +E +D  |
| --                      | ------    | ------    | --------  | --------- | ----------- | ------------ | ----------- |
| Total (1CPU) (seconds)  | 184.4±3.7 | 365.3±7.5 | 253.6±6.7 | 368.2±3.6 | 147.0±8.8   | 47.6±1.0     | **7.4±0.3** |
| Total (64CPU) (seconds) |           |           |           |           | 8.8±0.6     | **4.2±0.2**  |             |
* `+(-)E` indicates with (out) `ExpressionCache`
* `+(-)D` indicates with (out) `DatasetCache`

大多数通用数据库在加载数据方面花费了太多的时间。在研究了底层实现之后，我们发现，在通用数据库解决方案中，数据要经过太多层的接口和不必要的格式转换。
这样的开销大大减慢了数据的加载过程。
Qlib的数据是以一种紧凑的格式存储的，它可以有效地组合成数组，用于科学计算。

# Related Reports
- [Guide To Qlib: Microsoft’s AI Investment Platform](https://analyticsindiamag.com/qlib/)
- [微软也搞AI量化平台？还是开源的！](https://mp.weixin.qq.com/s/47bP5YwxfTp2uTHjUBzJQQ)
- [微矿Qlib：业内首个AI量化投资开源平台](https://mp.weixin.qq.com/s/vsJv7lsgjEi-ALYUz4CvtQ)

# Contact Us
- If you have any issues, please create issue [here](https://github.com/microsoft/qlib/issues/new/choose) or send messages in [gitter](https://gitter.im/Microsoft/qlib).
- If you want to make contributions to `Qlib`, please [create pull requests](https://github.com/microsoft/qlib/compare). 
- For other reasons, you are welcome to contact us by email([qlib@microsoft.com](mailto:qlib@microsoft.com)).
  - 我们正在招募新成员（包括全职和实习生），欢迎你的简历。

Join IM discussion groups:
|[Gitter](https://gitter.im/Microsoft/qlib)|
|----|
|![image](http://fintech.msra.cn/images_v070/qrcode/gitter_qr.png)|

# Contributing
We appreciate all contributions and thank all the contributors!
<a href="https://github.com/microsoft/qlib/graphs/contributors"><img src="https://contrib.rocks/image?repo=microsoft/qlib" /></a>

在我们于2020年9月在Github上发布Qlib作为一个开源项目之前，Qlib是我们小组的一个内部项目。不幸的是，内部的提交历史没有被保留下来。我们组的很多成员也为Qlib做出了很多贡献，其中包括王瑞华、张银达、于海苏、王树宇、彭博臣和[周东](https://github.com/evanzd/evanzd)。特别感谢[Dong Zhou](https://github.com/evanzd/evanzd)由于他的Qlib的初始版本。

## Guidance

This project welcomes contributions and suggestions.  
**Here are some 
[code standards and development guidance](docs/developer/code_standard_and_dev_guide.rst) for submiting a pull request.**

Making contributions is not a hard thing. Solving an issue(maybe just answering a question raised in [issues list](https://github.com/microsoft/qlib/issues) or [gitter](https://gitter.im/Microsoft/qlib)), fixing/issuing a bug, improving the documents and even fixing a typo are important contributions to Qlib.

For example, if you want to contribute to Qlib's document/code, you can follow the steps in the figure below.
<p align="center">
  <img src="https://github.com/demon143/qlib/blob/main/docs/_static/img/change%20doc.gif" />
</p>

If you don't know how to start to contribute, you can refer to the following examples.
| Type | Examples |
| -- | -- |
| Solving issues | [Answer a question](https://github.com/microsoft/qlib/issues/749);  [issuing](https://github.com/microsoft/qlib/issues/765) or [fixing](https://github.com/microsoft/qlib/pull/792) a bug |
| Docs | [Improve docs quality](https://github.com/microsoft/qlib/pull/797/files) ;  [Fix a typo](https://github.com/microsoft/qlib/pull/774) | 
| Feature |  Implement a [requested feature](https://github.com/microsoft/qlib/projects) like [this](https://github.com/microsoft/qlib/pull/754); [Refactor interfaces](https://github.com/microsoft/qlib/pull/539/files) |
| Dataset | [Add a dataset](https://github.com/microsoft/qlib/pull/733) | 
| Models |  [Implement a new model](https://github.com/microsoft/qlib/pull/689), [some instructions to contribute models](https://github.com/microsoft/qlib/tree/main/examples/benchmarks#contributing) |

[Good first issues](https://github.com/microsoft/qlib/labels/good%20first%20issue) are labelled to indicate that they are easy to start your contributions.

You can find some impefect implementation in Qlib by  `rg 'TODO|FIXME' qlib`
 
If you would like to become one of Qlib's maintainers to contribute more (e.g. help merge PR, triage issues), please contact us by email([qlib@microsoft.com](mailto:qlib@microsoft.com)).  We are glad to help to upgrade your permission.

## Licence
Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the right to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
