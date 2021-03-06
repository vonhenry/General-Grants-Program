# Open Grant Proposal

* **Project:** Dinfra

## Project Overview :page_facing_up: 
### Overview
* A brief description of the project.  
  The goal of this project is to provide instant, scalable API access to the Polkadot, Filecoin and IPFS networks, including blockchains' historical data.

  For DApps, stable, reliable and rich node API services are very important. However, it is not a simple thing to run multiple kinds of  blockchain nodes, blockchain historical data retrieval services, and ensure the high availability of each service, especially when DApps use a variety of underlying technologies and blockchains (such as Filecoin and IPFS), the operation and maintenance of infrastructure will be heavy work. The purpose of this project is to provide fast and highly available API services.

* An indication of how you will integrate this project into Substrate / Polkadot / Kusama.  
  Substrate and Polkadot provide a powerful parachains framework and ecosystem, Filecoin and IPFS provide a perfect distributed storage scheme. The combination of the two will support more diverse and complex decentralized applications.

  Dinfra provides DApps with a convenient and reliable API for accessing Polkadot and decentralized storage network, which enables DApp developers of Polkadot ecosystem to focus more on business logic, and Dinfra shields the complexity of underlying blockchain infrastructure implementation. Dinfra will provide corresponding tools and services to help developers manage storage conveniently
  
* An indication of why your team is interested in creating this project.  
  The reason why our team did this project is that we are very optimistic about the future of Polkadot and Filecoin, they are a perfect complement. We believe that the combination of the two can lead to new types of decentralized applications. We hope that this project can bring surprises to both Polkadot and Filecoin ecosystem.

### Project Details 

* Mockups/designs of any UI components  
  We will build the Dinfra website and provide detailed API documentation, the document is divided into three parts: Polkadot, Filecoin and IPFS. Each API has an example, which can be called online with one click.

* API specifications of the core functionality  
  Dinfra will export APIs of all kinds of nodes, including Polkadot, filecoin, IPFs, etc., try to keep the request path similar to the original node request path, and support version number management. Meanwhile, Dinfra will provide the details of Filecoin miners, so that users can realize the following functions.
  - support all operations of Polkadot relay chain and parachains
  - support to query the current and historical data of relay chain and parachains
  - support storaging of files of various sizes and durations
  - supoort user data encryption storage
  - support parachains currency direct purchase of Filecoin storage services
  - support convenient multi backup storage, management and status query
  - support storage in specified geographical area

* An overview of the technology stack to be used
  - Substrate / Polkadot
  - Filecoin 
  - IPFS
  - Powergate
  - Load balancer and high availability tools
  - Monitoring system: EBK stack
  - Frontend: reactjs
  - Backend: chain history tools and DBs
  - SDK（node.js, go, java）

* Documentation of core components, protocols, architecture etc. to be deployed  
  The core components include:
  - official website
  - user account system
  - API specification and document
  - multi language implementations of SDK
  - high availability system
  - monitoring system
  - user storage management

* PoC/MVP or other relevant prior work or research on the topic  
  Our team has been deeply involved in the underlying technology of blockchain for many years. We are very appreciate the next-generation blockchain framework provided by Substrate. In recent months, we have deeply studied Filecoin and its source code, and we are very proficient in Filecoin. We are also a mine pool of Filecoin. So, we are very suitable for this project.

