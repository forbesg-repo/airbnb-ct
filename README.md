# airbnb-ct


<br />
<p align="center">
  
  <h1 align="center">AirBnB analysis - Cape Town, South Africa</h3>

  <p align="center">
    This notebook is using data from Inside Airbnb. The goal is to investigate the data and find out more information about    the AirBnb landscape in Cape Town where I live.
    <br />
    <br />
    <a href="https://medium.com/@forbesg/listing-an-airbnb-in-cape-town-this-analysis-will-make-you-understand-the-landscape-3a928862b931">View Medium Post</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
* [Usage](#usage)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project

Airbnb is very popular and of course, in Cape Town we often wonder about the density of listings because its very expensive to rent as a local. So I decided to check out this data and investigate the foundational aspects of this landscape.

Some key questions / areas of investigation I hade were:

(1) Listings Dataset:
What does the price distribution look like in Cape Town & for specific Areas?
What is the difference in pricing between the property types?
What is the difference in pricing between areas / wards ?
How many hosts have multiple listings and where are they?
What is the difference between superhosts and normal hosts pricing?

(2) Reviews Dataset:
What are the reviews like for Cape Town hosts, good or bad?
How does demand fluctuate for AirBnb in Cape Town?
Is there the expected seasonality with seasons?
Is there higher demand with less seasonality in certain areas?

(3) Price Prediction:
As a new host, if you try to charge above market price for a listing, then renters will select more affordable alternatives which are similar. If you set price too low, you will miss out on potential revenue as well.

The k nearest neighbours results were not incredible, but lay a decent foundation to build upon.

It would be great to extend this to specific areas in the data, and also build out some more powerful models with more features.

Also, there is a Boat & Cave listing in Cape Town that was found!

### Built With

* [AWS Sagemaker Notebook](https://aws.amazon.com/sagemaker/)
* [Pandas](https://pandas.pydata.org/)
* [Numpy](https://numpy.org/)
* [Seaborn](https://seaborn.pydata.org/)
* [sklearn](https://scikit-learn.org/stable/)
* [python](https://www.python.org/download/releases/3.0/)



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple example steps.
* Go fetch the listings and reviews datasets (for the city of your choice) from [insideairbnb](http://insideairbnb.com/get-the-data.html)
* [Cape Town Reviews Data](http://data.insideairbnb.com/south-africa/wc/cape-town/2020-04-26/visualisations/reviews.csv)
* [Cape Town Listings Data] (http://data.insideairbnb.com/south-africa/wc/cape-town/2020-04-26/visualisations/listings.csv)
* Download the jupyter notebook from this repository, connect up the datasets loading cell to wherever you host your data ( I hosted mine on a s3 bucket in amazon)
* [Notebook Link](https://github.com/forbesg-repo/airbnb-ct/blob/master/airbnb-ct.ipynb)
* Run through the notebook and have fun!

### Prerequisites

Knowledge of python 3 and other libraries listed above.


<!-- USAGE EXAMPLES -->
## Usage

I wrote a post on medium about my findings, you can read that here:

* [Medium Article](https://medium.com/@forbesg/listing-an-airbnb-in-cape-town-this-analysis-will-make-you-understand-the-landscape-3a928862b931)



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Gareth Forbes - forbesg@moonwrench.com

Project Link: [Medium](https://medium.com/@forbesg/listing-an-airbnb-in-cape-town-this-analysis-will-make-you-understand-the-landscape-3a928862b931)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [Jeff Hale](https://towardsdatascience.com/scale-standardize-or-normalize-with-scikit-learn-6ccc7d176a02)
* [Rahul Gupta](https://medium.com/analytics-vidhya/identifying-most-important-amenities-affecting-the-price-of-airbnb-3a34af7e4a38)
* [Ankit Peshin, Sarang Gupta, Ankita Agrawal](http://www.columbia.edu/~sg3637/airbnb_final_analysis.html)


