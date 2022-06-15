# Web-Design-Challenge
<!DOCTYPE html>
<html lang="en-us">

<head>

    <style>
        img{ width: auto;
            height: auto;
            max-width: 100%;
            max-height: 100%;}
    </style>

    <meta charset="UTF-8">
    <title>index</title>

  <!-- <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous"> -->
 
  
     <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">

     <link rel="stylesheet" type="text/css" href="style.css">
</head>

<body>
      <div id="first_line_color">
        <div class="row">   
                <!-- <div class="form-inline">   -->
                <div class="col-md-6">    

                        <div class="first_line" >
                            <div class="div1"><h1>Latitude</h1> </div>
                        </div>    
                </div>  
                
               <div class="col-md-2">     
                    <!-- <div class="btn-group" role="group" aria-label="Basic example"> -->
                        <div class="dropdown">
                        <button class="btn btn-secondary dropdown-toggle" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                            plot
                        </button>
                        <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
                            <a class="dropdown-item" href="Temperature.html">Max Temperature</a>
                            <a class="dropdown-item" href="Humidity.html">Humidity</a>
                            <a class="dropdown-item" href="cloudiness.html">Cloudiness</a>
                            <a class="dropdown-item" href="wind-speed.html">Wind-speed</a>
                        </div>
                        </div>
                </div>  

                <div class="col-md-2">  
                    <form>
                       <input class="MyButton1" type="button" value="Comparison" onclick="window.location.href='comparison.html'" />       
                    </form>
                </div> 

                <div class="col-md-2">
                      <form>
                            <input class="MyButton2" type="button" value="data" onclick="window.location.href='weather_df.html'" />       
                      </form>
    <!-- <button type="button" href="data.html"> <a class="dropdown-item" href="https://www.youtube.com">Data</a> </button> --> 
                </div>
        </div>
<!-- </div> -->
     </div>
<br>


<div class="Col_container">
    <!--Normally these medium columns go full wide on small screen sizes-->
    <div class="row">
      
      
      <div class="col-md-8">
        <!-- <div class="box skyblue"> -->

          <main class="container1">
            <header>
                <h1>Summary: Lattitude vs. X</h1>
            </header>
                <section id="introduction">
                    <figure id="main_figure">
                      <!-- <figcaption>latitude_Max-Temperature</figcaption> -->
                      <img  id="main_fig" src="./Resources/latitude_Max-Temperature.png" alt="latitude_Max-Temperature" style="width:300px;height:300px;float:left">
                    </figure>
                <p> &nbsp &nbsp &nbsp &nbsp This project is to visualize a weather analysis results performed in a previous project <a href="https://github.com/yongjinjiang/Python-API"> Weather project</a>, in which we studied the current weather all over 
            the world. We are supposed to choose more than 500 cities 
            with random latitude and longitude coordinates. Query the
             weather data from OpenWeatherMap API, make some plots
              and draw some conclusions about the dependence of 
              weather on the latitude value.</p>
            
                 <p> &nbsp &nbsp &nbsp &nbsp Here we presented the results in a web visualization dashboard. 
                     This is a user-friendly way to access the results presented in <a href="https://github.com/yongjinjiang/Python-API"> Weather project</a>. For further technique detailes, please 
                go back to  <a href="https://github.com/yongjinjiang/Python-API"> Weather project</a> where we have python codes(jupyter notebook version) to attain the 
                corresponding data for today.
            </p>
        </section>
      </main> 

      </div>
      <!-- </div> -->
      
      
      <div class="col-md-4">
          
                <main class="container2">
                    <header>
                        <h2>Visualizations</h2>
                    </header>
                <!--Normally these medium columns go full wide on small screen sizes-->
                <div class="row">
                  <div class="col-xs-3 col-sm-3 col-md-6">
                      <figure id="main1_figure">
                          <!-- <figcaption>latitude_Max-Temperature</figcaption> -->
                        <a href="./Temperature.html">
                          <img src="./Resources/latitude_Max-Temperature.png" alt="latitude_Max-Temperature" style="width:150px;height:150px;">
                        </a>
                        </figure>
            
                  </div>
                  <div class="col-xs-3 col-sm-3 col-md-6">
                      <figure id="main1_figure">
                          <!-- <figcaption>latitude_Max-Temperature</figcaption> -->
                          <a href="./cloudiness.html">
                          <img   src="./Resources/latitude_Cloudiness(mph).png" alt="latitude_Cloudiness" style="width:150px;height:150px;">
                          </a>
                        </figure>
                  </div>
                <!-- </div> -->

                <!-- <div class="row"> -->
                    <div class="col-xs-3 col-sm-3 col-md-6">
                        <figure id="main1_figure">
                            <!-- <figcaption>latitude_Max-Temperature</figcaption> -->
                            <a href="./Humidity.html">
                            <img   src="./Resources/latitude_humidity.png" alt="latitude_humidity" style="width:150px;height:150px;">
                            </a>  
                        </figure>
                    </div>
                    <div class="col-xs-3 col-sm-3 col-md-6">
                        <figure id="main1_figure">
                            <!-- <figcaption>latitude_Max-Temperature</figcaption> -->
                            <a href="./wind-speed.html">
                            <img  src="./Resources/latitude_wind-speed(mph).png" alt="latitude_wind-speed" style="width:150px;height:150px;">
                            </a>  
                        </figure>
                    </div>
                  </div>
                  </main>
           
            
      </div>
    </div>

        
        
        <br><br>
<!-- <img id="bio-image" src="https://placehold.it/200x200" alt="Your Name"> -->


 

<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>

</body>

</html>
