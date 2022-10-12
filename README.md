Steps 

1.Clone the repo 
 git clone https://github.com/argadepp/Kubernetes.git
 
2. Fetch all branchecs 
 git fetch --all

3. Checkout to the dev branch 
 git checkout dev

4. Go to the helm\helloworld folder 
 cd helm/helloworld

5. Change the values of parameters like resources in values file as per requirnment and install the env vise chart 
  helm install prod . --values values-prod.yaml 
  helm install dev . --values values-dev.yaml
  helm install qa . --values values-qa.yaml