### Ecosystem Fit 
Are there any other projects similar to yours? If so, how is your project different?
 - [infura](https://infura.io)  
   Difference: infura mainly provides Ethereum, Filecoin/IPFS related data and API interfaces, while Dinfra mainly provides Polkadot and Filecoin/IPFS related data and API interfaces. More importantly, Dinfra is the first step of a big plan. We'll use Polkadot's parachain to build a perfect DApp development environment, especially for DApps related to web content, such as articles, blogs, pictures, music, video, media and so on.
   
 - [dfuse](https://dfuse.io/)  
   Difference: dfuse mainly provides eosio and Ethereum related data and API interfaces, while Dinfra mainly provides Polkadot and Filecoin/IPFS related data and API interfaces, and Dinfra will provide more abundant storage management functions, such as specified geographical location storage, multi-backup storage, convenient storage content addition, deletion and modification and other storage management functions.
   
## Team :busts_in_silhouette:

### Team members
* Simon Wang - https://github.com/vonhenry
* Victor Li -  https://github.com/vvvictorlee
* Frank - https://github.com/Frank-AFN

### Team Website	
* https://boscore.io/aboutUs 

### Legal Structure 
Company:  BOSCORE CAPITAL PTE. LTD.    
Address:  1 NORTH BRIDGE ROAD #21-10 HIGH STREET CENTRE SINGAPORE 179094   

### Team's experience
Our team members have many years of development experience in the field of blockchain. Our familiar projects include Bitcoin, Ethereum, Polkadot, EOSIO, Filecoin, IPFS, and the technologies we are good at include PBFT, IBC, Oracle, etc.   
Team related links:  
* https://boscore.io   
* https://github.com/boscore   
* https://github.com/cryptokylin   

### Team Code Repos
* https://github.com/vonhenry
* https://github.com/vvvictorlee
* https://github.com/Frank-AFN

### Team LinkedIn Profiles
* https://www.linkedin.com/in/vchengsong/
* https://www.linkedin.com/in/yuyang-zhang-499292107/

## Development Roadmap :nut_and_bolt: 

### Overview
* **Total Estimated Duration:** Three months
* **Full-time equivalent (FTE):** 3
* **Total Costs:** 0.9 BTC

### Milestone 1 Example — Implement Website and API Specification
* **Estimated Duration:** 1 month
* **FTE:**  1
* **Costs:** 0.3 BTC

| Number | Deliverable | Specification |
| ------------- | ------------- | ------------- |
| 0a. | License | Apache 2.0  |
| 0b. | Documentation | We will provide both code documentation and full API documentation |
| 0c. | Testing Guide | The code will have proper unit-test coverage (e.g. 90%) to ensure functionality and robustness. In the guide we will describe how to run these tests | 
| 1. | official website | we will build official website  |  
| 2. | user account system | we will build account and management system |
| 3. | API specification | we will design and wright API specification  |  

### Milestone 2 — Implement HA and user storage management
* **Estimated Duration:** 1 month
* **FTE:**  1
* **Costs:** 0.3 BTC

| Number | Deliverable | Specification |
| ------------- | ------------- | ------------- |
| 0a. | License | Apache 2.0  |
| 0b. | Documentation | We will provide both code documentation and full API documentation |
| 0c. | Testing Guide | The code will have proper unit-test coverage (e.g. 90%) to ensure functionality and robustness. In the guide we will describe how to run these tests | 
| 1. | high availability system | we will design and build high availability system |  
| 2. | user storage management | we will design and build user storage management |  

### Milestone 3 — Implement SDK and monitoring system
* **Estimated Duration:** 1 month
* **FTE:**  1
* **Costs:** 0.3 BTC

| Number | Deliverable | Specification |
| ------------- | ------------- | ------------- |
| 0a. | License | Apache 2.0  |
| 0b. | Documentation | We will provide both code documentation and full API documentation |
| 0c. | Testing Guide | The code will have proper unit-test coverage (e.g. 90%) to ensure functionality and robustness. In the guide we will describe how to run these tests | 
| 1. | monitoring system | we will design and build monitoring system |  
| 2. | SDK | we will impliment SDK in node.js |

### Community engagement
The tutorials and Documentation that we provide will be published as articles in Medium and other social media platforms with due mention about Web3 grant.

## Future Plans
Our goal is to build platform which suitable for DApps development based on polkadot parachains, especially those DApps related to decentralized storage and web content, such as decentralized articles, blogs, pictures sharing, music, video, media dapps and so on. Here is our whole roadmap:

Phase 1: Dinfra  
- Introduction: provide instant, scalable API access to the Polkadot, Filecoin and IPFS networks, including blockchains' historical data.
- Time plan: 2020.11 - 2021.2

Phase 2: Parachain with privacy algorithm added at the baselayer, fast filecoin token exchange with parachain's token
- Introduction: Develop parachain that can better support zero knowledge algorithms, and provide a fast fil exchange channel.
- Time plan: 2021.3 - 2021.6

Phase 3: Decentralized exchange and private transaction contract
- Introduction: develop DEX and private transaction contract, to provide more abundant environment for DApps.
- Time plan: 2021.7 - 2021.12

Phase 4: Decentralized web content application
- Introduction: We will select a decentralized web content application and develop it. Optional DApps are: decentralized vertical filed tiktok like product, decentralized music application, decentralized media platform, etc. 
- Time plan: 2022.1 - 2022.6


## Additional Information :heavy_plus_sign: 
* What work has been done so far?  
We are in the process of designing the overall technical architecture and further planning the development of future projects

* Are there are any teams who have already contributed (financially) to the project?  
We have started the research and development of this project, and now we have three developer involved.
