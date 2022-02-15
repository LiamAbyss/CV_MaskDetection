# CV_MaskDetection
**School Project** : Create an AI that detects whether a mask is on or off.

**Contributors** : Rémi ARBACHE, Paul BUCAMP, Eugénie DALMAS

---

### **Create dataset and train the model**

The mask detection model has been trained a custom dataset with the notebook *data_creation.ipynb* and trained with the first cells of the *project.ipynb* notebook.

### **Try the model**

The detection can be tried in *project.ipynb* using the camera. A pre-trained model *svm_model* can be loaded : in the cell "Initialize the model", uncomment `#svm = joblib.load(filename)` to load the pre-trained model and directly run the detection in the last cell "Try it !".
