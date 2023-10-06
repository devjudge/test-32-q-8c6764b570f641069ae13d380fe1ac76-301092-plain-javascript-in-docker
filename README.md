# plain-javascript-in-docker
JavaScript + HTML to render Hello Page 


IMPORTANT NOTES:

    1. The backend endpoint host url can be accessed using "API_URL" property (mentioned in env.js). An example is shown in index.js.
    2. PLEASE USE THIS PROPERTY ("API_URL") WHEN YOU ARE TRYING TO CALL A BACKEND API. 
    3. When testing in your local environment, please change API_URL to http://localhost:8080.
    4. Before committing your solution, ENSURE THAT YOU CHANGE THE API_URL TO 'http://restapi:8080' ELSE YOUR SUBMISSION WILL NOT BE SCORED.
    5. Also, ensure that env.js must be the first file that must be loaded so that API_URL is accessible in subsequent files.

PROJECT START STEPS:

    Pre-requisites:
    1. Install http-server module (https://www.npmjs.com/package/http-server).

    Steps:
    1. To run this application, do the following:
        1.a. Go to the project root directory.
        1.b. Run the following command(s) in the terminal/command line:    
            - http-server ./ -p 4200 -a 0.0.0.0
    
CLOUD-IDE SETUP STEPS(follow the below steps in case you are using the Cloud IDE instead of your Local IDE):

    1. Please run the below commands from the project root in a separate terminal to setup live run support in Cloud IDE:
        - chmod 0755 ./chrome-test-setup.sh
        - sh ./chrome-test-setup.sh
    2. Make the port 9515 public
