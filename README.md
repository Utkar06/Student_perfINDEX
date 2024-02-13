This model is used to find the Student Performance index based on the data given by the the user i.e [ 'Hours Studied', 'Previous Scores', 'Extracurricular Activities',
       'Sleep Hours', 'Sample Question Papers Practiced']

       
To create this model i have used the given training data to train my model.Firstly,I have modified my data as to convert given data in my desired format.
I checked the training data to find the dependence of each factor in my predicted outcome,by using pyplot from matplotlib library.
<img width="913" alt="image" src="https://github.com/Utkar06/Student_perfINDEX/assets/142239017/26cb26f1-22e2-42bb-a8c8-f943c21c958a">


Then i have created my model by Linear regression from scikit learn_Linear model.I tried to divide my data into train and val(by train_test split )to check the accuracy of the model 
<img width="914" alt="image" src="https://github.com/Utkar06/Student_perfINDEX/assets/142239017/18c3288c-faca-4591-8734-4f0e2c8217d5">

I also  tried using different models such as

Descision Tree Regressor

RandomForestRegressor 
<img width="888" alt="image" src="https://github.com/Utkar06/Student_perfINDEX/assets/142239017/e3f7c5d7-14da-4745-9091-c4aff5198de9">



       
