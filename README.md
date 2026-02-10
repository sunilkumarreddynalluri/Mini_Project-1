# Mini_Project-1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>House Price Prediction Project</title>
    <style>
        body{
            font-family: Arial, Helvetica, sans-serif;
            line-height: 1.6;
            margin: 40px;
            background-color: #ffffff;
            color: #000000;
        }
        h1, h2, h3 {
            color: #2c3e50;
        }
        h1 {
            text-align: center;
        }
        ul {
            margin-left: 20px;
        }
        pre {
            background: #f4f4f4;
            padding: 10px;
            overflow-x: auto;
        }
        hr {
            margin: 30px 0;
        }
        code {
            background: #f4f4f4;
            padding: 2px 6px;
            border-radius: 4px;
        }
    </style>
</head>
<body>

<h1>House Price Prediction Project</h1>

<hr>

<h2>Table of Contents</h2>
<ul>
    <li>Acknowledgements</li>
    <li>Project Overview</li>
    <li>Dataset Description</li>
    <li>Project Structure</li>
    <li>Technology Stack</li>
    <li>Implementation Steps</li>
    <li>Code Explanation</li>
    <li>Model Development</li>
    <li>Deployment Process</li>
    <li>Results and Output</li>
    <li>Challenges and Solutions</li>
    <li>Future Enhancements</li>
    <li>Conclusion</li>
    <li>References</li>
</ul>

<hr>

<h2>1. Acknowledgements</h2>

<h3>Dataset Source</h3>
<ul>
    <li><b>Dataset Name:</b> House Sales in King County, USA</li>
    <li><b>Source:</b> Kaggle – House Data Dataset</li>
    <li><b>Contributor:</b> Shreya Chaudhary</li>
</ul>

<h3>Tools and Libraries</h3>
<ul>
    <li>Flask</li>
    <li>Scikit-learn</li>
    <li>NumPy</li>
    <li>Pandas</li>
    <li>Pickle</li>
    <li>HTML / CSS</li>
    <li>Render</li>
    <li>Git & GitHub</li>
</ul>

<hr>

<h2>2. Project Overview</h2>

<p><b>Objective:</b> Develop a machine learning web application that predicts house prices based on various features such as location, size, condition, and temporal factors.</p>

<h3>Key Features</h3>
<ul>
    <li>User-friendly interface</li>
    <li>Real-time predictions</li>
    <li>17 input parameters</li>
    <li>Online deployment</li>
</ul>

<hr>

<h2>3. Dataset Description</h2>

<ul>
    <li><b>Total Records:</b> 21,613</li>
    <li><b>Features:</b> 18 columns</li>
    <li><b>Location:</b> King County, Washington, USA</li>
    <li><b>Time Period:</b> May 2014 – May 2015</li>
</ul>

<hr>

<h2>4. Project Structure</h2>
<pre>
House-Price-Prediction/
├── app.py
├── requirements.txt
├── Procfile
├── MINI_PROJECT.pkl
├── templates/
└── static/
</pre>

<hr>

<h2>5. Technology Stack</h2>

<h3>Backend</h3>
<ul>
    <li>Python</li>
    <li>Flask</li>
    <li>Scikit-learn</li>
    <li>Pandas</li>
    <li>NumPy</li>
</ul>

<h3>Frontend</h3>
<ul>
    <li>HTML5</li>
    <li>CSS3</li>
</ul>

<hr>

<h2>6. Implementation Steps</h2>

<h3>Environment Setup</h3>
<pre>
python -m venv venv
venv\Scripts\activate
pip install flask numpy pandas scikit-learn gunicorn
</pre>

<h3>Model Training</h3>
<ul>
    <li>EDA and preprocessing</li>
    <li>Train-test split</li>
    <li>Custom Linear Regression</li>
    <li>Model saved using Pickle</li>
</ul>

<hr>

<h2>7. Code Explanation</h2>

<p>Custom Linear Regression implemented using NumPy and SVD without sklearn regression.</p>

<ul>
    <li>Date feature extraction</li>
    <li>Manual label encoding</li>
    <li>Matrix-based coefficient calculation</li>
    <li>RMSE and R² evaluation</li>
</ul>

<hr>

<h2>8. Model Development</h2>

<ul>
    <li>Model: Linear Regression</li>
    <li>Simple and interpretable</li>
    <li>Efficient for continuous targets</li>
</ul>

<hr>

<h2>9. Deployment Process</h2>

<ul>
    <li>GitHub repository</li>
    <li>Render Web Service</li>
    <li>Gunicorn server</li>
</ul>

<hr>

<h2>10. Results and Output</h2>

<pre>
Estimated House Price: 7.68820929
</pre>

<ul>
    <li>Response time: &lt; 2 seconds</li>
    <li>24/7 availability</li>
</ul>

<hr>

<h2>11. Challenges and Solutions</h2>

<ul>
    <li>Manual categorical encoding</li>
    <li>Model persistence using Pickle</li>
    <li>Deployment dependency fixes</li>
</ul>

<hr>

<h2>12. Future Enhancements</h2>

<ul>
    <li>Advanced regression models</li>
    <li>Data visualization</li>
    <li>Mobile application</li>
    <li>Docker deployment</li>
</ul>

<hr>

<h2>13. Conclusion</h2>

<p>End-to-end machine learning project demonstrating full-stack ML deployment.</p>

<hr>

<h2>14. References</h2>

<ul>
    <li>Flask Documentation</li>
    <li>Scikit-learn Documentation</li>
    <li>Render Documentation</li>
    <li>Kaggle Dataset</li>
</ul>

<hr>

<p><b>Project By:</b> N. Sunil Kumar Reddy</p>
<p><b>Last Updated:</b> 10-02-2026</p>
<p><b>Live Application:</b> https://mini-project-1-2-i11k.onrender.com</p>
<p><b>GitHub Repository:</b> https://github.com/sunilkumarreddynalluri/Mini_Project-1.git</p>

</body>
</html>
