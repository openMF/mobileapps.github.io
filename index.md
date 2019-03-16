# Mobile Applications

Built on top of the Fineract APIs, the Mifos Initiative maintains a suite of staff and client-facing mobile apps to enable field-based operations and deliver an omni-channel banking experience for clients.

These apps can be used out-of-the-box for demonstration purposes, they can be white-labeled, extended and hardened for use in production or they can serve as the starting point for a new mobile application. 

This page is to help you understand the use cases each of the apps caters to whether you’re a financial institution or fintech looking to consume it or a developer looking to contribute to it. In addition you can find the github repository, a link to the latest APK, and the issue tracker/roadmap for ongoing development. 

Included on this page is information related to apps built on top of Fineract 1.x (Generation 2) and apps built on Fineract CN (Generation 3) 

# Self-Service Applications

## Mobile Banking App: 
Mobile Banking Applications are essentially a mobile interface to allow for a client to interact with the accounts they hold at a financial institution - typically they can view details of their loan/savings accounts, transfer money between accounts, and transfer money to other users. 
- Mifos Mobile
- Mifos Mobile CN

## Personal Financial Management App
A PFM app would allow clients or small businesses to track their expenditures, savings, and cash flows to have better visibility into their financial well-being. This could be built as a stand-alone app or functionality as subset of a mobile wallet, mobile banking or digital credit app.


## Digital Credit App
Digital Credit Applications are client-facing apps for the self-service application for, disbursement, and repayment of loans via a mobile phone. Leveraging mobile money, this lending limits in-person contact facilitating low-cost lending based on loan origination guided by big data and advanced analytics. 

<img src="/Screenshot_20170913-085024.jpg" width="300">

# Mobile Wallets
In all the following use cases below, the mobile wallet app provides a richer user interface to manage mobile or e-money balances as a store of value and a means of payment. The differences between the solutions outlined below are the holder of the wallet (client vs. merchant) and scope of the wallet (single digital money service vs multiple balances). 
## Consumer Wallet (single service)
Mifos X/Fineract can be used to as a back-end account management system for mobile wallets. In this example a telco or mobile money provider or e-money issuer in general, could build upon the mobile wallet to provide a client or end user a richer user interface to fund their mobile wallet account, initiate transfers, view account details and transaction histories, and pay merchants at point of sale. to manage mobile aStore of Value

## Consumer Wallet
A broader definition for the mobile wallet could be a wallet app like Google or Apple Pay whereby the wallet provides the ability to add multiple digital forms of payment in one unified account - this provides one interface in which to manage multiple digital money services, or even the ability to transfer between these digital money services.

## Merchant-Facing Wallet
Similar to a consumer wallet, this would be a mobile wallet account for a merchant allowing them to accept electronic payments via QR code, view transaction details, generate invoices. Ideally it would also help them track sales by consumer as well. 
      
# Field-Based Operations
Staff
Third Party/Agent Banking 
PAYG
## Field Operations Application (Internal Staff)
- Mifos Android Client (Mifos Droid: The Field Operations App enables a loan or field officer to conduct their daily operations while out in the field - it doesn’t aim to replicate the full functionality of the staff-facing web app but rather those essential operations for out in the field such as client onboarding, collections, loan origination, etc. A loan officer should be able to view and edit clients and their accounts both on and offline via the app. 
- Fineract CN Mobile

# Third Party/Agent Banking (External Staff)
This is a mobile app to enable a network of third party staff or agents to conduct operations on behalf of the financial institution or network - these would include operations similar to that of the field operations app (client onboarding, collections, origination) but a deeper feature set including bill payments, e-commerce, and other merchant services. Given these are external agents, functionality around management of the agent is more robust including location tracking, task assignment and management, communications/notifications, handling of commissions, performance tracking, agent training and tracking of time. 



You can use the [editor on GitHub](https://github.com/openMF/mobileapps.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/openMF/mobileapps.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
