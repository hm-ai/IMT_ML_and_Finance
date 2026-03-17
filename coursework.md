---
layout: full_width
title: Coursework
permalink: /coursework/
---

<header class="site-header">
  <nav class="site-nav">
    <a href="{{ site.baseurl }}/">Home</a>
    <a href="{{ site.baseurl }}/syllabus/">Syllabus</a>
    <a href="{{ site.baseurl }}/programming/">Programming</a>
    <a href="{{ site.baseurl }}/assessments/">Assessments</a>
    <a href="{{ site.baseurl }}/coursework/">Coursework</a>
    <a href="{{ site.baseurl }}/progress/">Progress Tracker</a>
  </nav>
</header>

<article>
  <div class="header-row">
    <div class="header-text">
      <h1>Coursework: Crypto Markets Group Project</h1>
      <p class="subtitle">50% of your final grade</p>
    </div>
  </div>

  <section>
    <h2>Overview</h2>
    <p>The coursework is a group project where you will apply machine learning techniques learned throughout the course to predict cryptocurrency price movements. You will engineer features, build models, and evaluate their performance on real crypto data.</p>
    <p>This is a <strong>group project</strong> completed in teams of <strong>3-4 students</strong>.</p>

    <div class="info-box">
      <p><strong>Note:</strong> You can achieve a high mark even if your strategy doesn't beat a buy-and-hold approach. The focus is on your methodology, not just performance.</p>
    </div>
  </section>

  <section>
    <h2>Key Information</h2>
    <table>
      <tbody>
        <tr>
          <td><strong>Project Notebook</strong></td>
          <td><a href="https://colab.research.google.com/drive/1f3bHbF3XDHPvvqiLJTMETKfwICYk9efV?usp=sharing" class="btn btn-colab">Open in Colab</a></td>
        </tr>
        <tr>
          <td><strong>Deadline</strong></td>
          <td>Coming soon</td>
        </tr>
        <tr>
          <td><strong>Team Size</strong></td>
          <td>3-4 students</td>
        </tr>
        <tr>
          <td><strong>Weight</strong></td>
          <td>50% of final grade</td>
        </tr>
      </tbody>
    </table>
  </section>

  <section>
    <h2>Project Sections</h2>

    <div class="assessment-card">
      <h3>1. Feature Engineering (20 marks)</h3>
      <p>Develop a set of features that might help predict cryptocurrency price movements. Consider:</p>
      <ul>
        <li>Technical indicators (momentum, volatility, trend)</li>
        <li>Relative strength indicators</li>
        <li>Moving averages and their crossovers</li>
        <li>Serial correlation features</li>
        <li>Time-lagged features</li>
        <li>Regimes from a Latent Variable Model</li>
      </ul>
    </div>

    <div class="assessment-card">
      <h3>2. Creating Labels (20 marks)</h3>
      <p>Trend scanning labeling identifies upward and downward trends in price data by defining an observation window, computing t-values for linear regressions over this window, and selecting the most statistically significant trend.</p>
      <p>For implementation guidance and examples, refer to Programming Sessions 1 and 5.</p>
    </div>

    <div class="assessment-card">
      <h3>3. Model Development (30 marks)</h3>
      <p>For predicting cryptocurrency price movements, consider these modeling approaches:</p>
      <ul>
        <li><strong>Model Selection:</strong>
          <ul>
            <li>Tree-based Models (Random Forests, XGBoost)</li>
            <li>Neural Networks (vanilla or Recurrent Neural Networks)</li>
          </ul>
        </li>
        <li><strong>Training Strategies:</strong>
          <ul>
            <li>Rolling Window</li>
            <li>Expanding Window</li>
            <li>One-time prediction</li>
          </ul>
        </li>
        <li><strong>Hyperparameter Optimization:</strong> Optimize your model parameters for best performance</li>
      </ul>
      <p>Refer to Programming Sessions 4-7 for implementation guidance.</p>
    </div>

    <div class="assessment-card">
      <h3>4. Feature Importance Analysis (10 marks)</h3>
      <p>For analyzing which features are most important for your cryptocurrency prediction model:</p>
      <ul>
        <li>Mean Decrease Impurity (MDI)</li>
        <li>Permutation Feature Importance (PFI)</li>
        <li>Perform analysis on a cluster level</li>
      </ul>
      <p>Refer to Programming Session 2 for implementation guidance.</p>
    </div>

    <div class="assessment-card">
      <h3>5. Model Evaluation (20 marks)</h3>
      <p>Evaluate your model's performance on the test period using classification metrics (accuracy, precision, recall, F1-score) and confusion matrix analysis.</p>
    </div>

    <div class="assessment-card" style="border-left: 4px solid #C4A35A;">
      <h3>Optional: Backtesting Performance (10 bonus marks)</h3>
      <p>Implement a backtesting framework to evaluate your strategy with these metrics:</p>
      <ul>
        <li>CAGR (Compound Annual Growth Rate)</li>
        <li>Volatility</li>
        <li>Sharpe Ratio</li>
        <li>Sortino Ratio</li>
        <li>Maximum Drawdown</li>
        <li>Average Holding Period</li>
        <li>Comparison with Buy and Hold Strategy</li>
      </ul>
    </div>
  </section>

  <section>
    <h2>Assessment Criteria</h2>
    <p>You will be judged primarily on:</p>
    <ol>
      <li>Quality and creativity of your feature engineering</li>
      <li>Appropriateness of your model selection and training approach</li>
      <li>Robustness of your implementation</li>
      <li>Critical analysis of your results</li>
      <li>Code quality and documentation</li>
    </ol>
  </section>

  <section>
    <h2>Final Submission Requirements</h2>
    <p>Your final code submission should include all five sections clearly implemented:</p>
    <ol>
      <li><strong>Feature Engineering:</strong> Code that generates relevant technical and statistical features from the OHLCV data</li>
      <li><strong>Creating Labels:</strong> Implementation of the trend scanning labeling approach</li>
      <li><strong>Model Development:</strong> Your chosen model implementation with appropriate training strategy</li>
      <li><strong>Feature Importance Analysis:</strong> Code to analyze and visualize which features are most important</li>
      <li><strong>Model Evaluation:</strong> Implementation of performance metrics and visualization tools</li>
    </ol>
    <p>Each section should be well-documented with comments explaining your approach and the rationale behind your design choices. Make sure your code is clean, efficient, and follows good programming practices.</p>
  </section>

  <section>
    <h2>Submission Rules</h2>
    <ul>
      <li><strong>One submission per team:</strong> Each team should submit a single notebook</li>
      <li><strong>Documentation:</strong> Code must be well-documented and reproducible</li>
      <li><strong>Academic integrity:</strong> All work must be original. Plagiarism will result in zero marks and potential disciplinary action.</li>
    </ul>
  </section>
</article>
