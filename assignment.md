# Assignment: Working with Cloud Storage in Azure and GCP


## Instructions

### 1. Upload Files Using the GUI
- **Azure Blob Storage:**
  - Navigate to the Azure portal and create a new Storage Account.
  - Create a Blob container within the Storage Account.
  - Upload a sample file (e.g., a text file or image) to the Blob container using the Azure portal.
<img width="1420" alt="azure1" src="https://github.com/user-attachments/assets/77fdc4f2-a4f6-49f5-a96f-de2f9f3982d8">
<img width="1518" alt="azure2" src="https://github.com/user-attachments/assets/324fac5a-e48d-4bb1-8c86-98425927829d">
<img width="1509" alt="azure3" src="https://github.com/user-attachments/assets/90988ffb-973b-488b-bc8a-60b7d25d6204">
<img width="770" alt="azure4" src="https://github.com/user-attachments/assets/30ad57f0-aa5c-44dc-80d7-9c7a76442997">
<img width="856" alt="azure5" src="https://github.com/user-attachments/assets/0b15a114-99ba-4a00-a8d0-48797e1aa382">
<img width="656" alt="azure6" src="https://github.com/user-attachments/assets/af892bbb-ed05-4a94-b6d0-15e22d0eba12">
<img width="1084" alt="azure7" src="https://github.com/user-attachments/assets/27a90683-9e7e-4e99-a57d-245012931589">
<img width="1301" alt="azure8" src="https://github.com/user-attachments/assets/0b98f38e-7f0e-4c6f-9636-2893a3898860">


- **GCP Cloud Storage:**
  - Access the Google Cloud Console and create a new Cloud Storage bucket.
  - Upload a similar sample file to the bucket using the GCP Console.
  - Example repo of what we did during class: ['Class Repo'](https://github.com/hantswilliams/gcp-cloud-storage-demo)

### 2. Upload Files Using Python
- For this section, if you want to make it more realistic, I recommend finding some open source open source x-ray images and uploading them to the cloud storage. This though is not a requirement, just a suggestion. Potential sites where you can find medical images: 
  - [Stanford - Center for Ai and Machine Learning](https://aimi.stanford.edu/shared-datasets)
  - [Kaggle - Xray COVID images](https://www.kaggle.com/datasets/andyczhao/covidx-cxr2)
  - [NLM - Open Access Biomedical images search engine](https://openi.nlm.nih.gov/)
  - [Cancer - Imaging Archive](https://www.cancerimagingarchive.net/browse-collections/)
- Using the Blob SAS URL I was able to retrieve the file I uploaded
  <img width="1108" alt="azure8-upload" src="https://github.com/user-attachments/assets/09fd4e9d-11c3-4f38-8f45-fbd1ac6485e1">
<img width="1501" alt="azure9-upload" src="https://github.com/user-attachments/assets/7a1d041e-48ff-4bbe-a0ff-f43c98d653ba">

- **Azure Blob Storage:**
  - Write a Python script that uploads a file to the Blob container you created. Use the `azure-storage-blob` library to handle the upload.
  - First error: load_dotenv() returned 'False'
  ![colab error2](https://github.com/user-attachments/assets/67124156-ddfc-4ff3-9fe1-d7e3c9ac180f)



- **GCP Cloud Storage:**
  - Write a Python script that uploads a file to the GCP Cloud Storage bucket you created. Use the `google-cloud-storage` library to handle the upload.

### 3. Explore Storage Features
- **Azure:**
  - Explore and document the options for managing and securing data in Azure Blob Storage (e.g., access policies, tiers).
- **GCP:**
  - Explore and document the options for managing and securing data in GCP Cloud Storage (e.g., IAM permissions, lifecycle rules).

### 4. Submit Your Work
- Create a Markdown document that includes:
  - Screenshots of the file upload process in both Azure Blob Storage and GCP Cloud Storage using the GUI.
  - The Python code used to upload files to both Azure and GCP.
  - Documentation of the storage management and security features you explored.
- Commit and push this Markdown document, along with the screenshots and code, to your GitHub repository.

## Deliverables
- A Markdown document in a GitHub repository called `HHA504_assignment_storage` that includes:
  - Screenshots of file uploads via GUI in Azure and GCP.
  - Python code for uploading files to Azure Blob Storage and GCP Cloud Storage.
  - Notes on storage management and security features in Azure and GCP.
