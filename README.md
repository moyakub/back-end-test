## Tech Stack Used ##
- Python, Pytest
- JSON, REST APIs

## Initial Installation ##

1. Make sure you have python3 and pip installed on your machine. 
    1. python3 --version
    2. pip --version
2. Downlaod the folder   
3. Run `python3 -m venv <virtual env folder name>` to start a virtual environment inside project folder.
4. Run `source <virtual env folder name>/bin/activate` to activate virtual environment
5. You should see (venv) in the termial which proves that virtual env is activated successfully.
6. Run `pip install -r requirements.txt` 



### To Run Pytest ###
1. Confiqure secret files - `.env` and `tests/packages/config_shop_environment.py`
2. Run `pytest`


### New Store Setup When Existing Store Expires ###
1. Crete a new store
2. Creat a new V2/V3 API Token inside the store.
3. update `STORE_HASH` and `TOKEN` environment variable
4. Done
