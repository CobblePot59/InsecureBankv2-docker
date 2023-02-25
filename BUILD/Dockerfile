FROM python:2.7.18

# Set the working directory
WORKDIR /opt/AndroLabServer 

# Copy the Python requirements file
COPY AndroLabServer /opt/AndroLabServer

# Install Python packages
RUN python2.7 -m pip install --no-cache-dir --upgrade pip && \
    python2.7 -m pip install --no-cache-dir flask sqlalchemy simplejson web.py

# Expose the application port
EXPOSE 8888

# Start the application
CMD ["python2.7", "app.py"]
