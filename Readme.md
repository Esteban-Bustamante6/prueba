hello welcome to exam of html module 2, i present i name is Esteban of the team Tesla cohorte 6 identified with cc = 1011590404
email : estebanbl090@gmail.com

instruction for view of exam in git hub 
name of profile = Esteban-Bustamante6
name of folder = PruebaE-B-L

for view the exam open the file name index.html there will be all codig elaborated for my , he recreated based on a layout provided in the figma modeling tool

The Figma tool provided us with everything we needed to replicate the page, such as images, icons, text, font type, and structure.

I will tell you about this information portal.

This portal, designed by the company Nexcent, is an interactive page with information and knowledge that they have developed over 8 years.

where in its different sections we can find, its associated clients, club or teams of the organization, work statistics, labor marketing, future innovations that will be presented among much more information from nexcent

code structure==

images they are saved is folder img and it breaks down into img / img-marketin   iconos  iconos-section

I will show you some of the main sections that make up my code


structure main = header and nav ___________________________________-

<nav id="navbar">
        <div class="logo"><img src="img/logo.png" alt=""></div>
        <ul class="nav-links">
            <li><a href="#" class="btn-nav">Home</a></li>
            <li><a href="#" class="btn-nav">Service</a></li>
            <li><a href="#" class="btn-nav">Facture</a></li>
            <li><a href="#" class="btn-nav">Produc</a></li>
            <li><a href="#" class="btn-nav">Testimonal</a></li>
            <li><a href="#" class="btn-nav">FAQ</a></li>
        </ul>
        <div class="navButton">
            <div><button class="b1">Login</button></div>
            <div><button class="b2">Sing Up</button></div>
        </div>
    </nav>

    <header class="slider">
        <div class="text">
            <h1>Lessons and  insights <span style="color: green;">from 8 years</span></h1>
            <p>where to grow  your  bussiness as a photograper: site or social media?</p>
            <button class="btnregister">Register</button>
        </div>
        <div class="photo"><img src="img/fondoprinci.png" alt=""></div>
    </header>



section of marketing _______________________________________-
<section id="caring">
            <div class="caringtex">
                <h2>Caring is the new marketing</h2>
                <p>The Nexcent blog is the best place to read about the latest membership insights, trends and more. See who's joining the community, read about how our community are increasing their membership income and lot's more.​</p>
            </div>

            <div id="divcaring">
                <article class="ar1">
                    <img src="img/marketin/Imagen pegada.png" alt="" width="100%">
                </article>
                <article class="ar2">
                    <img src="img/marketin/Imagen pegada (2).png" alt="" width="100%">
                </article>
                <article class="ar3">
                    <img src="img/marketin/Imagen pegada (4).png" alt="" width="100%">
                </article>
                <article class="ar4">
                    <h2>Creating Streamlined Safeguarding Processes with OneRen</h2>
                    <button>Readmore <div></div></button>

                </article>
                <article class="ar5">
                    <h2>What are your safeguarding responsibilities and how can you manage them?</h2>
                    <button>Readmore </button>

                    
                </article>
                <article class="ar6">
                    <h2>Revamping the Membership Model with Triathlon Australia</h2>
                    <button>Readmore</button>

                </article>
            </div>

for end section is clients --------------------------------
 <section id="producdesta">
            <div class="productos-destacados">
                <article class="item area-1">
                    <b>Our Cliente</b>
                    <br>
                    <p>we have been working with some fortune 500+ cleints</p>
                </article>
                <article class="item area-2"><img src="iconos/produc1.png" alt=""></article>
                <article class="item area-3"><img src="iconos/produc2.png" alt=""></article>
                <article class="item area-4"><img src="iconos/product3.png" alt=""></article>
                <article class="item area-5"><img src="iconos/produc4.png" alt=""></article>
                <article class="item area-6"><img src="iconos/product5.png" alt=""></article>
                <article class="item area-7"><img src="iconos/product6.png" alt=""></article>
                <article class="item area-7"><img src="iconos/produc7png" alt=""></article>


            </div>
        </section>


        