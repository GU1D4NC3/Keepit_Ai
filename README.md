# Nutrient Calculation Model for Diet
### Requirements
```!pip install --upgrade google-cloud-vision```

### Main Code: vision_api.ipynb
- You need to set the path for the authentication key, a json file, to use the vision API.
```os.environ['GOOGLE_APPLICATION_CREDENTIALS'] = 'Enter the path of the json file here'```

- You need to set the path of the image file to run the model.
file_name = os.path.abspath('Enter the path of the image file here')
-----
### output.txt
- The results of detecting objects in the image using the vision API are saved as a txt file.
-----
### nutrient_info.json
- A json file that stores the nutrient information of the objects detected by the vision API.
- Only the detected object information is retrieved from here to calculate the nutrients.
---
# Labor Contraction Cycle Calculation Model (Algorithm) [No use]
### sufficient.ipynb
- Based on medical information about labor contractions, it distinguishes between false labor and true labor, and calculates the contraction cycle.
- Please note that the codes and models are designed to work best with the specified file paths and settings. Always ensure to input the correct file path and format, and always check the output to ensure the models are running as expected.
