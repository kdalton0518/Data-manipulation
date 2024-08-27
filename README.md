## Data Manipulation

The `datasets_download.ipynb` notebook in the Data-Manipulation folder contains code for downloading and processing datasets. Currently, it includes:

1. MbarkDiAziz AI Dataset
   - Loading the dataset
   - Saving the dataset to JSON format
2. jacob-hugging-face
3. Lang-uk/recruitment-dataset-job-descriptions-english
4. Aneeth/job_description_7k
5. Aneeth/job_description_10k
6. Cnamuangtoun/resume-job-description-fit
7. nakamoto-yama/job-descriptions-public
8. nathansutton/data-science-job-descriptions

## Usage

To use the dataset downloader:

1. Open the `datasets_download.ipynb` notebook.
2. Run the following code:

```python
MDA = MbarkDiAzizAIDataset()
MDA.load_data()
MDA.save_to_json()
