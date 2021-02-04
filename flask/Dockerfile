FROM python:3.9-alpine
RUN mkdir dailyapp
RUN cd dailyapp
Add requirements.txt /dailyapp
WORKDIR /dailyapp
RUN pip install -r requirements.txt
RUN mkdir TransferApp
Add TransferApp /dailyapp/TransferApp
WORKDIR /dailyapp/TransferApp
CMD ["python","transfer.py"]
