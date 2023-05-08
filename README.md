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
