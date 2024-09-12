
# Synthesis Project: Data Visualization Techniques

This repository contains the synthesis project that explores various data visualization techniques and their appropriate use cases. The project aims to provide guidance on selecting the most suitable plots based on data type, size, and the specific analytical goals.

## 📋 Project Overview

### Objective
The primary objective of this project is to synthesize various data visualization methods into a cohesive guide that helps in selecting the right plot for different types of data and analysis requirements. 

### Methodology
The project uses a decision flowchart to guide users through the process of choosing an appropriate visualization technique. The decision points include:
- **Data Type**: Whether the data is categorical or continuous.
- **Data Size**: Whether the dataset is large or small.
- **Analysis Goal**: Whether the aim is to show relationships, distributions, or trends.

### Visualization Techniques
Based on the decision points, the following visualization techniques are recommended:
- **Hexbin Plot**: For large continuous datasets with overlap.
- **Jitter Plot**: For smaller datasets to display distribution.
- **Violin Plot / Box Plot**: To show the distribution of data.
- **Bee Swarm Plot**: For small datasets with detailed distribution.
- **Density Plot**: To visualize the density of continuous data.
- **Dot Plot**: For normally distributed data.
- **Scatter Plot**: To show correlations or trends between variables.

## 📂 Repository Structure

```
/data/          # Contains raw and processed datasets
/scripts/       # Scripts for data processing and visualization
/flowchart/     # Decision flowchart for plot selection
README.md       # Project overview and details (this file)
```

## 🛠️ Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/synthesis-project.git
   ```
2. **Install the required packages:**
   Ensure you have the necessary libraries installed for visualization:
   ```bash
   pip install matplotlib seaborn pandas
   ```
3. **Run the scripts:**
   Navigate to the `/scripts/` directory and execute the scripts to generate visualizations based on the provided datasets.

## 🤝 Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue to discuss improvements or suggestions.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

For questions or collaborations, please contact [Dhanyapriya Somasundaram](mailto:dhanyapriyas@arizona.edu).
