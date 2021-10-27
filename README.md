Data Scientist & Industrial Engineer

# [REST API created using R and Plumber](https://github.com/omkar-shetty/r_api)

Models built in R can be exposed to external resources via API endpoints. This repo includes scripts to :  
* build a simple classification model  (based on the Titanic dataset).
* expose the model prediction as an API endpoint via the Plumber package. Users will be able to input 3 features - the passenger's age, gender and the travelling class and the model returns a prediction for how likely was it that the passenger survived. 
* Expose the endpoints directly via the local server as well as a docker container.
* A Jupyter notebook to submit requests directly to the API and record the responses.
