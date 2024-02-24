# DNA Sequence Analysis Tool

This Python script provides a comprehensive set of tools for analyzing DNA sequences. It allows users to compare sequences, calculate matches with shifts, and find maximum contiguous chains. The script is designed to handle both console input and file input for sequence analysis tasks.

## Features

- **Sequence Comparison:**
  - Calculate the number of matching positions between two DNA sequences.
  - Visualize matches and mismatches between sequences.

- **Sequence Comparison with Shifts:**
  - Calculate the number of matching positions between sequences with a specified shift value.
  - Find the best number of matches with shifts by iterating over shift values.
  - Visualize matches and mismatches for each shift value.

- **Maximum Contiguous Chain:**
  - Calculate the maximum contiguous chain between sequences for a given shift value.
  - Find the maximum contiguous chain by iterating over shift values.
  - Visualize the maximum contiguous chain for each shift value.

- **File Handling:**
  - Read DNA sequences from a file.
  - Handle file not found errors.

- **User Interaction:**
  - Interactive menu for performing sequence analysis tasks.
  - Input validation and error handling for user interactions.

## Usage

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your_username/dna-sequence-analysis.git
   ```

2. **Navigate to the Project Directory:**
   ```bash
   cd dna-sequence-analysis
   ```

3. **Run the Script:**
   ```bash
   python sequence_analysis.py
   ```

4. **Follow the On-Screen Instructions to Perform Analysis:**
   - Choose options from the menu to perform sequence analysis tasks.
   - Enter DNA sequences when prompted or provide a file containing sequences.

## Dependencies

- Python 3.x
- Colorama (for console output coloring)

Install Colorama using pip:
```bash
pip install colorama
```

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvement, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
