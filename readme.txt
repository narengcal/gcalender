 
For simplicity  , i deployed this demo on 

		http://narengcal.site88.net



Source code can be found here:  https://github.com/narengcal/gcalender.git




  STEPS to test this application:

  1)  go to http://narengcal.site.net if this still works :), or checkout code from https://github.com/narengcal/gcalender.git and deploy to local webserver, once the page loads , it will show you authroize button.

  2) click on authorize button and login with the following account or your own gmail account
  		username:  narengcal@gmail.com
        password:  mobiquitydemo

  3) Select date from the date input tag. If there are any events on selected date it will show those events on third div section.

  4) you can also create events on particular date by entering event description.


  Note:  currently this application is not using Exact event time 

  



  Some other notes how to deploy or which ports this application allows.


 1) Hard coded CLIENT_ID in js/angular/g_calender_service.js file. Modify this file with your own client id, if you want that to work with
  another google api client account. Below are the instructions from google how to create client id.

  https://developers.google.com/google-apps/calendar/quickstart/js

 2) You can deploy this code on your webservers like apache..etc. Currently this application client id allows the following js origins
     http://narengcal.site88.net
     http://localhost:8888
     htt://localhost

     Note: i can enable your port number if your webserver is running on different port, please email me at narendar.fewd@gmail.com



