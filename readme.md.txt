DOCUMENTATION

HOW TO GET UPCOMING EVENTS :
1)This application works on the google calendar API.
2)You need to sign in first using your google account,make sure you have all events in that google calendar which you used to sign in
3)for security reaons google asks you for unnsafe proceed
4)After that you get a secret key or token, you need to copy this token in clipboard and come to the homepage in previous tab
5)paste the token in the given input and click to get events
6)It redirects you the page where you just need to click the button and you get your all upcing 10 events
7)Finish!

HOW TO CREATE EVENT:
1)first you need to set up following
  a)make a config folder in the root directory and inside it make a 'dev.env' file in it.
  b)It must contain 4 env variables as:
      SENDGRID_API_KEY=your sendgrid api key
      CLIENT_ID=your google api client id
      CLIENT_SECRET=your google client secret
      REFRESH_TOKEN=your developer refresh token
2)After this you are now authanticated to send email and create events through your application


YOU NEED FOLLOWING MODULES TO INSTALL IN YOUR APLLICATION
1)express
2)sendgrid

start your app using :
npm run dev