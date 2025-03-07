# Deep-Generative-Models
Coursework and projects for Deep Generative Models (DGM) course (Graduate), including theoretical homework solutions/problems, and the project of the course.

Here is the page of the course:
https://generative-ai-sut.github.io/


## CHW1's Results:
- **Implementing an LSTM to fit the `yfinance` data**:
  We developed a Long Short-Term Memory (LSTM) network to analyze and predict stock prices using the `yfinance` dataset. The LSTM model captures temporal dependencies and patterns in stock price data, allowing for more accurate predictions compared to traditional linear models. Key steps included data preprocessing, model architecture design, training, and evaluation.

  <div align="center">
    <img src="https://github.com/MohammadParsaTheFirst/Deep-generative-models-course/blob/main/CHW1/results/LSTM_Result2.png?raw=true" alt="LSTM Results" width="500"/>
  </div>

- **Implementing the PixelCNN's structure for Generation of `MNIST` dataset Numbers**:
  We implemented the PixelCNN model to generate images from the MNIST dataset. PixelCNN is an autoregressive model that predicts each pixel in the image sequentially, conditioned on previously generated pixels. This structure allows it to capture intricate spatial dependencies in the data. The process involved defining the model architecture, training it on the MNIST dataset, and evaluating the quality of the generated images.

  <div style="display: flex; justify-content: center;">
    <img src="https://github.com/MohammadParsaTheFirst/Deep-generative-models-course/blob/main/CHW1/results/Pixelcnn_Result1.png?raw=true" alt="LSTM Results" width="30%" style="margin-right: 10px;"/>
    <img src="https://github.com/MohammadParsaTheFirst/Deep-generative-models-course/blob/main/CHW1/results/Pixelcnn_Result2.png?raw=true" alt="PixelCNN Results" width="30%" style="margin-right: 10px;"/>
    <img src="https://github.com/MohammadParsaTheFirst/Deep-generative-models-course/blob/main/CHW1/results/Pixelcnn_Result3.png?raw=true" alt="Additional Results" width="30%"/>
  </div>
