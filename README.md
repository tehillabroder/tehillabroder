# Hi, I'm Tehilla 👋

**Applied Machine Learning | Model Reliability & Evaluation | Computer Vision**

Give me a messy dataset, a model behaving strangely, or a result that does not quite add up, and I will keep digging until I understand why.

I am particularly interested in applied ML problems where the interesting work starts underneath the headline metric: model behaviour, failure analysis, reliability, experimental design and figuring out why something is behaving the way it is.

I am completing an MSc in Computer Science and am based in Israel.

### 🔬 Current work

#### Vision Confidence Reliability Framework

My MSc project developed a Python/PyTorch framework for investigating how image-classifier confidence behaves as input quality deteriorates.

The framework applies controlled blur, Gaussian noise and low-light degradation, then preserves prediction-level evidence so that accuracy, calibration, failure detection and confidence behaviour can be analysed together.

The project includes:

* GTSRBCNN, ResNet18 and MobileNetV2 evaluation
* ImageNet-pretrained ResNet18 and MobileNetV2 with full fine-tuning
* controlled GTSRB and MNIST experiments
* track-aware GTSRB splitting to prevent validation leakage
* prediction-level failure and confidence analysis
* ECE, confidence-accuracy gap, HCER and failure-detection diagnostics
* paired bootstrap analysis for key findings
* trust-rule attribution and ablation
* reproducible configuration, checkpoint and experiment metadata
* 197 automated tests covering the research pipeline and safeguards

One of the findings I found most interesting was how much aggregate metrics could hide. Two models could reach almost identical accuracy while failing on different images and showing very different confidence behaviour. In another case, overall confidence fell while many predictions the model was already getting wrong became more confident.

That kind of result is exactly the work I enjoy: not stopping at the metric, but working out what is actually happening underneath it.

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

I am looking for an ML or ML-adjacent engineering role where I can bring curiosity and persistence, get deep into difficult technical problems, and help turn them into something that actually works.

I am especially interested in computer vision, model evaluation, robotics and autonomous systems, and data-heavy scientific applications.

📍 Israel
