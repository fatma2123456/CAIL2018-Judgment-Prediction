<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CAIL2018-Judgment-Prediction Dataset Documentation</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            margin: 20px;
            color: #333;
        }
        h1, h2, h3 {
            color: #2c3e50;
        }
        h1 {
            text-align: center;
        }
        p {
            font-size: 1.1em;
        }
        ul {
            padding-left: 20px;
        }
        blockquote {
            border-left: 4px solid #3498db;
            padding-left: 15px;
            font-style: italic;
            color: #555;
            margin: 20px 0;
        }
        hr {
            border: none;
            height: 1px;
            background: #ddd;
        }
        .highlight {
            color: #e74c3c;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <h1>✨ CAIL2018-Judgment-Prediction Dataset ✨</h1>

    <h2>🌟 Dataset Summary</h2>
    <p>
        Imagine transforming the legal world with the power of Artificial Intelligence! 
        The <strong>CAIL2018 dataset</strong> aims to do just that. It focuses on advancing 
        <span class="highlight">Legal Judgment Prediction (LJP)</span> by combining cutting-edge NLP techniques with a deep understanding of legal knowledge.
    </p>

    <blockquote>
        "A world where justice is swift, informed, and data-driven is not just a dream—it's a possibility!"
    </blockquote>

    <h3>Challenges</h3>
    <ul>
        <li><strong>Imbalanced Data:</strong> With the top 10 charges covering 79% of cases, there's a steep hill to climb!</li>
        <li><strong>Task Interdependencies:</strong> Navigating the complex relationships between law articles, charges, and prison terms isn't for the faint of heart.</li>
    </ul>

    <h3>Performance</h3>
    <p>Despite these challenges, incredible progress has been made:</p>
    <ul>
        <li>Law Articles Prediction: <strong>90.62%</strong> accuracy</li>
        <li>Charges Prediction: <strong>87.91%</strong> accuracy</li>
        <li>Prison Terms Prediction: <strong>78.22%</strong> accuracy</li>
    </ul>

    <hr>

    <h2>🔍 Key Features</h2>

    <h3>🚀 Large-scale Criminal Dataset</h3>
    <p>
        The dataset is a treasure trove for researchers:
    </p>
    <ul>
        <li><strong>Massive Scale:</strong> 5.7 million criminal documents from China Judgment Online!</li>
        <li><strong>Groundbreaking:</strong> One of the largest publicly available datasets for legal judgment prediction.</li>
    </ul>

    <h3>🛠 Primary Tasks</h3>
    <ul>
        <li><strong>Law Articles:</strong> Predict the legal backbone of a case.</li>
        <li><strong>Charges:</strong> Identify what the defendant is up against.</li>
        <li><strong>Prison Terms:</strong> Determine the sentence based on the facts.</li>
    </ul>

    <h3>🌐 Advanced Techniques</h3>
    <p>
        Leveraging the might of machine learning and deep learning, the project taps into:
    </p>
    <ul>
        <li>Neural models</li>
        <li>Attention mechanisms</li>
        <li>Reinforcement learning</li>
    </ul>

    <hr>

    <h2>📊 Dataset Construction</h2>
    <p>
        Building a robust dataset of this scale is no easy feat. It includes <strong>5,730,302 criminal documents</strong>, collected meticulously from China Judgment Online. 
    </p>

    <h3>Stages</h3>
    <ul>
        <li><strong>First Stage:</strong> Early trials to test the waters with a selected subset of documents.</li>
        <li><strong>Second Stage:</strong> Final evaluations with new documents for an unbiased assessment of model performance.</li>
    </ul>

    <hr>

    <h2>🧠 Approaches to Legal Judgment Prediction</h2>
    <h3>🔷 Approach 1: Deep Learning Text Classification</h3>
    <ul>
        <li><strong>Description:</strong> Directly predicts judgment results from case facts.</li>
        <li><strong>Limitations:</strong> Lacks intermediate reasoning or transparency.</li>
    </ul>

    <h3>🔷 Approach 2: Chain-of-Thought Prompting</h3>
    <ul>
        <li><strong>Description:</strong> Encourages step-by-step reasoning.</li>
        <li><strong>Output:</strong> Predictions are enriched with logical reasoning steps.</li>
    </ul>

    <h3>🔷 Approach 3: Legal Syllogism Prompting</h3>
    <ul>
        <li><strong>Description:</strong> Uses structured, deductive reasoning:
            <ul>
                <li><strong>Law:</strong> Identify relevant rules.</li>
                <li><strong>Fact:</strong> Apply the case facts.</li>
                <li><strong>Judgment:</strong> Reach a transparent conclusion.</li>
            </ul>
        </li>
    </ul>

    <blockquote>
        "The future of legal AI is not just in answers—it's in explanations that everyone can trust!"
    </blockquote>

    <hr>

    <h2>📖 References</h2>
    <ul>
        <li>J. Cui, X. Shen, and S. Wen. "A survey on legal judgment prediction: Datasets, metrics, models, and challenges."</li>
        <li>Devlin, J., Chang, M. W., Lee, K., & Toutanova, K. "BERT: Pre-training of deep bidirectional transformers for language understanding."</li>
        <li>Vaswani, A., et al. "Attention is all you need."</li>
        <li>Cui, J., Shen, X., & Wen, S. "A survey on legal judgment prediction: Datasets, metrics, models, and challenges."</li>
        <li>Liu, P., Zhang, W., Ding, Y., Zhang, X., & Yang, S.-H. "SEMDR: A semantic-aware dual encoder model for legal judgment prediction."</li>
    </ul>

</body>
</html>
