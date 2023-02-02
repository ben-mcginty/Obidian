## What are requirements?
- functional and non-functional
- also legal and technical requirements
## Functional Requirements
- relate to a products functionality
	- performance
	- stability
	- security
	- technical specifications
## Functional v. Non-Functional Requirements
Both types of requirements are important. One affects the other
Both are different.
- server setup & config are non functional that has an impact on the system
- **Functional**
	- Payment processing functionality
- **Non-Functional**
	- SSL certificate
SSL (Secure Sockets Layer)
- establish a link between two clients
	- Public-private cryptography
SSL is a non-functional requirement - an element of the implementation
directly affects functional requirements - securely proccesing transactions
-   **Functional Requirement:** tools and resources (PDF, infographics, courseware, spreadsheets) available for users, accessible via the Resources landing page
-   **Non-Functional Requirement:** administrative panel file format specs (e.g. “The following file formats are valid for upload within the administrative user panel, in relation to the Resources page: .zip, .jpeg, .csv, .pdf”)
## **The importance of requirements management**
Requirements management is important for two main reasons:
-   Requirements documentation serves as a **point of reference to document the evolution of a project**, its moving parts, and its implementation
-   Requirements documentation serves as a **blueprint for the client to better understand what to expect out of the project** (the what, where, when, and why of the project).
Part of requirements management planning should outline what _not_ to expect.
Including an “Assumptions” and/or “Exclusions” section is a wise approach to eliminate the risk of the dreaded _client imagination_.
## Requirem-   **What:** PayPal integration
-   **Where:** Checkout
-   **When:** Within step 3 of 4 in the checkout experience (after the shipping address webform, before confirmation)
-   **Why:** An established integration (e.g. PayPal) is a better solution than a robust custom build integration for a payment service in this case because it easily meets client requirements.
-   **Assumptions**
    -   Flat fee for all shipping & handling
    -   All shipping is within Australia. (not including External Territories)
    -   Taxes do not apply
-   **Exclusions**
    -   Custom shipping & handling fee calculations
    -   Shipping internationally, or to External Territories
    -   Tax rulesent example

# Activity
Software chosen: [obsidian](https://obsidian.md/)
#### Product requirements
-   What will the product do?
	- The product is a PKM (personal knowledge managment) application
-   What is the product’s main functionality?
	- To enable the management and editing of markdown (.md) files.
-   What other actions should the product perform?
	- Showing a graph of linked notes
	- Allowing for plugins to be installed to expand the use of the application
-   How many sections does the product have?
	- $\infty$
-   How many parameters?
	- 4
-   How does each parameter work?
	- Acess file, edit file, save file, read file
-   Does your product require maintenance?
	- Yes and no. The application should be stable, but may recieve updates to bring new functionality to the user
-   Does your product contain replaceable parts?
	- Yes, core plugins can be replaced with alternatives

#### Regarding the user:
-   Who will be the primary user of the product?
	- Students and professionals
-   What is the age range for the user?
	- $\geq$ 12
-   Where does the user live?
	- Any country
-   How does the user live (lifestyle)?
	- Any - intended for students and professionals
-   What are the user’s everyday life activities?
	- Varies
-   What are the user’s interests?
	- Varies

#### Regarding the user’s relationship with the product:
-   How will the user interact with the product?
	- As an application on thier computer or smartphone
-   What need will the product satisfy for the user?
	- Note-taking and information management
-   How is the user currently satisfying this need?
	- Varies
-   How much will the user be willing to spend on the product?
	- Varies (Obsidian is free for personal use - optional donation)

#### Regarding branding:
-   What branding should the product have?
	- Logo
-   Is the branding shared?
	- No
-   Does the product have an independent branding?
	- Yes
-   Is the branding adaptable to the product?
	- Yes

#### Regarding competitors:
-   What is the main competitor for the product?
	- OneNote, Evernote, etc.
-   What are the secondary competitors?
	- Microsoft Word, Google Keep, etc.
-   What is the main competitor’s differentiator?
	- Cloud syncing & data is not locally stored
-   What is the differentiator of the proposed product vs. all competitors?
	- Users own thier data
	- Plugins
	- Fast
	- Free

#### Regarding sales and marketing:
-   How will the product be sold?
	- Via the Internet
-   How will it be advertised?
	- No advertising - too expensive

#### Regarding customer service:
-   What problems could the user encounter with the product?
	- Crashes, deleted notes
-   How can the user solve these problems?
	- Ensure that adequate data storage is in place.
-   What channels are available for the user to seek customer service?
	- Community forum

#### Regarding other stakeholders:
-   What other stakeholders will be interacting with this product?
	- No
-   How will these stakeholders interact with the product?
	- N/A

#### Regarding platforms and devices:
-   In which operating system will the product be developed? (iOS, Android, Windows, etc.)
	- Windows (ARM, x86, x86_64), macOS (Intel & ARM), Linux (AppImage, Snap, Flatpak, .deb), iOS, Android,
-   Which devices will the product need? (mobile, tablet, wearables, desktop, specific, etc.)
	- Computer or Smartphone
-   Are there any limitations for the product with regard to technology?
	- No. Assuming the user has a compatible platform or is willing to port it to another system

#### Regarding user stories:
-   Who will perform the task?
	- Users
-   What does the user need to do?
	- Include Obsidian in the name
-   Why does the user need to perform this task?
	- They don’t