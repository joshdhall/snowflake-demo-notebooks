# Snowflake Notebook Demos
Snowflake Notebooks is your familiar, interactive development environment to perform Data Science, Data Engineering, and AI/ML workloads end-to-end in Snowflake. Write Python & SQL in the same interface.

This repo contains a collection of Snowflake Notebook demos, tutorials, and examples. Browse each folder to access the notebook files associated with each demo. Below is the list of notebooks you can find in this repo:


|  | Notebook | Video | Topics |
|---|---|---|---|
| My First Notebook Project | [Link](https://github.com/Snowflake-Labs/snowflake-demo-notebooks/blob/main/My%20First%20Notebook%20Project/My%20First%20Notebook%20Project.ipynb) | [Link](https://www.youtube.com/watch?v=tpg35YgA9Gk) | Using Notebooks |
| Visual Data Stories With Snowflake Notebooks | [Link](https://github.com/Snowflake-Labs/snowflake-demo-notebooks/blob/main/Visual%20Data%20Stories%20with%20Snowflake%20Notebooks/Visual%20Data%20Stories%20with%20Snowflake%20Notebooks.ipynb) | [Link](https://www.youtube.com/watch?v=WJUNTudCsYM) | Using Notebooks, Data Science, Python |
| Data Analysis and Churn Prediction using Snowflake Notebooks | [Link](https://github.com/Snowflake-Labs/snowflake-demo-notebooks/blob/main/Telco%20Churn%20Data%20Analysis/Telco%20Churn%20Data%20Analysis.ipynb) | [Link](https://www.youtube.com/watch?v=eqb5RdmpW8c) | Data Science, Python |
| Create and Manage Snowflake Objects Like a Pro | [Link](https://github.com/Snowflake-Labs/snowflake-demo-notebooks/blob/main/Create%20and%20Manage%20Snowflake%20Objects%20Like%20a%20Pro/Create%20and%20Manage%20Snowflake%20Objects%20Like%20a%20Pro.ipynb) | [Link](https://www.youtube.com/watch?v=Dj8aAoEOfrw) | Data Engineering, SQL |
| Data Engineering Pipelines with Snowpark Python | [Link](https://github.com/Snowflake-Labs/snowflake-demo-notebooks/blob/main/Data%20Engineering%20Pipelines%20with%20Snowpark%20Python/Data%20Engineering%20Pipelines%20with%20Snowpark%20Python.ipynb) | [Link](https://www.youtube.com/watch?v=mpstEt0fU8U) | Data Engineering, Python |
| End-to-End Machine Learning with Snowpark ML | [Link](https://github.com/Snowflake-Labs/snowflake-demo-notebooks/tree/main/End-to-End%20Machine%20Learning%20with%20Snowpark%20ML) | [Link](https://www.youtube.com/watch?v=LeSGBW0YoLg) | Machine Learning, Python |
| Creating Snowflake Object using Python API | [Link](https://github.com/Snowflake-Labs/snowflake-demo-notebooks/blob/main/Creating%20Snowflake%20Object%20using%20Python%20API/Creating%20Snowflake%20Object%20using%20Python%20API.ipynb) | - | Data Engineering, Python |
| Import Custom Package from Stage into Notebook | [Link](https://github.com/Snowflake-Labs/snowflake-demo-notebooks/blob/main/Import%20Package%20from%20Stage/Import%20Package%20from%20Stage.ipynb) | - | Using Notebooks |
| Reference cells and variables | [Link](https://github.com/Snowflake-Labs/snowflake-demo-notebooks/blob/main/Reference%20cells%20and%20variables/Reference%20cells%20and%20variables.ipynb) | - | Using Notebooks |
| Hyperparameter Tuning with sklearn | [Link](https://github.com/Snowflake-Labs/snowflake-demo-notebooks/blob/main/Hyperparameter%20Tuning%20with%20sklearn/Hyperparameter%20Tuning%20with%20sklearn.ipynb) | - | Machine Learning, Python |
| How to work with Files in Snowflake Notebooks | [Link](https://github.com/Snowflake-Labs/snowflake-demo-notebooks/blob/main/Working%20with%20Files/Working%20with%20Files.ipynb) | - | Using Notebooks |
| Navigating and Browsing Files in Snowflake Notebooks | [Link](https://github.com/Snowflake-Labs/snowflake-demo-notebooks/blob/main/Navigating%20and%20Browsing%20Files/Navigating%20and%20Browsing%20Files.ipynb) | - | Using Notebooks |
| How to Ingest JSON Data from Public Endpoint | [Link](https://github.com/Snowflake-Labs/snowflake-demo-notebooks/blob/main/Ingest%20Public%20JSON/Ingest%20Public%20JSON.ipynb) | - | Data Science |
| How to load CSV files from S3 stage | [Link](https://github.com/Snowflake-Labs/snowflake-demo-notebooks/blob/main/Load%20CSV%20from%20S3/Load%20CSV%20from%20S3.ipynb) | - | Data Science |
| Access External Endpoints | [Link](https://github.com/Snowflake-Labs/snowflake-demo-notebooks/blob/main/Access%20External%20Endpoints/Access%20External%20Endpoints.ipynb) | - | Using Notebooks |
| Getting Started with Snowflake Cortex ML-Based Functions | [Link](https://github.com/Snowflake-Labs/snowflake-demo-notebooks/blob/main/Getting%20Started%20with%20Snowflake%20Cortex%20ML-Based%20Functions/Getting%20Started%20with%20Snowflake%20Cortex%20ML-Based%20Functions.ipynb) | - | ML, SQL |

## Load demo notebooks to Snowflake

The notebook files are available for download as `.ipynb` files. To load the demo notebooks into your Snowflake Notebook, follow these steps: 

1. On Github, click into each folder containing the tutorial and the corresponding `.ipynb file`, such as [this](https://github.com/Snowflake-Labs/notebook-demo/blob/main/My%20First%20Notebook%20Project/My%20First%20Notebook%20Project.ipynb). Download the file by clicking on the `Download raw file` from the top right.

2. Go to the Snowflake web interface, [Snowsight](https://app.snowflake.com), on your browser.

3. Navigate to `Project` > `Notebooks` from the left menu bar. 

3. Import the .ipynb file you've download into your Snowflake Notebook by using the `Import from .ipynb` button located on the top right of the Notebooks page.

4. Select the file from your local directory and press `Open`.

5. A `Create Notebook` dialog will show up. Select a database, schema, and warehouse for the Notebook and click `Create`.

## Resources

Here are some resources to learn more about Snowflake Notebooks:

* [Documentation](https://docs.snowflake.com/LIMITEDACCESS/snowsight-notebooks/ui-snowsight-notebooks-about)
* [YouTube Playlist](https://www.youtube.com/playlist?list=PLavJpcg8cl1Efw8x_fBKmfA2AMwjUaeBI)
* [Solution Center](https://developers.snowflake.com/solutions/?_sft_technology=notebooks)

## License

All code and notebooks included in this repo is available with an Apache 2.0 license.

## Other links

* Interested in developing and running interactive Streamlit apps in Snowflake? Check out the [Streamlit in Snowflake Demo Repo](https://github.com/Snowflake-Labs/snowflake-demo-streamlit/) to learn more!
