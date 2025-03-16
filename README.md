## Solution for MLOps zoomcamp course

### Environment management
- Create a virtual environment: `python3.12 -m venv env_mlops_zoomcamp_solution`
- Activating python virtual environment: `source env_mlops_zoomcamp_solution/bin/activate`
- Extract library lists: `pip freeze > requirements.txt`
- Install necessary libraries: `pip install -r requirements.txt`
- Installed packages: 
    - pip install mlflow==2.19.0

### Deleting Python
#### The version of Python that you want to delete
- `python_version_number=3.10`
- `sudo rm -rf /Library/Frameworks/Python.framework/Versions/${python_version_number}/`
- `sudo rm -rf "/Applications/Python ${python_version_number}/"`
- `cd /usr/local/bin && ls -l | grep "/Library/Frameworks/Python.framework/Versions/${python_version_number}" | awk '{print $9}' | sudo xargs rm`


### Code execution
- Execute a python script: `python <python_script>`
- Run Jupyter notebook: `jupyter notebook`


### Essential documents
- MLOps Zoomcamp [Repo link](https://github.com/DataTalksClub/mlops-zoomcamp/tree/main)
- Learnings from MLOps Zoomcamp [Doc link](https://docs.google.com/document/d/1437MvdABVBOh9HRQB3thOg3pKjkYzK1XjiUHtE0Vp1g/edit?tab=t.0#heading=h.nz4m1i7zq94x)


### Other links:
- The data set [Link](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
    - 2021-01 [dataset](https://d37ci6vzurychx.cloudfront.net/trip-data/green_tripdata_2021-01.parquet)
    - 2021-02 [dataset](https://d37ci6vzurychx.cloudfront.net/trip-data/green_tripdata_2021-02.parquet)
    - 2021-03 [dataset](https://d37ci6vzurychx.cloudfront.net/trip-data/green_tripdata_2021-03.parquet)