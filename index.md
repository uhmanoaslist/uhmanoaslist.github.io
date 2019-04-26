[Project Board](https://github.com/uhmanoaslist/uhmanoalistcode/projects/1)

[Repository](https://github.com/uhmanoaslist/uhmanoalistcode)

[Deployed Website](http://uhmanoaslist.meteorapp.com)

# About UHManoasList

UHManoasList is a service that is going to be available for UH Manoa students. Students who have an interest in selling or buying school or campus living related objects would use this service to do just that. This service would be a method for students to sell some things that they think that another student would find useful but no longer need themselves, such as textbooks or a piece of furniture for a dorm room. Similarly, it is a method to buy an item you think you might be interested in from sellers of an object of that nature.

# Intended Functionality

This application is meant specifically for UH students, faculty, and staff. Our application will make sure that buyers and sellers fit within these categories and buyers and sellers will connect to the service through their UH credentials. The goods and services being sold on this service should also be relevant to UH students. Transactions must be carried out on-campus if a seller wants to meet off-campus, that could be a potential red flag.

 * You will be able to search for goods and services through categories, such as textbooks and furniture among other things.

 * You can receive notifications through email or text. Users can set up notifications to appear to alert them when an item they are looking for is listed for sale.

 * The system supports photos to pair with items. You can specify images by URL or by uploading an image.

 * You can mark content or other users as inappropriate. The admins will look into this case and possibly ban users who violate the Terms of Use.

All of these functionalities are tentative and have not been developed yet, this page will update as progress has been made in development.

# User Guide

Each user will start with the landing page, which provides basic information as to what UHManoasList is.  New and returning users must create a new account or sign in to gain full access to the website.

<img class="ui centered image" src="/images/LandingPage.png">

[Landing Page](http://uhmanoaslist.meteorapp.com/#/)


Upon logging in with the correct credentials, functionality to 
  *Sell an item*,
  *View Categories page to buy an item*,
  *View different user profiles to buy items*,
will be granted.

To list an item for sale, head to the *Sell an Item* page and fill out the respective information, the name of the item, your asking price for the item, the condition the item is in, and a image to show what the item looks like and what category you believe your item falls under as well as a description for the item you are selling. Press submit to put up your item for sale.

<img class="ui centered image" src="/images/sell1.png">

[Sell Page](http://uhmanoaslist.meteorapp.com/#/add)

Each user will have a profile page with the ability to view items that they are putting up for sale, as well as items that they are potentially looking to buy.

To buy an item, head to the categories page to browse the numerous different categories and different items within their respective categories for sale.  

<img class="ui centered image" src="/images/CategoriesPage.png">

[Categories page](http://uhmanoaslist.meteorapp.com/#/list)

Each category will include items for sale realated to that category.

<img class="ui centered image" src="/images/CategoryPage2.png">

[Category page](http://uhmanoaslist.meteorapp.com/#/category/Electronics)


To see more details about an individual item, click the view button on the item you want to buy.  You will be redirected to the item page where you can look at the seller's profile page which contains the contact information to buy the item.

<img class="ui centered image" src="/images/ItemPage.png">

[Item Page](http://uhmanoaslist.meteorapp.com/#/edit/WkNRoWoM5uHgJE99p)

If you find any suspicious or illegal items, head to the report page to send an alert to our admins by providing a description of why the item needs to be checked over and press submit.

<img class="ui centered image" src="/images/ReportPage.png">

[Report Page](http://uhmanoaslist.meteorapp.com/#/report/WkNRoWoM5uHgJE99p)

## Developer Guide

To download the source code for UHManoasList, head to the [repository](https://github.com/uhmanoaslist/uhmanoalistcode) and download the master branch.

To run the native app, cd into the master branch directory of your computers native terminal and get to the app folder 

<img class="ui centered image" src="/images/meteor2.png">

Then, install meteor in the app folder using this command

<img class="ui centered image" src="/images/Meteor1.png">

Then run *meteor npm run start* within the app folder head to http://localhost:3000 to see the app running.

<img class="ui centered image" src="/images/meteor3.png">

To modify the native source code, we recommend you use IntelliJ Idea to modify the source code to your liking. You can download it [here](https://www.jetbrains.com/idea/download/#section=mac)
