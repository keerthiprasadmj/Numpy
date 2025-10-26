# NumPy Calculator
An interactive Jupyter Notebook calculator that performs arithmetic operations, statistical analysis, and array manipulation using NumPy. This project provides a menu-driven interface for working with 1D NumPy arrays through live code execution.


## ✨ Features


### Module 1: Arithmetic Operations
- **Addition** (`+`): Element-wise addition of two arrays
- **Subtraction** (`-`): Element-wise subtraction between arrays
- **Multiplication** (`*`): Element-wise multiplication of arrays
- **Division** (`/`): Element-wise division operations
- **Exponentiation** (`**`): Raise array elements to powers


### Module 2: Statistical Operations
- **Central Tendency**: `mean()`, `median()`
- **Dispersion Metrics**: `std()` (standard deviation), `var()` (variance)
- **Range Analysis**: `min()`, `max()`
- **Aggregation Functions**: `sum()`, `product()`
- **Array Properties**: `shape`, `size`, `dtype` (data type)


### Module 3: Array Manipulation
- **Reshaping Operations**: `reshape()` - Transform 1D arrays to 2D or 3D with automatic shape validation
- **Sorting**: `sort()` (ascending), reverse sort (descending)
- **Data Extraction**: `unique()` value extraction, get first element, get last element
- **Filtering**: Extract values greater than mean


### Practical Application
- Interactive menu-driven calculator interface
- Flexible array input methods
- Real-time array operations
- Shape validation and suggestions


## 🚀 Getting Started


### Prerequisites


```bash
Python 3.6+
Jupyter Notebook or JupyterLab
NumPy library
```


### Installation


1. Clone the repository:
```bash
git clone https://github.com/keerthiprasadmj/numpy-calculator.git
cd numpy-calculator
```


2. Install dependencies:
```bash
pip install numpy jupyter
```


### Running the Notebook


**Option 1: Jupyter Notebook**
```bash
jupyter notebook numPyCalculator.ipynb
```


**Option 2: JupyterLab**
```bash
jupyter lab numPyCalculator.ipynb
```


**Option 3: Google Colab**
1. Upload the `.ipynb` file to Google Drive
2. Open with Google Colab
3. Run all cells (Runtime → Run all)


**Option 4: VS Code**
1. Install Python and Jupyter extensions
2. Open the `.ipynb` file
3. Select Python kernel and run cells


## 📊 Sample Output


The notebook provides an interactive calculator with multiple operation types:
- **Operation Categories**: Arithmetic, Statistical, Array Manipulation
- **Input Methods**: Manual entry (space-separated) or Random generation


**Example: Statistical Analysis**
```
Choose the type of operation to perform: 2
['mean', 'median', 'std', 'var', 'min', 'max', 'sum', 'product', 'shape', 'size', 'data type']

Choose any operator in statistical operations: mean
Enter the array elements separated by space: 10 20 30 40 50

Result...
30.0
```


**Example: Array Reshaping**
```
Choose any operator in Array manipulation: reshape
Enter the size of the 1D array (number of elements): 12
[15  3 18  7 11  9 14  2 19  5 16  8]

Enter the new shape dimension (2d or 3d): 2d
[(1, 12), (2, 6), (3, 4), (4, 3), (6, 2), (12, 1)]
Enter any one of the possible above shapes: (3,4)

Result calculating...
[[15  3 18  7]
 [11  9 14  2]
 [19  5 16  8]]
```


## 📖 Learning Objectives


After working through this notebook, you will understand:


1. **NumPy Array Fundamentals**
   - Creating arrays from user input and random generation
   - Understanding array properties (shape, size, dtype)
   - Working with 1D arrays


2. **Array Operations**
   - Element-wise arithmetic operations
   - Array size validation for operations
   - Input validation and error handling


3. **Statistical Analysis**
   - Computing descriptive statistics (mean, median, std, var)
   - Aggregation functions (sum, product, min, max)
   - Analyzing array properties


4. **Practical Applications**
   - Interactive calculator interface design
   - Menu-driven program flow
   - Shape transformation and validation
   - Real-time data manipulation


## 🔧 Key NumPy Functions Demonstrated


| Category | Functions |
|----------|-----------|
| Creation | `array()`, `random.randint()` |
| Arithmetic | `+`, `-`, `*`, `/`, `**` (element-wise operations) |
| Statistics | `mean()`, `median()`, `std()`, `var()`, `min()`, `max()`, `sum()`, `product()` |
| Properties | `shape`, `size`, `dtype` |
| Manipulation | `reshape()`, `sort()`, `unique()`, array slicing, boolean indexing |


## 📁 Project Structure


```
numpy-calculator/
│
├── numPyCalculator.ipynb      # Main Jupyter notebook
├── README.md                   # Project documentation
├── requirements.txt            # Python dependencies
└── LICENSE                     # License file
```


## 💡 Use Cases


This calculator can be adapted for:
- Educational tutorials and NumPy workshops
- Quick numerical computations and analysis
- Learning array operations interactively
- Prototyping NumPy-based algorithms
- Understanding statistical functions
- Interview preparation for data science roles


## 🎓 How to Use This Notebook


1. **Sequential Execution**: Run all code cells in order from top to bottom
2. **Launch Calculator**: Execute the final cell to start the interactive interface
3. **Select Operation**: Choose from 4 menu options (Arithmetic, Statistical, Array Manipulation, Exit)
4. **Input Arrays**: Enter manually (space-separated) or generate randomly with custom range
5. **View Results**: See calculated results displayed immediately
6. **Continue Operations**: Perform multiple operations in one session
7. **Exit**: Select option 4 to exit the calculator


## 🤝 Contributing


Contributions are welcome! Feel free to:
- Add data visualizations (matplotlib, seaborn)
- Include more statistical analyses
- Add interactive widgets (ipywidgets)
- Improve documentation and examples
- Report bugs or issues
- Suggest additional NumPy functions to demonstrate


### How to Contribute
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## 📝 License


This project is licensed under the MIT License - see the LICENSE file for details.


## 👨‍💻 Author


Keerthi Prasad M J
- GitHub: [@keerthiprasadmj](https://github.com/keerthiprasadmj)
- LinkedIn: [keerthi-m-j-3a3b7b2a5](https://www.linkedin.com/in/keerthi-m-j-3a3b7b2a5)
- Email: keerthiprasadmj@gmail.com


## 🙏 Acknowledgments


- NumPy documentation and community
- Jupyter Project for the amazing notebook interface
- Educational resources on array programming
- Open source contributors


## 📚 Additional Resources


- [NumPy Official Documentation](https://numpy.org/doc/)
- [Jupyter Notebook Documentation](https://jupyter-notebook.readthedocs.io/)
- [NumPy Tutorial for Beginners](https://numpy.org/doc/stable/user/absolute_beginners.html)
- [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)


## 🐛 Troubleshooting


**Kernel Issues:**
- Restart kernel: `Kernel → Restart & Clear Output`
- Reinstall NumPy: `pip install --upgrade numpy`


**Import Errors:**
- Ensure NumPy is installed: `pip install numpy`
- Check Python version compatibility


**Cell Not Running:**
- Check if another cell is currently executing
- Restart the kernel and run again


---


⭐ **If you find this notebook helpful, please consider giving it a star!**


📧 **Questions or suggestions?** Open an issue or reach out!
