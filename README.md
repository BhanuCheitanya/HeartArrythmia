# HeartArrythmia
The previous model (Heart Arrhythmia Detection LSTM) concluded the detection
of heart arrhythmia using uni-directional LSTM model from deep learning. The results were
found to be great but there was some room for improvement, the model had a decent
performance which was suitable to make the predictions but as this was a medical scenario, the
room for improvement should always be given importance over anything. Thus, the LSTM was
introduced, this drastically improved the results and the accuracy was increased, although not
much but it was significant. This recent approach has some of the updates which make it easier
for the computation and adds another layer to the project which enables it to use the dataset in
a particular fashion. As the case in which the dataset is to be received can be in the format of
CSV, ‘Comma Separated Values’, it doesn’t need to go through the processing and
computational power of the previous model (Heart Arrhythmia Detection using LSTM) as this
model did the conversion of ‘.dat’, ‘.hea’ file format which was usually produced by the
ECG/EKG machines. Thus, reducing the time required for the processing of the dataset.
Additional change is the introduction of back propagation with the help of batch size as it
drastically decreases the computational and the runtime of the model from 7-8 hours to 2-3
hours, all this occurs at a faster rate for even bigger dataset and has the accuracy gaining at
double the rate for much less epochs.


# Findings of the model
As there were multiple classes to predict the results of irregularities, a precision, recall and f1-
score was calculated for each class to be predicted the results of. The accuracy was found to be
above the 99 thresholds. All this was followed by the final confusion matrix which made the
concept of the performance of the model clear for the understanding of further development.
This concluded the working of the entire model in brief. The model was found to be 99%
accurate and is found fit for those datasets which are present in .cv format. The model gives us
knowledge about the values of True Positives, False Positives, True Negatives and False
Negatives. This tells us how good our model is and how many times it gives us the appropriate
results. The results of the current model can be improved further by using other "Feature
Extraction" techniques and also by adding additional layers. The model does seem to have more
room for improvement although the limitations for the existing technology and knowledge acts
as a barrier and hence these seems a theoretical approach for the improvements further, being
able to detect the R sinusoidal wave, we can further calculate the less evasive and less
complicated waves which are easier for the computation and then combine the models to get a
complete and accurate figure for the prediction which might not be needed to be read by the
medical professional and solely by the current existing model.

## Link to the dataset- https://drive.google.com/drive/folders/1oj25ksVlVzDFQ28664sbbl9zhJbEXbMz?usp=sharing
