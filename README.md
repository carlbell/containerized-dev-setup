# containerized-dev-setup
## Prerequisites
- Docker Desktop
- VSCode with the Dev Containers extension `ms-vscode-remote.remote-containers`
- Git
## nginx static site development
1. Clone `https://github.com/carlbell/nginx-static-site-starter`
2. Open the directory in VSCode
3. If you See the Dev Containers pop up in the bottom right that has a `Reopen in Container` option click that. Otherwise, open the VSCode command prompt with cntrl-shift-p and search and run `Dev Containers: Reopen in Container`
4. The workspace should open with the following directory structure.
![image](https://github.com/user-attachments/assets/10474062-8dca-4e4b-be3e-7ad632416875)
6. You should be able to see the `nginx-static-site-starter` container in your Docker Desktop
![image](https://github.com/user-attachments/assets/04de9b0b-11ce-454e-996a-0dda4c8d2007)
8. You should be able to see the Hello, World! page by going to `http://localhost:8080/` in your browser.
![image](https://github.com/user-attachments/assets/cfb9899c-b28c-4b73-a0d0-ad55ffd619ee)
