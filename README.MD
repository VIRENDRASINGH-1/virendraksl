# Coffee Hut

[![Build Status](https://travis-ci.com/jamie/project.coffeehut.svg?branch=master)](https://travis-ci.com/jamie/projectcoffeehut)

###  https://project.jamiecoffeehut.com/
### https://jamiecoffeehut.com/
<p>
CoffeeHut is a web based application through which a user can order craft coffee drinks from their local coffee shop, CoffeeHut. Upon navigating to the application the user will be prompted to log in or create an account. Once the user logs in they can create a new order or view any previous orders they’ve placed. When creating a new order, the user can select a drink from the given menu. Each drink may be modified using a list of customizations that are offered. Users may also visit their Profile page to adjust login information and view previous orders. 

</p>

## Contributors:

### Frontend: 
Jamie
<br>

### Backend:
Jamie
</p>

## Demo:

<p> Front page, which includes an About Me, along with a confirmation card detailing if you are logged in. This card also displays if the user entered an incorrect email or if the user is not logged in.

<img style="display: block;-webkit-user-select: none;margin: auto;cursor: zoom-out;background-color: hsl(0, 0%, 90%);transition: background-color 300ms;" src="https://cdn.dribbble.com/users/3889620/screenshots/6909862/media/a404a638ceabeb755aa5f25d71666edc.jpg?compress=1&amp;resize=800x600&amp;vertical=top" width="800" height="600">

<p>Order Screen, where the user may select from the given options. The options are pulled from a MySQL database, and upon adding an item to the cart, the number within the Cart Icon on the Navigation bar is updated to depict the number of items within the cart. Future development would include an Admin only page, where the developer can dynamically add/remove menu items to the Database, which would update the Order Screen to include all options that are held within the MySQL database.

<img style="display: block;-webkit-user-select: none;margin: auto;cursor: zoom-out;background-color: hsl(0, 0%, 90%);transition: background-color 300ms;" src="https://img.freepik.com/free-vector/coffee-cafe-menu_1284-3844.jpg?w=740&amp;t=st=1657944567~exp=1657945167~hmac=e60cadf7d25c3291fe369672cbf091d41114b909c80b2d2a2899731ad3bf2b6c" width="740" height="740">

<p>The card below shows options the user may pick from to customize their drink. The card is a modal the overlays the interface. Upon clicking the "Add Drink to Order" button, the item will be added to the Cart and the modal will close. When the modal closes, the order cart modal will open on the right side of the screen, as is shown in the next image.

![](assets/images/Demo3.png)
![](public/assets/images/Demo3.png)

<p>The image below depicts the Order Cart Modal. This modal includes all drinks that have been added to the user's order, the price of each drink including additional customization, and the order total with included tax. This modal also includes a "remove item" feature beside each added drink incase the user would like to delete an item. Future development would modify the modal into a div that would not overlay over the entire interface. The updated div would remain open, allowing the user to open new drink cards while keeping the Order Cart up.

![](assets/images/Demo4.png)
![](public/assets/images/Demo4.png)

<p> Upon completing their order, the user will be taken to the Order Confirmation screen shown below. This allows the user to know that their order has been completed and is being processed. The user may see each item they selected, the modifications that have been made, the item's total price, and their order's total price. Upon completing their order, it can bee seen in the Navigation bar that the cart has been reset to include zero items. Future Development would allow the amount of time in the "Your order will be ready in x minutes" to be updated to accurately reflect how much time the order is estimated to take.

![](assets/images/Demo5.png)
![](public/assets/images/Demo5.png)

<p>The image below shows the Profile page. On the Profile page, the user is welcomed and shown the email associated with their account. The user may update their profile information, delete their account, and refresh the page so that it accurately reflects their changes. Below this, the user is shown their order history, in case they may want to recreate a previous order or forgot what items they have ordered before. 

![](assets/images/Demo6.png)
![](public/assets/images/Demo6.png)

<img alt="" class="hCL kVc L4E MIw" importance="auto" loading="auto" src="https://i.pinimg.com/564x/fb/e0/a9/fbe0a9273d4eb6a4b32bf7858279cb5b.jpg">