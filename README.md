# Mongo_Express_WebApp_Deployment
Deployment of Mongo_Express WebApp using Kubernetes and using MongoDB as database.
 1. Create a Secret.yaml to provide credentials for your database.
    - Do not push secret to github repo as it contains credentials.
 2. Create a ConfigMap to provide the url of our mongoDB service which we create later.
 3. Create a Deployment manifest to deploy the MongoDB image.
 4. Create a Service manifest to expose the MongoDB.
 5. Craete a Deployment manifest to deploy the image of the Mongo-Express webapp.
 6. Create a Service manifest to expose our webapp to outer world.
 7. Now apply all the manifest using the kubectl command.
    - kubectl apply -f < manifest-name >
 8. Now run our webapp using the below command.
    - minikube service < service-name >
 9. Now we can see our webapp on browser.

   ![image](https://github.com/user-attachments/assets/fe3244b2-ad4b-4717-b775-7a7ddbb1e43d)


