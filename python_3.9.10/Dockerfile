FROM python:3.9.10

# Setting up structure
WORKDIR /home/metrograph
COPY . /home/metrograph

# Dependencies Installation
RUN pip install --no-cache-dir -r action/requirements.txt

# Running Action
ENTRYPOINT ["python", "gateway.py"]