## Hackathon Guvi #2

### Pizza Delivery Application

1. Create a full stack app using react, mongo db and nodejs.

1. Create a user login with complete registration, authorization, email verification and forgot password system. 

1. Create an admin login with complete registration, authorization, email verification and forgot password system. 

    - Users when login can view the available pizza varieties in the dashboard.

    - Users can start making the custom pizza with the following flow.

        - Choose a pizza base from 5 options.

        - Choose a sauce from 5 options.

        - Choose a cheese type from 4 options.

        - Choose veggies from many options.

        - Choose meat from many options.

        - Users can choose 3 free veggies and 1 free meat. On adding extra veggies and meat, charge them accordingly.

        - Also display the charge of extra veggies and meat.

1. Integrate the razor pay checkout for payment. Create a dummy account and integrate the test mode. In test mode on clicking success, place and confirm the order.

1. In the admin login, create a mini inventory management system to keep a track of available pizza base, sauce, cheese, veggies and meat. 

1. Once a order has been made, update the necessary changes in stock and present in admin dashboard. 

1. Schedule a notification to the admin email id when the available stock goes beyond the threshold value. (eg. total pizza base is below 20 after so many consecutive orders, trigger an email)

1. Admin must receive the order and change the status of the pizza as “order received”, “In the kitchen” and “Sent to delivery”.

1. For every update from admin, the status change must be reflected in the user dashboard.

1. Integrate polling for pizza status update from client to server. 

