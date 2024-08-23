<body>
    <div class="container">
        <h1>Visual Question Answering (VQA) System</h1>
        <h2>Overview</h2>
        <p>This project involves the development of a state-of-the-art Visual Question Answering (VQA) system. The system interprets and responds to questions based on the content of images, integrating both textual and visual data using advanced deep learning models.</p>
        <h2>Features</h2>
        <ul>
            <li><strong>Visual Feature Extraction:</strong> Utilizes ResNet-50 to extract high-quality visual features from images.</li>
            <li><strong>Textual Feature Processing:</strong> Employs BERT for understanding the context and semantics of the question, with LSTM handling the sequential nature of text.</li>
            <li><strong>Multi-Modal Integration:</strong> Combines textual and visual data using a compact bi-linear pooling architecture that efficiently merges high-dimensional data.</li>
            <li><strong>Attention Mechanisms:</strong> Enhances the model’s focus on the most relevant parts of the image and question, leading to more accurate answers.</li>
        </ul>
        <h2>Tools Used</h2>
        <ul>
            <li><strong>Gradio:</strong> Used to create a user-friendly interface for interacting with the VQA system. Gradio allows users to upload images and ask questions, making the system accessible </li>
            <li><strong>Transformers:</strong> Leveraged the Hugging Face Transformers library to utilize state-of-the-art models like BERT for natural language processing tasks. The library provided pre-trained models and utilities that were integral to the project's success.</li>
        </ul>
        <h2>Technologies</h2>
        <ul>
            <li>Programming Language: Python</li>
            <li>Libraries: TensorFlow, Keras, NumPy, Pandas</li>
            <li>Deep Learning Models: BERT, LSTM, ResNet-50</li>
            <li>Interface : Gradio,Flask</li>
            <li>Architecture: Multi-modal Compact Bi-linear Pooling</li>
        </ul>
        <h2>Installation</h2>
        <p>To set up the project locally, follow these steps:</p>
        <h3>Prerequisites</h3>
        <ul>
            <li>Python 3.8+</li>
            <li>pip (Python package installer)</li>
            <li>Virtual environment (recommended)</li>
        </ul>
        <h3>Clone the Repository</h3>
        <pre><code>git clone https://github.com/tarak0506/vqa-system.git
cd vqa-system</code></pre>
        <h3>Create and Activate a Virtual Environment</h3>
        <pre><code>python -m venv venv
source venv\Scripts\activate</code></pre>
        <h3>Install Dependencies</h3>
        <pre><code>pip install -r requirements.txt</code></pre>
        <h2>Usage</h2>
        <p>To run the system locally:</p>
        <pre><code>python app.py</code></pre>
        <p>Then open your browser and go to <a href="http://127.0.0.1:5000" target="_blank">http://127.0.0.1:5000</a>.</p>
        <h3>Interacting with the System</h3>
        <p>Use the Gradio interface to upload images and ask questions. The system will analyze the image and the question to provide a relevant answer.</p>
    </div>
</body>


https://github.com/user-attachments/assets/b9a24483-be74-4fe4-b12e-0240922f0c20
