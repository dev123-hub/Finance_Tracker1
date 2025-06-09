# Personal Finance Tracker 💰

A beginner-friendly Python project for learning programming fundamentals while building a practical personal finance management tool.

## 📖 About This Project

This is a hands-on learning project designed for complete Python beginners. By building a personal finance tracker from scratch, you'll learn essential programming concepts while creating something genuinely useful for managing your money.

## 🎯 Learning Goals

By completing this project, you'll master:

### Basic Python Concepts
- Variables and data types
- Functions and parameters
- Control flow (if/else, loops)
- Lists and dictionaries
- File input/output

### Intermediate Concepts
- Classes and objects
- Error handling
- Working with dates
- Data validation
- File management

### Advanced Topics
- Data analysis and visualization
- Regular expressions
- Decorators
- Context managers
- Testing your code

## 🚀 Features

### Current Features
- [ ] Track income and expenses
- [ ] Categorize transactions
- [ ] View transaction history
- [ ] Calculate totals and balances
- [ ] Save data to files

### Planned Features
- [ ] Generate spending reports
- [ ] Budget tracking
- [ ] Data visualization with charts
- [ ] Export to CSV/Excel
- [ ] Monthly/yearly summaries

## 📁 Project Structure

```
personal-finance-tracker/
│
├── README.md                   # This file
├── requirements.txt            # Python dependencies
├── .gitignore                 # Git ignore file
│
├── src/                       # Source code
│   ├── __init__.py
│   ├── finance_tracker.py     # Main tracker class
│   ├── transaction.py         # Transaction handling
│   ├── data_manager.py        # File operations
│   └── utils.py              # Helper functions
│
├── data/                      # Data storage
│   ├── transactions.json     # Transaction data
│   └── backups/              # Data backups
│
├── tests/                     # Unit tests
│   ├── __init__.py
│   ├── test_transaction.py
│   └── test_tracker.py
│
└── docs/                      # Documentation
    ├── learning_notes.md      # Your learning journey
    └── api_reference.md       # Code documentation
```

## 🛠️ Installation

### Prerequisites
- Python 3.8 or higher
- Basic text editor or IDE (VS Code, PyCharm, etc.)

### Setup
1. Clone or download this repository
```bash
git clone https://github.com/yourusername/personal-finance-tracker.git
cd personal-finance-tracker
```

2. Create a virtual environment (optional but recommended)
```bash
python -m venv finance_env
source finance_env/bin/activate  # On Windows: finance_env\Scripts\activate
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

## 🎮 Usage

### Quick Start
```bash
python src/finance_tracker.py
```

### Example Usage
```python
from src.finance_tracker import FinanceTracker

# Create a new tracker
tracker = FinanceTracker()

# Add an expense
tracker.add_expense(
    amount=4.50,
    description="Morning coffee",
    category="food"
)

# Add income
tracker.add_income(
    amount=500.00,
    description="Freelance payment",
    category="freelance"
)

# View your balance
print(f"Current balance: ${tracker.get_balance()}")
```

## 📚 Learning Path

### Phase 1: Basics (Beginner)
1. **Variables and Data Types** - Store transaction information
2. **Functions** - Create reusable code for calculations
3. **Lists** - Store multiple transactions
4. **Loops** - Process multiple transactions
5. **Conditionals** - Validate user input

### Phase 2: Structure (Intermediate)
1. **Classes** - Organize code with Transaction and Tracker classes
2. **File I/O** - Save and load data from files
3. **Error Handling** - Handle invalid input gracefully
4. **Modules** - Split code into multiple files

### Phase 3: Advanced Features
1. **Data Analysis** - Generate reports and statistics
2. **Visualization** - Create charts and graphs
3. **Testing** - Write unit tests for your code
4. **Packaging** - Make your code shareable

## 🧪 Testing

Run the test suite:
```bash
python -m pytest tests/
```

Run specific tests:
```bash
python -m pytest tests/test_transaction.py -v
```

## 📊 Sample Data

The project includes sample transaction data to help you get started:
- Monthly income: $3,000
- Various expense categories
- 30 days of sample transactions

## 🤝 Contributing

This is a learning project! Here's how you can contribute:

1. **Share your improvements** - Found a better way to do something?
2. **Report bugs** - Learning from mistakes is valuable
3. **Suggest features** - What would make this more useful?
4. **Share your learning journey** - Help other beginners

## 📝 Learning Notes

Document your learning journey in `docs/learning_notes.md`:
- Concepts that were challenging
- "Aha!" moments
- Code snippets you're proud of
- Questions for further exploration

## 📖 Resources

### Python Learning Resources
- [Python.org Official Tutorial](https://docs.python.org/3/tutorial/)
- [Automate the Boring Stuff](https://automatetheboringstuff.com/)
- [Python for Everybody](https://www.py4e.com/)

### Programming Concepts
- [Object-Oriented Programming](https://realpython.com/python3-object-oriented-programming/)
- [File Handling in Python](https://realpython.com/python-file-handling/)
- [Error Handling](https://realpython.com/python-exceptions/)

## 🏆 Milestones

Track your progress:

- [ ] **Hello World** - First program runs successfully
- [ ] **Basic Calculator** - Can add/subtract transactions
- [ ] **File Saver** - Can save data to file
- [ ] **Class Master** - Created Transaction and Tracker classes
- [ ] **Error Handler** - Program handles invalid input
- [ ] **Data Analyst** - Can generate spending reports
- [ ] **Visualizer** - Created charts and graphs
- [ ] **Tester** - Wrote unit tests
- [ ] **Packager** - Code is well-organized and documented

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**[Your Name]** - *Learning Python through practical projects*

- GitHub: [@yourusername](https://github.com/yourusername)
- Email: your.email@example.com

## 🙏 Acknowledgments

- Thanks to the Python community for excellent learning resources
- Inspired by real-world personal finance management needs
- Built as part of a structured learning journey

---

## 📈 Progress Tracking

### Current Status: Getting Started
- [x] Project setup and README creation
- [ ] Basic Python syntax and variables
- [ ] First transaction tracking
- [ ] File operations
- [ ] Classes and objects
- [ ] Advanced features

### Next Steps
1. Set up your development environment
2. Create your first Python file
3. Start with basic variables and print statements
4. Begin tracking your first transaction

**Remember: Every expert was once a beginner. Take it one step at a time!** 🚀
