# Sweeger

Sweeger is an open-sourced solution that allows you to become a better software engineer by ensuring you stay up-do-date with your favorite programming languages, frameworks and libraries, but also find new content that we feel you may be interested in! You will receive email feeds with new content (including articles, videos, etc.) related to your topics of choice

# Setup

(NOTE: We are having issues running Sweeger on Linux, we are looking into this. Sweeger currently works on Windows and Mac OS)

To get started with Sweeger, navigate to the `/run` directory of the project. Depending on if you are using a Windows- or Unix-based machine, run either `windows.bat` or `unix.sh`. If asked to open a port other than port 3000, enter 'y'. This should start Sweeger in your browser:

![Login](https://github.com/AnshG714/sweeger/blob/master/rsc/login.png?raw=true)

To create an account, click "Sign Up" in the top right corner of the screen. This will take you to the "Sign Up" page (see below), where you can enter an email and password for your account. Secure email authentication is achieved using Firebase.

![Sign Up](https://github.com/AnshG714/sweeger/blob/master/rsc/signup.png?raw=true)

When you click "Sign Up," you will be informed that your email has not been verified yet. Open the inbox of the email you used to register. You should have received an email from Sweeger. Follow the link in that email to register.)

![Verify Email](https://github.com/AnshG714/sweeger/blob/master/rsc/verify_email.PNG?raw=true)

Now, *refresh* the page, where you should see the home screen:

![Home](https://github.com/AnshG714/sweeger/blob/master/rsc/home.png?raw=true)

Here, you can enter a list of topics you would like to receive content for. Enter your desired content in a comma-separated list (e.g. "C++,Java,Python"). Finally, click "Find articles." This will trigger a web scraper which will search various websites for content related to your desired topics. It will take a few minutes for the scraper to finish, but within 3-5 minutes, you should receive an email containing a list of useful resources!:

![Emailed Content](https://github.com/AnshG714/sweeger/blob/master/rsc/email.png?raw=true)

# Flowchart

![flowchart](https://github.com/AnshG714/sweeger/blob/master/rsc/flowchart.png?raw=true)
