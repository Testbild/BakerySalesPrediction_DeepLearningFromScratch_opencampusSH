# Bakery Sales Prediction Deep Learning From Scratch opencampus.sh

This github repository is the submission for the Deep Learning From Scratch course from opencampus.sh

We used neural networks as well as primitve approaches to predict the sales of bakeries in Kiel the capitol of Schleswig-Holstein in Germany. The data consisted of 6 different sales groups for the different products, the weather data and the week of KiWo (KiWo is the Kieler Woche, which is the worldwide largest sailing ship festival with around 3 million visitors each year).

After trying a DNN model, an LSTM model, a Fourier Analysis and a simple moving average the outcome was, that the Fourier Analysis had the lowest MAE over all 6 sales groups combined. The weather data had only very little influence on the loss and accuracy in the prediction, hence is has been removed from the dataset for training. This is maybe also a reason, why the moving average is a good indicator, as it also does not look on the weather data. On the other hand we added the day of the week, as we considered this information to be important, because in Germany for example on sundays the supermarkets are closed but bakeries are open.

Feel free to have a look into the code.

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
\
Further there is absolute no warranty for the provided code.
