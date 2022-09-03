# gcp_cloud

https://cloud.google.com/sdk/docs/install

Steps 'gcloud CLI' installation for MAC M1:
- down load 'google-cloud-cli-400.0.0-darwin-arm.tar.gz'
- connect the gcloud folder location like 'cd Desktop/ '
- ./google-cloud-sdk/install.sh 'run this command'
- do you want to help improve the google cloud sdk: N
- Do you want to continue: Y
- Enter a path to an rc file to update: 'same path' to 'same path'
- ./google-cloud-sdk/bin/gcloud init
- would you like to login: Y
- gcloud app browse 'to show the browser'
-brew install --cask google-cloud-sdk "install google-cloud-sdk file in my local folder"


* Below commnad importand for any project:

gcloud init
gcloud app browse --project=movie-recommendation-361414
gcloud app deploy app.yaml --project movie-recommendation-361414
