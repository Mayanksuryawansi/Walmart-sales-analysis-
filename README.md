# Walmart-sales-analysis
<h1>📊 Walmart End-to-End Data Engineering + Analytics Project</h1>
<h3>Python + MySQL/PostgreSQL | Kaggle API | Data Cleaning | SQL Business Insights</h3>

<p>
This project demonstrates a complete <b>end-to-end Data Engineering & Analytics workflow</b> using Walmart sales data.  
Raw data is extracted from Kaggle, cleaned with Python, loaded into SQL databases, and analyzed using advanced SQL queries to solve real business problems.
</p>

<hr>

<h2>📌 Project Architecture</h2>

<pre>
Kaggle → Python (Pandas) → Clean & Transform → Load to MySQL/PostgreSQL → SQL Analysis → Business Insights
</pre>

<p>(Pipeline diagram can be placed here)</p>

<hr>

<h2>📂 Project Components</h2>

<table>
  <tr><th>Component</th><th>Description</th></tr>
  <tr><td><b>Dataset</b></td><td>Walmart Sales Data (from Kaggle)</td></tr>
  <tr><td><b>Python Notebook</b></td><td>Data cleaning, processing, loading to SQL DB</td></tr>
  <tr><td><b>SQL Scripts</b></td><td>Business queries for analytics</td></tr>
  <tr><td><b>Business Problem PDF</b></td><td>Detailed problem statements & objectives</td></tr>
  <tr><td><b>Requirements File</b></td><td>Python dependencies</td></tr>
</table>

<hr>

<h2>🗂️ Dataset Information</h2>
<p>Dataset fields include:</p>

<ul>
  <li>Invoice details</li>
  <li>Date & time</li>
  <li>Branch & city</li>
  <li>Product category</li>
  <li>Unit price, quantity</li>
  <li>Payment method</li>
  <li>Ratings</li>
  <li>Total amount & profit margin</li>
</ul>

<p><b>Files Used:</b><br>
✔ Walmart.csv (raw)<br>
✔ walmart_clean_data.csv (cleaned)
</p>

<hr>

<h2>🐍 Technologies & Libraries Used</h2>

<h3>Python</h3>
<ul>
  <li>Pandas</li>
  <li>SQLAlchemy</li>
  <li>PyMySQL</li>
  <li>Psycopg2</li>
  <li>IPython</li>
</ul>

<h3>Databases</h3>
<ul>
  <li>MySQL</li>
  <li>PostgreSQL</li>
</ul>

<h3>Tools</h3>
<ul>
  <li>Kaggle API</li>
  <li>Jupyter Notebook</li>
</ul>

<hr>

<h2>⚙️ Project Steps</h2>

<h3>1️⃣ Extract Data (Kaggle API)</h3>
<p>Dataset downloaded automatically using the Kaggle API.</p>

<h3>2️⃣ Process & Clean Data (Python)</h3>
<p>Cleaning and transformations done inside <b>project.ipynb</b>:</p>
<ul>
  <li>Fixing NULL values</li>
  <li>Cleaning date & time columns</li>
  <li>Standardizing categories</li>
  <li>Creating new features</li>
</ul>

<h3>3️⃣ Load Cleaned Data into SQL Databases</h3>
<ul>
  <li>Create MySQL/PostgreSQL tables</li>
  <li>Load using SQLAlchemy</li>
  <li>Validate row counts & types</li>
</ul>

<h3>4️⃣ Analyze Using SQL</h3>
<p>All advanced SQL queries included in <b>MySQL Queries.sql</b>.</p>

<hr>

<h2>🧠 Business Problems Solved</h2>

<ol>
  <li><b>Analyze Payment Methods</b> — transactions & items sold by type</li>
  <li><b>Highest-Rated Category per Branch</b> — using window functions</li>
  <li><b>Busiest Day per Branch</b> — using date functions</li>
  <li><b>Total Quantity Sold by Payment Method</b></li>
  <li><b>Category Ratings by City</b> (min, max, avg)</li>
  <li><b>Total Profit by Category</b> — calculated using formula</li>
  <li><b>Most Common Payment Method per Branch</b></li>
  <li><b>Sales Shift Analysis</b> — Morning / Afternoon / Evening</li>
  <li><b>Revenue Decline YoY</b> — branches with highest drops</li>
</ol>

<hr>

<h2>📜 SQL File</h2>
<p>Full analysis queries are available in <b>MySQL Queries.sql</b>.</p>

<hr>

<h2>📦 Installation & Setup</h2>

<h3>Clone Repository</h3>
<pre>
git clone &lt;your-repo-url&gt;
cd walmart-sales-analysis
</pre>

<h3>Install Python Dependencies</h3>
<pre>
pip install -r requirements.txt
</pre>

<hr>

<h2>🚀 How to Run the Project</h2>

<h3>1. Download Dataset</h3>
<p>Using Kaggle API</p>

<h3>2. Run Python Notebook</h3>
<pre>
jupyter notebook project.ipynb
</pre>

<h3>3. Load Data to MySQL/PostgreSQL</h3>
<p>Executed through SQLAlchemy inside the notebook.</p>

<h3>4. Run SQL Queries</h3>
<p>Use MySQL Workbench / pgAdmin.</p>

<hr>

<h2>📈 Final Output</h2>

<ul>
  <li>Clean dataset stored in SQL database</li>
  <li>Insights derived from advanced SQL queries</li>
  <li>ETL pipeline from extraction → transformation → loading → analysis</li>
  <li>Business problem document + SQL reports</li>
</ul>

<hr>

<h2>⭐ Highlights</h2>

<ul>
  <li>Fully automated ETL pipeline</li>
  <li>Real-world business analysis</li>
  <li>Easy to understand for beginners</li>
  <li>Industry-level SQL usage</li>
</ul>
