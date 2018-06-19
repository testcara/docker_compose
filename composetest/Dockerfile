FROM python:3.4-alpine
# add the current dir to image /code dir
ADD . /code
# set(change) workdir to the image /code
WORKDIR /code
# under the /code dir, run the commands
RUN pip install -r requirements.txt
# run the commands as default
CMD ["python", "app.py"]
