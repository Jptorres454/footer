<footer>
    <div class="container bottom_border">

        <div class="row-footer">
          <div class="col-4">
             <img src="https://www.cityworks.com/wp-content/uploads/2021/06/Innovate_Sponsors-White-Esri.png" alt="logo" class="img-logo">
          </div>


            <div class="col-4 contacto">                
                <div class="parrf">
                    <h6 class="headin5_amrc col_white_amrc">Póngase en contacto con nosotros</h6>
                    <p><img src="/imagenes/mensaje.png" alt="" class="mg">  sostenibilidad@esri.co</p>
                </div>
            </div>
        </div>

    </div>

    <div class="container1">
        <ul class="foote_bottom_ul_amrc">
            <li><a href="https://www.esri.co/es-co/home">Colombia</a></li>
            <li><a href="https://www.esri.co/es-ec/home">Ecuador</a></li>
            <li><a href="https://www.esri.co/es-pa/home">Panamá</a></li>
            <p class="parrf2"><a href="#">Creado con @ ArcGIS Hub</a></p>
        </ul>

        <ul class="social_footer_ul">
            <li><a href="https://www.facebook.com/EsriColombia"><img src="/imagenes/facebook.png" alt="" class="fb"></a></li>
            <li><a href="https://www.youtube.com/c/EsriColombia"><img src="/imagenes/youtube.png" alt="" class="yt"></a></li>
            <li><a href="https://twitter.com/EsriColombia"><img src="/imagenes/twitter.png" alt="" class="tw"></a></li>
            <li><a href="https://www.linkedin.com/company/esri-colombia/"><img src="/imagenes/linkedin.png" alt="" class="lk"></a></li>
            <li><a href="https://www.instagram.com/esricolombia/"><img src="/imagenes/instagram.png" alt="" class="ig"></a></li>
        </ul>
    </div>

</footer>
------------------------------------
<Style>
body{
    display: block;
    margin: 0;
}

.footer{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    border: none;
    background-color: #2b2b2b;
}

footer { 
    width:100%; 
    background-color: #2b2b2b; 
    min-height:250px; 
    padding:10px 0px 25px 0px ;
}

.container{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 150px;
    padding-right: 10px;
    padding-left: 80px;
}

.card{
    display: flex;
    flex-direction: column;
    margin: 0px;
    overflow: hidden;
    width: 300px;
    backdrop-filter: blur(1rem);
    color: var(--white-text);
    height: 10rem;
}

.card h6{
    letter-spacing: .1rem;
    text-transform: uppercase;
}

.card h2{
    letter-spacing: .1rem;
    margin: 1rem 0;

}

.carddiv{
    padding: 1rem;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;

}

.carddiv i{
    font-size: 2rem;
}

.content{
    padding: 2rem;
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: space-between;
}

.content p{
    font-size: 20px;
}

@media (max-width:1030px){
    .container{
        flex-direction: column;
        justify-content: center;
        align-items: center;
        height: auto;
    }
}

.carddiv img{
    margin: -15px 90px 20px 20px;
    height: 10rem;
    width: 15rem;
    padding: 15px;
}

.container a{
    text-decoration: none;
}

.carddiv1{
    padding: 0.9rem;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;

}

.carddiv1 i{
    font-size: 2rem;
}

.carddiv1 img{
    margin: auto;
    height: 10rem;
    width: 10rem;
    padding: 1rem;
}
.card1{
    border-radius: 1rem;
    display: flex;
    flex-direction: column;
    margin: 5.5rem;
    overflow: hidden;
    width: 20rem;
    backdrop-filter: blur(1rem);
    color: var(--white-text);
    height: 23rem;
}

.card1 h6{
    letter-spacing: .1rem;
    text-transform: uppercase;
}

.card1 h2{
    letter-spacing: .1rem;
    margin: 1rem 0;

}

.col_white_amrc { 
    color:#ffffff;
}

a{
    color: #007bff;
    text-decoration: none;
}

.col-md{
    padding: 15px 5px 5px 15px;
}

.pt2 { 
    padding-top:40px ; 
    margin-bottom:20px ;
}

footer p { 
    font-size:13px; 
    color:#ffffff; 
    padding-bottom:0px; 
    margin-bottom:8px;
}

footer p .mg{ 
    margin: 30px;
    width: 15px;
    padding: auto;
    margin: auto;
    height: auto;
}

.mb10 { 
    padding-bottom:15px ;
}

.footer_ul_amrc { 
    margin:0px ; 
    list-style-type:none ; 
    font-size:14px; 
    padding:0px 0px 10px 0px ; 
}

.footer_ul_amrc li {
    padding:0px 0px 5px 0px;
}

.footer_ul_amrc li a{ 
    color:#ffffff;
}

.footer_ul_amrc li a:hover{ 
    color:#d4d4d4; 
    text-decoration:none;
}

.fleft { 
    float:left;
}

.padding-right { 
    padding-right:10px; 
}

.footer_ul2_amrc {
    margin:0px; 
    list-style-type:none; 
    padding:0px;
}

.footer_ul2_amrc li p { 
    display:table; 
}

.footer_ul2_amrc li a:hover { 
    text-decoration:none;
}

.footer_ul2_amrc li i { 
    margin-top:5px;
}

.bottom_border { 
    border-bottom:1px solid #838282;
    padding-bottom:10px;
    align-items: center;
    margin: -10px 100px 10px ;
    width: auto;
    display: flex;
    justify-content: center;
}

.foote_bottom_ul_amrc {
    list-style-type:none;
    padding:0px;
    display:table;
    margin-top: 10px;
    margin-right: auto;
    margin-bottom: 10px;
    margin-left: auto;
}

.foote_bottom_ul_amrc li { 
    display: inline-block;
}

.foote_bottom_ul_amrc li a { 
    color:#a5a5a5; 
    margin:0 12px;
}

.social_footer_ul { 
    display:table; 
    margin: auto; 
    list-style-type:none;
    text-align: center;
    padding: initial;
}

.social_footer_ul li { 
    padding-left:0px; 
    padding-top:0px; 
    float:left; 
}

.social_footer_ul li a { 
    color:#ffffff;
    padding:0px;
}

.social_footer_ul li i {  
    width:20px; 
    height:20px; 
    text-align:center;
}

.parrf{
    margin: 12px -90px 3px 20px;
}

.parrf2{
    list-style-type: none;
    text-align: center;
}

.fb{
    width: 40px;
    padding: 4px;
    margin: 10px;
    height: 40px;
}
.yt{
    width: 40px;
    padding: 0px;
    margin: 10px;
    height: 40px;
}
.tw{
    width: 40px;
    padding: 4px;
    margin: 10px;
    height: 40px;
}

.lk{
    width: 40px;
    padding: 4px;
    margin: 10px;
    height: 40px;
}

.ig{
    width: 40px;
    padding: 4px;
    margin: 10px;
    height: 40px;
}
.img-logo{
    width:10rem;
    margin: -10px -100px -20px;
}
      
.row-footer{
    display:flex;
    flex-direction:row;
    justify-content:space-around;
}
  
.contacto{
    display:flex;
    flex-direction:center;
    align-items:center;
    padding-right: 15px;
    padding-left: 90px;
}
</Style>