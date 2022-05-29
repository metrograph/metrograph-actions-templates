FROM python:3.9.10

# Setting up structure
COPY . /home/metrograph

# Dependencies Installation
WORKDIR /home/metrograph
RUN pip install --no-cache-dir -r /home/metrograph/action/requirements.txt

# ENV Configuration
ENV PYTHONDONTWRITEBYTECODE=1

# Running Action
ENTRYPOINT ["python", "/home/metrograph/gateway.py"]