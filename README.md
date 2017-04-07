# Brooklyn Cello

This repository contains an [Apache Brooklyn](https://brooklyn.apache.org/) blueprint to deploy a [Hyperledger Cello](https://github.com/hyperledger/cello) cluster.

### Step 1: Install Cloudsoft AMP

Use [this guide](http://docs.cloudsoft.io/tutorials/tutorial-get-amp-running.html) to install
AMP.

### Step 2: Create a Deployment Location

In order to deploy a Cello cluster with AMP, you must first configure a location to which
AMP will deploy it.

Use [this guide](http://docs.cloudsoft.io/locations/index.html) to learn more about AMP locations
and how to create your own.

### Step 3: Deploy Hyperledger Cello

#### 3.1 Add Hyperledger Cello to the AMP Catalog

From the AMP UI home screen, perform the following steps:

* Click the square button on the top right corner
* Click "Blueprint importer"
* Copy and paste the [catalog file](catalog.bom) into the editor
* Click "Import" on the bottom right corner

#### 3.2 Deploy Hyperledger Cello

From the AMP UI home screen, perform the following steps:

* Browse to the AMP user interface (address listed in the installation guide)
* Scroll through the "Quick launch" tile and click "Hyperledger Cello Cluster"
* Optionally provide a name
* Provide the location that you created
* Customize the parameter values if desired
* Click the "Deploy" button

### Step 4: Use Your Deployed Cluster

From the AMP UI home screen, perform the following steps:

* Click "App inspector"
* Click on the Hyperledger Cello cluster that you deployed
* Click the link next to `main.uri` which ends in `:8080`

Congratulations! You have successfully deployed a Hyperledger Cello cluster and have
navigated to its home screen which is ready to be used.
