---
title: Eventos
layout:  null
tab: true
order: 2
tags: eventos-tag
---

## Eventos
<!--Eventos por realizar
<img src='assets/images/emailfooter.png' style='text-align:center;'><br>
-->
<!--<div>
<img src='assets/images/under01.jpg' style='float:left;margin:25px;max-width:30%;max-height:30%;'/>
<p style='color:black;text-align:justify;'>
<h1>En espera de informacion</h1>
</p>
</div>-->
<!-- 
<style type="text/css">
  .slider-container {
  display: flex;
  width: 100%;
  height: 100vh;
  overflow-x: scroll;  
  scroll-snap-type: x mandatory;
}

.slider-container img {
  flex: 0 0 100%;
  width: 100%;
  object-fit: cover;
  scroll-snap-align: center;
}
</style>
<h1>OWASP Conociendo los Activos Digitales</h1>
<div class="slider-container">  
  <img
    class="slider-item"
    src='assets/images/01charla01.jpg'
  />
  <img
    class="slider-item"
    src='assets/images/01charla02.jpg'
  />
  <img
    class="slider-item"
    src='assets/images/01charla03.jpg'
	/>
	<img
    class="slider-item"
    src='assets/images/01charla04.jpg'
	/>
	<img
    class="slider-item"
    src='assets/images/01charla05.jpg'
	/>
	
</div> -->
<style>
            .slide {
				float:left;
				display: flex;
				width: 100%;
				height: 50vh;
                box-shadow: 0px 1px 6px rgba(0, 0, 0, 0.64);
                margin-top: 5px;
				max-width:40%;
				max-height:30%;	
            }
            .slide-inner {
                flex: 0 0 100%;
				height: auto;
				width: 100%;
				object-fit: cover;
				position: relative;
                overflow: hidden;                
            }
            .slide-open:checked + .slide-item {
                position: static;
                opacity: 100;
            }
            .slide-item {
                position: absolute;
                opacity: 0;
                -webkit-transition: opacity 0.6s ease-out;
                transition: opacity 0.6s ease-out;
            }
            .slide-item img {
                display: block;
                height: auto;
                max-width: 100%;
				text-align:center;
            }
            .slide-control {
                background: rgba(0, 0, 0, 0.28);
                border-radius: 50%;
                color: #fff;
                cursor: pointer;
                display: none;
                font-size: 40px;
                height: 40px;
                line-height: 35px;
                position: absolute;
                top: 50%;
                -webkit-transform: translate(0, -50%);
                cursor: pointer;
                -ms-transform: translate(0, -50%);
                transform: translate(0, -50%);
                text-align: center;
                width: 40px;
                z-index: 10;
            }
            .slide-control.prev {
                left: 2%;
            }
            .slide-control.next {
                right: 2%;
            }
            .slide-control:hover {
                background: rgba(0, 0, 0, 0.8);
                color: #aaaaaa;
            }
            #slide-1:checked ~ .control-1,
            #slide-2:checked ~ .control-2,
            #slide-3:checked ~ .control-3,
			#slide-4:checked ~ .control-4,
			#slide-5:checked ~ .control-5
			{
                display: block;
            }
            .slide-indicador {
                list-style: none;
                margin: 0;
                padding: 0;
                position: absolute;
                bottom: 2%;
                left: 0;
                right: 0;
                text-align: center;
                z-index: 10;
            }
            .slide-indicador li {
                display: inline-block;
                margin: 0 5px;
            }
            .slide-circulo {
                color: #828282;
                cursor: pointer;
                display: block;
                font-size: 35px;
            }
            .slide-circulo:hover {
                color: #aaaaaa;
            }
			
            #slide-1:checked ~ .control-1 ~ .slide-indicador 
                 li:nth-child(1) .slide-circulo,
            #slide-2:checked ~ .control-2 ~ .slide-indicador 
                  li:nth-child(2) .slide-circulo,
            #slide-3:checked ~ .control-3 ~ .slide-indicador 
                  li:nth-child(3) .slide-circulo, 
			#slide-4:checked ~ .control-4 ~ .slide-indicador 
                  li:nth-child(4) .slide-circulo,	  
			#slide-5:checked ~ .control-5 ~ .slide-indicador 
                  li:nth-child(5) .slide-circulo{
                color: #428bca;
            }
			
            #titulo {
                width: 100%;
                position: absolute;
                padding: 0px;
                margin: 0px auto;
                text-align: center;
                font-size: 27px;
                color: rgba(255, 255, 255, 1);
                font-family: 'Open Sans', sans-serif;
                z-index: 9999;
                text-shadow: 0px 1px 2px rgba(0, 0, 0, 0.33), 
                     -1px 0px 2px rgba(255, 255, 255, 0);
            }
			
</style>
<h1>Desafios de los Activos Virtuales 15 Octubre de 2022</h1>
<div class="slide">
    <div class="slide-inner">
         <input class="slide-open" type="radio" id="slide-1" 
                  name="slide" aria-hidden="true" hidden="" checked="checked">
            <div class="slide-item">
                    <img src='assets/images/01charla01.jpg'>
            </div>
         <input class="slide-open" type="radio" id="slide-2" 
                 name="slide" aria-hidden="true" hidden="">
            <div class="slide-item">
                    <img src='assets/images/01charla02.jpg'>
            </div>
                <input class="slide-open" type="radio" id="slide-3" 
                      name="slide" aria-hidden="true" hidden="">
                <div class="slide-item">
                    <img src='assets/images/01charla03.jpg'>
                </div>
				<input class="slide-open" type="radio" id="slide-4" 
                      name="slide" aria-hidden="true" hidden="">
                <div class="slide-item">
                    <img src='assets/images/01charla04.jpg'>
                </div>
				<input class="slide-open" type="radio" id="slide-5" 
                      name="slide" aria-hidden="true" hidden="">
                <div class="slide-item">
                    <img src='assets/images/01charla05.jpg'>
                </div>
				
				
				<label for="slide-5" class="slide-control prev control-1">‹</label>
                <label for="slide-2" class="slide-control next control-1">›</label>
				
                <label for="slide-1" class="slide-control prev control-2">‹</label>
                <label for="slide-3" class="slide-control next control-2">›</label>
				
                <label for="slide-2" class="slide-control prev control-3">‹</label>
                <label for="slide-4" class="slide-control next control-3">›</label>
				
				<label for="slide-3" class="slide-control prev control-4">‹</label>
                <label for="slide-5" class="slide-control next control-4">›</label>
				
				<label for="slide-4" class="slide-control prev control-5">‹</label>
                <label for="slide-1" class="slide-control next control-5">›</label>
				
                <ol class="slide-indicador">
                    <li>
                        <label for="slide-1" class="slide-circulo">•</label>
                    </li>
                    <li>
                        <label for="slide-2" class="slide-circulo">•</label>
                    </li>
                    <li>
                        <label for="slide-3" class="slide-circulo">•</label>
                    </li>
					<li>
                        <label for="slide-4" class="slide-circulo">•</label>
                    </li>
					<li>
                        <label for="slide-5" class="slide-circulo">•</label>
                    </li>
                </ol>
    </div>
</div>  