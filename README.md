# Linear-Regression-MFM

An implementation of Linear Regression in ulam.

To run the example, just clone this repo, and run the following command:

mfzrun stable_debug.mfz

![start](https://github.com/ericrosenbrown/Linear-Regression-MFM/blob/master/start.png)

The model (dark blue) moves around, and consumes data (light blue) to update the estimated parameters. DGen (purple) generate data sampled from a line with adjustable parameters.

In the log, you will see the current weight and bias (y-interncept) that is estimated by the model. Open the tool box, and click on the DGen element, and change the slope, bias, noise ect. to the generated data, and the model will update the parameters as new data comes in. In the model parameters, you can adjust the learning rate.
