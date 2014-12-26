tapis

Dette er mit forsøg på at lave et lagersystem til mit værksted, et hackerspace, en forening med mange forskellige slags dimser/dutter de skal holde styr på.

Systemet er baseret på et stykke E-handelssoftware som bliver kraftigt modificeret for at opfylde det nye behov.

Indholdet af de forskellige afsnit ovenfor vil blive specificeret her:
<ul>
    <li>Original
        <ul>
            <li>Indeholder skærmdump af phpinfo på det webhotel (Gigahost) som siden laves på, samt originalfilerne, der                 modificeres på.
                <ul><li>Først sættes databasen op på dit webhotrel
                    <li>Herefter uploades alle filerne til webhotellet. Når FTP-klienten er færdig med at uploade alle                          filerne, åbnes en browser som sættes til at pege på adresen http://dinhjemmeside.dk/install
                    <li>Du skal bruge dit servernavn, login til databasen (brugernavn og password) samt navnet på                                databasen
                    <li>Det tager under 5 minutter at installere standardversionen. Når det er gjort kan man slette                             install-folderen
                </ul>
        </ul>
    <li>Version_2 - Easy Populate
        <ul>
            <li>Filerne til dette add-on kan hentes <a href="http://addons.oscommerce.com/info/7725">her</a>
            <li>EasyPopulate gør det lettere at oprette ens database/varekartotek når der kommer mange produkter, 
                forskellige sprog, mange atrinutter osv. fordi det nu kan ske ved at down- og uploade en cvs-fil, som
                man kan lave i Excel, >Google Documents eller OpenOffice
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
</ul>
