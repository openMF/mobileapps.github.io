# Mobile Applications

Built on top of the Fineract APIs, the Mifos Initiative maintains a suite of staff and client-facing mobile apps to enable field-based operations and deliver an omni-channel banking experience for clients.

These apps can be used out-of-the-box for demonstration purposes, they can be white-labeled, extended and hardened for use in production or they can serve as the starting point for a new mobile application. 

This page is to help you understand the use cases each of the apps caters to whether you’re a financial institution or fintech looking to consume it or a developer looking to contribute to it. In addition you can find the github repository, a link to the latest APK, and the issue tracker/roadmap for ongoing development. 

Included on this page is information related to apps built on top of Fineract 1.x (Generation 2) and apps built on Fineract CN (Generation 3) 

# Self-Service Applications (Clients)

## Mobile Banking App: 
Mobile Banking Applications are essentially a mobile interface to allow for a client to interact with the accounts they hold at a financial institution - typically they can view details of their loan/savings accounts, transfer money between accounts, and transfer money to other users. 

### Mifos Mobile (Fineract 1.x)
Currently in its 3rd version, this is the reference mobile banking app built on top of Mifos X/Fineract 1.x that consumes the self-service APIs. It can be used out of the box or white-labeled for your institution. 
      
<img src="https://github.com/openMF/mobileapps.github.io/Screen-Shot-2017-08-01-at-4.14.32-PM.png" width="300">

### Mifos Mobile CN (Fineract CN)
Currently in its first version, this is the reference mobile banking app built on top of Fineract CN - it currently only consumes a mock layer of data and is still to be integrated with the API gateway for Fineract CN. 

<img src="/68747470733a2f2f692e696d6775722e636f6d2f35534d506b69322e676966 (1).gif" width="300">

## Personal Financial Management App
A PFM app would allow clients or small businesses to track their expenditures, savings, and cash flows to have better visibility into their financial well-being. This could be built as a stand-alone app or functionality as subset of a mobile wallet, mobile banking or digital credit app.


## Digital Credit App
Digital Credit Applications are client-facing apps for the self-service application for, disbursement, and repayment of loans via a mobile phone. Leveraging mobile money, this lending limits in-person contact facilitating low-cost lending based on loan origination guided by big data and advanced analytics. 


# Mobile Wallets
In all the following use cases below, the mobile wallet app provides a richer user interface to manage mobile or e-money balances as a store of value and a means of payment. The differences between the solutions outlined below are the holder of the wallet (client vs. merchant) and scope of the wallet (single digital money service vs multiple balances).

## Consumer Wallet (single service)
Mifos X/Fineract can be used to as a back-end account management system for mobile wallets. In this example a telco or mobile money provider or e-money issuer in general, could build upon the mobile wallet to provide a client or end user a richer user interface to fund their mobile wallet account, initiate transfers, view account details and transaction histories, and pay merchants at point of sale.

<img src="/Screen-Shot-2017-08-08-at-6.48.27-AM (1).png" width="300">

## Consumer Wallet
A broader definition for the mobile wallet could be a wallet app like Google or Apple Pay whereby the wallet provides the ability to add multiple digital forms of payment in one unified account - this provides one interface in which to manage multiple digital money services, or even the ability to transfer between these digital money services.


## Merchant-Facing Wallet
Similar to a consumer wallet, this would be a mobile wallet account for a merchant allowing them to accept electronic payments via QR code, view transaction details, generate invoices. Ideally it would also help them track sales by consumer as well. 
      
# Field-Based Operations (Staff)

## Field Operations Application (Internal Staff)

### Mifos Android Client (Mifos Droid)
The Field Operations App enables a loan or field officer to conduct their daily operations while out in the field - it doesn’t aim to replicate the full functionality of the staff-facing web app but rather those essential operations for out in the field such as client onboarding, collections, loan origination, etc. A loan officer should be able to view and edit clients and their accounts both on and offline via the app. 

<img src="/Screen-Shot-2017-08-08-at-6.47.45-AM (1).png" width="300">


### Fineract CN Mobile
Similar to the scope of Android Client for Fineract 1.x, this is the equivalent app but on top of Fineract CN. 

# Third Party/Agent Banking (External Staff)
This is a mobile app to enable a network of third party staff or agents to conduct operations on behalf of the financial institution or network - these would include operations similar to that of the field operations app (client onboarding, collections, origination) but a deeper feature set including bill payments, e-commerce, and other merchant services. Given these are external agents, functionality around management of the agent is more robust including location tracking, task assignment and management, communications/notifications, handling of commissions, performance tracking, agent training and tracking of time. 

# Take Action

## Client Apps

### Mifos Mobile
- [Find the Code](https://github.com/openMF/mifos-mobile)
- [Download most Recent Build](https://drive.google.com/open?id=1AaNv-mHXs6q33N-sVJUf2wVEhhiHbV-D)
- [Roadmap/Issue Tracker](https://github.com/openMF/mifos-mobile/issues)
- [Latest Progress](https://gist.github.com/miPlodder/2c872981e9a05be7e5fe65f5f05c31f9)

### Mifos Mobile CN
- [Find the Code](https://github.com/openMF/mifos-mobile-cn)
- [Download most Recent Build](https://drive.google.com/open?id=1AaNv-mHXs6q33N-sVJUf2wVEhhiHbV-D)
- [Roadmap/Issue Tracker](https://github.com/openMF/mifos-mobile-cn/issues)
- [Latest Progress](https://gist.github.com/ivary43/2021a4f8b9202884e7ed52128cedcccf)

### Mobile Wallet
- [Find the Code](https://github.com/openMF/mobile-wallet)
- [Download most Recent Build]
- [Roadmap/Issue Tracker](https://github.com/openMF/mobile-wallet/issues)
- [Latest Progress](https://gist.github.com/ankurs287/d9ef88cedcebe678f09fd555b17c7546)

### FiinWallet
- [Find the Code](https://github.com/openMF/fiinwallet)
- [Download most Recent Build]
- [Roadmap/Issue Tracker](https://github.com/openMF/fiinwallet/issues)
- [Latest Progress]

There is no reference digital credit app but good examples from the community that use Mifos on the back-end for loan management are Kwikcash from Mines.io and RuPie.  



## Staff Apps

### Mifos Android Client
- [Find the Code](https://github.com/openMF/android-client)
- [Download most Recent Build](https://drive.google.com/open?id=1cTlKeeqyLiBQhkmga2LHE1_w-CLZcCMz)
- [Roadmap/Issue Tracker](https://github.com/openMF/android-client/issues)
- [Latest Progress](https://medium.com/@gaksh007/my-gsoc-journey-with-mifos-initiative-7165a961ea55)

### Fineract CN Mobile
- [Find the Code](https://github.com/apache/fineract-cn-mobile)
- [Download most Recent Build]
- [Roadmap/Issue Tracker](https://github.com/apache/fineract-cn-mobile/issues)
- [Latest Progress](https://github.com/mohak1712/fineract-cn-mobile-1/wiki)

There is no reference application for an app for managing external third party staff but partners like Mann India have built solutions like [Mimo](https://www.youtube.com/watch?v=JEIxgh6FH1w) 
