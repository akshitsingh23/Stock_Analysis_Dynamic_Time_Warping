# Stock Price Comparison Using DTW
![StonksUpStongsGIF](https://github.com/user-attachments/assets/947f06f6-cd41-4353-9749-f35463509931)

## Project Overview
This project aims to compare the stock prices of 15 top companies, including Google, Microsoft, PayPal, P&G, and others. The comparison is performed using Dynamic Time Warping (DTW) to find the most similar stock price patterns and K-Nearest Neighbors (KNN) to group the companies based on their stock price similarities.

## Features
- **Stock Price Comparison**: Analyze and compare the stock prices of 15 major companies.
- **Dynamic Time Warping (DTW)**: Measure the similarity between different stock price time series.
- **K-Nearest Neighbors (KNN)**: Group companies based on the similarity of their stock prices.
- **Visualization**: Visualize the stock price trends and the results of the DTW and KNN analysis.

## Dynamic Time Warping (DTW)
Dynamic Time Warping (DTW) is an algorithm used to measure the similarity between two temporal sequences that may vary in speed. It is particularly useful for time series analysis where the sequences can be of different lengths or have different time scales.

### How DTW Works
DTW calculates an optimal match between two sequences by warping the time axis iteratively until an optimal match between the two sequences is found. This involves stretching and compressing the sequences to minimize the distance between them. The algorithm finds the best alignment by considering all possible alignments and selecting the one with the minimum cumulative distance.

### Applications of DTW

#### 1. Speech Recognition
DTW has been widely used in speech recognition to compare spoken words and identify similarities, even when words are spoken at different speeds. This is crucial for recognizing words spoken by different people at different paces.

#### 2. Speaker Recognition
In speaker recognition, DTW helps in identifying and verifying speakers by comparing their voice patterns. This is useful in security systems where voice authentication is required.

#### 3. Online Signature Recognition
DTW is also used in online signature recognition to compare the dynamic properties of signatures, such as speed and pressure, to verify the authenticity of a signature.

#### 4. Other Applications
- **Video and Graphics Data**: DTW can be applied to temporal sequences of video and graphics data to find similarities and patterns.
- **Partial Shape Matching**: It is used in applications where partial shapes need to be matched, such as in computer vision and pattern recognition.

DTW’s flexibility in handling different time scales and lengths makes it a powerful tool in various domains beyond speech recognition.


## Installation
To run this project, you need to have Python and Jupyter Notebook installed. You can install the required libraries using the following command:

```bash
pip install -r requirements.txt
```
## Usage
1. **Clone the repository:**
     ```bash
    git clone https://github.com/yourusername/stock-price-comparison.git
    cd stock-price-comparison
    ```
2. **Install the required libraries:**
   ```bash pip install -r requirements.txt```
3. **Open the Jupyter Notebook:**
   ```bash jupyter notebook```
   ## Project Structure
- `data/`: Contains the stock price data for the 15 companies.
- `notebooks/`: Contains the Jupyter Notebook with the analysis.
- `requirements.txt`: Lists the required Python libraries.
- `README.md`: Project documentation.

## Results
The project outputs include:
- Similarity scores between different stock price time series using DTW.
- Grouping of companies based on stock price similarities using KNN.
- Visualizations of stock price trends and analysis results.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.


