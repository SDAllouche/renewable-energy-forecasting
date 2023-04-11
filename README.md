# Renewable Energy Forecasting

## Introduction

In the electricity grid, the balance must be maintained at all times between consumption and electricity production. For example, wind production is directly related to wind speed and, unlike conventional production systems, is not easily distributable.  The problem becomes more complex when renewable energy begins to provide more than a small percentage of the total electricity supplied to the grid. For this, better forecasts allow utilities to deploy fewer rotating reserves, usually natural gas generators.

Forecasts are typically requested by utilities on two distinct time scales:

* Short-term forecast (from a few minutes to 6 hours) : used to adjust rotating reserves.
* Long-term forecast (weekday): is used by the utility to plan the energy mix or purchase electricity from other suppliers. In general, this information is needed for the next day (for example, before 6 am), but markets tend not to work on weekends and holidays, so longer forecasts are sometimes used.

## Why we need Forecasting ?

As mentioned earlier, as an increasing number of megawatts of renewable energy sources feed into the grid, predicting capacity levels has become critical to ensuring a stable and efficient grid. But forecasting renewable energy production in the short or long term is not an easy task. Renewable energy cannot be produced on demand because it is linked to natural resources such as wind and sun. Therefore, in order to have a stable grid and sufficient energy production, we need a forecasting method.

Prior to exploiting AI, most forecasting techniques relied on individual weather models that provided a narrow view of variables affecting renewable energy availability.

## forecast & AI

Today, AI programs have been developed with support from other emerging technologies, such as the Internet of Things (IoT), sensors, big data and distributed registry technology, AI has the capacity to unlock the vast potential of renewable energy. For example, the result was a 30% improvement in the accuracy of solar predictions, leading to gains on several fronts. We found that improved solar forecasting reduced the operational costs of generating electricity, the start-up and shutdown costs of conventional generators, and solar power reductions.', explains Hendrik Hamann, Distinguished Researcher and Chief Scientist for Geoinformatics at IBM.

In addition, AI is far superior to man when it comes to quickly performing complex tasks. Given that an energy network is one of the most complex machines ever built and that it requires near-second real-time decision-making, AI algorithms are perfectly suited.

## Model Architecture

In this project, we will use a hybrid model contains two architectures : one dimension CNN and LSTM 

* Convolutive neural networks (CNN) 

CNN are more often used for classification and computer vision tasks. Prior to the advent of CNN, manual and time-consuming feature extraction methods were used to identify objects in images. However, convolutive neural networks now offer a more evolutionary approach to image classification and object recognition tasks, taking advantage of the principles of linear algebra, especially matrix multiplication, to identify patterns in an image.

![image](https://user-images.githubusercontent.com/102489525/231289434-dca42906-8709-4808-b543-568e6f8566b7.png)

* Recurring neural network (RNN) 

RNN is a type of artificial neural network that uses sequential data or time series data. These deep learning algorithms are commonly used for ordinal or temporal problems, such as language translation, natural language processing (NLT), speech recognition and sub-processing.image titration; they are integrated into popular applications such as Siri, voice search and Google Translate. Like direct-dominated neural networks and convolutive neural networks (NCNs), recurring neural networks use training data to learn. They are distinguished by their "memory", because they use information from previous entries to influence current input and output. While traditional deep neural networks assume that inputs and outputs are independent of each other, the output of recurring neural networks depends on the anterior elements of the sequence. Among the RNN architectures: LSTM, GRUs…  

![image](https://user-images.githubusercontent.com/102489525/231288902-5e206685-32f7-4daf-ab2d-5e895f1ae2c7.png)


## License

[MIT License](LICENSE)

