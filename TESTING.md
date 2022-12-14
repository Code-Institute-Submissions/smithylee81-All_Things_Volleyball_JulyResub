# All Things Volleyball - Testing Documentation

The Main README documentation can be found under [README.md](README.md)

## **Contents**

- [**User Story Testing**](#user-story-testing)
- [**Home Page Testing**](#home-page-testing)
  - [**My Account Testing**](#my-account-testing)
    - [Register](#register)
    - [Log In](#log-in)
     >1. [Forgot Password](#forgot-password)
     >2. [My Profile](#my-profile)
     >3. [Update Information](#update-information)
  - [**Product Management**](#product-management)
  - [**Shopping Bag Testing**](#shopping-bag-testing)
    - [Shopping Bag Empty Keep Shopping](#shopping-bag-empty-keep-shopping)
    - [Add to Bag](#add-to-bag)
    - [Update Quantity](#update-quantity)
    - [Remove Item](#remove-item)
    - [Keep Shopping](#keep-shopping)
    - [Secure Checkout](#secure-checkout)
    >1. [Adjust Bag](#adjust-bag)
    >2. [Complete Order](#complete-order)
  - [**Search Bar Testing**](#search-bar-testing)
  - [**Main Logo Testing**](#main-logo-testing)
- [**Product Category Testing**](#product-category-testing)
    - [***All Products***](#all-products)
    >1. [By Price](#by-price)
    >2. [By Rating](#by-rating)
    >3. [By Category](#by-category)
    >4. [All Products](#all-products)
    - [***Clothing***](#clothing)
    >1. [Leggings](#leggings)
    >2. [T-Shirts & Tank Tops](#T-Shirts-&-Tank-Tops)
    >3. [Hoodies](#hoodies)
    >4. [All Clothing](#all-clothing)
    - [***Accessories***](#accessories)
    >1. [Bags](#bags)
    >2. [Bottles](#bottles)
    >3. [Knee Pads](#knee-pads)
    >4. [All Accessories](#all-accessories)
    - [***Equipment***](#equipment)
    >1. [Balls](#balls)
    >2. [Nets](#nets)
    >3. [All Equipment](#all-equipment)
- [**Product Page Testing**](#product-page-testing)
    - [Product Page Keep Shopping](#keep-shopping)
    - [Product Size Option](#product-size-option)
    - [Product Page Add to Bag](#add-to-bag)
    - [Product Page Go to secure checkout](#product-page-go-to-secure-checkout)
- [**Blog and Comments Testing**](#blog-and-comments-testing)
- [**Validators and Tools**](#validators-and-tools)
- [**Browser Testing**](#browser-testing)
- [**Mobile and Tablet Testing**](#mobile-and-tablet-testing)
- [**Significant Bugs**](#significant-bugs)
- [**Further possible improvements**](#further-possible-improvements)

# **User Story Testing**
## Home Page Testing
### ***My Account Testing***
- ## Register

**Acceptance Criteria**: A user should be able to register for an account, have an option to sign-in form that selection if they remember they "Already have an Account"? and be able to see clearly what sections of the registration form to complete and a clear indication of what information is required ie: **E-mail address**, **Username** and **Password**. The user should also be given hints if any fields are left blank and if their email address or username is already registered oe exists for another user. The user should recieve an email verification process.

**Summary:** Form is easy to use, has pre-fixes in the required fields and a "Sign Up" button. The form also has warning messages for any fields left blank to advise the user to fully complete their information. 

![account register form](static/testingimages/accountregisterform.png "accountregisterform")
![Reg Email Required](static/testingimages/RegEmailRequired.png "RegEmailRequired")
![Reg Username Required](static/testingimages/RegUsernameRequired.png "RegUsernameRequired")
![Reg Password Required](static/testingimages/RegPasswordRequired.png "RegPasswordRequired")
![Reg Password Repeat Required](static/testingimages/RegPasswordRepeatRequired.png "RegPasswordRepeatRequired")
![Pass Too Short Note](static/testingimages/PassTooShortNote.png "PassTooShortNote")
![User Email Already Registered](static/testingimages/UserEmailAlreadyRegistered.png "UserEmailAlreadyRegistered")
![User Name Already Exists](static/testingimages/UserNameAlreadyExists.png "UserNameAlreadyExists")
![Email Verification Notice](static/testingimages/EmailVerificationNotice.png "EmailVerificationNotice")
![Terminal Verification Email](static/testingimages/TerminalVerificationEmail.png "TerminalVerificationEmail")
![Confirm Email Note](static/testingimages/ConfirmEmailNote.png "ConfirmEmailNote")
![Confirmed Email Success](static/testingimages/ConfirmedEmailSuccess.png "ConfirmedEmailSuccess")
![Confirmed Email Terminal](static/testingimages/ConfirmedEmailTerminal.png "ConfirmedEmailTerminal")

**Outcome: Pass**

- ## Log In

**Acceptance Criteria**: A user should be able to sign in to their account and have the option to view their profile, see their default delivery details and order history.

**Summary:** Sign in form is easy to use, has pre-fixes in the required fields and a "Sign Up" button. The form also has warning messages for any fields left blank to advise the user to fully complete their information, as per the above screenshots. 'Toast' messsges are also displayed ot tell the user they have successfully signed in.

![Sign In Success](static/testingimages/SignInSuccess.png "SignInSuccess")

**Outcome: Pass**

- ### Forgot Password

**Acceptance Criteria**: A user should be able to have the facility to reset their password should they forget it and go back to the login page should they remember it. The user should have clear instructions and information on what to do next.

**Summary:** Forgotten password form easy to use, has pre-fixes in the required field and a "Reset my Password" button. The form also has warning messages for any fields left blank to advise the user to fully complete their information, as per the above screenshots. 'Toast' messsges are also displayed ot tell the user they have successfully signed in.

![Pass Reset Option](static/testingimages/PassResetOption.png "PassResetOption")
![Pass Reset Warning](static/testingimages/PassResetWarning.png "PassResetWarning")
![Pass Reset Instructions](static/testingimages/PassResetInstructions.png "PassResetInstructions")
![Pass Reset Email Terminal](static/testingimages/PassResetEmailTerminal.png "PassResetEmailTerminal")
![Change Pass Option](static/testingimages/ChangePassOption.png "ChangePassOption")
![Password Warning Note](static/testingimages/PasswordWarningNote.png "PasswordWarningNote")
![Pass Change Success Note](static/testingimages/PassChangeSuccessNote.png "PassChangeSuccessNote")

**Outcome: Pass**

  - ### My Profile

**Acceptance Criteria**: A user should be able to access their own profile easily onced logged in and view my 'Default Delivery Information' & my 'Order History'.

**Summary:** Profile selection works well upon log-in and displays both delivery information and order history. 

![My Profile Test](static/testingimages/myprofiletest.png "myprofiletest")

**Outcome: Pass**

  - #### Update Information

**Acceptance Criteria**: A user should be able to access their own profile easily & update their delivery information. 

**Summary:** Update information button easy to see and saves new information accordingly with a **toast** alert section confirming the "profile updated successfully".

![Update Info Test](static/testingimages/updateinfotest.png "updateinfotest")

**Outcome: Pass**

### ***Product Management***

**Acceptance Criteria**: A a 'Superuser' I should be able to access the 'Product Management' section and add products and delete or edit where necessary. I should also be able to select an image if desired and have easy to use buttons available to add a product. I should also be able to edit or delete any item/product on each page of the site.

**Summary:** Superuser log in works with visibility of 'Product Management' option under the dropdown in 'My Account'. An easy to use form is presented and the options to select an image, cancel the activity and 'Add Product'. On each page of the site each individual product has the option for me to edit or delete. Screenshots below to demonstrate:

![Product Man](static/testingimages/ProductMan.png "ProductMan")

![Select Image](static/testingimages/SelectImage.png "SelectImage")

![Add Product](static/testingimages/AddProduct.png "AddProduct")

![Edit Delete Options](static/testingimages/EditDeleteOptions.png "EditDeleteOptions")

**Outcome: Pass**

### ***Shopping Bag Testing***

**Acceptance Criteria**: A user should be able to add items to their shopping bag, access their shopping bag, have the option to update the quantity of their selections, remove items they no longer require, an option to keep shopping and an option to go to the secure checkout. They should be able to complete their order securely and have clear instructions throughout with an option to adjust their shopping bag even at the point of the secure checkout.

**Summary:** All options for the above criteria are available and work well providing the user with ease of use for their shopping experience.

- #### Shopping Bag Empty Keep Shopping
![Bag Empty Note](static/testingimages/BagEmptyNote.png "BagEmptyNote")
- #### Add to Bag
![Add To Bag Note](static/testingimages/AddToBagNote.png "AddToBagNote")
- #### Update Quantity
![Update Bag Quantity](static/testingimages/UpdateBagQuantity.png "UpdateBagQuantity")
- #### Remove Item
![Remove Bag Item](static/testingimages/RemoveBagItem.png "RemoveBagItem")
- #### Keep Shopping
![Keep Shopping Option](static/testingimages/KeepShoppingOption.png "KeepShoppingOption")
- #### Secure Checkout
![Secure Checkout Option](static/testingimages/SecureCheckoutOption.png "SecureCheckoutOption")

  - ##### Adjust Bag
![Adjust Bag Option](static/testingimages/AdjustBagOption.png "AdjustBagOption")
  - ##### Complete Order
![Complete Order](static/testingimages/CompleteOrder.png "CompleteOrder")

**Outcome: Pass**

[Back to contents](#contents)
### ***Search Bar Testing***

**Acceptance Criteria**: A user should be able to search for items on the site and receive back the correct items.

**Summary:** All search criteria tried and brings back the correct items requested each time.

**Outcome: Pass**
### ***Main Logo Testing***

**Acceptance Criteria**: A user should be able to select the main logo to take them back to the home page no matter what page of the site they are on.

**Summary:** Main logo on all pages works well bringing the user back to the home page.

**Outcome: Pass**

[Back to contents](#contents)

## Product Category Testing

**Acceptance Criteria**: A user should also be able to use the selection bar at the top of the page to browse and select out the items they wish. Each section and dropdown should provide the user with their specific request.

**Summary:** All options selected from the selection bar and dropdown menu's display the correct items requested each time as demonstrated below, along with the filters to display items "Sort by..." such as Price 'low to high', Rating, Name and Category respectively. 
### ***All Products***
 - ##### By Price
![ByPriceOption](static/testingimages/ByPriceOption.png "ByPriceOption")
 - ##### By Rating
![By Rating Option](static/testingimages/ByRatingOption.png "ByRatingOption")
 - ##### By Category
![By Category Option](static/testingimages/ByCategoryOption.png "ByCategoryOption")
 - ##### All Products
Displays all products successfully.
### ***Clothing***
 - ##### Leggings
![Leggings](static/testingimages/Leggings.png "Leggings")
 - ##### T-Shirts & Tank Tops
![Ts and Tanks](static/testingimages/TsandTanks.png "TsandTanks")
 - ##### Hoodies
![Hoodies](static/testingimages/Hoodies.png "Hoodies")
 - ##### All Clothing
Displays all clothing successfully.

[Back to contents](#contents)

### ***Accessories***

 - ##### Bags
![Bags](static/testingimages/Bags.png "Bags")
 - ##### Bottles
![Bottles](static/testingimages/Bottles.png "Bottles")
 - ##### Knee Pads
![KneePads](static/testingimages/KneePads.png "KneePads")
 - ##### All Accessories
Displays all accessories successfully.

[Back to contents](#contents)
### ***Equipment***

 - ##### Balls
![Balls](static/testingimages/Balls.png "Balls")

 - ##### Nets
 ![Nets](static/testingimages/Nets.png "Nets")
 - ##### All Equipment
Displays all equipment successfully.

 **Outcome: Pass**

 ## Product Page Testing

 **Acceptance Criteria**: A user should be able to view each individual product, have the option to keep shopping and the option to add it to their shopping bag. Where size of clothes is relevent the option to choose size should display. Once any product has been added to the bag they should have the option on the page to go to the secure checkout. 

**Summary:** All options selected display the correct functions as demonstrated below.
- ##### Product Page Keep Shopping
![ProductPageKeepShopping](static/testingimages/ProductPageKeepShopping.png "ProductPageKeepShopping")
- ##### Product Size Option
![ProductSizeOption](static/testingimages/ProductSizeOption.png "ProductSizeOption")
- ##### Product Page Add to Bag
![ProductPageAddToBag](static/testingimages/ProductPageAddToBag.png "ProductPageAddToBag")
- ##### Product Page Go to secure checkout
![Product Page Secure Checkout](static/testingimages/ProductPageSecureCheckout.png "ProductPageSecureCheckout")

**Outcome: Pass**

 ## Blog and Comments Testing

 **Acceptance Criteria**: Posted blogs being able to be seen on the one page with the optin to enter into the actual blog itself where the user can read any comments about the blog, go back to the main blog page and have the option to add a comment should they wish to do so, the latter being a 'Future Feature' the developer would like to implement. Current custom models for this pull data through from the Django Administration backend. 

**Summary:** All options ('Visit our Blog!' and 'Read Comments') when selected display the correct pages and detail pulled from the Django Administration page as demonstrated below.

- ##### Blog Posts Main Page
![Visit Blog Posts Main Page](static/testingimages/VisitBlogPostsMainPage.png "VisitBlogPostsMainPage")

- ##### Read Blog and Comments Success
![Read Blog and Comments Success](static/testingimages/ReadBlogandCommentsSuccess.png "ReadBlogandCommentsSuccess")

- ##### How To Play Post Django Admin
![How To Play Post Django Admin](static/testingimages/HowToPlayPostDjangoAdmin.png "HowToPlayPostDjangoAdmin")

- ##### How To Play Comments Django Admin
![How To Play Comments Django Admin](static/testingimages/HowToPlayCommentsDjangoAdmin.png "HowToPlayCommentsDjangoAdmin")

**Outcome: Pass**

[Back to contents](#contents)

# Validators and Tools
### W3C Markup Validation
* [W3C Markup Validation](https://validator.w3.org/) was used to validate the HTML codes of the website in all pages. There were only minor errors and warnings such as:
  - missing a required instance of child element,
  - attribute must point to an element in the same document, 
  - Attribute http-equiv not allowed on element meta at this point,
  - Element meta is missing one or more of the following attributes: itemprop, property
  - Lots of "Bad value" errors due to the Jinja templating {} syntax; "{% static 'css/base.css' %} for attribute href on element link: Illegal character in path segment: { is not allowed" etc. 
  - Error: Non-space characters found without seeing a doctype first. Expected <!DOCTYPE html>, again due to Jinja templating {} syntax and using "{% extends "base.html" %}" etc.
  - Warning: Consider adding a lang attribute to the html start tag to declare the language of this document, again due to Jinja templating {} syntax and using "{% extends "base.html" %}" etc.

### W3C CSS Validation

* [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) was used to check the CSS syntax. The results show:
  - One Error in 'base.css" ; "Sorry! We found the following errors (1); URI : TextArea; 161		#000 is not a box-shadow value : #000. 
  - 6 'warnings':

![Base Css Validator Warnings](static/testingimages/BaseCssValidatorWarnings.png "BaseCssValidatorWarnings")

### JSHint
* [JSHint](https://jshint.com/) was used to check the JavaScript syntax. There were 3 minor warnings:
  - Three warnings; 
   1. "34	'template literal syntax' is only available in ES6 (use 'esversion: 6')."
   2. "98	'template literal syntax' is only available in ES6 (use 'esversion: 6')."
   3. "117	Missing semicolon."
### PEP8 Online
* [PEP8 Online](http://pep8online.com/) was used to check the Python syntax.There were only warnings about "line too long" or "indentation" for which most were all fixed accordingly. Some "lines too long" were left due to time constraints as these do not affect the overall code.

The only warning left is on file settings.py file where there are still 4 lines too long at variable AUTH_PASSWORD_VALIDATORS. The longest line here is 91 characters. As this is system's related string and doesn't affect readability of code this has been left as is:

![PEP8 Settings.py Line Too Long](static/testingimages/PEP8Settings.pyLineTooLong.png "PEP8Settings.pyLineTooLong")

![PEP8 Settings.py](static/testingimages/PEP8Settings.py.png "PEP8Settings.py.png")


[Back to contents](#contents)

## Browser Testing

Using Chrome Development tools, either via the pre-set mobile device resolutions or via the manual responsive tool (using `Google Lighthouse Inspection Tool`), the following was completed:

- Manual responsive testing via Chrome Development Tools, selecting `Inspect`.
- Cycling through each available device, and performing the tests as detailed above:
  - iPhone SE
  - iPhone 12 Pro
  - iPhone XR
  - Pixel 5
  - Samsung Galaxy S8+
  - Samsung Galaxy S20 ULtra
  - iPad Air
  - iPad Mini
  - Surface Pro 7
  - Surface Duo
  - Galaxy Fold
  - Samsung Galaxy A51/71
  - Nest Hub
  - Nest Hub Max
- Ensure all Features function,appear correctly from at least 320px wide and are presented appropriately on all viewports:
  - Interaction is enabled.
  - The majorty of the site fits on device's screen.
  - The content is legible.
  - The user can select all available options.
### Mobile and Tablet Testing

The website was physically tested on an iPhone 11, and an iPad. The following tests were completed:

- Ensure all interactive **icons** are distinguishable, identifiable, and are correctly sized and placed to allow users to interact with each of them via touchscreen individually.
- Ensure all inputs within data entry fields and forms respond appropriately to touchscreen devices.
- Ensure all text input fields respond appropriately to on-screen keyboards.
- Ensure the **Dropdown Nav** can be selected to collapse or reveal.

#### ***Chrome/Firefox/Edge/Safari (iOS)***

- All functionality worked as intended.

[Back to contents](#contents)


# Significant Bugs

### 1. The search bar function appears to drop down the page on mobile and tablet/smaller devices and overhangs the page content. The search icon does appear on reducing device size and functions well however very hard to see due to the presence of the main search bar also. 

- I struggled to fix this and hence giving a poorer user experience looking like the site is broke!

- I eventually deleted the "mobile-top-header.html" code which helped resolve duplicate icons being shown on reduction of screen size. However my placement of Blog, Account & Shopping Bag Icons remain poor on smaller screens. I'm assuming more time and adding some media queries would resolve this issue.

***Fixed: No***

### 2. Implementing a 'Blog' model, posts & comments was particularly a challenge for me, using a significant amount of time re-watching CI tutorial videos, sourcing web tutorials & YouTube Videos to assit in adding some 'custom models' to the project.

- Several code attempts tried along with viewing multiple web tutorials and YouTube videos (as outlined in the README.md document)

- I finally managed to render comments and blog posts pulling these through from the backend of the Django Administration site with the current code, following a few different tutorials & videos. This issue was presented given the developers very basic knowledge and current understanding of the Python and Django models, views, URL's etc. I believe if I had gained a deeper insight into these I may have been able to implement these a little more easily. 

***Fixed: Yes***


[Back to contents](#contents)

### Further possible improvements
* Further refactoring could have been done to improve clean code and readability. This was done only to small extend due to the time constraint.
* A more custom designed page for the Django admin dashboard could have been implemented in order to give shop owners/Superusers a much better user experience in controlling and maintaining the database.
* Further sytling and media queries to allow a better user experience on smaller screen devices. 
* Adding extra functions for the user to 'Add a Comment' & 'Add a Post' would complete the users experience of the Blog application. 

---
[Back to contents](#contents)

[Click here](README.md) to return to the main README.md.