tapis

Dette er mit forsøg på at lave et lagersystem til mit værksted, et hackerspace, en forening med mange forskellige slags dimser/dutter de skal holde styr på.

Systemet er baseret på et stykke E-handelssoftware som bliver kraftigt modificeret for at opfylde det nye behov.

Indholdet af de forskellige afsnit ovenfor vil blive specificeret her:
<ul>
    <li><b>Original</b>
        <ul>
            <li>Indeholder skærmdump af phpinfo på det webhotel (Gigahost) som siden laves på, samt originalfilerne, der                 modificeres på.
                <ul><li>Først sættes databasen op på dit webhotrel
                    <li>Herefter uploades alle filerne til webhotellet. Når FTP-klienten er færdig med at uploade alle                          filerne, åbnes en browser som sættes til at pege på adresen http://dinhjemmeside.dk/install
                    <li>Du skal bruge dit servernavn, login til databasen (brugernavn og password) samt navnet på                                databasen
                    <li>Det tager under 5 minutter at installere standardversionen. Når det er gjort kan man slette                             install-folderen
                </ul>
        </ul>
    <li><b>Version_2 - Easy Populate</b>
        <ul>
            <li>Filerne til dette add-on kan hentes <a href="http://addons.oscommerce.com/info/7725">her</a>
            <li>EasyPopulate gør det lettere at oprette ens database/varekartotek når der kommer mange produkter, 
                forskellige sprog, mange atrinutter osv. fordi det nu kan ske ved at down- og uploade en cvs-fil, som
                man kan lave i Excel, Google Documents eller OpenOffice
            <li>Følgende foldere og filer er rettet/uploadet under installationen.
                <ul><li>Oprettet en folder ved navn <i>temp</i>
                    <li>I folderen <i>admin</i> er følgende uploadet:
                        <ul>
                            <li>Folderen <i>EPDocumentation</i>, der indeholder <i>contents.htm</i>, <i>index.html</i>                                 & <i>links.html</i>
                            <li>filen <i>easypopulate.php</i>, <i>easypopulate.php.orig</i> &                 
                                <i>easypopulate_functions.php</i>
                        </ul>
                    <li>Ud over ovenstående filer, der bare skal uploades er der rettelser til en enkelt fil. Læs
                        evt vejledningen, der følger med filen
                </ul>
        </ul>
    <li><b>Version_3 - Products Extra Fields</b>
        <ul>
            <li>Filerne til dette add-on kan hentes <a href="http://addons.oscommerce.com/info/7810">her</a>
            <li>Products Extra Fields giver mulighed for let at oprette nye felter til dine produkter. F.eks. et felt 
                stregkoder, lokation, længder osv.<br>
                Værdierne er søgbare. De felter du opretter dukker op som søgbare i 'Avanceret søgning'
            <li>Følgende folderer og filer er rettet/uploadet under installationen:
                <ul><li>I folderen <i>admin => images </i> er følgende uploadet:
                    <ul>
                        <li>Filen <i>EPF_Example_Image.jpg</i>
                    </ul>
                    <li>I folderen <i>admin => includes => languages => english </i> er følgende uploadet:
                    <ul>
                        <li>Filerne <i>extra_fields.php</i> & <i>extra_values.php</i>
                    </ul>
                    <li>I folderen <i>admin</i> er følgende uploadet:
                    <ul>
                        <li>Filerne <i>extra_fields.php</i> & <i>extra_values.php</i>
                    </ul>
                    <li>I folderen <i>images</i> er en folder med navn <i>eps</i> oprettet. (mappen er tom)
                    <li>I folderen <i>includes</i> er følgende fil uploadet:
                    <ul>
                        <li>Filen <i>template_top_extra_fields.php</i>
                    </ul>
                    <b>Du mangler filerne i mappen changed files!!!!!!!!!!!
                    
</ul>



