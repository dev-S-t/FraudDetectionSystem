# FDS

A complete platform for fraud detection solutions 

main index / starting page is "FSD_Landing-main"

<div style="display: flex; flex-direction: row; align-items: flex-start;">
  <div style="flex: 1; text-align: center;">
    <img src="Home (2).png" width="50%" title="UI" alt="UI">
  </div>
  <div style="flex: 1;">
    <h3>Folder descriptions</h3>
    <p><strong>FSD landing page (web)</strong></p>
    <pre>
    ```bash
    FSD_landing-main
    ```
    </pre>
    <p><strong>script for making predictions (api)</strong></p>
    <pre>
    ```bash
    fsd-v2-main
    ```
    </pre>
    <p><strong>Form for user input (web)</strong></p>
    <pre>
    ```bash
    form-fsd-main
    ```
    </pre>
    <p><strong>API doc (web)</strong></p>
    <pre>
    ```bash
    api_page-main
    ```
    </pre>
    <p><strong>Prediction Results (web)</strong></p>
    <pre>
    ```bash
    results-main
    ```
    </pre>
    <p><strong>Jupyter File for model creation (web)</strong></p>
    <pre>
    ```bash
    Model_creation
    ```
    </pre>
  </div>

</div>



## Run Locally

* Clone the project folder "FSD(team4)" 
* get model files 
  (the model files are big and need to be downloaded separately and placed in resources folder 
  
download here "https://github.com/dev-S-t/fsd-v2/tree/main/resources" 
required 
* knn_model.pkl 
* neural_network_model.h5 
* random_forest_model.pkl 
* scaler.pkl 
* xgboost_model.pkl)

Go to the project directory

```bash
  cd FSD(team4)
```

Go to api folder "fsd-v2-main"
```bash
  cd fsd-v2-main
```


Install dependencies

```bash
  pip install -r requirements.txt
```

Start the server

```bash
  uvicorn main:app --relaod
```

Now either use test.py or the web ui to get results

