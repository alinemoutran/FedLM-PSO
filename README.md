#  FedLM-PSO: Federated Learning MLP using Particle Swarm Optimization and Levenberg Marquardt algorithm
This paper proposes a hybrid protocol FedLM-PSO that combines Particle Swarm Optimization (PSO) and Levenberg Marquardt (LM) to train MLP models in an Federated Learning environment to find the near-optimal configurations for FL.<br><br>
The experiments demonstrated that our proposed FedLM-PSO outperformed the most famous Federated Averaging algorithm FedAvg, achieving an accuracy of 96%. Moreover, it showed an improvement in decreasing error by approximately 75%. <br><br>

<img src='./doc/imgs/Framework Architecture- showing the weight update process of FedLM-PSO.png' title='Schematic diagram of the proposed FedLM-PSO
model' >
<center>Schematic diagram of the proposed FedLM-PSO model</center>

# Requirements
Install all the packages from requirments.txt
<ul>
<li>NumPy
<li>Pandas
<li>scikit-learn
<li>MLPRegressor
</ul>
You will also need to have software installed to run and execute a Pycharm IDE.

# Data

These data were collected and disseminated according to this publication: https://www.nature.com/articles/s41597-020-00582-3

# Running the experiments
The baseline experiment trains the model in the conventional way.

To run the baseline experiment on FedLM-PSO using CPU:<br>
<pre><b> &nbsp; python ./FedLM_PSO.py </b> </pre>

# Citation
If you find our work useful in your research, please cite:
Aline Abboud, Mohamed-el-Amine Brahmia, Rocks Mazraani, Abdelhafid Abouaissa and Ahmad Shahin, <b>"A Hybrid Aggregation Approach for Federated Learning to Improve Energy Consumption in Smart Buildings"</b>, 2023.
