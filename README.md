# watsonx Image Model Assets
## Getting Started
- Add any images you would like to send to watsonx to the [*images*](/images/) folder
- Using the format of the *.env.example* file, add your API key, project ID, and url to a .env file in the project root directory

## Scripts  
### User Interface [ui]  
**Description:**
A user interface designed with [chainlit](https://docs.chainlit.io/get-started/overview) to provide a similar experience to the watsonx "chat with images" functionality with the added benefit of customizability.  
  
![UI Screenshot](/misc/ui_screenshot.png)

**Usage:** 
In a terminal window navigate into the *scripts* folder. Use the `make setup-ui` command to install dependencies and set up a virtual environment. Next use the `make start-ui` command to start the application. A new tab should open to the address [http://localhost:8000/](http://localhost:8000/) where the UI can be found.  

### chat_with_image.py
**Description:**
A simple python script that enables the programatic usage of watsonx's "chat with images" functionality via REST API calls.  

**Usage:**  
In a terminal window navigate into the *scripts* folder. Use the `make setup` command to install dependencies and set up a virtual environment. Next use the `make start-script` command to run the script.  

## Notebooks
### chat_with_image.ipynb
A simple notebook that enables the programatic usage of watsonx's "chat with images" functionality via REST API calls.

---
**Contact Info:** Reach out to drew.letvin@ibm.com if you have any questions.  
  
  ***Acknowledgements:** credit james.heavey@ibm.com for UI elements*