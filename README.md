# OutpatientLabPrediction

Insert the proc_code for all the labs you'd like to run into the list titled label_labs. Then run the entire notebook to 1) generate a feature matrix unique to each label lab 2) output the accuracy metrics resultant from running it through an ML model. The output will be in the form of a dictionary with the key as the proc_code and the values  as a list containing labs, dx, hx, med, AUROC, TNR, and NPV.
