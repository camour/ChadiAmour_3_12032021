<!DOCTYPE html>
<html lang="fr">
    <head>
        <meta charset="utf-8" />    
        <meta name="viewport" content="width=device-width" />
        <link rel="stylesheet" href="./css/style.css" />
        <script src="https://kit.fontawesome.com/3c341fdad4.js" crossorigin="anonymous"></script>
        <title>Ohmyfood</title>
    </head>

    <body>

        <div class="loader"></div>
        <div class="page_body">
        <header class="header">
           <div class="header__logo">               
           </div>
        </header>

        <div class="map">
            <div class="map__research">
                <i class="fas fa-map-marker-alt"></i><input type="text" value="Paris, Belleville">
            </div>              
        </div> 

        <div class="view">
            <h1>Réservez le menu qui vous convient</h1>
            <p>Découvrez des restaurants d'exception,<br/>selectionnés par nos soins</p>
            <button class="btn btn--color">Explorez nos restaurants</button>
        </div>
        <h2>Fonctionnement</h2>
        <div class="process">

            
            <div class="etape"><div class="etape__X"><div class="etape__circle">1</div><i class="fas fa-mobile-alt"></i><p>Choisissez un restaurant</p></div></div>
            <div class="etape"><div class="etape__X"><div class="etape__circle">2</div><i class="fas fa-list"></i><p>Composez votre menu</p></div></div>
            <div class="etape"><div class="etape__X"><div class="etape__circle">3</div><i class="fas fa-store"></i><p>Dégustez au restaurant</p></div></div>

        </div>

        
        <div class="summary-restaurants">
            <h2>Restaurants</h2>
            <div class="bloc_restaurants">
                <div class="restaurant">
                    <a href="./menu_la_palette_du_gout.html"><div class="restaurant__new" id="restaurant__picture1"></div></a>
                    <div class="restaurant__description">
                        <h3>La palette du goût</h3>
                        <p>Ménilmontant</p>
                    </div>
                    <i class="fas fa-heart"></i><i class="far fa-heart"></i>
                    
                </div>

                <div class="restaurant">
                    <a href="./menu_la_note_enchantee.html"><div class="restaurant__new" id="restaurant__picture2"></div></a>
                    <div class="restaurant__description">
                        <h3>La note enchantée</h3>
                        <p>Charonne</p>
                    </div>
                    <i class="fas fa-heart"></i><i class="far fa-heart"></i>
                    
                </div>

                <div class="restaurant">
                    <a href="./menu_a_la_francaise.html"><div class="restaurant__new" id="restaurant__picture3"></div></a>
                    <div class="restaurant__description">
                        <h3>À la française</h3>
                        <p>cité Rouge</p>
                    </div>
                    <i class="fas fa-heart"></i><i class="far fa-heart"></i>
                    
                </div>

                <div class="restaurant">
                    <a href="./menu_le_delice_des_sens.html"><div class="restaurant__new" id="restaurant__picture4"></div></a>
                    <div class="restaurant__description">
                        <h3>Le délice des sens</h3>
                        <p>Folie-Méricourt</p>
                    </div>
                    <i class="fas fa-heart"></i><i class="far fa-heart"></i>
                    
                </div>
            </div>
            

        </div>

        <footer>
            <div class="footer__logo">ohmyfood</div>
            <ul>
                <li><a href="#"><i class="fas fa-utensils"></i><p> Proposer un restaurant </p></a></li>
                <li><a href="#"><i class="fas fa-handshake"></i><p> Devenir partenaire </p></a></li>
                <li><a href="#"><p>Mentions légales</p></a></li>
                <li><a href="mailto:support@gmail.com"><p>Contact</p></a></li>
            </ul>
        </footer>
               

    </div>

    </body>
</html>