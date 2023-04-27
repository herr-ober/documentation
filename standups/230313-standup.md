## Standup 13.03.2023

### Outcomes

- During the work on the Kanban Boards, all teams realized that one product owner per team is too much overhead. Istead we introduce the new globally responsible product owner Sven Luipold.

- The description of our software will be created by Samuel Matzeit
- The user stories and the corresponding map will be defined by Jonas Nunnenmacher, Matthias Schneider and Sven Luipold
- The prototype of the different user interfaces is already existent and will be used further
- The recap will be written by Linas Vockensohn
- The project kickoff will take place on Thursday, 16.03.

### Recap:

- What we **have to** achieve for sure:
    - Account management
      - Create organizer account
      - Sign in with organizer account
      - Sign in as staff with code
    - Create event
      - Add staff
      - Add product
      - Add table
    - Manage event
      - Manage staff
      - Manage products
      - Manage tables
      - End event
    - Manage orders
      - Add new order
      - View and edit product state
      - Mark product as delivered
      - Display all orders
   
- What we **can** achieve for sure:
  - Add special wishes to orders
  - Split the bill
  - Visually appealing interface
  - Performant and stable software
  - Lock or unlock products
  - Update organizer account

- What we **could** achieve (with risks):
  - Payment options
    - In addition to the two common payment options such as card and cash also offer external payment providers, like for example PayPal
    - Risk: In order to include external service providers in the process, additional external accounts must be created. In this way, the cash flow is managed via different providers instead of via cash and a single bank account. You have to be able to keep track of this and manage the money.
    - Risk: Additional providers usually require fees and our product should not cost extra or generate negative revenue through too many providers.
  - Statistics 
    - Revenue statistics
    - Waiter statistics
    - Reduce money in portemonnaies
    - Order statistics
    - Export event statistics
    - Risk: Statics need a large amount of historical data. This data must be processed and stored efficiently. Optimization can quickly become time consuming. 
