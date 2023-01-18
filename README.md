# Motor Vehicle Collisions in NY City

![python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)
![plotly](https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white)
![pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)

This is a Streamlit web app that allows users to explore and analyze data on motor vehicle collisions in NY City. The app allows users to filter collisions by location, date, and type of collision, and to view statistics on the number and severity of collisions, as well as maps showing the locations of collisions.

[Go to page](https://mrdaliselmi-nyc-motorvehiclecollisions.streamlit.app/)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Python 3.6 or later
- Streamlit
- Pandas
- Plotly
- Geopandas
  
### Installing

1. Clone the repository to your local machine:

   `git clone https://github.com/mrdaliselmi/NYC-Motor-Collisions-Streamlit-WebApp.git`
2. Navigate to the project directory:

    `cd NYC-Motor-Collisions-Streamlit-WebApp`
3. Install the required packages:

    `pip install -r requirements.txt`
4. Run the app:

    `streamlit run app.py`

## Features

- The app allows users to view the locations of collisions on a map, filtered by the number of people injured.
- The app allows users to see the number of collisions that occur during a selected hour of the day.
- The app allows users to view a breakdown of collisions by minute during the selected hour.
- The app allows users to view the top 5 dangerous streets in terms of collisions involving pedestrians, cyclists, or motorists.

## Data

The data used in this app is obtained from the New York City Open Data portal.

## Built With

- [Streamlit](https://streamlit.io) - Web App Framework
- [Pandas](https://pandas.pydata.org) - Data manipulation and analysis
- [Plotly](https://plotly.com) - Data visualization
- [Pydeck](https://deckgl.readthedocs.io/en/latest/) - Map visualization

## Author

Your Name - Your Github username

## Acknowledgments

The data for this project is obtained from the New York City Open Data portal.
