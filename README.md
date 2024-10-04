## PROJECT SOLUTION
## Author
Vibha Gupta

# Clone the Repository
git clone https://github.com/vibha45/Crisp-API-Collection  &nbsp;&nbsp;                   #   Repository URL <br/>
cd "Crisp-API-Collection"                           &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;       # Repository name
# Install the dependencies
npm install newman<br/>
npm install newman-html-extra
# Run the newman tests:
newman run CrispAPI.postman_collection.json 
-d testdata.csv
-e UAT-ENV.postman_environment.json
-r cli,htmlextra 


