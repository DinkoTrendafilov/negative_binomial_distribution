Negative Binomial Distribution Visualizer

📊 A Python tool to model and visualize the Negative Binomial Distribution
Key Features

    Calculates probabilities for "k failures before r successes" scenarios

    User inputs:

        p: Probability of success per trial (0 < p < 1)

        r: Target number of successes

        max_failures: Upper limit for failures to simulate

    Implements the formula:
    P(k) = C(k+r-1, k) * pʳ * (1-p)ᵏ

    Generates a professional chart with:

        Probabilities labeled on bars (as %)

        Mean (red dashed line) and standard deviation range (orange zone)

Why It Matters

🔹 Real-world applications: Modeling scenarios like "sales attempts until 3 conversions" or "manufacturing defects before 5 good units"
🔹 Clean, annotated visuals (Matplotlib)
🔹 Statistical insights: Mean and variance derived from theory
Usage

    Run the script:
    bash

python negative_binomial.ipynb

Enter:

    Probability of success (e.g., 0.3 for 30%)

    Target successes (e.g., 3)

    Max failures to consider (e.g., 20)

The chart auto-generates!
