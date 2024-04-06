# Data Analysis on TWitter (Formerly X) We_Rate_Dogs Account

**Overview**

This repository contains a data analysis project focused on gathering, assessing, cleaning, storing, wrangling, analysing and visualising a dataset. The dataset is the tweet archive of X (formerly Twitter) user @dog_rates, also known as WeRateDogs. WeRateDogs is an X account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. which indicates how high the dog is rated. WeRateDogs has over 4 million followers and has received international media coverage.

**Dataset**

Three datasets would be worked on in this project

**Datasets and Files**

_twitter-archive-enhanced-2.csv_: This contains a fitered down list of tweets from the WeRateDogs X archive that have ratings. Some tweets do not have ratings. The file would still need to be checked to ensure that it was cleaned properly.

_Data via X API_: This is data gathered through the use of the X API. Access to this API is requested from X. You could use the directly downloaded file (twitter-archive-enhanced-2.csv) or you could use this API and download the required file from X directly after you have requested and been granted access by X.

_image-predictions.tsv_: This is a file created from a neural link (see the AIPND-Pre-Trained repository) that can classify dog breeds.

_wrangle_act.ipynb_: Jupyter notebook that contains the Python doe for data analysis

_wrangle_report.pdf_: file that contains a report on how the data was wrangled and analysed

_act_report.pdf_: file that contains a report on the visualisations and insights gotten from the data analysis exercise.

_tweet-json.txt_: file that contains all the saved tweets from the X API returned as JSON objects.

**Dependencies**

The analysis is conducted using Python programming language and several libraries including:

_Pandas_: For data manipulation and analysis.

_Matplotlib_: For data visualization.

_Seaborn_: For statistical data visualization.

_NumPy_: For numerical computing.

_Tweepy_: For accessing X API

_Requests_: For sending HTTP requests

_Json_: For working with JSON data

_timeit_: For determining the time for the code execution

_os_: For creating and accessing files

**Usage**

To run the analysis on your local machine, follow these steps:

Clone this repository to your local machine using the following command:

bash

Copy code
git clone https://github.com/Olatokunbo360/We_Rate_Dogs.git

Navigate to the project directory:

bash

Copy code
cd We_Rate_Dogs

Install the required dependencies.
You can use the following command to install dependencies using pip:

Copy code
pip install -r requirements.txt

Once the dependencies are installed, you can open the Jupyter Notebook wrangle_act.ipynb to view the analysis and execute the code cells.

Follow the instructions provided in the notebook to explore the dataset, analyze trends, and visualize insights related to the dataset.

**Contributing**

Contributions to this project are welcome. If you have suggestions for improvements or new analyses, please feel free to open an issue or submit a pull request.


**License**
This project is licensed under the MIT License - see the LICENSE file for details.


By [Yusuf Sanni] - [yusufsanni2003@yahoo.co.uk]
