<br><br><br><br><br>
<ol>
<li><a href="http://addons.oscommerce.com/info/8728/v,23">Show order id</a><br>A single line to show orders id in order page or where you wish, no upload required, just add a single line.
<li><a href="http://addons.oscommerce.com/info/8741/v,23">Skip Payments Page</a><br>This add-on is written to skip the payments page if the basket total is zero.
<li><a href="http://addons.oscommerce.com/info/8742/v,23">Skip Shipping Page</a><br>
This add-on is written to skip the shipping page if the basket total is zero and the total weight is zero. You can amend these rules to reflect your requirements.
<li><a href="http://addons.oscommerce.com/info/7703/v,23">Tab Menu Section (TMS)</a><BR>With this add-on you can add a tab-menu with content to the products site, see screenshot.jpg inside of this package.
This contribution is very useful if you have a lot of content for articles and no space on the article page. For example,
you can create tabs for: Description, Additional Images, Reviews, Related Products, Prices, Twitter, Facebook etc.
<li><a href="http://addons.oscommerce.com/info/8751/v,23">Choose destination on Log in if cart has items</a><br>This addon detects if an item is in the customers shopping cart when they log in, if there is then they are presented with a choice page.
<li><a href="http://addons.oscommerce.com/info/8782/v,23">Display month name in other languages</a><br>shows correct name of months for standard oscommerce installation, supported languages English, German and Spanish. For other languages, please follow the same method, please remember to modify according to your language_id.
<li><a href="http://addons.oscommerce.com/info/8138/v,23">Mouse over product images</a>
<li><a href="http://addons.oscommerce.com/info/8792/v,23">Automatically add QR Code containin product url to product ino</a>
<li><a href="http://addons.oscommerce.com/info/8794/v,23">Purchases Addon</a><br>This addon will allow you to key in products that you have bought from your suppliers/manufacturers so that you can keep track of the purchases that you have made, to view your current stock levels of each product, and to view the stock flow of your items.
This addon will appear in your admin page on the left below "Catalog".
<li><a href="http://addons.oscommerce.com/info/8378/v,23">Shop By Attribute</a><br>This contribution allows you to add a a Shop by feature on your site so you customers can shop by color, size or any other attribute you have.
<li><a href="http://addons.oscommerce.com/info/8364/v,23">PDF Datasheet</a><br>This addon creates a PDF document containing the information found on each of your osCommerce product pages. This allows your customer to save or print a nice-looking catalog page for each of your products.
<li><a href="http://addons.oscommerce.com/info/8868/v,23">Display Both Products & Categories</a><br>
By default osCommerce only displays the products contained in a category if the category happens to contain both products and other subcategories. Since users browsing the web site might not notice that the category contains subcategories if they are listed only in the categories info box I wanted to display both the subcategories and the products contained in the category in the main window. This modification allows you to do that with simple changes to only one file.
<li><a href="http://addons.oscommerce.com/info/7993/v,23">One Page Checkout for 2.3.1</a>
<li><a href="http://addons.oscommerce.com/info/8982/v,23">Thumbnail Pop-Up</a><br>his simple add-on replaces the default 2.3+ image functionality in product_info.php to give the image pop-up directly when clicking on the thumbnails.
<li></a href="http://addons.oscommerce.com/info/8988/v,23">Gray Oscommerce 2.3.3.4 Template</a><br>Simple Gray template for 2.3.3.4 utilizing a Jquery UI Bootstrap style skin and Colorbox image popup.
<li><a href="http://addons.oscommerce.com/info/8991/v,23">Fast Status change button</a><br>it's little addon for faster order status change. If you are changing order's statuses with same comments, you can prepare new update buttons like bind in CounterStrike.
<li><a href="http://addons.oscommerce.com/info/9017/v,23">Customer Checkout Blacklist</a><br>This module will help block potentially fraudulent customers checking out on your shop and preventing future charge-backs; whilst retaining the customer on the store to keep a record of the transactions and to be able to communicate with said customer.
<li><a href="http://addons.oscommerce.com/info/9014/v,23">Advanced Categories Box V1.0</a><br>This is an osCommerce 2.3.x rewrite of the original RC2 version of the categories box. The primary differences between this and the osCommerce version are as follows:
    <ol><li>Easy N level categories navigation.
        <li>A sidebar menu is included to make it easy to go to any category without requiring multiple mouse clicks.
        <li>A nice little pointer image replaces the -> text to indicate that a category has a subcategory.
    </ol>
