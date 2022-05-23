 This project setup Docker and Docker compose and Deploy any application on target server using Ansible
 The Apllication is running in Docker
 - install Docker
 - install Docker Compose 
 - install dependencies used by the application to run  
 - run The application
 
`ansible-playbook playbook.yml -e python_version=${Maven} -e docker_version=${NodeJs} -e docker_compose_version=${SonarScanner}  -e target_slave=${targethost} -i hosts -u jenkins"`
