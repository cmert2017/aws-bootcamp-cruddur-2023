FROM node:16.18

ENV PORT=3000
# Set the command to be executed as a variable
ENV COMMAND_TO_RUN "npm start"

COPY . /frontend-react-js
# Copy the script that will run the command
COPY run-frontend.sh /usr/local/bin/run-frontend.sh
WORKDIR /frontend-react-js
RUN npm install
# Make the script executable
RUN chmod +x /usr/local/bin/run-frontend.sh
EXPOSE ${PORT}

# Set the script as the entrypoint
ENTRYPOINT ["/usr/local/bin/run-frontend.sh"]
#CMD ["npm", "start"]









