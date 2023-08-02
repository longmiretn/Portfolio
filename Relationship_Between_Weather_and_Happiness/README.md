# Data Cleaning, Merging, and Visualization Project

This repository contains a data cleaning, merging, and visualization project that aims to analyze and visualize data from multiple sources. The project involves cleaning data from CSV files, merging it into a SQLite database, and creating visualizations to gain insights.

## Project Structure

The repository is organized as follows:

- `Cleaning_API_Source.ipynb`: Jupyter notebook containing data cleaning code for the API data source.
- `Cleaning_Flat_File.ipynb`: Jupyter notebook containing data cleaning code for the flat file data source.
- `Cleaning_Website_Source.ipynb`: Jupyter notebook containing data cleaning code for the website data source.
- `Merging_and_Visualizing_Data.ipynb`: Jupyter notebook containing data merging and visualization code.
- `flat_file_data.csv`: CSV file containing the original flat file data.
- `website_data.csv`: CSV file containing data from the website source.
- `api_data.csv`: CSV file containing data from the API source.
- `final_project.sqlite`: SQLite database file storing the cleaned and merged data.
- `README.md`: This file, providing an overview of the project and repository.

## Getting Started

To run the data cleaning, merging, and visualization code, make sure you have Python and the required libraries installed. The necessary packages can be installed using the following command:

pip install pandas sqlite3 matplotlib numpy geopandas shapely


Once the packages are installed, you can run the Jupyter notebooks (`Cleaning_API_Source.ipynb`, `Cleaning_Flat_File.ipynb`, and `Cleaning_Website_Source.ipynb`) to clean the data from each source. After cleaning, run the `Merging_and_Visualizing_Data.ipynb` notebook to merge the cleaned data into the SQLite database and create visualizations.

## Data Cleaning and Merging

The data cleaning process involves loading the CSV files for each source and cleaning them using Python's Pandas library. The cleaned data is then stored in separate tables in the `final_project.sqlite` database. The merging process combines the cleaned data from different sources into a single table named `FINAL_TABLE`.

## Data Visualization

After data merging, visualizations are created using Matplotlib and Geopandas. The visualizations include scatter plots, bar plots, and world maps with marked locations to explore relationships and insights in the data.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to modify and use the code and data for your own projects or research.

## Acknowledgments

- The project code was created as part of the Data Cleaning, Merging, and Visualization project milestone.
- The data used in this project is for illustrative purposes only and does not represent real-world data.

