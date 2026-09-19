# Marc Cheng (Zhongmang Cheng)

## Selected Work

### [AlphaVerify — Trading-Signal Validation Framework](https://github.com/doubletrends/alpha-verify) ⠀<img alt="Finance" src="https://img.shields.io/badge/Finance-20397E?style=flat-square" align="absmiddle">⠀<img alt="Machine Learning" src="https://img.shields.io/badge/Machine_Learning-7E6A99?style=flat-square" align="absmiddle">
Checks whether trading signals actually work. It measures how often price moves ±X% within N days under each indicator condition, then compares that against 1,000 simulated random markets. On NASDAQ, 25 of 552 conditions passed. Pure chance would give you 27.6.

### [Minecraft CityGen — Customizable AI City Generator](https://github.com/chengmarc/minecraft-citygen) ⠀<img alt="Software" src="https://img.shields.io/badge/Software-5A6B7A?style=flat-square" align="absmiddle">
Turns your own Minecraft builds into a whole city. You mark buildings in-game with a few special blocks, the app lays out roads and places buildings from a seed, then writes the city back into a playable world. Windows app with an installer.

### [WeChat Skill — Agentic AI Plugin](https://github.com/chengmarc/wechat-to-ai) ⠀<img alt="AI Agents" src="https://img.shields.io/badge/AI_Agents-2E7D6B?style=flat-square" align="absmiddle">⠀<img alt="Data Engineering" src="https://img.shields.io/badge/Data_Engineering-C49A3D?style=flat-square" align="absmiddle">
A Claude Code plugin that exports your WeChat history for AI to read. It reads from the local databases on your own machine and turns private and group chats into plain text an LLM can work with. Nothing leaves your computer.

### [Mamba State-Space Forecaster](https://github.com/doubletrends/state-space-mamba) ⠀<img alt="Machine Learning" src="https://img.shields.io/badge/Machine_Learning-7E6A99?style=flat-square" align="absmiddle">⠀<img alt="Finance" src="https://img.shields.io/badge/Finance-20397E?style=flat-square" align="absmiddle">
Mamba written from scratch in PyTorch, without the mamba-ssm library, and used to forecast Bitcoin. Compared against LSTM, SegRNN and Transformer models with walk-forward testing, so no model ever sees future data.

### [PaySim Fraud Detection Data Warehouse](https://github.com/chengmarc/paysim-dw) ⠀<img alt="Data Engineering" src="https://img.shields.io/badge/Data_Engineering-C49A3D?style=flat-square" align="absmiddle">⠀<img alt="Finance" src="https://img.shields.io/badge/Finance-20397E?style=flat-square" align="absmiddle">
A fraud-analytics data warehouse on Hadoop, Hive and PySpark. It loads 6.36M transactions through three layers (raw, cleaned, reporting) and produces fraud rates by transaction type and a list of high-risk accounts.

### [GPT-2 from Scratch](https://github.com/chengmarc/GPT-replication) ⠀<img alt="Machine Learning" src="https://img.shields.io/badge/Machine_Learning-7E6A99?style=flat-square" align="absmiddle">
GPT-2 (162M parameters) written from scratch in PyTorch. Each part is its own module: tokenizer, attention, layer norm, feed-forward, training loop. Trained on the Harry Potter books.

## Technical Stack

<table>
<tr><td>Machine Learning</td><td>

[![Python](https://img.shields.io/badge/Python-46637F?logo=python&logoColor=white)](https://www.python.org/) 
[![PyTorch](https://img.shields.io/badge/PyTorch-46637F?logo=pytorch&logoColor=white)](https://pytorch.org/) 
[![scikit-learn](https://img.shields.io/badge/scikit--learn-46637F?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/) 
[![TensorFlow](https://img.shields.io/badge/TensorFlow-46637F?logo=tensorflow&logoColor=white)](https://www.tensorflow.org/) 
[![CUDA](https://img.shields.io/badge/CUDA-46637F?logo=nvidia&logoColor=white)](https://developer.nvidia.com/cuda-toolkit)

</td></tr>
<tr><td>Data Science</td><td>

[![R](https://img.shields.io/badge/R-46637F?logo=r&logoColor=white)](https://www.r-project.org/) 
[![Jupyter](https://img.shields.io/badge/Jupyter-46637F?logo=jupyter&logoColor=white)](https://jupyter.org/) 
[![SciPy](https://img.shields.io/badge/SciPy-46637F?logo=scipy&logoColor=white)](https://scipy.org/)
[![NumPy](https://img.shields.io/badge/NumPy-46637F?logo=numpy&logoColor=white)](https://numpy.org/) 
[![Pandas](https://img.shields.io/badge/Pandas-46637F?logo=pandas&logoColor=white)](https://pandas.pydata.org/)

</td></tr>
<tr><td>Big Data</td><td>

[![Apache Hadoop](https://img.shields.io/badge/Hadoop-46637F?logo=apachehadoop&logoColor=white)](https://hadoop.apache.org/) 
[![Apache Hive](https://img.shields.io/badge/Hive-46637F?logo=apachehive&logoColor=white)](https://hive.apache.org/) 
[![PySpark](https://img.shields.io/badge/PySpark-46637F?logo=apachespark&logoColor=white)](https://spark.apache.org/docs/latest/api/python/)

</td></tr>
<tr><td>Client-side</td><td>

[![JavaScript](https://img.shields.io/badge/JavaScript-46637F?logo=javascript&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) 
[![Node.js](https://img.shields.io/badge/Node.js-46637F?logo=node.js&logoColor=white)](https://nodejs.org/) 
[![HTML5](https://img.shields.io/badge/HTML5-46637F?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML) 
[![CSS3](https://img.shields.io/badge/CSS3-46637F?logo=css&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS) 
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-46637F?logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)

</td></tr>
<tr><td>Server-side</td><td>

[![TypeScript](https://img.shields.io/badge/TypeScript-46637F?logo=typescript&logoColor=white)](https://www.typescriptlang.org/) 
[![SQLite](https://img.shields.io/badge/SQLite-46637F?logo=sqlite&logoColor=white)](https://www.sqlite.org/) 
[![MySQL](https://img.shields.io/badge/MySQL-46637F?logo=mysql&logoColor=white)](https://www.mysql.com/) 
[![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-46637F?logo=cloudflareworkers&logoColor=white)](https://workers.cloudflare.com/)

</td></tr>
<tr><td>Package Management</td><td>

[![pip](https://img.shields.io/badge/pip-46637F?logo=pypi&logoColor=white)](https://pip.pypa.io/) 
[![conda](https://img.shields.io/badge/conda-46637F?logo=anaconda&logoColor=white)](https://docs.conda.io/) 
[![nvm](https://img.shields.io/badge/nvm-46637F?logo=nvm&logoColor=white)](https://github.com/nvm-sh/nvm) 
[![npm](https://img.shields.io/badge/npm-46637F?logo=npm&logoColor=white)](https://www.npmjs.com/)

</td></tr>
<tr><td>CLI & Markups</td><td>

[![Bash](https://img.shields.io/badge/Bash-46637F?logo=gnu-bash&logoColor=white)](https://www.gnu.org/software/bash/) 
[![Git](https://img.shields.io/badge/Git-46637F?logo=git&logoColor=white)](https://git-scm.com/) 
[![LaTeX](https://img.shields.io/badge/LaTeX-46637F?logo=latex&logoColor=white)](https://www.latex-project.org/) 
[![Markdown](https://img.shields.io/badge/Markdown-46637F?logo=markdown&logoColor=white)](https://www.markdownguide.org/)

</td></tr>
</table>

**Favorite Editors:** Notepad++, VS Code