# uds
ubuntu-docker-staticsite

1.Add user info and IP address to hosts.ini
2.Execute the ansible playbook with:
ansible-playbook --ask-pass --become --ask-become-pass -i hosts.ini setup_docker_compose.yml
For authentication private/public key can be also used 
3. Test on port 80 using curl

Resources used: 
-https://github.com/nishanttotla/DockerStaticSite
-https://phoenixnap.com/kb/letsencrypt-docker