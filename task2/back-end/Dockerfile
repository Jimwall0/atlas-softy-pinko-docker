FROM python:3.10-slim
WORKDIR /app
RUN apt-get update && apt-get upgrade -y
RUN pip install flask
COPY api.py .
EXPOSE 5252
CMD ["python3", "api.py"]