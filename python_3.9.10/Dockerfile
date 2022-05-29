FROM python:3.9.10

# Setting up structure
COPY . /home/metrograph

# Dependencies Installation
WORKDIR /home/metrograph/action
RUN pip install --no-cache-dir -r requirements.txt

# Running Action
ENTRYPOINT ["python", "gateway.py"]