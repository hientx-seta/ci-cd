# Info about CI/CD

## Azure DevOps - Giới Thiệu Về CI CD 
https://www.youtube.com/watch?v=4SmtlSL5vGA&list=PL80CNtS5d8_yTKlngum6k1nCPWmmB9-BE

## Azure Key Concept pipline

https://learn.microsoft.com/en-us/azure/devops/pipelines/get-started/key-pipelines-concepts?view=azure-devops

- Azure DevOps - Tạo Build Pipeline 

https://www.youtube.com/watch?v=MXSsVg4IhOE&list=PL80CNtS5d8_yTKlngum6k1nCPWmmB9-BE&index=3


## Google Cloud

- Compute with Google Kubernetes Engine
https://www.youtube.com/watch?v=5-9Zdxp0GT0&list=PLIivdWyY5sqJOQJCXW_aYEqwfyi6bu1gC&index=5

- Sample code
https://github.com/GoogleCloudPlatform/microservices-demo

### CI/CD on Google Cloud

https://www.youtube.com/watch?v=orZEBSXbmFU&list=PLIivdWyY5sqJOQJCXW_aYEqwfyi6bu1gC&index=9

- DevOps capabilities
  
https://cloud.google.com/architecture/devops?utm_source=youtube&utm_medium=unpaidsoc&utm_campaign=CDR_ret_gcp_orzebsxbmfu_GCPStartupGuides_012522&utm_content=description

- Quick start

https://cloud.google.com/deploy/docs/deploy-app-gke?utm_source=youtube&utm_medium=unpaidsoc&utm_campaign=CDR_ret_gcp_orzebsxbmfu_GCPStartupGuides_012522&utm_content=description

## Deploy Android app with firebase and app tester

https://firebase.google.com/codelabs/appdistribution-app-bundles#3

    android {

       // ...

       buildTypes {
            getByName("release") {
                firebaseAppDistribution {
                  appId = "yourAppId"
                  artifactType = "AAB"
                  testers = "ali@example.com, bri@example.com, cal@example.com"
                }
            }
        }

        // ...
    }
```
./gradlew :base:bundleRelease

export FIREBASE_TOKEN=your_firebase_token

./gradlew --stop // Only needed for environment variable changes

./gradlew bundleRelease appDistributionUploadRelease

```

## Android CI/CD with Github

https://blog.zelarsoft.com/ci-cd-for-android-using-github-actions-dbea47cad9b4
