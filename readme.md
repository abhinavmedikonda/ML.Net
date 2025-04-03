adjust the absolute path to the 
training data in the corresponding .mbconfig file. 
The path in the .mbconfig file should point to the 
TrainingData folder that you find in this directory.

To change the path in the .mbconfig to your own TrainingData folder, you have two options:

a) Open an .mbconfig-file by double-clicking it in 
   Visual Studio's Solution Explorer. Change the path 
   in the user interface by selecting your training file or folder. 
   This means that you have to re-do the settings after 
   selecting a new file or folder to retrain your model.
   
b) Open an .mbconfig-file in a texteditor and change 
   the path "D:\\TrainingData\\..." to your own training data path.
   Save the .mbconfig file and open it in Visual Studio by 
   double-clicking it in Solution Explorer. With this approach,
   you don't have to re-do the settings to retrain your model.
