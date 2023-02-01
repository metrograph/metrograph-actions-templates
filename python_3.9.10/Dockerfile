FROM python:3.8.0

# Setting up structure
COPY . /home/metrograph

# Dependencies Installation
WORKDIR /home/metrograph
RUN pip install --no-cache-dir -r /home/metrograph/action/requirements.txt

# ENV Configuration
ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONPATH /home/metrograph

# Running Action
ENTRYPOINT ["python", "gateway.py"]
