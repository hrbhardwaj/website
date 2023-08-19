# website

In this project I used these tools:

* Git and github
* Ansible
* Docker
* Jenkins

Step1 : launch three machine one master and two slave 
<img width="525" alt="image" src="https://github.com/hrbhardwaj/website/assets/131919525/2b0a2dec-d6d0-4336-84c6-a63d8723b01f">

Step2 : Make ansible connection between master & slaves
<img width="468" alt="image" src="https://github.com/hrbhardwaj/website/assets/131919525/7bbc3793-70fe-4970-846f-82e52ea7c3bd">

Step3 : Create a Ansible playbook to install software in machine. 
<img width="283" alt="image" src="https://github.com/hrbhardwaj/website/assets/131919525/41164f2e-eb86-4ff8-a139-cf7d8033663b">

Step4 : Create a Docker File and push to repository github
<img width="376" alt="image" src="https://github.com/hrbhardwaj/website/assets/131919525/99227931-5db9-43fc-bada-010aafbfee5d">

Step5: Go to Jenkins and create connection between nodes and Jenkins master for running the job on slaves .
<img width="468" alt="image" src="https://github.com/hrbhardwaj/website/assets/131919525/abab9dcf-7845-4628-aabe-8ec50bc0ce48">

Step6 : Create a Job1 on test machine to fetch the code from the develop branch of repo. And deploy the website on container through Jenkins pipeline                      
<img width="338" alt="image" src="https://github.com/hrbhardwaj/website/assets/131919525/c628af0c-e8bc-4426-aa8f-54497f496883">

Step7 : Create a job2 on same test machine but from master branch and deploy through docker file on container 
Step8 : Create a job 3 on prod machine 
<img width="468" alt="image" src="https://github.com/hrbhardwaj/website/assets/131919525/9735859a-c1f2-4f8f-ab92-46930c498d55">

Step9 : Check you website is running fine .
<img width="468" alt="image" src="https://github.com/hrbhardwaj/website/assets/131919525/1defaeea-9157-404a-83f3-99fe0f6db3b6">


Congratulation !! Now If you will push a file on github it will automatically fetch.











