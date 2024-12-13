# Statistical Calculator

## Features

- **Real-time Calculations**: Instantly updates results as you input numbers
- **Multiple Statistical Measures**:
  - Mean (average)
  - Median (middle value)
  - Mode (most frequent value)
  - Range (difference between highest and lowest values)
  - Variance (measure of spread)
  - Standard Deviation (square root of variance)
- **Flexible Input**: Accepts comma-separated numbers with optional spaces
- **Input Validation**: Automatically filters out invalid entries

## Usage

1. Input your numbers in the text field, separated by commas (e.g., "1, 2, 3, 4, 5")
2. The calculator will automatically process your input and display:
   - Mean
   - Median
   - Mode (displays "null" if all values occur equally often)
   - Range
   - Variance
   - Standard Deviation

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/statistical-calculator.git
```

2. Open `index.html` in your web browser

## Code Structure

- `index.html`: Main HTML file with the user interface
- `script.js`: Contains all the statistical calculation functions:
  - `getMean()`: Calculates arithmetic mean
  - `getMedian()`: Finds the middle value
  - `getMode()`: Determines most frequent value(s)
  - `getRange()`: Calculates the spread of values
  - `getVariance()`: Measures data dispersion
  - `getStandardDeviation()`: Calculates standard deviation

## Technical Details

The calculator utilizes modern JavaScript features and methods including:
- Advanced array methods (`reduce`, `map`, `filter`, `forEach`)
- Modern array sorting with `toSorted()`
- Regular expressions for input parsing
- ES6+ syntax features
- DOM manipulation for real-time updates


## Contributing

Feel free to submit issues and enhancement requests!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## Author

Kash Pandey

## Acknowledgments

- frontend code by freeCodeCamp.

---

# statistical-calculator-using-advanced-array-methods
