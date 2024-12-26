# Climbing Analytics Project

This project analyzes your Mountain Project climbing data to provide insights about your climbing history, progression, and trends. Additionally, it provides a "processed_climbing_data.csv" that incldues all data cleansing and feature engineering. So that you may import this data into other notebooks or BI tools such as Tableau for further personal climbing data exploration.

## Prerequisites

- A Google account with access to Google Drive and Google Colab
- Your Mountain Project "Ticks" export file (CSV format)

## Setup Instructions

1. Export your Mountain Project ticks:
   - Go to [Mountain Project](https://www.mountainproject.com)
   - Navigate to your profile
   - Click on "Export Ticks" to download your `Ticks.csv` file

2. Set up the project directory:
   - Create a new folder in your Google Drive
   - Upload the following files to this folder:
     - Your downloaded `Ticks.csv` file
     - The `climbing_ticks.ipynb` notebook file

## Running the Analysis

1. Open Google Colab:
   - Go to [Google Colab](https://colab.research.google.com)
   - Click on "File" → "Open notebook"
   - Select the "Google Drive" tab
   - Navigate to your project folder
   - Open `climbing_ticks.ipynb`

2. Running the notebook:
   - Click on "Runtime" → "Run all" to execute all cells
   - The notebook will process your climbing data and generate various visualizations
   - A processed data file will be created in your project directory for future use

## Visualizations Included

- Interactive climbing grade pyramid showing sends by style
- Heatmap of climbing volume by month and year
- Geographic distribution of climbs (US states and countries)
- Most visited crags and areas
- Grade distribution analysis
- Send style analysis by grade

## Sample Statistics

The analysis generates comprehensive climbing metrics including:

### Overall Metrics
```
Total Climbs: 1,763
Unique Routes: 1,047
Total Pitches: 2,479
Average Stars: 2.53
```

### Style Distribution
```
Sport Climbs: 1,366
Trad Climbs: 404
Boulder Problems: 5
Multipitch Climbs: 213
```

### Performance Metrics
```
Overall Success Rate: 65.5%
First Try Success Rate: 43.5%
Sport Success Rate: 66.0%
Trad Success Rate: 63.1%
```

### Grade Distribution
```
5.9 and under: 586 climbs
5.10: 558 climbs
5.11: 350 climbs
5.12: 253 climbs
5.13: 11 climbs
```

### Location Stats
```
Countries Visited: 3
Unique Areas: 72
Unique Crags: 341
Climbing Days: 524
Weekend Ratio: 44.9%
```

*Note: These are sample statistics. Your actual numbers will vary based on your climbing data.*

## Troubleshooting

- If you encounter permission errors, make sure you've authorized Google Colab to access your Google Drive
- Verify that your `Ticks.csv` file is in the same directory as the notebook
- Check that your Mountain Project export is recent and properly formatted
- Install missing libraries via !apt-get install -y 'name of library' in jupyter notebook cell

## Contributing

Feel free to fork this project and submit pull requests with improvements or additional features. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
