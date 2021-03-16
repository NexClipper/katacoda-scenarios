# Step 2 - Create NexClipper Cluster

Go to [https://console.nexclipper.io/login](https://console.nexclipper.io/login) Page or Click the NexClipper tab next to the terminal console.

And login with your Account.

Now, Select Kubernetes platform to provision. And Create Cluster and enter the unique cluster name you want. 

And bootstrap script will be created to install on the selected platform.

![img](./assets/nc-step3.png)

Run the generated script at Terminal.

```
curl -sL gg.gg/provbee | K3S_SET=N K_API_KEY="testapikeyd045612" K_PLATFORM="kubernetes" K_MANAGER_URL="https://console.nexclipper.io:8090" K_ZONE_ID="338" K_CLUSTER_NAME="katacoda" bash
```

When NexClipper is in the Running state, Continue button will be activated.

Next, click the Continue button to move on to the next step.