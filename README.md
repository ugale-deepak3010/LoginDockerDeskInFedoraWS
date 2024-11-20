# LoginDockerDeskInFedoraWS
LoginDockerDeskInFedoraWS

### How to Login Docker Desktop In Linux Machine / Fedora Work Station?

1.  Install Docker desktop in Laptop/PC.
2.  Open Terminal
Type this command
`$ gpg --generate-key`

![image](https://github.com/user-attachments/assets/72a8f8d3-147d-461e-baa7-99c318abca56)

3. Now provide Name

- [ ] example "DeeepakDocker"
- [ ] email: "u********@*mail.c**"

4. Now press `O`
5. Pop up will come & Enter the same password in both box 
6. click ok so that will generate `pub key`

![image](https://github.com/user-attachments/assets/748c346a-a302-45f7-9147-4fe724c6051a)

7. Copy pub key
8. Open new terminal 
Type this command
`pass init ` and paste pub key

9. Try docker login using

`docker login -u your_username -p your_docker_password`
![image](https://github.com/user-attachments/assets/c5231b4a-8de9-4055-9e86-9415f65ad375)

10. Done Docker will logged in




