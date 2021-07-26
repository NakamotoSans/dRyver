# Implementation of Decentralised Taxi Hailing Service using Ethereum Smart Contract

This project showcases the interaction between the commuter and driver during the course of booking a ride on the blockchain. 

dRyver handles the sequence of activities and processes smoothly to make the experience of traveling seamless.

### Video:
[![dRyver](https://res.cloudinary.com/marcomontalbano/image/upload/v1627261143/video_to_markdown/images/youtube--VzWq9QpSnq0-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/VzWq9QpSnq0 "dRyver")

### Problems in Existing System ⚠💀
---

- Applications like Uber provide a matching service and apparently they decentralize it. This is P2P technology at its finest. Or is it? 
Several scandals have emerged out of Uber’s corporate culture as of late. Uber has become notorious both for its business practices and for what it incentivizes and allows its drivers to do. 

- An Uber executive told the company to dig up dirt on a particular critical female reporter as well as other opponents. The power the company exerts over its drivers has grown from surveillance into possibly predatory practices. They have the ability to see all rides happening at any location in real-time with all social data attached to each rider And have been the subject of controversy on multiple occasions. 

- Despite these concerns, Uber has grown at an exponential rate over the past few years and is showing revenue numbers in the billions. It provides a useful service: people prefer using a location-aware app to hail a ride over calling a taxi, and it’s safe to say the demand for real-time ride-sharing isn’t going away anytime soon. But privacy invasion and the vast imbalance of power between a billion-dollar corporation and the drivers are the negatives of Uber that riders must accept when they use its service.



		
 

### What we are providing 😇
---

- We eliminate the existence of the middle agency, thereby completely removing the regulation of salaries of drivers by corporations. So, the earnings of the driver are solely dependent on the number of rides he/she makes. 
- All the data is stored on the peer-to-peer decentralized Polygon Matic Chain. This not only ensures complete security, but also a lightning-fast experience. Data privacy is maintained by the access specifiers of data members and methods defined in the smart contracts. 
- We are not only eliminating the middle man, the L2 solution by Polygon gives us a boost in transaction rate. It is also a known fact that data transfer is faster in a mesh network.
- We have implemented a smart contract addressing the issue of storing critical data necessary at different stages of Taxi Hailing and making it verifiable by all stakeholders in dRyver.




### Application Workflow Diagram 📝
---
![](https://github.com/NakamotoSans/Screens/blob/main/workflow.png?raw=true)

### Smarts Contracts 😍
---

1. User
2. Driver
3. Customer

**Owner:** Owner deploys the contract.

**User:**  User is the base contract containing some common attributes and behaviour of Customers and Drivers.

**Driver:** This Contract contains essential details of drivers along with some driver-specific methods.

**Customer:** This contract contains methods that allow customers to request a ride.

### Included Components
---
-  Solidity (**Ethereum**)
-  Metamask  (**Ethereum** wallet)
-  Mumbai testnet ( **Polygon** Network with **Matic** Faucet )
-  Remix IDE
-  Truffle
-  IPFS
-  Web3JS
-  React Native 
-  Nodejs (Express)
-  Google Map Api
-  Firebase for Google Auth


### UI screenshots of Mobile App:

<p align="center">	
<table>
	
  <tr>
	  <td><b>Welcome Screen</b></td>
	  <td><b>Login Screen</b></td>
	  <td><b>Google AUth</b></td>
  </tr>
  <tr>
    <td><img src="https://github.com/NakamotoSans/Screens/blob/main/IMG_20210725_143841.jpg" width=320 height=570></td>
    <td><img src="https://github.com/NakamotoSans/Screens/blob/main/IMG_20210725_145106.jpg" width=320 height=570></td>
    <td><img src="https://github.com/NakamotoSans/Screens/blob/main/IMG_20210725_145547.jpg" width=320 height=570></td>
  </tr>
		
  <tr>
	  <td><b>Add Driver Details</b></td>
	  <td><b>Link Wallet</b></td>
	  <td><b>Searching Phase</b></td>
  </tr>
  
	
  <tr>
    <td><img src="https://github.com/NakamotoSans/Screens/blob/main/Screenshot_2021-07-25-15-06-28-217_com.sans.nakamoto.jpg" width=320 height=570></td>
    <td><img src="https://github.com/NakamotoSans/Screens/blob/main/IMG_20210725_150003.jpg" width=320 height=570></td>
    <td><img src="https://github.com/NakamotoSans/Screens/blob/main/IMG_20210725_150640.jpg" width=320 height=570></td>
  </tr>	
		
  <tr>
	  <td><b>Select Pickup and Drop Locations</b></td>
	  <td><b>Active Ride Requests</b></td>
	  <td><b>Ride Confirmed</b></td>
  </tr>
  <tr>
    <td><img src="https://github.com/NakamotoSans/Screens/blob/main/IMG_20210725_151310.jpg" width=320 height=570></td>	
    <td><img src="https://github.com/NakamotoSans/Screens/blob/main/Screenshot_2021-07-25-15-06-57-049_com.sans.nakamoto.jpg" width=320 height=570></td>
    <td><img src="https://github.com/NakamotoSans/Screens/blob/main/IMG_20210725_150832.jpg" width=320 height=570></td>
    
  </tr>	
 </table>	
</p>


### Prerequisites
---
- Nodejs v9.10 or above
- Truffle v4.1.8 (core: 4.1.8) (http://truffleframework.com/docs/getting_started/installation)
- Solidity v0.8.0
- Metamask (https://metamask.io) /Ganache Wallet

### Deployment Steps:
---

#### Smart contracts

Steps to Execute Solidity Smart Contract using Remix IDE

Remix IDE is generally used to compile and run Solidity smart contracts. Below are the steps for the compilation, execution, and debugging of the smart contract. 
 

Step 1: First clone our GitHub project from here. Open Remix IDE on any of your browsers, Choose solidity as the environment.
```
git clone https://github.com/NakamotoSans/Contracts
cd Contracts
```
Step 2:Import the contracts from your local system. Click the Compile button under the Compiler window to compile the contract.
Step 3: To execute the code, click on the Deploy button under the Deploy and Run Transactions window.
Step 4: After deploying the code click on the method calls under the drop-down of deployed contracts to run the program, and for output, check to click on the drop-down on the console.
Step 5: For debugging click on the Debug button corresponding to the method call in the console. Here you can check each function call and variable assignment.

#### Mobile Application

Step 1: Make sure you have the development environment is setup for [React-Native](https://reactnative.dev/docs/environment-setup).
Step 2: Clone our Application GitHub repo
```
git clone https://github.com/NakamotoSans/Application
cd Application
```
Step 3: Install all the dependencies
```
yarn install //recommended
```
or
```
npm install
```
Step 4: Start the Metro

```
npx react-native start
```

Step 5: Run the Application
```
npx react-native run-android
```
