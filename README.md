# drought-fingerprint-plots
This repository contains a Jupyter notebook for generating a graphical depiction of drought intensity at a specified location and date.

## Key Features

*   Retrieves precipitation data with an API call to the Applied Climate Information System (ACIS).
*   Depicts drought intensity using percentiles based on the U.S. Drought Monitor categories.
*   Can use total precipitation or a simplified breakdown into effective precipitation and runoff.

## Getting Started

###  Prerequisites

*   Python 3.5+
*   Git
*   Jupyter (Notebook or Lab)

###  Installation

1.	**Clone the repository**   
	'''bash   
	git clone https://github.com/your-username/drought-fingerprint-plots.git   
	cd drought-fingerprint-plots   
	'''

2.	**Create a custom virtual environment (optional)**

3.	**Install libraries (if not already installed in your environment)**   
	'''bash   
	conda install environment.yml   
	'''

###  Usage

1.	**Fire up your Jupyter notebook or lab**

2.	**Open DroughtFingerprintV1.ipynb**

3.	**Run the cells through "Beginning of user inputs"**

4.	**(Optional) Specify user inputs for Production cell #1**   
    station: The ID of the station whose drought conditions you wish to display   
	sname: The name of the station (used only to label the graph)   
    savefigprefix: If not '', will output graphic to savefigprefix directory)

6.	Note: If a variable is defined on two consecutive lines, comment out the second line to use the default value on the first line, uncomment the second line to use the value specified there.  To preserve the default value, only change the value in the second line.

7.	**Run the cells through "Other user settings"**

8.	Note the output table of most recent precipitation.  If the data isn't as up-to-date as you want, you may wish to change the station and sname and rerun Production cell #1.

9.	**(Optional) Modify the settings in User Input Data** 

10.	**Run that cell**
	The fingerprint plot should appear beneath that cell. Below that plot is an explanation of how to interpret drought fingerprint plots.

##  Example Output

The drought fingerprint plot should look something like this:

[Drought Fingerprint Plot, Tallahassee, Florida](images/tlhthr.png)

Your plot will probably cover a different time period than the one in this stored image.  The stored plot shows that, despite recent rain at Tallahassee, the period of time since mid-2025 has been record dry.

##  Contributing

For minor stuff, fork the repository, make changes, and submit pull requests.  For major stuff, open an issue.

## License

This project is licensed under the MIT License - see [LICENSE](LICENSE) file for details.

## Author

*   **John Nielsen-Gammon** - [Link to profile](https://github.com/nielsengammon)

