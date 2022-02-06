#Group-Hub Meeting Room Implementation
Technologies used are HTML, CSS, JavaScript and the Agora SDK

# Installation
1. Download/Clone the Group-Hub project on github.
2. Register an account on agora.io and get the APP ID, Temporary Token and Channel Name values
3. Update APP ID, Temporary Token and Channel Name values in script.js

#Running the project
1. Ensure python3 is installed in your system
2. Ensure ngrok is running on your system. This is used to provide a public web address for your localhost url.
2. Navigate to project folder in your command terminal.
3. Start HTTP server with this command -  python3 -m http.server. This will start running the localhost server.
4. Open another new terminal window.
5. In the new terminal window run this command - ngrok http http://localhost:'port on which localhost is running'.
6. Copy paste the URL that ngrok generates onto the browser and your good to go.
