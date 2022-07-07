FROM node

WORKDIR /mysampleangularapp

COPY . .
RUN npm install -g http-server

EXPOSE 3580
CMD ["http-server", "--port", "3580"]



