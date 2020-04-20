
   docker build -t hello_gitops:1.1 .
   docker tag hello_gitops:1.1 ahmedmmoussa/hello_gitops:1.1
   docker push ahmedmmoussa/hello_gitops:1.1
docker login --username=ahmedmmoussa  
A7medmou4sa
   ---------------------------------------

   Creating encrypted secrets
On GitHub, navigate to the main page of the repository.
Under your repository name, click Settings.
In the left sidebar, click Secrets.
Type a name for your secret in the "Name" input box.
Type the value for your secret.
Click Add secret.

--------------------------------