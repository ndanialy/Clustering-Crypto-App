# Clustering Crypto App
 An app for clustering crypto currencies based on performance over time

---

## Technologies

This project uses Jupyter Lab in addition to the following libraries and add ons:

* [pathlib](https://docs.python.org/3/library/pathlib.html) for the path functions to locate the csv files.

* [pandas](https://pandas.pydata.org/docs/) for working with dataframes.

* [matplotlib](https://docs.python.org/3/library/pathlib.html) for the data visualization.

* [sklearn](https://scikit-learn.org/stable/user_guide.html) for analyzing the data.

---

## Installation Guide

Please run the following commands in your terminal before running the app:
```
pip install jupyterlab

```
---

## Usage

The App imports crypto data from a csv and stores it into a dataframe before plotting it as a lince chart:

![Data_import](https://user-images.githubusercontent.com/96391748/156911372-635cfb12-1c24-478b-bcd7-28ac89e79588.PNG)

An elbow curve is computed and visualized using the imported data:

![elbow_curve](https://user-images.githubusercontent.com/96391748/156911417-7f11ed1a-7be4-4f70-9113-1b7b0b229474.PNG)

A k-means model is then run using the optimal k value with the results visualized as a scatter plot:

![clusters](https://user-images.githubusercontent.com/96391748/156911435-5a427250-e550-4d43-b044-9a85798af7f4.PNG)

Finally, a prinicpal component analysis is performed on the data before the previous steps are repeated:

![PCA](https://user-images.githubusercontent.com/96391748/156911458-d618a2a4-6223-489f-af1d-ea2092d67417.PNG)


---

## Contributors

* Nicklaus Danialy nickdanialy@gmail.com 

---

## License

Copyright (c) [2021] [Nicklaus Danialy]

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