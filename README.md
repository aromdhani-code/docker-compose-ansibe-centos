 ansible-playbook playbook.yml -e python_version=${Maven} -e docker_version=${NodeJs} -e docker_compose_version=${SonarScanner}  -e target_slave=${targethost} -i hosts -u jenkins"
