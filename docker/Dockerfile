FROM python:3.10-slim

WORKDIR /
COPY src/requirements.txt /requirements.txt
RUN pip install -r requirements.txt
COPY src/rp_handler.py /

# Start the container
CMD ["python3", "-u", "rp_handler.py"]