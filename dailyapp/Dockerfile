FROM python:3.9-alpine
RUN mkdir dailyapp
RUN cd dailyapp
Add requirements.txt /dailyapp
WORKDIR /dailyapp
RUN pip install -r requirements.txt
RUN mkdir DailyApp
Add DailyApp /dailyapp/DailyApp
WORKDIR /dailyapp/DailyApp
CMD ["python","transfer.py"]
