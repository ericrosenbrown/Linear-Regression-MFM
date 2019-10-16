# Linear-Regression-MFM

An implementation of Linear Regression in ulam.

To run the example, just clone this repo, and run the following command:

mfzrun stable_debug.mfz


The model moves around, and consumes data to update the estimated parameters. DGen generate data sampled from a line with adjustable parameters.

In the log, you will see the current weight and bias (y-interncept) that is estimated by the model. Open the tool box, and click on the DGen element, and change the slope, bias, noise ect. to the generated data, and the model will perform new estimations.
