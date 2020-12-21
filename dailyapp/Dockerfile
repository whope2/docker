FROM python:3.9-alpine
WORKDIR /dailyapp
Add . /dailyapp
RUN pip install -r requirements.txt
WORKDIR /dailyapp/TransferApp
CMD ["python","transfer.py"]
