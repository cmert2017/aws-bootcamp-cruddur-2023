FROM python:3.10-slim-buster

WORKDIR /backend-flask

COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt

COPY . .
# Copy the script that will run the command
COPY run-backend.sh /usr/local/bin/run-backend.sh

# Set the command to be executed as a variable
ENV COMMAND_TO_RUN "python3 -m flask run --host=0.0.0.0 --port=4567"
ENV FLASK_ENV=development

# Make the script executable
RUN chmod +x /usr/local/bin/run-backend.sh


EXPOSE ${PORT}

# Set the script as the entrypoint
ENTRYPOINT ["/usr/local/bin/run-backend.sh"]
#CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0", "--port=4567"]









