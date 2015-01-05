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
<li>a href="http://addons.oscommerce.com/info/7703/v,23">Tab Menu Section (TMS)</a><BR>With this add-on you can add a tab-menu with content to the products site, see screenshot.jpg inside of this package.
This contribution is very useful if you have a lot of content for articles and no space on the article page. For example,
you can create tabs for: Description, Additional Images, Reviews, Related Products, Prices, Twitter, Facebook etc.
<li><a href="http://addons.oscommerce.com/info/8751/v,23">Choose destination on Log in if cart has items</a><br>This addon detects if an item is in the customers shopping cart when they log in, if there is then they are presented with a choice page.
<li><a href="http://addons.oscommerce.com/info/8782/v,23">Display month name in other languages</a><br>shows correct name of months for standard oscommerce installation, supported languages English, German and Spanish. For other languages, please follow the same method, please remember to modify according to your language_id.
<li><a href="http://addons.oscommerce.com/info/8138/v,23">Mouse over product images</a>
<li><a href="http://addons.oscommerce.com/info/8792/v,23">Automatically add QR Code containin product url to product ino</a>
<li><a href="http://addons.oscommerce.com/info/8794/v,23">Purchases Addon</a><br>This addon will allow you to key in products that you have bought from your suppliers/manufacturers so that you can keep track of the purchases that you have made, to view your current stock levels of each product, and to view the stock flow of your items.
This addon will appear in your admin page on the left below "Catalog".
<li><a href="http://addons.oscommerce.com/info/8378/v,23">Shop By Attribute</a><br>This contribution allows you to add a a Shop by feature on your site so you customers can shop by color, size or any other attribute you have.
<li>< a href="http://addons.oscommerce.com/info/8364/v,23">PDF Datasheet</a><br>This addon creates a PDF document containing the information found on each of your osCommerce product pages. This allows your customer to save or print a nice-looking catalog page for each of your products.
<li><a href="http://addons.oscommerce.com/info/8868/v,23">Display Both Products & Categories</a><br>
By default osCommerce only displays the products contained in a category if the category happens to contain both products and other subcategories. Since users browsing the web site might not notice that the category contains subcategories if they are listed only in the categories info box I wanted to display both the subcategories and the products contained in the category in the main window. This modification allows you to do that with simple changes to only one file.
<li><a href="http://addons.oscommerce.com/info/7993/v,23">One Page Checkout for 2.3.1</a>
<li><a href="http://addons.oscommerce.com/info/8982/v,23">Thumbnail Pop-Up</a><br>his simple add-on replaces the default 2.3+ image functionality in product_info.php to give the image pop-up directly when clicking on the thumbnails.
<li></a href="http://addons.oscommerce.com/info/8988/v,23">Gray Oscommerce 2.3.3.4 Template</a><br>Simple Gray template for 2.3.3.4 utilizing a Jquery UI Bootstrap style skin and Colorbox image popup.
</ol>
