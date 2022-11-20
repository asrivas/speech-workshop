# Cloud Speech Transcription and Content Classification Tutorial

This tutorial goes through how get content classification for audio files using
pretrained models on Google Cloud. We use the Speech-to-Text API to provide
transcription of public sample audio files stored in Google Cloud Storange. 
Then use the content classification functionality of the Natural Language API 
to provide a label for the unstructured text. NLP analysis can be used to 
categorize content and provide categorization like 
`/Arts & Entertainment/Entertainment Industry/Film & TV Industry` and `/Arts & Entertainment/Humor/Live Comedy` 
cross many broad top-level areas such as `Finance`, `Health`, 
`/Hobbies & Leisure/` and several more. For the full list see the documentation
[here](https://cloud.google.com/natural-language/docs/categories#categories_version_2).

This notebook is meant for educational use in the form of workshops, this is not meant for production use.

1. Create a new Python 3 notebook in Vertex AI Workbench
1. Import this notebook 
1. Enable the Speech-to-Text and Cloud Natural Language APIs

To do this on the command line: 
```
gcloud services enable speechtotext.googleapis.com
gcloud services enable language.googleapis.com
```
