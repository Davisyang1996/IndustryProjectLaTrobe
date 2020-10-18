# IndustryProjectLaTrobe

# Discovery Engine

A react app for identifying objects from an image and searching image tags using AWS. Upload Image from react UI. The image will be sent to API Gateway where it triggers the Lambda Function to store it in S3 Bucket. The stored image is sent to Amazon Recognition which will identify objects from the image, the image details will then be stored in RDS server.

# High level architecture diagram 
diagram.jpg

# Terminal Commands to set up: 

cd frontend
npm install 

# To run the program:
npm start (make sure you're in frontend directory)

OR

Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

# Backend
All backend codes are deployed to Davis Yang's personal AWS Manaagement Console. A copy of the codes are provided in the backend folder.

