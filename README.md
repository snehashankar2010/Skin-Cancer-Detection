# Skin-Cancer-Detection
An interactive website where the details about the patient can be provided along with their their skin lesion images. 
Using deep learning and neural networks a learning model was built to classify benign and malignant skin diseases, which may help the doctor diagnose skin cancer at an earlier stage.
![image](https://user-images.githubusercontent.com/71886103/199205919-93f40acc-1d3d-4f45-8fb1-1a357c2e3504.png)

After providing patient details with skin lesion image , output:

![image](https://user-images.githubusercontent.com/71886103/199287434-58cf90b7-ed61-4659-b955-ea323bb3912e.png)
![image](https://user-images.githubusercontent.com/71886103/199280684-5c93a124-9a26-401b-bb07-409bd5664f89.png)

<ul>No.of training samples: 2000</ul>
        <ul>No. of validation samples: 150</ul>
        <ul>No. of testing samples: 600</ul>
        Upon evaluation:
        <ul>Loss: 0.4678</ul>
        <ul>Accuracy: 0.7834</ul>
        After predicting all test samples according to curated model:</p>
    <p>Confusion matrix so formed:</p>
    <img src="{{ url_for('static', filename='images/confusion_matrix.png') }}" class="center">
    <ul>Melanoma sensitivity: 0.8632</ul>
    <ul>Melanoma Specificity: 0.4513</ul>
    <p>Receiver Operating Characteristic <br> ROC AUC: 0.657 </p></h2>
    <img src="{{ url_for('static', filename='image
![confusion_matrix](https://user-images.githubusercontent.com/71886103/199452660-9adab5d8-0723-4175-bd1d-fa644a5df2a0.png)
![ROC](https://user-images.githubusercontent.com/71886103/199452728-c58031cf-d161-44d7-a588-f816179917fa.png)

