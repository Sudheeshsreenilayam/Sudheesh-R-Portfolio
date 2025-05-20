<h2>📁 Featured Projects</h2>

<!-- Filter Buttons -->
<div style="margin-bottom: 20px;">
  <button onclick="filterProjects('all')" style="margin-right: 10px;">All</button>
  <button onclick="filterProjects('r')">R</button>
  <button onclick="filterProjects('sql')">SQL</button>
  <button onclick="filterProjects('tableau')">Tableau</button>
</div>

<!-- Project Cards -->
<div id="project-container">

  <!-- R Project -->
  <div class="project r" style="margin-bottom: 20px;">
    <h3>📘 Linear Regression with Multicollinearity (R)</h3>
    <p>Simulation-based analysis demonstrating how multicollinearity affects regression coefficients and interpretation.</p>
    <a href="https://sudheeshsreenilayam.github.io/dissect-with-sudheesh/R-Projects/Linear-Regression-Multicollinearity-R/linear_regression_analysis.html">View Report</a>
  </div>

  <div class="project r" style="margin-bottom: 20px;">
    <h3>🌲 Tree-Based Sales Prediction (R)</h3>
    <p>Used decision trees, pruning, bagging, and random forests to predict sales from product and customer data.</p>
    <a href="https://sudheeshsreenilayam.github.io/dissect-with-sudheesh/R-Projects/Tree-Based-Sales-Prediction-R/tree_model_sales.html">View Report</a>
  </div>

  <div class="project r" style="margin-bottom: 20px;">
    <h3>🏙️ Boston Crime Regression (R)</h3>
    <p>Explored how Boston crime rates correlate with 13 socioeconomic variables using linear regression and visualizations.</p>
    <a href="https://sudheeshsreenilayam.github.io/dissect-with-sudheesh/R-Projects/Boston-Crime-Regression-R/boston_crime_regression.html">View Report</a>
  </div>

  <!-- SQL Project -->
  <div class="project sql" style="margin-bottom: 20px; display:none;">
    <h3>🧠 Superstore SQL Insights (SQL)</h3>
    <p>Coming soon: Business-focused SQL queries and KPIs from the Global Superstore dataset.</p>
    <a href="#">Coming Soon</a>
  </div>

  <!-- Tableau Project -->
  <div class="project tableau" style="margin-bottom: 20px; display:none;">
    <h3>📊 Sales Dashboard (Tableau)</h3>
    <p>Interactive Tableau dashboard visualizing regional sales performance and customer segments. Launching soon.</p>
    <a href="#">Coming Soon</a>
  </div>

</div>

<!-- Filtering Script -->
<script>
  function filterProjects(category) {
    const projects = document.querySelectorAll('.project');
    projects.forEach(project => {
      if (category === 'all' || project.classList.contains(category)) {
        project.style.display = 'block';
      } else {
        project.style.display = 'none';
      }
    });
  }
</script>
