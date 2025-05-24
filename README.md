<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Machine Learning & Data Science Notebooks</title>
    <style>
      /* --- Base layout --- */
      * {
        box-sizing: border-box;
      }
      body {
        margin: 0;
        padding: 2rem;
        font-family: Arial, Helvetica, sans-serif;
        background: #f5f7fa;
        color: #333;
      }
      h1 {
        text-align: center;
        margin-bottom: 2.5rem;
        font-size: 2rem;
      }

      /* --- Grid of cards --- */
      .container {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
        gap: 1.5rem;
        max-width: 1200px;
        margin: 0 auto;
      }
      .card {
        background: #fff;
        border-radius: 12px;
        padding: 1.5rem;
        box-shadow: 0 2px 6px rgba(0, 0, 0, 0.08);
        transition: transform 0.2s ease-in-out, box-shadow 0.2s ease-in-out;
      }
      .card:hover {
        transform: translateY(-6px);
        box-shadow: 0 6px 16px rgba(0, 0, 0, 0.12);
      }
      .card h2 {
        margin: 0 0 0.5rem;
        font-size: 1.1rem;
        color: #0066cc;
        word-break: break-all; /* handles long filenames */
      }
      .card p {
        margin: 0;
        line-height: 1.45;
        font-size: 0.95rem;
      }
    </style>
  </head>
  <body>
    <h1>Machine Learning & Data Science Notebooks</h1>
    <div class="container">
      <div class="card">
        <h2>Detecting_Diabetes.ipynb</h2>
        <p>
          Builds a machine‑learning model that predicts diabetes likelihood from
          clinical metrics such as blood pressure, insulin levels, and BMI.
        </p>
      </div>
      <div class="card">
        <h2>Matplotlib_Practice.ipynb</h2>
        <p>
          Hands‑on exploration of data‑visualization techniques in Matplotlib,
          covering a variety of plot types, styling tricks, and layout
          strategies for compelling visual storytelling.
        </p>
      </div>
      <div class="card">
        <h2>Q_Learning_Multi_Armed_Bandit_Problem.ipynb</h2>
        <p>
          Demonstrates reinforcement learning by implementing Q‑Learning to
          tackle the Multi‑Armed Bandit problem, balancing exploration vs.
          exploitation to maximise cumulative reward.
        </p>
      </div>
      <div class="card">
        <h2>Supervised_Learning.ipynb</h2>
        <p>
          Survey of core supervised‑learning algorithms—linear regression,
          decision trees, support‑vector machines—and their application to both
          classification and regression tasks across multiple datasets.
        </p>
      </div>
      <div class="card">
        <h2>Wine_Quality_Test.ipynb</h2>
        <p>
          Trains predictive models that estimate wine quality from
          physicochemical attributes such as acidity, residual sugar, and pH.
        </p>
      </div>
      <div class="card">
        <h2>SatelliteImagery</h2>
        <p>
          Uses convolutional neural networks to classify satellite images into
          land‑cover categories, showcasing end‑to‑end computer‑vision
          workflow.
        </p>
      </div>
      <div class="card">
        <h2>Backpack</h2>
        <p>
          Employs XGBoost to predict backpack prices based on product features
          and market attributes, highlighting gradient‑boosting performance on
          tabular data.
        </p>
      </div>
    </div>
  </body>
</html>