<li><a href="http://addons.oscommerce.com/info/9047/v,23">categories and products on one page (cap)</a><br>If sub-categories and products exists in one categorie, only the products are shown. The sub-categories are only shown in the category box. With this contribution the sub-categories and the products are both shown at the same time.
<li><a href="http://addons.oscommerce.com/info/9051/v,23">Common Product Notes for osCommerce 2.3</a><br>This contribution provides an easy way to add footnotes to products such as "discontinued when sold out" or "limited to stock on hand". The contribution is multi-language capable with a separate translation of the note for each installed language. Notes are displayed like they would be in a book with superscript numbers behind the product name indicating applicable notes and the actual note explanations at the bottom of the page.
<li><a href="http://addons.oscommerce.com/info/8384/v,23">Categories Expanded</a><br>Categories and subcategories are visible and expanded default version of oscommerce 2.3
<li><a href="http://addons.oscommerce.com/info/7717/v,23">Login Box</a><br>Adds a login box to left/right column
Displayes the My Account Links if logged in (optional) Displays a welcome greeting with customers first name (optional)
<li><a href="http://addons.oscommerce.com/info/9098/v,23">If price = 0.00 dont display price (Update)</a>
<li><a href="http://addons.oscommerce.com/info/9089/v,23">Shopping List</a><br>This addon provides a Shopping List that your customers can use to keep track of items that they want to reorder periodically, or that they want to save for a future order. It was designed for an osCommerce store that sells consumables, but it works with any type of business that wants to increase repeat business.
<li><a href="http://addons.oscommerce.com/info/8306/v,23">Social Login</a><br>This plugin adds social login on an osCommerce site letting users log in through their existing IDs such as Facebook, Twitter, Google, Yahoo and over 15 more! This eliminates lengthy registration process i.e. filling up a long registration form, verifying email ID, remembering another username and password so your users are just one click away from logging in to your website. Other than social login, this plugin also provides User Profile Data and Social Analytics.
<li><a href="http://addons.oscommerce.com/info/8490/v,23">Extra pages-info box w/ admin for OSC2.3</a><br>Do you need an "About Us" page? Maybe a "Company News" page that needs updating?
Now you can make as many as you want with the links in 1 new Information Box.
This contribution allows you to create and manage new pages (like Shipping or Conditions) on the fly.
It also creates a new box that holds the page names which are links to those pages.
In Admin, you click new, enter a title and the page text or HTML. You can Add, Edit, Delete pages as well as turn them on and off with Status. 
When you create a new page, the link in the box appears automatically!
If you delete a page or turn it off with Status, the link in the box disappears automatically!
<li><a href="http://addons.oscommerce.com/info/7724/v,23">Down for Maintenance</a>
<li><a href="http://addons.oscommerce.com/info/8555/v,23">Notify when back in stock</a><br>This add-on will give your customers the option to contact you to register their interest in purchasing youre out of stock products when they return to stock.
It checks stock levels and if a selected item is out of stock it will replace the add to cart button with a notify me button, once clicked will take the user to another "notify" page, that contains the product information, they then enter their details and click continue and you will receive an email from the users email making it easy to reply once back in stock.
<li><a href="http://addons.oscommerce.com/info/9169/v,23">NotifyVisitors - Notification Management Software</a><br>Create notifications and show them to target audience based on multiple filters like location, traffic source, browser or device type, visit frequency or duration, time of day, page views, operating system, cookie, leave intent targeting, custom data rules and many more.
<li><a href="http://addons.oscommerce.com/info/7786">QTpro for osc 2.3</a><br>Track and manage attribute stock.
You need this if you sell 1 items with various attributes, and you want to control stock on attribute level.
<li><a href="http://addons.oscommerce.com/info/7702/v,23">Cron Simulator V 1.0</a>
<li><a href="http://addons.oscommerce.com/info/7796/v,23">New Orders Notification</a><br>If anyone would like to receive an email when orders are placed without using up your extra orders field in admin. This is a 1 line add on only takes 5 mins or less.
<li><a href="http://addons.oscommerce.com/info/7914/v,23">Quantity Box on Product Info Page</a><br>Update to Quantity Box on Producy Info Page that is found <a href="http://addons.oscommerce.com/info/7430">here</a>
<li><a href="http://addons.oscommerce.com/info/7930/v,23">Welcome Email username & password</a><br>ADD CUSTOMERS USERNAME & PASSWORD TO WELCOME EMAIL
<li><a href="http://addons.oscommerce.com/info/8146/v,23">Unit of Weight</a><br>It is fairly easy for myself as a developer to remember what the weight field is on the "Add a product page" in the admin. But for someone who adds products infrequently it can be a mystery. Do I use kilograms or lbs, or ounces or grams or some other unit? This add on will help address that problem.
This add-on will let the shop owner specify which weight unit they want to use for their shop and also let them enter the weight in a different unit and convert it to the main specified unit of weight.
<li><a href="http://addons.oscommerce.com/info/8096/v,23">Products Specifications</a><br>This addon allows the addition of an unlimited number of
specifications to the site's products. These can be used for:
1. A table of specifications on the Product Info page.
2. A comparison table showing the specifications of a group of products.
3. A set of filters to allow the customer to show only products that meet
certain criteria. This could be all AGP video cards with 256MB of memory, the
parts for a 1992 Yugo, or anything else you might want to set up.
4. Feeds to search engines and shopping sites needing extra data fields
<li><a href="http://addons.oscommerce.com/info/8260/v,23">add field to shopping cart</a><br>A new field is added to the table products. The data of this new field is shown on the one hand at the product_info-page after the products description and on the other hand as an additional info to the comment in the shopping_cart (s. screenshots).
<li><a href="http://addons.oscommerce.com/info/8523/v,23">Member Approval 1.6</a><br>This module will allow administrators to approve members before they have access to the shopping cart facilities.
Customers will follow the usual signup routine, whereby on completion the site administrator receives an e-mail notifying that a new customer has signed up.
<li><a href="http://addons.oscommerce.com/info/8582/v,23">Cleared Checkout Layout</a><br>The position of the checkout bar moved from bottom to the top of the page and numbers have been added to it.
At the checkout-confirmation page the arrangement of shipping, payment, etc was shifted to the bottom.
At the checkout-confirmation page the layout of the product list was changed and a product image was added to each item.
<li><a href="http://addons.oscommerce.com/info/8588/v,23">Cleaning statistics</a><br>Cleaning statistics for: most watched and most purchased, adapted to version 2.3.3
<li><a href="http://addons.oscommerce.com/info/8627/v,23">Suspending Customer Account</a><br>This addon allows you to lock a user account. For example, if a customer has not paid, You can lock his account. Customer can contact You for more info with contact form.
<li><a href="http://addons.oscommerce.com/info/8721/v,23">product_listing as list or grid</a><br>The layout of product_listing can be shown as a list (s. list.gif) or as a grid (s.grid.gif).
In the admin-area you can choose the way of display (s. admin.gif).
In the grid-layout 3 columns are the default value. If you want more than 3 columns, just change the value in line 98 < if ($count_column > 2) > accordingly.
<li><a href="http://addons.oscommerce.com/info/8794/v,23">Purchases Addon</a><br>This addon will allow you to key in products that you have bought from your suppliers/manufacturers so that you can keep track of the purchases that you have made, to view your current stock levels of each product, and to view the stock flow of your items.
This addon will appear in your admin page on the left below "Catalog".
<li><a href="http://addons.oscommerce.com/info/8880/v,23">product description language</a><br>n the admin when the product description in some language stay empty, you can try do this modification:
<li><a href="http://addons.oscommerce.com/info/8939/v,23">CMS for oscommerce</a><br>oscommerce cms updated for the new version 2.3.1 
<li><a href="http://addons.oscommerce.com/info/8672/v,23">Quick Inventory</a><br>Features:
- Easy to Install and use
- Various options to search products to update the inventory. Those options are Search by Products Model, Select a product by Model, Search by Category, Search By Brands.
- With the check box options, the products images also will be display.
<li><a href="http://addons.oscommerce.com/info/9010/v,23">Multi Orders Update V1.0 - (eng-fra-ita)</a><br>it's simple, when you have a lot of orders, i'm sure you want to updates the pending or another status. but the other contribution i found update only statuses;
this one updates statuses, you can add comments by orders, and when you submit the store send mail to customers with his new status and his own comment.
<li><a href="http://addons.oscommerce.com/info/9030/v,23">Contribution Tracker</a><br>This package will allow you to keep track of your add-ons to osCommerce and notify you when updates are available.
<li><a href="http://addons.oscommerce.com/info/9104/v,23">404 Page Not Found Redirect to index</a>
<li><a href="http://addons.oscommerce.com/info/9135/v,23">Alternative Administration System v0.3</a><br>
Innovative way to manage products, and edit categories. Better multitasking tools with a new temporary products list. Sort and view your stock the way you want to with customized columns and category views. Display important product information directly in your full category view without having to run a special report. Easily manage and maintain your store's specials for products in a completely new way. Best of all is the completely reinvisioned Attribute Manager that allows for easy virtual product management. No more customer complaints because of faulty download paths.
<li><a href="http://addons.oscommerce.com/info/9087/v,23">Database Check Tool 1.4</a><br>This contribution will allow you to check your database for simple errors such as duplicate product names, products price £0, products no weight, duplicate products_to_categories, categories no products and more.
It also check for illogical database records such as product to category records that point to non-existent categories or product.
if you load categories longer than 32 characters using easypopulate this add-on allows you to clear out the whole thing, ten you can correct the EP file and start again.
Results have clickable buttons and links to delete records or edit them through categories.php in admin. 
<li><a href="http://addons.oscommerce.com/info/8273/v,23">Clean orange template for 2.3.1</a><br>A very easy on the eye orange template for oscommerce version 2.3.1.
<li><a href="http://addons.oscommerce.com/info/7912/v,23">Beautiful Breadcrumbs</a><br>
Replaces the product model to product name when viewing a product in category view, Adds the product model to the end of the bread crumb only when viewing in manufacturer view mode.
<li><a href="http://addons.oscommerce.com/info/7727/v,23">OSC PDF Catalogue 2.1</a><br>This is an updated version of the 2.0.9 release. The only changes are to make the contribution compatible with osCommerce v2.3.1.
<li><a href="http://addons.oscommerce.com/info/7986/v,23">Inactive User Report/Removal version 2.0.1</a><br>This small report for admins shows all inactive users. Inactive means: User Creates an account and never made an order.
You also can see: Newsletter YES or NO. Customers Name and Mailadress with link to mail him
<li><a href="http://addons.oscommerce.com/info/7763/v,23">Low Stock Report v1.4<br>The purpose for this add on is to report the stock level of the products in your shop and highlight the products which are under stock level. Also, it will keep track the stock level for you and send the notification on top header in admin if the products stock level needs to be filled up.
<li><a href="http://addons.oscommerce.com/info/9151/v,23">qrcode for invoice and packing for 2.3.x and BS2334</a>
<li><a href="http://addons.oscommerce.com/info/9184/v,23">PayPal App</a><br>The PayPal App for osCommerce Online Merchant bundles all official PayPal payment modules including Log In with PayPal into one App package.
<li><a href="http://addons.oscommerce.com/info/8497/v,23">Configuration Infobox Multilingual-2.3.1</a><br>I have made the Configuration Infobox in the Admin CP multilingual. If yor browser turn on german, it's shows the box in German.
If your brower in english, it's shows the box in english.
<li><a href="http://addons.oscommerce.com/info/8065/v,23">Scroll boxes</a><br>Scroll whats new box and specials box for 2.3 , some extra functions.
<li><a href="http://addons.oscommerce.com/info/9177/v,23">Product Delete Delay</a><br>Have you ever deleted a product from your web site and then wished that you hadn't done so? This contribution will help by delaying actual product deletion for a selectable number of months. You may restore any deleted product easily so long as you do so before the time set for permanent deletion expires.
<li><a href="http://addons.oscommerce.com/info/8057/v,23">Optional Related Products</a>
<li><a href="http://addons.oscommerce.com/info/8114/v,23">Compare Products</a>
<li><a href="http://addons.oscommerce.com/info/8545/v,23">Unique Order Number</a><br>
This contribution will create a unique Order Number, which is basically based on php's date() function.
The order number will consist of: Month, Year, Hour, Minute, Second. Basically:
date("mdY-His") = mmddyyyy-hhmmss (14 DIGITS)
<li><a href="http://addons.oscommerce.com/info/1611">More_Pics_6 for 2.2 ms2</a><br>Add UP to 6 more Pics to Oscommerce 2.2 ms2. This will allow you to use 0-7 pics with oscommerce 2.2 ms2
<li><a href=""></a><br>
<li><a href=""></a><br>
<li><a href=""></a><br>
<li><a href=""></a><br>
<li><a href=""></a><br>
<li><a href=""></a><br>
<li><a href=""></a><br>
<li><a href=""></a><br>
<li><a href=""></a><br>
<li><a href=""></a><br>
<li><a href=""></a><br>
<li><a href=""></a><br>
<li><a href=""></a><br>
<li><a href=""></a><br>
<li><a href=""></a><br>
<li><a href=""></a><br>
<li><a href=""></a><br>
<li><a href=""></a><br>
<li><a href=""></a><br>
<li><a href=""></a><br>


</ol>
