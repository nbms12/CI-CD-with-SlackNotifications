pluggin : slack notification 

create slack account 

1. create channel ( project /prod team )

2. create slack app


   enable and copy webhook url 

   <img width="810" height="271" alt="image" src="https://github.com/user-attachments/assets/12e83c71-7e31-4bea-b2b8-cf0ff929d6d9" />


  create oath token and create a cred in jenkins 

  <img width="680" height="250" alt="image" src="https://github.com/user-attachments/assets/20aa0313-7f6a-4855-af5d-0e397ad557ab" />


  add custom scopes of slack to permissions 

  <img width="664" height="572" alt="image" src="https://github.com/user-attachments/assets/27b77a18-182b-43f3-9c1e-8e4ed89db675" />

  Re -install the workspace 



3. configure jenkins

     ( system config ) 

   <img width="1123" height="523" alt="image" src="https://github.com/user-attachments/assets/0db69628-6f75-4c7d-bd7f-36bb7d6c3f5f" />

    ( add credentail )

   create cred using slack webhook URL . URL becomes secret text


4. Build


   <img width="552" height="264" alt="image" src="https://github.com/user-attachments/assets/9bfbd3fd-ff6e-4eeb-8b52-44d7426cde5f" />

  <img width="511" height="231" alt="image" src="https://github.com/user-attachments/assets/56ae12ea-4b6f-4ee7-9fd9-6540326e0fea" />


    
