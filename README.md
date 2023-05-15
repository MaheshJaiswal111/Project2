# Word Frequency Analyzer

This is a React.js frontend application that fetches the contents of a text file, analyzes the word frequencies, and displays a histogram of the 20 most occurring words. It also provides an option to export the histogram data as a CSV file.

## Components

The application consists of the following components:

### WordFrequencyAnalyzer

This component handles the main functionality of fetching data, analyzing word frequencies, rendering the histogram, and exporting the data. It uses the following libraries:

- React: A JavaScript library for building user interfaces.
- axios: A promise-based HTTP client for making API requests.
- react-chartjs-2: A React wrapper for Chart.js, which provides interactive charts and graphs.
- chart.js: A JavaScript library for creating charts and graphs.

### App

This is the main component that renders the `WordFrequencyAnalyzer` component and provides the basic structure of the application.

## Installation

To run the application locally, follow these steps:

1. Make sure you have Node.js installed on your machine.
2. Clone this repository or download the code.
3. Open the project directory in your terminal.
4. Run the following command to install the required dependencies:

   ```bash
   npm install
