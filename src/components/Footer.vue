<template>
  <section id="footer">
    <div id="lki" class="footer container">
      
      <h2>Muhammad Dzaki Fakhrezi </h2>
      <p>Copyright © 2023 Dzaki. All rights reserved</p>
      <div id="medsos" class="social-icon">
        <div class="social-item">
          <a href="https://api.whatsapp.com/send/?phone=%2B628999234378&text&type=phone_number&app_absent=0" target="_blank"><img src="https://img.icons8.com/bubbles/100/000000/whatsapp.png" /></a>
        </div>
        <div class="social-item">
          <a href="https://www.instagram.com/rezi_trix/" target="_blank"><img src="https://img.icons8.com/bubbles/100/000000/instagram.png" /></a>
        </div>
        <div class="social-item">
          <a href="https://www.tiktok.com/@izerbetter" target="_blank"><img src="https://img.icons8.com/bubbles/100/000000/tiktok.png" /></a>
        </div>
        
      </div>
       
    </div>
  </section>
  
 
 
</template>



<style>

#footer {
	background-image: linear-gradient(60deg, #3B3B3B 0%, #3B3B3B 100%);

  
}

#lki{
	background-image: linear-gradient(60deg, #3B3B3B 0%, #3B3B3B 100%);

  
}

#footer .footer {
	min-height: 200px;
	flex-direction: column;
	padding-top: 50px;
	padding-bottom: 10px;
}
#footer h2 {
	color: white;
	font-weight: 500;
	font-size: 1.8rem;
	letter-spacing: 0.1rem;
	margin-top: 10px;
	margin-bottom: 10px;
}
#footer .social-icon {
	display: flex;
	margin-bottom: 30px;
}
#footer .social-item {
	height: 50px;
	width: 50px;
	margin: 0 5px;
  
}
#footer .social-item img {
	filter: grayscale(1);
	transition: 0.3s ease filter;
}
#footer .social-item:hover img {
	filter: grayscale(0);
}
#footer p {
	color: white;
	font-size: 1.3rem;
}

#footer {
  text-align: center;
}


</style>
