# Use Python Image
FROM python:3.7
# Install apt dependencies
 
# Copy contents into image
COPY . .
# Run pip dependencies
RUN pip install flask 
# Expose the correct port
EXPOSE 5000
# Create an entrypoint
ENTRYPOINT ["python", "app.py"]
