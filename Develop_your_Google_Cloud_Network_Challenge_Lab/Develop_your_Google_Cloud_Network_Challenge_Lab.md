# Develop your Google Cloud Network: Challenge Lab || [GSP321](https://www.cloudskillsboost.google/focuses/10603?parent=catalog) ||

### Run the following Commands in CloudShell

```
export ZONE=
```

```
curl -LO raw.githubusercontent.com/QUICK-GCP-LAB/2-Minutes-Labs-Solutions/main/Develop%20your%20Google%20Cloud%20Network%20Challenge%20Lab/gsp321.sh

curl -LO raw.githubusercontent.com/Develop_your_Google_Cloud_Network_Challenge_Lab/gsp321.sh

sudo chmod +x gsp321.sh

./gsp321.sh
```

### Task 8. Enable monitoring

1. Go to [Services and Ingress](https://console.cloud.google.com/kubernetes/discovery)
2. Copy `endpoint's`(wordpress) `IP address`. Look at picture below: (34.30.27.240)
   ![alt text](image.png)
3. Then go to -> [Uptime Checks](https://console.cloud.google.com/monitoring/uptime) -> `+ CREATE UPTIME CHECK`.
4. Fill in the details as provided below :

- Hostname : `endpoint's IP address` (without http and port number)
- Path : `/`
  ![alt text](image-2.png)
- Title: `Wordpress Uptime`
  ![alt text](image-1.png)

5. Leave everything as default. Click `Create`

### Congratulations 🎉 for completing the Challenge Lab !

##### _You Have Successfully Demonstrated Your Skills And Determination._

#### _Well done!_
