# Hi, I'm Tehilla 👋

**Applied Machine Learning | Model Reliability & Evaluation | Computer Vision**

Give me a messy dataset, a model behaving strangely, or a result that does not quite add up, and I will keep digging until I understand why.

I am particularly interested in ML work where the useful questions start underneath the headline metric: how models fail, whether confidence is actually meaningful, what an experiment is really measuring, and why two apparently similar results can behave completely differently underneath.

I am based in Israel and have an MSc in Computer Science.

### 🔬 Featured project

#### Vision Confidence Reliability Framework

I built a Python/PyTorch framework for investigating how image classifiers behave as input quality deteriorates.

It applies controlled blur, Gaussian noise and low-light degradation, saves prediction-level evidence, and makes it possible to analyse accuracy, calibration, failure detection and confidence behaviour together rather than stopping at a single performance score.

The project includes:

* GTSRBCNN, ResNet18 and MobileNetV2 evaluation
* ImageNet-pretrained ResNet18 and MobileNetV2 with full fine-tuning
* controlled GTSRB and MNIST experiments
* track-aware GTSRB splitting to prevent validation leakage
* prediction-level failure and confidence analysis
* ECE, confidence-accuracy gap, HCER and failure-detection diagnostics
* paired bootstrap analysis for key findings
* trust-rule attribution and ablation
* reproducible experiment configuration and evidence tracking
* 197 automated tests across the evaluation pipeline and safeguards

Some of the most useful findings came from results that looked ordinary at first. Two models reached almost identical accuracy under severe noise while failing on different images and showing very different confidence behaviour. In another case, overall confidence fell while many predictions the model was already getting wrong became more confident.

That kind of problem is exactly what I like working on: something looks simple from the top, then gets much more interesting once you start pulling it apart.

### 💻 Other work

**Online Shopper Purchase Prediction**
Built and evaluated purchase-intent models using scikit-learn, including feature engineering, imbalanced classification and comparison of SVM, Random Forest, HistGradientBoosting and MLP models.

**REST API Development**
Built an authenticated REST API using Node.js and MongoDB, containerised with Docker and deployed to Google Cloud.

**Data & Software Development**
Experience across relational databases and SQL, Java and object-oriented development, network/PCAP analysis, Git/GitHub, automated testing and collaborative Agile projects.

### 🛠️ Tools I work with

**ML & Data:** Python, PyTorch, scikit-learn, pandas, NumPy, torchvision
**Software & Data:** Java, JavaScript, SQL, REST APIs
**Tools:** Git/GitHub, pytest, Docker, Jupyter

### 👋 What I'm looking for

I am looking for an ML or ML-adjacent engineering role where I can get deep into difficult technical problems, work out what is actually going wrong, and help turn that understanding into something useful and reliable.

I am especially interested in computer vision, model evaluation, robotics and autonomous systems, and data-heavy scientific applications.

📍 Israel
