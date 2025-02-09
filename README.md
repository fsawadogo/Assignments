# Python Data Analysis Assignment

## Overview
This assignment consists of three main questions focusing on fundamental concepts in Python programming, probability theory, and statistical analysis. The assignment is designed to test understanding of:
- Basic Python programming concepts
- Mathematical functions implementation
- Statistical sampling and analysis
- Linear regression modeling
- Data visualization

## Requirements

### Python Version
- Python 3.6 or higher

### Required Libraries
```bash
pip install numpy
pip install matplotlib
pip install seaborn
pip install scikit-learn
pip install ipython
```

## Question Breakdown

### Question 1: Basic Python Functions (1 point)
- Implementation of Greatest Common Divisor (GCD) function
- Prime number generator function
- Error handling for invalid inputs
- Colored output formatting

### Question 2: Statistical Analysis (6 points)
- Exponential distribution analysis (λ = 1.2)
- Sample generation and mean estimation
- Visualization of sample means
- Statistical inference
- Confidence interval analysis

### Question 3: Linear Regression (8 points)
- Data simulation with controlled noise
- Linear regression model fitting
- Visualization of relationships
- Parameter estimation
- Impact of noise analysis

## File Structure
```
assignment/
│
├── Assignment01.ipynb    # Main Jupyter notebook
├── README.md            # This file
└── requirements.txt     # Python dependencies
```

## Setup Instructions

1. Clone or download the assignment repository
2. Create a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```
4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
5. Open `Assignment01.ipynb`

## Running the Code

Each question is contained in separate cells within the Jupyter notebook. To run the code:

1. Start from the top of the notebook
2. Run each cell in sequence using Shift+Enter
3. Make sure to run the initial setup cell that contains the color formatting code

## Notes

- Set random seeds as specified in the questions for reproducibility
- Pay attention to the color formatting for error messages
- Follow the specified parameter values exactly
- Comment your code appropriately
- Include explanations in markdown cells where required

## Grading Breakdown
- Question 1: 1 point
  - GCD function (0.5 points)
  - Prime numbers function (0.5 points)
- Question 2: 6 points
  - Population mean calculation (0.5 points)
  - Sample generation (1 point)
  - Mean estimation (1.5 points)
  - Visualization (1 point)
  - Statistical inference (2 points)
- Question 3: 8 points
  - Data generation (1 point)
  - Scatterplot creation (0.5 points)
  - Model fitting (2 points)
  - Visualization (2 points)
  - Noise analysis (2.5 points)

## Tips
- Test your functions with various inputs
- Pay attention to error handling
- Use appropriate visualization techniques
- Provide clear explanations for your analysis
- Follow Python best practices for code style
- Make sure your visualizations are clear and properly labeled

## Submission Guidelines
- Submit the completed Jupyter notebook
- Include all generated plots and outputs
- Make sure all cells have been executed in order
- Include any additional files used in your analysis
- Follow the provided naming conventions

## Academic Integrity
- All work must be your own
- Cite any external sources used
- Do not share solutions with others
- Follow your institution's academic integrity guidelines

## Support
If you encounter any issues or have questions:
- Consult the course materials
- Contact the teaching assistants
- Utilize office hours
- Post in the course forum (if available)