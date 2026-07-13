## Technical Stack

<table>
<tr><td>Machine Learning</td><td>

[![Python](https://img.shields.io/badge/Python-34495E?style=flat-square&logo=python&logoColor=white)](https://www.python.org/) 
[![PyTorch](https://img.shields.io/badge/PyTorch-34495E?style=flat-square&logo=pytorch&logoColor=white)](https://pytorch.org/) 
[![scikit-learn](https://img.shields.io/badge/scikit--learn-34495E?style=flat-square&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/) 
[![TensorFlow](https://img.shields.io/badge/TensorFlow-34495E?style=flat-square&logo=tensorflow&logoColor=white)](https://www.tensorflow.org/) 
[![CUDA](https://img.shields.io/badge/CUDA-34495E?style=flat-square&logo=nvidia&logoColor=white)](https://developer.nvidia.com/cuda-toolkit)

</td></tr>
<tr><td>Data Science</td><td>

[![R](https://img.shields.io/badge/R-34495E?style=flat-square&logo=r&logoColor=white)](https://www.r-project.org/) 
[![Jupyter](https://img.shields.io/badge/Jupyter-34495E?style=flat-square&logo=jupyter&logoColor=white)](https://jupyter.org/) 
[![NumPy](https://img.shields.io/badge/NumPy-34495E?style=flat-square&logo=numpy&logoColor=white)](https://numpy.org/) 
[![Pandas](https://img.shields.io/badge/Pandas-34495E?style=flat-square&logo=pandas&logoColor=white)](https://pandas.pydata.org/)

</td></tr>
<tr><td>Big Data</td><td>

[![Java](https://img.shields.io/badge/Java-34495E?style=flat-square&logo=openjdk&logoColor=white)](https://www.java.com/) 
[![Apache Hadoop](https://img.shields.io/badge/Hadoop-34495E?style=flat-square&logo=apachehadoop&logoColor=white)](https://hadoop.apache.org/) 
[![Apache Hive](https://img.shields.io/badge/Hive-34495E?style=flat-square&logo=apachehive&logoColor=white)](https://hive.apache.org/) 
[![PySpark](https://img.shields.io/badge/PySpark-34495E?style=flat-square&logo=apachespark&logoColor=white)](https://spark.apache.org/docs/latest/api/python/)

</td></tr>
<tr><td>Client-side</td><td>

[![JavaScript](https://img.shields.io/badge/JavaScript-34495E?style=flat-square&logo=javascript&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) 
[![Node.js](https://img.shields.io/badge/Node.js-34495E?style=flat-square&logo=node.js&logoColor=white)](https://nodejs.org/) 
[![HTML5](https://img.shields.io/badge/HTML5-34495E?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML) 
[![CSS3](https://img.shields.io/badge/CSS3-34495E?style=flat-square&logo=css&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS) 
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-34495E?style=flat-square&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)

</td></tr>
<tr><td>Server-side</td><td>

[![TypeScript](https://img.shields.io/badge/TypeScript-34495E?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/) 
[![SQLite](https://img.shields.io/badge/SQLite-34495E?style=flat-square&logo=sqlite&logoColor=white)](https://www.sqlite.org/) 
[![MySQL](https://img.shields.io/badge/MySQL-34495E?style=flat-square&logo=mysql&logoColor=white)](https://www.mysql.com/) 
[![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-34495E?style=flat-square&logo=cloudflareworkers&logoColor=white)](https://workers.cloudflare.com/)

</td></tr>
<tr><td>Package Management</td><td>

[![pip](https://img.shields.io/badge/pip-34495E?style=flat-square&logo=pypi&logoColor=white)](https://pip.pypa.io/) 
[![conda](https://img.shields.io/badge/conda-34495E?style=flat-square&logo=anaconda&logoColor=white)](https://docs.conda.io/) 
[![nvm](https://img.shields.io/badge/nvm-34495E?style=flat-square&logo=nvm&logoColor=white)](https://github.com/nvm-sh/nvm) 
[![npm](https://img.shields.io/badge/npm-34495E?style=flat-square&logo=npm&logoColor=white)](https://www.npmjs.com/)

</td></tr>
<tr><td>CLI & Markups</td><td>

[![Bash](https://img.shields.io/badge/Bash-34495E?style=flat-square&logo=gnu-bash&logoColor=white)](https://www.gnu.org/software/bash/) 
[![Git](https://img.shields.io/badge/Git-34495E?style=flat-square&logo=git&logoColor=white)](https://git-scm.com/) 
[![LaTeX](https://img.shields.io/badge/LaTeX-34495E?style=flat-square&logo=latex&logoColor=white)](https://www.latex-project.org/) 
[![Markdown](https://img.shields.io/badge/Markdown-34495E?style=flat-square&logo=markdown&logoColor=white)](https://www.markdownguide.org/)

</td></tr>
</table>

**Favorite Editors:** Notepad++, Spyder

## Projects

### Data Engineering

**[WeChat Export Tool](https://github.com/chengmarc/wechat-to-LLM)**  
Agent-oriented export pipeline for WeChat chat histories (Python + SQL). Interfaces with `ylytdeng/wechat-decrypt` for decryption, supports both 1-on-1 and group conversations, and outputs LLM-readable compressed text. Table schema reverse-engineered independently.

**[PaySim Fraud Detection Data Warehouse](https://github.com/chengmarc/paysim-dw)**  
Offline data warehouse for fraud detection on 6.3M PaySim transactions, built on PySpark + Hive + Hadoop. 3-layer architecture (ODS → DWD → ADS): DWD uses ORC + Snappy with derived fraud features; ADS outputs per-type fraud rates and a high-risk account registry.

### Blockchain

**[MambaSSM for Time Series Forecasting](https://github.com/chengmarc/state-space-mamba)**  
Sequence-to-sequence 30-day forecasting on multi-feature on-chain data (PyTorch). Addresses lag-1 degeneracy via logarithmic detrending, orthogonal multi-feature inputs, and MambaSSM's selective state gating. Benchmarks six architectures — MambaSSM achieves best performance and strongest resistance to trivial state copying.

**[Quant Analysis Tools](https://github.com/chengmarc/quant-analysis)**  
Five modules, each self-contained:
- `overview/` — market statistics and Monte Carlo simulation across 28,000 CoinGecko coins
- `binance/` — live trading framework via Binance REST API
- `exponential-DCA/` — DCA strategy using volatility-normalized residuals
- `random_walk_interval.py` — BTC price simulation segmented by halving cycles
- `UTXO.ipynb` — on-chain indicator analysis

**[ERC-20 Memecoin](https://github.com/chengmarc/ECR-20-memecoin)**  
ERC-20 token implementation in Solidity with full deployment to Ethereum mainnet. Covers contract structure, token mechanics, and the end-to-end on-chain deployment workflow.

### Deep Learning

**[GPT-2 Replication](https://github.com/chengmarc/gpt-replication)**  
From-scratch replication of GPT-2, based on `rasbt/LLMs-from-scratch`. 162M parameters, 768-dim embeddings, 12 heads, 12 layers. Architecture details: learned positional embeddings, pre-LayerNorm placement, GELU with tanh approximation, causal masking via $-\infty$ pre-softmax. Tokenization via BPE (`tiktoken`, gpt2 vocab). Trained on the Harry Potter corpus with AdamW (lr=4e-4, weight decay=0.1), cross-entropy next-token prediction objective. (PyTorch)

**[Image Classification](https://github.com/chengmarc/image-labelling)**  
ConvNet on MNIST/EMNIST; ResNet-34 and ResNet-101 on CIFAR-10/100. ResNet-34 uses basic blocks (two 3×3 convolutions), ResNet-101 uses bottleneck blocks (1×1 → 3×3 → 1×1). Core focus: how identity shortcut connections and network depth interact across datasets of varying difficulty. (PyTorch)
