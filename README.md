# Industrial-Control-System-Anomaly-Detection-by-Constrained-Devices
This thesis focuses on anomaly detection in Industrial Control Systems (ICS) and evaluates various techniques, including Autoencoder, OCSVM, PCA, k-NN, and Isolation Forest, to identify the most suitable one for Secu-Box in ICS. Data is generated using the Tennessee Eastman process (TEP) simulator, and attacks are designed to evaluate the effectiveness and efficiency of the detection technique. Performance metrics such as accuracy, precision, recall, F1-score, fpr, and prediction time are calculated to compare the models and select the best one. By detecting anomalies early, the thesis aims to enhance the security and dependability of ICS, protecting critical infrastructure. This research contributes valuable insights to improve anomaly detection techniques in ICS environments, strengthening the detection and protection against cyberattacks on critical infrastructure.

For Autoencoder model was inspired from https://github.com/scy-phy/ICS_Generic_Concealment_Attacks.git

conda create --name py38 python=3.8
conda activate py38
pip install -r requirements.txt
sudo apt install default-jre

For OCSVM, PCA, k-NN, Isolation Forest models was inspired from https://github.com/yzhao062/pyod.git

pip install pyod           
pip install --upgrade pyod  
conda install -c conda-forge pyod
git clone https://github.com/yzhao062/pyod.git
cd pyod
pip install .
