# Crypto Clustering using Unsupervised Learning


Week 10 challenge, utilizing python and unsupervised learning to cluster cryptocurrencies by performance and plot the results. 

To do so, we:

Imported the data from a given CSV file of crypto information
Prepared the data using StandardScaler's fit_transform
Found the best value for k using the scaled data
Clustered the crypto currencies using that k-value
Optimized the data using Principal Component Analysis
Found the best value for k using the new PCA Data
Clustered the crypto currencies using that k-value on the PCA Data
Visualized and compared the two different groupings

The analysis determined that using PCA to synthesize the data down to fewer features made tighter groupings with less overlap. The inertia of the optimal k also dropped from ~79 to ~50.


---

## Contributors

This analysis was created by Nico Cortese with support from the lovely Fintech Coding Boot Camp Team at Boot Camp Spot / Columbia School of Engineering

Nico Cortese

XXX-XXX-XXXX

XXXX@gmail.com

---

## License

MIT License

Copyright (c) 2022 NicoCortese

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