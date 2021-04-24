***Activate the virtual environment**

'''
source blockchain-env/Scripts/activate
'''

**Install all packages**
'''
pip install -r requirement.txt
'''

**Run the tests**

make sure to activate the virtual environment.
'''
python -m pytest backend/tests
'''

**Run the application and API**
make sure to activate the virtual environment.

'''
python -m backend.app
'''

**Run a peer instance**

Make sure to activate the virtual environment

'''
export PEER=True && python -m backend.app
'''


**Seed the backend with data**

Make sure to activate the virtual environment.
'''
export SEED_DATA=True && python -m backend.app
'''