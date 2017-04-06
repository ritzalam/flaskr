Setup virtual environment

virtualenv env
. env/bin/activate

deactivate

Install dependencies
pip install --editable .

pip freeze > requirements.txt
pip install -r requirements.txt

To run:

export FLASK_APP=flaskr
export FLASK_DEBUG=true
flask run --host=192.168.23.19
