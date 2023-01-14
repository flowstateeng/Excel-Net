<p align="center">
	<img src='https://github.com/johnathanalyst/Excel-Net/blob/main/imgs/banner.png' alt='Cover Slide'/>
</p>
<br/>

# Excel-Net
A neural network in a single Excel spreadsheet.

![Build Status](https://img.shields.io/badge/build-Stable-green.svg)
![License](https://img.shields.io/badge/license-NONE-green.svg)
<br/>


# Description
Using a small training dataset, the single-layer neural network learns to predict housing prices, based on several input values (e.g., # of bedrooms, # of bathrooms, sq. ft., etc.). It does this by adjusting the model's weights over ten cycles of "gradient descent." After training, the model then is tested on new, unseen data from a small testing dataset.

Graphs of the model's predictions are shown at each cycle of training, along with the model's error, training accuracy, etc. The first and final graphs are shown again at the top of the sheet for comparison, as well as graphs of the model's cost and accuracy throughout training.

Check the video demo [on YouTube](https://youtube.com/@johnathanalyst)

[Follow](https://www.youtube.com/@johnathanalyst?sub_confirmation=1) on YouTube for demos and guides in AI, finance, IoT, software engineering and more.

Feel free to ask me questions on [GitHub](https://github.com/johnathanalyst) or at me@johnathanalyst.com

Enjoy!
<br/><br/>


## Prerequisites
* Excel
<br/><br/>


## Installation
```bash
	git clone https://github.com/johnathanalyst/Excel-Net.git
```
<br/>


## Usage
Download the repository and open the Excel file. You can adjust the "learning rate" cell at the top of the sheet and it will update instantly (depending on the speed of your pc), to show the new values & graphs during the training and testing processes.

!!! WARNING: NONE OF THE CELLS IN THIS SHEET ARE LOCKED OR PROTECTED! IF YOU CHANGE ANY CELLS OTHER THAN THE LEARNING RATE, THINGS CAN EASILY FAIL! !!!
<br/>


<p align="center">
	<img width=650 src='https://github.com/johnathanalyst/Excel-Net/blob/main/imgs/results.png' alt='Results'/>
</p><br/>

<p align="center">
	<img width=650 src='https://github.com/johnathanalyst/Excel-Net/blob/main/imgs/gradient-descent.png' alt='Training'/>
</p><br/>

<p align="center">
	<img width=650 src='https://github.com/johnathanalyst/Excel-Net/blob/main/imgs/cost.png' alt='Cost'/>
</p><br/>

<p align="center">
	<img width=650 src='https://github.com/johnathanalyst/Excel-Net/blob/main/imgs/accuracy.png' alt='Accuracy'/>
</p>
<br/>


## Authors
* **Johnathan Chivington:** [YouTube](https://youtube.com/@johnathanalyst), [Email](me@johnathanalyst.com)

## Contributing
Not currently accepting outside contributors, but feel free to use as you wish.

## License
There is no license associated with this content.
<br/><br/>
