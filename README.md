###                                             The Microservice architecture is designed as follows.
#####   		 						--						The purpose of this application is to sell books online. </br> </br>
<img width="683" alt="Ekran Resmi 2021-09-01 13 51 22" src="https://user-images.githubusercontent.com/8803806/131659579-72bad589-a7c7-42f1-a263-43a1734567d0.png"></br>
**Firstly you need to install docker in your computer. After that you need to follow steps below.**</br>

  1-  Download docker-compose file from this repository. </br>
  2-  Open your terminal than write 'docker-compose up' to run applications. (It may take some time.) </br>
  3-  Than you can reach swagger over this link. http://localhost:8000/swagger-ui/ </br>
  4-  You can select application from right-top. </br>
  5-  Firstly you must select auth applicaiton to call login service . You can send any string than get a token from login service. </br>
  6-  When you get a token, You can authorize one time then call all services.</br>
  7-  Select one of the application from top-right on the swagger-ui interface.</br>
  8-  Press the authorize button which is appears like below.</br> </br>
                  	     <img width="269" alt="Ekran Resmi 2021-09-01 16 13 28" src="https://user-images.githubusercontent.com/8803806/131677636-f5c32ebe-49a8-45b9-a957-1a5bd54659e9.png">
  </br>
  9-  Enter token for input field. Than press the authorize button and close the window.</br> </br>
  <img width="896" alt="Ekran Resmi 2021-09-01 16 13 52" src="https://user-images.githubusercontent.com/8803806/131678029-0335666f-3d1e-497e-8625-09f9dfe5ffd2.png"></br>
  10- Now you can call what services you want. </br>
  11- I populated dummy data for all services.

