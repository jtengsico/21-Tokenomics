<div id="top"></div>

<h3 align="center">KaseiCoin</h3>

  <p align="center">
MarketWhale is a project dedicated to researching, testing, and providing users with machine learning enhanced algorithmic trading bots that make accurate predictions for crypto currency.
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#evaluation-evidence">Sample Data</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project
The project utilizes SVM, LSTM, and CNN models in order to forecast future crypto prices. Based on testing, the model for SVM that utilizes the fear and greed index performs better than LSTM/CNN models. Future steps involve creating a hybrid of LSTM and CNN models with the fear and greed index to increase accuracy. In general, machine learning models tend to have prediction rates above 50% which is considered good but application using live data tends to perform worse than prediction. Once the models are complete, backtesting will be performed to check degree of accuracy and if predications can be applied to live data. There are also plans to integrate trading strategies into the algorithm and utilize 1-minute price data instead of hourly data. Increasing accuracy above 51 - 53% percent and making sure that the model performs well in the market is a future goal of our company.

<p align="right">(<a href="#top">back to top</a>)</p>

### Built With

* python 3.7.10
*

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

To setup this algorithm locally on your desktop, please clone the repo.
After cloning the repo, you can run the program utilizing jupyter lab/notebook.

The machine learning model was run using Google Colab. 
A saved LSTM and CNN model is saved in json and you can use those models so you won't have to import the ipynb file to Google Colab to re-run the model. 

### Installation

1. Clone the repo
   ```sh
   git clone 
   ```
2. Install required python packages listed in the ipynb file. 
   ```sh
   use conda or pip install
   ```
3. Run the file in jupyter lab/notebook

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- Evaluation Evidence -->
## Evaluation Evidence
SVM Model is shown below. 
![svm_fear.greed.png](images/svm_fear.greed.png)
![fear_and_greed.png](images/fear_and_greed.png)  
![svm_plot.png](images/svm_plot.png)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- LICENSE -->
## License

Distributed under the MIT License.
See [license txt](https://github.com/git/git-scm.com/blob/main/MIT-LICENSE.txt)

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- ACKNOWLEDGMENTS -->
## Acknowledgments
Credit to creator of readme template. The repo also has useful resources. 
* [README Template](https://github.com/othneildrew/Best-README-Template.git)

<p align="right">(<a href="#top">back to top</a>)</p>
