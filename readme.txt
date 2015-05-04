 
For simplicity  , i deployed this demo on 

		http://narengcal.site88.net



Source code can be found here:  https://github.com/narengcal/gcalender.git


 1) This application is hard coded for the following account.
  username:  narengcal@gmail.com
  password:  mobiquitydemo

 2) Hard coded CLIENT_ID in js/angular/g_calender_service.js file. Modify this file with your own client id, if you want that to work with
  another gmail account. Below are the instructions from google how to create client id.

  https://developers.google.com/google-apps/calendar/quickstart/js

 3) You can deploy this code on your webservers like apache..etc. Currently this application client id allows the following js origins
     http://narengcal.site88.net
     http://localhost:8888
     htt://localhost

     Note: i can enable your port number if your webserver is running on different port, please email me at narendar.fewd@gmail.com




  STEPS to test this application:

  1) once you go to http://narengcal.site.net , it will show your authroize button.
  2) click on authorize button and login with the following account
  		username:  narengcal@gmail.com
        password:  mobiquitydemo
  3) Select date from the date input tag. If there are any events on selected date it will show those events on third div section.
  4) you can also create events on particular date by entering event description.


  Note:  currently this application is not using Exact event time 



