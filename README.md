---


---

<h1 id="yolo-from-scratch">YOLO from Scratch</h1>
<h2 id="overview">Overview</h2>
<p><img src="https://github.com/Satzil/Yolo_from_scratch/blob/main/Architecture.png?raw=true" alt="enter image description here"></p>
<p>This repository contains an implementation of YOLO (You Only Look Once) object detection algorithm from scratch using Python and PyTorch. The project aims to provide a comprehensive understanding of how YOLO architecture works by building the model and training it on the Pascal VOC dataset.</p>
<h2 id="aim">Aim</h2>
<p>The aim of this project is to provide a hands-on experience and understanding of how YOLO architecture works. By building the model from scratch and training it on the Pascal VOC dataset, users can gain insights into the inner workings of YOLO and its components, including the network architecture, loss calculation, and training process.</p>
<h2 id="project-structure">Project Structure</h2>
<p>The project is organized into the following main components:</p>
<ol>
<li>
<p><strong>Data Collection:</strong> Data for training the YOLO model is downloaded using a Bash script (<code>get_data.sh</code>). This script fetches the required images and annotations from the Pascal VOC dataset.</p>
</li>
<li>
<p><strong>Data Preparation:</strong> The <code>generate_csv.py</code> script processes the downloaded data and generates CSV files containing image paths and corresponding bounding box annotations. This step prepares the data for training the YOLO model.</p>
</li>
<li>
<p><strong>Model Architecture:</strong> The YOLO model architecture is implemented in the <code>model.py</code> file. This file contains the definition of the YOLO neural network, including the backbone network, detection head, and loss calculation.</p>
</li>
<li>
<p><strong>Training:</strong> The <code>train.py</code> script is used to train the YOLO model on the prepared dataset. It loads the data from the generated CSV files, initializes the model, and performs training using gradient descent optimization.</p>
</li>
<li>
<p><strong>Loss Calculation:</strong> The <code>loss.py</code> file defines the custom loss function used for training the YOLO model. It computes the loss between predicted bounding boxes and ground truth annotations.</p>
</li>
</ol>
<h2 id="references">References</h2>
<p><a href="https://github.com/Satzil/Transformer_from_scratch#references"></a></p>
<ul>
<li><a href="https://arxiv.org/pdf/1506.02640v5">You Only Look Once: Unified, Real-Time Object Detection</a>  paper.</li>
</ul>

