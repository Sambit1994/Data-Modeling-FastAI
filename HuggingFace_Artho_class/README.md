The artho-train model creates an image model for classifying arthropods using collected images

It is based on the 'convnext_small' image model in the timm library; So, pip install and import if not already done

The artho-app uses Gradio to create a temporary webpage to test the app
* The app classifies an uploaded picture into 6 categories ('Arachnida', 'Crustacea', 'Insecta', 'Chilopoda', 'Diplopoda', and 'Inconclusive')
* The model classifies accurately for roughly 70-75% (the inconclusives are the primary outliers)

## Model Hosting

The model is hosted on [Hugging Face Spaces](https://huggingface.co/spaces/Sambit94/Arthopod_Classifier)
