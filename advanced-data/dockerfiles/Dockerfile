# Describe the steps necessary to turn [app in current folder] into an image

# What is this image based on?
FROM python:latest

# Put necessary files on the image
COPY requirements.txt .
RUN pip install -r requirements.txt

COPY main.py .

# When a container runs based on this image, what should it do?
CMD ["python", "main.py"]
