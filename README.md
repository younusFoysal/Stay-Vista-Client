
<h1 align="center">Stay Vista </h1>


<br>


## Live Link:

[https://stayvista-new.web.app](https://stayvista-new.web.app)

## Overview:
The goal is to develop a user-friendly hotel booking platform similar to Airbnb, providing a seamless experience for users to browse, filter, book, and manage accommodations. The platform will serve both guests and hosts, facilitating property listings, bookings & secure transactions. Admin roles will also be there to monitor overall statistics and manage user roles.

## Features:


### Registration, Login and Profiles
* Users can create accounts as guests.
* Profile creation with email, password, name & photo upload.
* Registered Users can Login using their credentials.
* Sign In with google popup feature.
* Secure with JWT. (Store token in browser cookie)



### Guest Role:
* Guests can book available rooms.
    - Secure booking system for guests to reserve properties.
    - Instant booking or host approval options.
    - Calendar integration for managing reservations.
* Dashboard:
    - Statistics Page
    -  Booking Management Page
    -  Guests can request for a host role.
    -  Detailed Profile page with profile info & update action buttons.

### Host Role:
- Extends all the features of guests.
- Statistics Page
-  Add Room Page for listing Rooms.
-    Hosts can list their properties for rent.
-    Property details including photos, descriptions, amenities, availability, and pricing.
-    My Listing Page for managing added rooms.
-    Booking Management Page.
-    Detailed Profile page with profile info & update action buttons.


### Admin
- Statistics Page
-  User Management Page
-  Change user roles based on request.
-  Detailed Profile page with profile info & update action buttons.

### Notifications
- Implement Automatic Email Notification system for Booking actions/ User actions.

### Payments and Transactions:
- Secure payment gateway integration using Stripe.



<h3 align="center">All Credentials</h3>

### Admin Credentials:
```
Admin Email: foysal@gmail.com
Admin Pin: 12312
```
### Agent Credentials:
```
Admin Email: altaf@gmail.com
Admin Pin: 12378
```
### User Credentials:
```
Admin Email: nafisa@gmail.com
Admin Pin: 12345
```


Installed Npm Packages:
```
@headlessui/react
@stripe/react-stripe-js
@tanstack/react-query
axios
Firebase
react
react-hot-toast
react-icons
react-router-dom
react-toastify
sweetalert2
tailwindcss
```

### How to Set Up Locally

1. Install npm packages:
    ```sh
    npm i
    ```
2. Create a `.env.local` file containing API keys and Firebase credentials.
3. Run the API server from [Stay-Visa-Server](https://github.com/younusFoysal/Stay-Vista-Server).
4. Run the development server:
    ```sh
    npm run dev
    ```
5. Browse the application at:
    ```sh
    http://localhost:5173/
    ```
