<h2>REST API</h2>

<p>Instructions on how to download the source files and use the App: </p>

<h3>Terminal (Chosen directory to clone the files - Recommended --> Desktop)</h3>

- git clone https://github.com/KyoukanPT/REST-API.git

<hr>

<h3>Node Installation</h3>
 
- Download and install <a href="https://nodejs.org/en/download"> Node.js </a> <br>

<hr>

<h3>API Documentation</h3>
<a href="https://secrets-api.appbrewery.com/"> Secrets API Documentation </a> <br>

<hr>

<h3>Project Folder Directory (Terminal)</h3>
- npm install <br>
- npm install <a href="https://expressjs.com/en/starter/installing.html"> Express </a> <br>
- npm install <a href="https://ejs.co/"> EJS </a> <br>
- npm install <a href="https://axios-http.com/docs/intro"> Axios </a> <br>
- npm install <a href="https://www.npmjs.com/package/body-parser"> Body Parser </a> <br>

<hr>

<h3>Setup before using the App</h3>
<h4> For the following steps, you'll need to use <a href="https://www.postman.com/downloads/"> Postman </a> for API testing. </h4>
<p> - Register your user with a username and password (Check API documentation). </p>
<p> - Generate a Bearer Token (Check API documentation). </p>
<p> - After doing all the above steps, replace the placeholder value on line 9.  </p>
<p> - Start your server with the following command on your terminal: <b>node index.js</b> .</p>

<hr>

<h3>How to use the App?</h3>
<p> - After running the app with Node, go to <a href="http://localhost:3000/">Localhost</a>. </p>
<p> - Testing "GET" > Fill in the <b>Id</b> and click on the "GET" button to generate the respective secret. </p>
<p> - Testing "POST" > Fill in the <b>Secret</b>, the <b>Score</b> and click on the "POST" button to generate a new secret. </p>
<p> - Testing "PUT" > Fill in the <b>Id</b>. Then, you have the option to fill in the <b>Secret</b> and/or the <b>Score</b>. "PUT" will fully replace the edited <b>Id</b>. Which means that if you don't fill the <b>Secret</b> or <b>Score</b>, it won't be saved in the API. Don't forget to click on the "PUT" button to replace the data from the selected <b>Id</b>.</p>
<p> - Testing "PATCH" > Fill in the <b>Id</b>. Then, you have the option to fill in the <b>Secret</b> and/or the <b>Score</b>. The non-updated option(s) will be returned with the already saved data from the API. The updated option(s), will update the data from the API. Don't forget to click on the "PATCH" button to update the selected <b>Id</b>.</p>
<p> - Testing "DELETE" > Fill in the <b>Id</b> and click on the "DELETE" button to delete everything from the selected <b>Id</b></p>
