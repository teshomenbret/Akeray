# Akeray
## Brief Description
This app is believed to be some kind of connector between rental service providers as shop centers and customers. So as anyone can guess, there are two types of users:
* Companies as service providers with administrative privileges
* Customers as served users with minimal privileges    

For our admin users, it will be capable of calculating different types of sales transactions and will be able to generate a summary based on the initial prices of information that is set b8y themselves beforehand.

For our second users aka customers, the system should provide with the appropriate information like the list of companies that have already partnered with our platform with a respective summary, and the list of items provided by each institution for renting.

The application is cross-platform and will be functional both in android and iOS. The application will only need an internet connection and a smartphone to operate and nothing else.

The application will utilize a database of items that are to be entered by us or our business partner’s technical department.

## Authorization and Authentication

### Autherization Features

So we will authorize our first users aka companies to have full CRUD functionalities for their item lists. That means they can **CREATE** new items, **UPDATE** existing items in the list, **DELETE** items that are no longer available and last but not least they obviously can **READ** the list of items. However, one company can only manage their own list. We carefully authenticate this so that they will be no way near interfering with our companies.

We have only given the other users, i.e. our customers full CRUD functionality only once when they create their accounts and/or when they potentially delete their accounts. But beyond that they have only **READ** privileges to see the list of available companies providing the items they seek to be provided.

### Authentication Features

The two users of this platform are required to *register* before using the application business features. So that they can *login* to the system independently and do their work as per their privileges in a hassle free manner. They can logout temporarily from the app and login again. Additionally, if either the company or the customers are not satisfied by our care they can delete their accounts permanently and their related data.

## Contributors
1. Surafel Getahun Aragaw - UGR/5965/12
2. Bereket Asnake Tsegaye - UGR/9574/12
3. Teshome Nbret Yersaw - UGR/3281/12
4. Abdulkarim Getachew Mohammed - UGR/7992/12
5. Petros Beyene Mola - UGR//12
