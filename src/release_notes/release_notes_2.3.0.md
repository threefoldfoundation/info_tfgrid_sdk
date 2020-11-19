# TF Grid 2.3.0 Release Note

## High Level Summary

[__The ThreeFold Grid__](https://wiki.threefold.io/#/grid_why) is a peer-to-peer and autonomous Internet grid that provides game-changing performance and empowers new possibilities. It sets the foundation for a better Internet, based on new principles: Peer-to-Peer, decentralized, autonomous, private, secure, and sustainable.

__ThreeFold Grid 2.3__ release introduces the addition of testnet resource capacity to make your testing experience more effective. Please go to 
[Testnet TF Explorer](https://explorer.threefold.io/testnet) for more details. We have also added some improvements to the grid’s stability, new features, as well as introducing TFT and TFT on testnet as the only tokens used for reserving capacity on the Grid to avoid payment complications.


## What’s New on ThreeFold Grid 2.3.0

### ThreeFold NOW

- This 2.3 release introduces an improved user interface of [ThreeFold NOW Marketplace](marketplace.threefold.io), providing categories for a better navigation experience. 
- Along with new categories, this release introduces ThreeFold NOW solution: you can now try using a decentralized video calling solution deployable via ThreeFold NOW Marketplace on [this link](https://marketplace.threefold.io/marketplace/#/solutions/meetings). 


### [ThreeFold Explorer](https://github.com/threefoldtech/tfexplorer/releases/tag/v0.4.1)

On ThreeFold Explorer you could see node information and check all the available IT Capacity on both testnet and mainnet environment. The encryption scheme used to send sensitive information to workloads is improved. The explorer also only cancel workloads that are actually consuming resources when a capacity pool is exhausted.

### [ThreeFold Connect (rebranded from: 3Bot Connect)](https://github.com/threefoldtech/3Bot_connect/releases/tag/v2.0.0)

- On this release, 3Bot Connect App is rebranded to into __ThreeFold Connect App__. ThreeFold Connect App is your main access point to the ThreeFold Grid.
- A lot of improvement on the signing in process have been made on this release. Now, you could use your FaceID and TouchID to sign into your ThreeFold Connect account. Your 3Bot recovery flow is now improved and signin issues for incorrectly setup time on their mobile device is fixed. 
- Performance and feature wise, the app’s speed is increased and Freeflow Pages feature is removed from ThreeFold Connect app since it is no longer promoted for usage.


### 3Bot Deployer

A 3Bot deployer should do what it was designed to do: deploy your virtual system administrator in a fast and easy manner. Deployment speed is increased and the deployment flow of 3Bot is simplified. The decentralization aspect of your 3Bot is also improved by making it possible for you to choose where you would assign your 3Bot- be it on a specific location, farm, or even to a specific node that you prefer.


### 3Bot

With this 2.3 release, a lot of automation to the processes is added to scale the effectiveness of 3Bot deployment and improve your user experience as described below: 

- when you have successfully deployed a hosted 3Bot, a functional wallet would be added automatically. 
- Automation is also added with the way how packages are added to your 3Bot. You are now able to directly add packages from subfolders in your github repos and the package code can be reloaded without the need to restart the 3Bot. 
- You can now automatically extend your capacity pools when they are expiring, that way it will minimize workload downtime due to lacking resources. An escalation email would also be sent automatically as a reminder to extend your capacity pool.
- SSH access capability is added, as well as a backup option for downloaded packages, .ssh, and code directories that improve your workload management and security.



### [Zero-OS](https://github.com/threefoldtech/zos/releases/tag/v0.4.6)

Zero-OS (ZOS) is the operating system which allows the 3Nodes to be used to provide IT capacity required by the solutions running on the TFGrid. With this Grid 2.3 release, the resource management on Zero-OS level is improved. The main focus is on improving the accuracy of the information reported by the nodes to the explorer regarding the amount of reserved capacity and improving the freeing of unused resources.


### Jumpscale Framework ([JS-NG](https://github.com/threefoldtech/js-ng/releases/tag/v11.0-b7) and [JS-SDK](https://github.com/threefoldtech/js-sdk/releases/tag/11.0-b11))

Jumpscale is an automation framework and the foundation of the autonomous layer. It includes all the components involved in creating the IT architecture for autonomous operations, like a container running a webserver, a database server, and then all the required network paths in between. This release introduces a lot of component improvements and bugs fixes, such as adding statistics to container and making it easier for monitoring, as well as improved the logs of containers. We have also added support for test certificates.

