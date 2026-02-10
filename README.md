# Mini Project

<h1>House Price Prediction Project</h1>

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
<p><b>Dataset Name:</b> House Sales in King County, USA</p>
<p><b>Source:</b> Kaggle – House Data dataset</p>
<p><b>Contributor:</b> Shreya Chaudhary</p>
<p>This dataset contains house sale prices for King County, including Seattle, from May 2014 to May 2015.</p>

<h3>Tools and Libraries</h3>
<ul>
<li>Flask</li>
<li>Scikit-learn</li>
<li>NumPy</li>
<li>Pandas</li>
<li>Pickle</li>
<li>HTML/CSS</li>
<li>Render</li>
<li>Git/GitHub</li>
</ul>

<h3>Special Thanks</h3>
<ul>
<li>Kaggle community</li>
<li>Open-source contributors</li>
<li>Render platform</li>
</ul>

<hr>

<h2>2. Project Overview</h2>

<h3>Objective</h3>
<p>Develop a machine learning web application that predicts house prices based on location, size, condition, and temporal factors.</p>

<h3>Problem Statement</h3>
<ul>
<li>Create a predictive model using historical data</li>
<li>Build an intuitive web interface</li>
<li>Deploy the application publicly</li>
<li>Provide accurate price estimations</li>
</ul>

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
<li>Total Records: 21,613</li>
<li>Features: 18 columns</li>
<li>Time Period: May 2014 – May 2015</li>
<li>Location: King County, Washington, USA</li>
</ul>

<h3>Data Preprocessing</h3>
<ul>
<li>Missing value handling</li>
<li>Date feature extraction</li>
<li>City and country encoding</li>
<li>Feature selection</li>
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
<li>Pickle</li>
</ul>

<h3>Frontend</h3>
<ul>
<li>HTML5</li>
<li>CSS3</li>
</ul>

<h3>Development Tools</h3>
<ul>
<li>PyCharm</li>
<li>Git & GitHub</li>
<li>Jupyter Notebook</li>
</ul>

<h3>Deployment</h3>
<ul>
<li>Render</li>
<li>Pip</li>
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
<li>Linear Regression training</li>
<li>Model saved using pickle</li>
</ul>

<h3>Flask Development</h3>
<ul>
<li>Create app.py</li>
<li>Load trained model</li>
<li>Create prediction routes</li>
</ul>

<h3>Local Testing</h3>
<pre>
python app.py
http://localhost:5000
</pre>

<hr>

<h2>7. Code Explanation</h2>

<p>Custom Linear Regression implemented using NumPy and SVD without sklearn regression.</p>

<h3>Main Steps</h3>
<ul>
<li>Data loading</li>
<li>Date feature engineering</li>
<li>Manual label encoding</li>
<li>Matrix-based coefficient calculation</li>
<li>RMSE and R² evaluation</li>
</ul>

<hr>

<h2>8. Model Development</h2>

<h3>Model Selection</h3>
<p>Linear Regression</p>

<h3>Why Linear Regression?</h3>
<ul>
<li>Simple and interpretable</li>
<li>Low computational cost</li>
<li>Good baseline model</li>
</ul>

<hr>

<h2>9. Deployment Process</h2>

<ul>
<li>Create GitHub repository</li>
<li>Connect repository to Render</li>
<li>Configure build and start commands</li>
<li>Deploy using gunicorn</li>
</ul>

<p><b>Live URL:</b> https://mini-project-1-2-i11k.onrender.com</p>

<hr>

<h2>10. Results and Output</h2>

<h3>Sample Prediction</h3>
<pre>
Estimated House Price: 7.68820929
</pre>

<ul>
<li>Response time: &lt; 2 seconds</li>
<li>Availability: 24/7</li>
</ul>

<hr>

<h2>11. Challenges and Solutions</h2>

<ul>
<li>Categorical feature encoding</li>
<li>Model persistence with pickle</li>
<li>Deployment dependency issues</li>
</ul>

<hr>

<h2>12. Future Enhancements</h2>

<ul>
<li>Advanced ML algorithms</li>
<li>Data visualization</li>
<li>Mobile application</li>
<li>Docker deployment</li>
</ul>

<hr>

<h2>13. Conclusion</h2>

<p>This project demonstrates a complete end-to-end machine learning pipeline from data preprocessing to cloud deployment.</p>

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
<p><b>GitHub Repository:</b> https://github.com/sunilkumarreddynalluri/Mini_Project-1.git</p>

</body>
</html>
