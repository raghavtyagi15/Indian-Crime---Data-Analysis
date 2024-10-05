
</head>
<body>

<header>
    <h1>Indian Crime Data Analysis</h1>
</header>

<section>
    <h2>Project Overview</h2>
    <p>This project involves <strong>Exploratory Data Analysis (EDA)</strong> on Indian crime reports from 2019 to 2024. The goal is to uncover key insights, patterns, and trends related to crime incidents across various cities, age groups, genders, and time periods. The analysis provides a deeper understanding of the types of crimes, their distribution, and trends over time.</p>
</section>

<section>
    <h2>Dataset Description</h2>
    <p>The dataset contains crime reports from different cities in India and includes the following attributes:</p>
    <ul>
        <li><strong>Crime Type</strong></li>
        <li><strong>Victim’s Age</strong></li>
        <li><strong>Gender of the Victim</strong></li>
        <li><strong>City</strong></li>
        <li><strong>Crime Year</strong></li>
        <li><strong>Time of Crime</strong></li>
        <li><strong>Case Status</strong> (open/closed)</li>
    </ul>
</section>

<section>
    <h2>Key Insights from EDA</h2>
    <ul>
        <li>Crime reports have remained stable, except for 2024, which has fewer reports due to incomplete data.</li>
        <li>Delhi has the highest crime rate, while cities like Lucknow report fewer cases.</li>
        <li>The <strong>10-20 age group</strong> is the most affected, showing higher vulnerability among younger populations.</li>
        <li>Females are more frequently victims across most cities and crime types, highlighting social risks.</li>
        <li>Knives are the most commonly used weapon in violent crimes.</li>
        <li>50% of the cases are still pending resolution.</li>
    </ul>
</section>

<section>
    <h2>Project Structure</h2>
    <p>The project is organized as follows:</p>
    <pre>
Indian-Crime-Data-Analysis/
│
├── Indian Crime Data Analysis.ipynb   # Jupyter notebook with the EDA process
├── data/                              # Directory containing the cleaned dataset
├── images/                            # Directory containing generated charts
└── README.html                        # This readme file as HTML
    </pre>
</section>

<section>
    <h2>Setup Instructions</h2>

    <h3>Prerequisites</h3>
    <p>You will need the following tools to run this project:</p>
    <ul>
        <li>Python 3.7+</li>
        <li>Jupyter Notebook or Jupyter Lab</li>
        <li>The following Python libraries:
            <ul>
                <li>pandas</li>
                <li>numpy</li>
                <li>matplotlib</li>
                <li>seaborn</li>
                <li>plotly</li>
            </ul>
        </li>
    </ul>

    <h3>Installation</h3>
    <ol>
        <li>Clone the repository:
            <pre><code>git clone https://github.com/yourusername/Indian-Crime-Data-Analysis.git</code></pre>
        </li>
        <li>Navigate to the project folder:
            <pre><code>cd Indian-Crime-Data-Analysis</code></pre>
        </li>
        <li>(Optional) Create and activate a virtual environment:
            <pre><code>python -m venv venv<br>
source venv/bin/activate  # Windows: venv\Scripts\activate</code></pre>
        </li>
        <li>Install the required libraries:
            <pre><code>pip install -r requirements.txt</code></pre>
        </li>
        <li>Start Jupyter Notebook:
            <pre><code>jupyter notebook</code></pre>
        </li>
        <li>Open the <code>Indian Crime Data Analysis.ipynb</code> notebook and run all the cells to view the analysis.</li>
    </ol>
</section>

<section>
    <h2>Future Work</h2>
    <ul>
        <li>Conduct multivariate analysis to investigate more complex relationships between variables.</li>
        <li>Develop machine learning models to predict future crime trends.</li>
        <li>Create interactive dashboards using Plotly or Tableau.</li>
    </ul>
</section>

<section>
    <h2>Contributing</h2>
    <p>Feel free to fork the repository and submit pull requests with improvements or additional analysis techniques.</p>
</section>

<section>
    <h2>License</h2>
    <p>This project is licensed under the MIT License - see the LICENSE file for details.</p>
</section>

</body>
</html>

