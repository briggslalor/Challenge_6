# Challenge_6
Geographic Analysis of the San Fransisco Rental Market 

This project uses data, including sales prices per square foot and gross rent, to analyze trends within the San Fransisco rental housing market between 2010 and 2016. In addition to provide aggregated data and research analysis, this project includes a number of interactive plots to help visualize the identified trends in the data. 

___

## Technologies

This project is built to run using Python 3.7 in a Jupyter Notebook. It is important to run the program within Jupyter Lab as it will allow the user to take full advantage of the analysis and visualizations provided. In addition to the standard Python libraries, this project uses the following:

  [pandas](https://pandas.pydata.org/docs/)
  
  [pathlib](https://docs.python.org/3/library/pathlib.html)
  
  [hvplot](https://hvplot.holoviz.org/user_guide/Introduction.html)
  
  [geoviews](https://pypi.org/project/geoviews/)
  
  [pyviz](https://pyviz.org/)
  
___
  
## Installation Guide
  
In order to install the required libraries to utilize this program, the user will need to begin by creating a new Python development environment, pyvizdev. This can be accomplisehed using the following code in the command line:

```python
   conda create -n pyviz dev python=3.7 anaconda
```

Once the user has created the new development environment, the user must install the neccessary packages. This can be accomplished using the following code: 

```python
   conda activate dev
   
   conda install -c pandas pyviz hvplot geoviews
```

___

## Usage

This project is built to be used by opening the project within a Jupyter Lab notebook and running the program from start to finish. Once the program has completed running it will load the data, analysis and visualizations used to generate the answers to the research questions provided. Given that the plots utilize the hvplot library, they can be intereacted with when using Jupyter Lab by toggling over the plots and using the toolbar on the right-side.

___

## Contributors

Briggs Lalor
briggsclalor@gmail.com

___

## License

MIT License

Copyright (c) [2021] [Briggs Lalor]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
