# betting-risk-management
This Python project simulates portfolio evolution in sports betting using advanced financial modeling concepts, including:

🔍 Key Components
	1.	Leverage Cycle Simulation
Models the amplification and collapse of capital under leverage, with and without risk controls (VaR-based caps).
	2.	Uncertainty-Adjusted Kelly Criterion
Evaluates bankroll growth under probability misestimation using full, adjusted, and half Kelly strategies.
	3.	Event Correlation Stress Test
Simulates correlated losses due to simultaneous underdog wins across various bet types (favorites, balanced, underdog).
	4.	CVaR (Conditional Value-at-Risk) Protection Analysis
Assesses long-term bankroll outcomes and tail-risk exposure across multiple simulated betting strategies.
	5.	Comprehensive Visualization Suite
A multi-panel matplotlib dashboard visualizes key outcomes, including leverage trajectories, bankroll evolution, stress test losses, CVaR vs final capital, and leverage vs capital mapping.

🛠️ Libraries Used
	•	numpy, matplotlib, seaborn for computation and visualization
	•	scipy.stats for density estimation (KDE)

📈 Output
	•	A high-resolution multi-panel plot (sports_betting_simulations.png)
	•	Detailed performance metrics printed to the console (max drawdown, leverage, Kelly performance, CVaR safety zones)
