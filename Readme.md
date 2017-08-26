Brain Tracker Using Muse headband to Calculate Concentration

This was made from scratch at the LA Hacks 2017. The idea was the improve our concentration. Muse band calculates EEG Values which can be used to separate in 5 bands. Using an already conducted research, the 5 bands can be used to calculate concentration levels.

This application has 2 stages, that work synchronously.

You open a PDF and upload to the web app. It calculates your time spent on each page and the muse band calculates the EEG values at each mili second. From here, we can calculate the concentration at any given time. The idea is to find out how much you are concentrating on each page, so you can come back to pages you could not concentrate in your first go.

Using the training data that we generated very uniquely, we went on to use the Microsoft Azure Machine Learning repository. Using a Decision tree model, we trained our data nd the hypothesis was correct, we got a correlation of 78% on the testing data.

This app tells you graphically how long you spent on each page and how much you concentrated during that time. Helps you understand your brain better, just like a Fitbit, but for the brain waves
