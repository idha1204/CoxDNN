# Fitting Cox-DNN models
This is Python code for fittting Cox-DNN models for simulated data.
The fitting procedure is below.
1) Generation of simulated data
2) Fit Cox-based DNN models using "Cox-DNN" and "DeepSurv".
3) In particular, to fit "Cox-DNN" and calculate the Brier Score,
   two new functions need to be specified: the "Breslow loss function" and the "Brier Score".
   Note that Cox-based loss functions, such as "Breslow loss function", are not available as built-in functions in tf.keras.
