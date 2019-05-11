# studentAdmissionsKeras
Simple NN for student admissions; Based on Udacity DL course exercises

Results



model.compile(loss = 'categorical_crossentropy', optimizer='rmsprop', metrics=['accuracy'])
360/360 [==============================] - 0s 121us/step

 Training Accuracy: 0.705555555556
40/40 [==============================] - 0s 118us/step

 Testing Accuracy: 0.775


model.compile(loss = 'categorical_crossentropy', optimizer='adam', metrics=['accuracy'])
360/360 [==============================] - 0s 154us/step

 Training Accuracy: 0.7
40/40 [==============================] - 0s 111us/step

 Testing Accuracy: 0.775

model.compile(loss = 'mean_squared_error', optimizer='rmsprop', metrics=['accuracy'])
360/360 [==============================] - 0s 275us/step

 Training Accuracy: 0.716666666667
40/40 [==============================] - 0s 135us/step

 Testing Accuracy: 0.65

model.compile(loss = 'mean_squared_error', optimizer='adam', metrics=['accuracy'])
360/360 [==============================] - 0s 292us/step

 Training Accuracy: 0.713888888889
40/40 [==============================] - 0s 121us/step

 Testing Accuracy: 0.65


