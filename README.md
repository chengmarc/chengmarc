# Zhongmang (Marc) Cheng

Math & stats (UofT, 2023). Mostly PyTorch and Python. \
Interested in sequence modeling and whatever sits between ML and quantitative methods.

Personal website: [chengmarc.com](https://chengmarc.com/)

## Research Interest

LLMs and the Default Mode Network — whether self-referential processing in language models has meaningful structural parallels to introspective cognition. No strong claims yet.

## Technical Stack

**Languages & Tools**

[![Python](https://img.shields.io/badge/Python-2C3E50?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![R](https://img.shields.io/badge/R-2C3E50?style=flat-square&logo=r&logoColor=white)](https://www.r-project.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-2C3E50?style=flat-square&logo=javascript&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Node.js](https://img.shields.io/badge/Node.js-2C3E50?style=flat-square&logo=node.js&logoColor=white)](https://nodejs.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-2C3E50?style=flat-square&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![HTML5](https://img.shields.io/badge/HTML5-2C3E50?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Bash](https://img.shields.io/badge/Bash-2C3E50?style=flat-square&logo=gnu-bash&logoColor=white)](https://www.gnu.org/software/bash/)
[![Git](https://img.shields.io/badge/Git-2C3E50?style=flat-square&logo=git&logoColor=white)](https://git-scm.com/)
[![LaTeX](https://img.shields.io/badge/LaTeX-2C3E50?style=flat-square&logo=latex&logoColor=white)](https://www.latex-project.org/)
[![Markdown](https://img.shields.io/badge/Markdown-2C3E50?style=flat-square&logo=markdown&logoColor=white)](https://www.markdownguide.org/)
[![Solidity](https://img.shields.io/badge/Solidity-2C3E50?style=flat-square&logo=solidity&logoColor=white)](https://soliditylang.org/)

**Machine Learning / Data**

[![PyTorch](https://img.shields.io/badge/PyTorch-34495E?style=flat-square&logo=pytorch&logoColor=white)](https://pytorch.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-34495E?style=flat-square&logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![Keras](https://img.shields.io/badge/Keras-34495E?style=flat-square&logo=keras&logoColor=white)](https://keras.io/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-34495E?style=flat-square&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![NumPy](https://img.shields.io/badge/NumPy-34495E?style=flat-square&logo=numpy&logoColor=white)](https://numpy.org/)
[![Pandas](https://img.shields.io/badge/Pandas-34495E?style=flat-square&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-34495E?style=flat-square&logoColor=white)](https://matplotlib.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-34495E?style=flat-square&logo=jupyter&logoColor=white)](https://jupyter.org/)

**Favorite Editors:** Notepad++, Spyder

## Projects

### Deep Learning

**[MambaSSM for Time Series Forecasting](https://github.com/chengmarc/state-space-mamba)**  
Sequence-to-sequence forecasting on multi-feature time series. Detrending pipeline: logarithmic trend extraction via non-linear least squares, residual forecasting, inverse reconstruction. Benchmarks six architectures: SegRNN, LSTM, Seq2Seq LSTM, Attention LSTM, Transformer, and MambaSSM (selective SSM with dual-branch projection, depthwise convolution, SiLU gating). MambaSSM achieved best performance across all tested configurations. (PyTorch)

**[GPT-2 Replication](https://github.com/chengmarc/gpt-replication)**  
From-scratch replication of GPT-2. 162M parameters, 768-dim embeddings, 12 heads, 12 layers. Architecture details: learned positional embeddings, pre-LayerNorm placement, GELU with tanh approximation, causal masking via $-\infty$ pre-softmax. Tokenization via BPE (`tiktoken`, gpt2 vocab). Trained on the Harry Potter corpus with AdamW (lr=4e-4, weight decay=0.1), cross-entropy next-token prediction objective. (PyTorch)

**[Image Classification](https://github.com/chengmarc/image-labelling)**  
ConvNet on MNIST/EMNIST; ResNet-34 and ResNet-101 on CIFAR-10/100. ResNet-34 uses basic blocks (two 3×3 convolutions), ResNet-101 uses bottleneck blocks (1×1 → 3×3 → 1×1). Core focus: how identity shortcut connections and network depth interact across datasets of varying difficulty. (PyTorch)

### Quantitative & Data

**[Quant Analysis Tools](https://github.com/chengmarc/quant-analysis)**  
Five modules, each self-contained:
- `overview/` — market statistics and Monte Carlo simulation across 28,000 CoinGecko coins
- `binance/` — live trading framework via Binance REST API
- `exponential-DCA/` — DCA strategy using volatility-normalized residuals
- `random_walk_interval.py` — BTC price simulation segmented by halving cycles
- `UTXO.ipynb` — on-chain indicator analysis

**[Market Data Crawlers](https://github.com/chengmarc/trade-scan)**  
Three separate scrapers: TradingView ([trade-scan](https://github.com/chengmarc/trade-scan)), CoinGecko ([gecko-scan](https://github.com/chengmarc/gecko-scan)), CoinMarketCap ([cmcs](https://github.com/chengmarc/cmcs)). Built to feed the quant work above.

**[ECR-20 Memecoin](https://github.com/chengmarc/ECR-20-memecoin)**  
ERC-20 implementation in Solidity.
