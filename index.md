<img width="200px" class="rounded float-start pe-4" src="../img/ethical-haccers_logo.png">

*Final Project*

### Project Files
<ul>
    <li>
        <a href="http://161.35.230.155/">Deployment</a>
    </li>
    <li>
        <a href="https://github.com/orgs/ethical-haccers/repositories">Ethical-HACCers Organization</a>
    </li>
    <li>
        <a href="https://github.com/orgs/ethical-haccers/projects/1/views/1">M1 Project Page</a>
    </li>
    <li>
        <a href="https://github.com/orgs/ethical-haccers/projects/5">M2 Project Page</a>
    </li>
     <li>
        <a href="https://github.com/orgs/ethical-haccers/projects/8">M3 Project Page</a>
    </li>
    <li>
        <a href="https://github.com/orgs/ethical-haccers/projects/8">M3 Project Page</a>
    </li>
    <li>
        <a href="https://docs.google.com/document/d/1xthjIASahe-UT9g0HBzNF65iaGU2X9AgG1eLLhN9xsU/edit?usp=sharing">TEAM CONTRACT</a>
    </li>
</ul>


[Click Here For Developer Guide](#developers-guide)


# Overview

## The Problem
The non-profit organization, Full Cycle Takeout, is confronted with a pressing issue. They operate a reusable takeout container program designed to replace single-use plates and clamshells at events. However, they are currently experiencing a substantial problem as they lose 20-30% of their containers due to event attendees taking them home. This situation jeopardizes the program’s goal of sustainability. They are seeking an efficient solution to hold customers accountable for returning their reusable containers, especially during their fast-paced environment events.

## Our Solution
Our goal is to design an app for the reusable takeout container program Full Cycle Takeout. They’re in need of a user interface that allows for users to ‘check out’ a reusable container and be sufficiently incentivised to return said container consistently. Additionally, the interface should be intuitive (so as to not require physical intervention). As a solution, a mobile-compatible app with a user-centered design would be able to automate the container rental process without too much hassle on the customer-end. 
A few mockup-page designs that we had in mind include utilizing external hardware like the proposed RFID chips/scanners to make user transactions more reliable. Having a ‘collection’ or database of existing containers and their chips would be an efficient way to keep track of the containers as they cycle through users. As for the accompanying application, it would be similar to pre-existing bike/scooter rental services that allow registered users to rent the containers without having to re-enter payment information repeatedly. The account system has the additional benefit of being able to link user-accounts to the corresponding RFIDs as they’re checked out and returned, holding users accountable for returning the containers. 
## Special Sauce
The sponsor described the types of events that Full Cycle Takeout has previously taken part of. As a more formal example, companies hosting large events that request the containers en-mass would require a different UI as opposed to a more casual event where containers are rented on an individual basis. On the admin side, the sponsors will be able to monitor the id’s of containers and their status of checkout-out, returned, cleaned, etc.

# Page Mockups

## Sign In
<img src="../img/sign_in_mock.png" width="600px" style="display: block; margin-left: auto; margin-right: auto;">

Sample of the sign-in page where the user inputs their email and password and is granted access to the rest of the site.

## Sign Up
<img src="../img/sign_out_mock.png" width="600px" style="display: block; margin-left: auto; margin-right: auto;">

Where a new user account can be created by entering a name, email, and password. Optionally a user can also choose to include the organization they are associated with.

## Container Return 
<img src="../img/return_mock.png" width="600px" style="display: block; margin-left: auto; margin-right: auto;">

The page where a user can scan the QR code on their container to log their return at a certified drop off site.

## Catalog 
<img src="../img/catalog_mock.png" width="600px" style="display: block; margin-left: auto; margin-right: auto;">

A catalogue page containing information for mass rentals (for specific events or for vendors).

# User Guide

## Container Rental
<img src="../img/rental.png" width="600px" style="display: block; margin-left: auto; margin-right: auto;">

The container rental form can be used to request a rental container form Full Cycle Takeout. The container ID can be found on the container that you wish you rent. The other fields will be automatically taken care of for you. (The autofill feature is not complete yet.)

## Order History
<img src="../img/history.png" width="600px" style="display: block; margin-left: auto; margin-right: auto;">

The Order History page can be used to track active container rentals, as well as you past completed orders.

## Admin Order History
<img src="../img/admin_history.png" width="600px" style="display: block; margin-left: auto; margin-right: auto;">

For Admin accounts, access to the admin history page allows you to view all orders, active and completed, along with the (account) owners of each order.

## FAQs
<img src="../img/faqs.png" width="600px" style="display: block; margin-left: auto; margin-right: auto;">

Have more questions about the Full Cycle Takeout process? You might find your answer on the FAQs page. It also includes information about the motivation behind Full Cycle Takeout.

## Landing Page
<img src="../img/mobile_landing_scrnsht.png" width="400px" style="display: block; margin-left: auto; margin-right: auto;">

The landing page contains access to other pages and will contain information about how the program works. The navigation bar at the top of the screen can be used to access the different pages and features of the Full Cycle Takeout Application.

# Developers Guide

After cloning the [repository](https://github.com/ethical-haccers/full-cycle-app), make sure you do this step first:

Start off in the console with.
```
meteor npm install
```
With meteor installed, we can start the app
```
meteor npm run start
```
To reset the application's database
```
meteor reset
```
All front-end files can be found within the directory:
<li>
    <a href="https://github.com/ethical-haccers/full-cycle-app/tree/main/app/imports/ui">app/imports/ui</a>
</li>

All server-side files can be found within the directories
<li>
    <a href="https://github.com/ethical-haccers/full-cycle-app/tree/main/app/imports/api">app/imports/api</a>
</li>
<li>
    <a href="https://github.com/ethical-haccers/full-cycle-app/tree/main/app/imports/startup">app/imports/startup</a>
</li>
<li>
    <a href="https://github.com/ethical-haccers/full-cycle-app/tree/main/app/client">app/client</a>
</li>

All CSS styling can be found within the file:
<li>
    <a href="https://github.com/ethical-haccers/full-cycle-app/blob/main/app/client/style.css">app/client/style.css</a>
</li>
