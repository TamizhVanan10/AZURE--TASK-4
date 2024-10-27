# AZURE--TASK-4


### STEP-1

##  Create 4 VNets:

1) Sign in to Azure Portal.

2) Navigate to Create a resource > Virtual Network.

3) Fill in required fields (Name, Address Space, Subscription).

4) Click Create.

5) Repeat for the other VNets and name it with A,B,C,D.

6) Hence the 4 Vnets will be created.

### STEP-2

##  Create Management VNet (Hub)

1) Follow the same steps to create a VNet.
  
2) In the Advanced section, choose to Add a virtual network for hub-spoke setup.
   
3) Create spoke VNets and connect them to the hub.


### STEP-3

## Set Up Production VNet

1) Create another VNet for production workloads using the same method.

2) Ensure to create subnets for different resource types.

### STEP-4

## Create Testing VNet

1) Follow the same steps to create a separate VNet for testing and development.

### STEP-5

## Create Developing VNet & Hub-Spoke Architecture


1) Create the Developing VNet with appropriate settings.

2) Create the Hub VNet as described. 

3) For each spoke VNet, go to Connectivity > Add > connect to the Hub VNet.


### STEP-6

## 6. Launch VMs and Verify Connectivity.

1) Now Launch VMs in each VNet.
  
2) From the management VM in the hub, ping the VMs in spoke VNets to verify connectivity.
   
3)This should give you a clear and quick overview of setting up your VNets in Azure!


##### HENCE THE DAY-4 TASK IS FINSHED !!!.... ####
