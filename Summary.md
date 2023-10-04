# Project on kodecloud Link:
    https://kodekloud.com/courses/gcp-devops-project/

# What will be implemented:
    1-Setting up the project
    2-Budget and alerting
    3-Kubernetes refresher
    4-CI/CD design discussion
    5-Cloud build trigger
    6-Automate docker build
    7-Kubernetes deployment file
    8-Debug and fix cloudbuild error
    9-Upgrade replicas


# To Deploy a GKE using Terraform
    - Tutorial: https://medium.com/cloud-native-daily/provision-gke-cluster-with-terraform-ee787457f3e#id_token=eyJhbGciOiJSUzI1NiIsImtpZCI6ImI5YWM2MDFkMTMxZmQ0ZmZkNTU2ZmYwMzJhYWIxODg4ODBjZGUzYjkiLCJ0eXAiOiJKV1QifQ.eyJpc3MiOiJodHRwczovL2FjY291bnRzLmdvb2dsZS5jb20iLCJhenAiOiIyMTYyOTYwMzU4MzQtazFrNnFlMDYwczJ0cDJhMmphbTRsamRjbXMwMHN0dGcuYXBwcy5nb29nbGV1c2VyY29udGVudC5jb20iLCJhdWQiOiIyMTYyOTYwMzU4MzQtazFrNnFlMDYwczJ0cDJhMmphbTRsamRjbXMwMHN0dGcuYXBwcy5nb29nbGV1c2VyY29udGVudC5jb20iLCJzdWIiOiIxMDc3ODE2NTAyMTI5MDk2NDQzNzgiLCJlbWFpbCI6Im1vaG1kNDZhbGFhQGdtYWlsLmNvbSIsImVtYWlsX3ZlcmlmaWVkIjp0cnVlLCJuYmYiOjE2OTYzMjk0ODAsIm5hbWUiOiJNb2hhbWVkIEFsYWEiLCJwaWN0dXJlIjoiaHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EvQUNnOG9jS0FVcUxfNXZSSndFOEQ1LW9Lak1CcEUzRTM5T3NXMFNVUEI0X1p5X1RPcEtBPXM5Ni1jIiwiZ2l2ZW5fbmFtZSI6Ik1vaGFtZWQiLCJmYW1pbHlfbmFtZSI6IkFsYWEiLCJsb2NhbGUiOiJlbi1HQiIsImlhdCI6MTY5NjMyOTc4MCwiZXhwIjoxNjk2MzMzMzgwLCJqdGkiOiJhMDNkNDEwY2ZhMzMwZGUxZjUyMmY5MDUxNzJhNzZhMGQ5OWYzMGY1In0.p6DpgFIXKr_A6-fKGiiGqxbZGN3xKHxhwiKl_ZW3Xb-xgLWC87so3xNKYI5SyM3kpvO5TDWXiEdVQmdk4S3WNLO15PE3Vu-l6FR8hnhynLt1nK0v4DUQjJaAR4sKaGY0O7PlSKtXnIzYSE8eiDuue2q9KppWHPyFCmhip56p5_jGzrYrztKoF4dNRF1L7ITN3ZGu1CsEcP7tOI2TUJMZSzH-CKPOQVHA2YIGmeuny25VBpdGUwU6BlUWS5kqch6LZpPWwhiLPZAD6eLmbjNPAd6siRlScyuoHp5TSsewCK8aYuC-lvLm5rH0HMmts0LAIV1MjHScHx8Fk2Ds3dREHQ



# Project Details
    1- Create a Github Repo with the application and Dockerfile.
    2- Create a Kubernetes Cluster on GCP (GKE).
    3- Connect the Github Repo to the Cloud Build CICD Service on GCP.
    4- Create the build steps to "cloudbuild.yaml" File.
          4.1- Build the Docker Image using docker build command.
          4.2- Push this Image to Google Container Registry (gcr).
    5- 