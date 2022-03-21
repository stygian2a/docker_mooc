# Start from the alpine image that is smaller but no fancy tools
FROM python:3.6

EXPOSE 5000

COPY . .
RUN pip install -r requirements.txt

CMD python app.py



