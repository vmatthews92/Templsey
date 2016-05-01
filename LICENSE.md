<!DOCTYPE html>
  <html>
  
    <title> Tempsley Home page Draft </title>
  
   <!--- START OF HEAD --->
  
    <head>
  
   <link href="http://s3.amazonaws.com/codecademy-content/courses/ltp/css/shift.css" rel="stylesheet">
    <link rel="stylesheet" href="http://s3.amazonaws.com/codecademy-content/courses/ltp/css/bootstrap.css">
  <link rel="stylesheet" href="stylesheet.css" >
  
   <link rel="stylesheet" href="main.css">
   
   <style>
   .navbar {
    background-color: white;
    
}

.nav button {
    margin-right: 16px;
    margin-bottom: 4px;
    background-color: #4CAF01; /* Green */
    border-radius: 4px;
    border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    cursor: pointer;
}

.nav a1 {
    color: black;
    font-size: 17px;
    padding-right: 15px;
}
.nav a2 {
    color: black;
    font-size: 17px;
    padding-right: 15px;
}
.nav a3 {
    color: black;
    font-size: 17px;
    padding-right: 15px;
}
.nav li {
    display: inline;
}
.jumbotron {
    background-image: url('http://media.oregonlive.com/ent_impact_dining/photo/matt-lightnerjpg-b590cada546d806d.jpg');
    background-repeat: no-repeat;
    height: 550px;
    background-size: cover;
}
.jumbotron h1 {
    color: white;
    padding-top: 80px;
    font-size: 80px;
}
.jumbotron p {
    padding-top: 30px;
    color: white;
    font-size: 22px;
}
.jumbotron button {
    padding-top: 40px;
    border-radius: 4px;
    background-color: #4CAF51; /* Green */
    border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
}

/* start of new jumbotron section !*/
.jumbotron1 h1 {
    font-size: 26px;
    padding-left: 15px;
    padding-right: 15px;
    
}

.jumbotron1 h3 {
    position: inline;
    padding-left: 200px;
    padding-right: 200px;
}

.learn-more p {
    
} 


.row img {
    padding-top: 30px;
    padding-left: 30px;
    width: 370px;
    height: 370px;
}

.row h3 {
    font-size: 25px;
    padding-top: 50px;
    
}
.row p {
     font-size: 20px;
     padding-top: 30px;
     
}

.row button {
    size: 12px;
    background-color: #4CAF01; /* Green */
    border: none;
    border-radius: 4px;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
}

.row a {
    font-size: 15px;
    padding-left: 15px;
    color:black;

}

.row2 h3 {
    padding-top: 25px;
    
    
}

.row2 button {
    size: 12px;
    border-radius: 4px;
    background-color: #4CAF01; /* Green */
    border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
}

.row2 p {
    padding-top: 25px;
     font-size: 20px;
     padding-top: 30px;  
    
}


.row2 a {
    font-size: 15px;
    padding-left: 15px;
    color:black;

}

.row2 img {
    padding-top: 30px;
    padding-right: 30px;
    width: 370px;
    height: 370px;
}

/* NOT SURE YET -------
.row3 button {
    margin-top: 40px;
    border-radius: 4px;
    background-color: #4CAF51; /* Green */
    /*border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
}
*/
.jumbotron10 {
    background-color: rgb(0, 124, 93);
    
}

.jumbotron10 h1 {
    color: white;
    font-size: 40px;
    
}

.jumbotron10 p {
    color:  white;
    font-size: 17px;
    padding-top: 10px;
    
}

.row3 {
    background-color: rgb(247, 214, 64);
    
}

.row3 h3 {
    color: White;
    
}

.row3 p {
    font-size: 18px;
    color: rgb(247, 214, 64);
    
}

.jumbotron20 {
     background-image: url('http://blog.corbis.com/wp-content/uploads/2014/07/42-59954347.jpg');
     background-repeat: no-repeat;
     height: 750px;
     background-size: cover;

}

.jumbotron20 h1 {
    font-size: 50px;
    padding-top: 30px;
    padding-right: 25px;
    color: black;
      
}

.jumbotron20 ul{
    color: rgb(247, 214, 64);
    
    
}

.jumbotron20 a {
    color: white;
    font-size: 17px;
    padding-right: 15px;
}
    
.jumbotron20 li {
    font-size: 18px;
    color: black;
    
}


.jumbotron20 button {
    margin-right: 16px;
    margin-bottom: 4px;
    background-color: rgb(0, 124, 189);
    border-radius: 4px;
    border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    cursor: pointer;
}

.learn-more21 {
    background-color: rgb(0, 124, 93);
    
}


    
    
    
    
    

/* http://blog.corbis.com/wp-content/uploads/2014/02/JOE_459013.jpg 
*/

.dropdown {
    position: relative;
    display: inline-block;
}

.dropdown-content {
    display: none;
    position: absolute;
    background-color: #f9f9f9;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    padding: 12px 16px;
}

.dropdown:hover .dropdown-content {
    display: block;
}
.dropdown a {
    color: black;
    font-size: 16px;
}

</style>
   
   
   
   
   
   </head>
   
   <!--- END OF HEAD --->
   
      <body>
   
   <!--- navigation bar start --->
      
       <div class="nav">
          <nav class="navbar navbar-fixed-top navbar-inverse">
            <ul>
             <div class="pull-right">
              <li><a1 href="url">Login</a1></li>
              <li><a3 href="url">How it works</a3></li>
              <li><a2 href="url">Contact</a2></li>
              <div class="dropdown">
              <button><span><li>Signup Now</li></span></button>
           <div class="dropdown-content">
             <a href="url">Schedule a staffer</a>
             <a href="url">Become a staffer</a>
       </div>
    </div>
              
             </div>
            </ul>
        <div class="container">
        </div>
        </div>
        
    <!--- end of navigation bar--->
    
    <!--- start of image section --->
       
         <div class="jumbotron">
            <center><h1>Automated Shift Scheduling</h1>
                      <p>We automatically schedule your workforce with Screened, Insured, and Trained staffers all in one place.</p>
                      <p>Sign up for our private beta.</p>
 
         <center><form class="form-inline">
       <input type="Search" class="form-control" size="50"         placeholder=" Email address " required>
         <button type="button" class="btn btn-danger">Try it now</button></center>
  </form>
                      <!--<button><p2>Try it now</p2></button></center>  ---->
                      
             <div class="container">
            </div>
           </div>
             
    <!--- end of image section --->
    
    <!--- start of new jumbotron info section --->
          
           <div class="jumbotron1">
           
              <center><h1>Businesses and Staffers connect with each other through their mobile devices. We connect you instantly with our staffers who are employed by us, but who you schedule-exactly when you need them.</h1></center>
              <hr> </hr>
              
               <div class="container">
                  </div>
                 </div>
                 
                  
     <div class="container">  
       <div class="row">
         <div class="col-sm-6"> 
         <img src="https://www.staffjoy.com/static/images/homepage/schedule.png">
      </div>
     
       <div class="col-sm-6">      
          <h3><strong>Search our staffers availability instantly.</strong></h3>
          <p>View our staffers availability and simply schedule them for shifts, and they will confirm from their mobile device and show up ready-to work.</p>
          <button><p1>Schedule a staffer</p1></button>
          <a href="url">Learn more</a>
    </div>
  </div>
</div>
                  
            
            <hr>  </hr>
            
             <div class="container">  
       <div class="row2">
         <div class="col-sm-6">
         <h3><strong>Choose when you want to work.</strong></h3>
          <p>Using the mobile-friendly Planner, you can set your availability, recieve shifts, view scheduled shifts, and claim open shifts.</p>
          <button><p1>Become a staffer</p1></button>
          <a href="url">Learn more</a>
       
      </div>

       <div class="col-sm-6">
         <img src="https://www.staffjoy.com/static/images/homepage/demand.png">
         
            
         </div>
        </div>
    </div>
        
          <hr>         </hr>
        
        <!---
        <div class="learn-more3">
         <center><h1>Jobseekers: Open the doors to Flexibility.</h1></center>
                 <center><p>No commitment or credit card required.</p>
                 <button><p>Become a staffer</p></button></center>
         </div>
        </div>
        --->          

             
            
            <div class="jumbotron10">
            
            <div class="container-fluid">
       <center><h1>We do the busy work for you, so you can focus on the important stuff.</h1></center>
       
             <center><p>Tempsley automates all of the time-consuming work that goes into staffing.
Now, long processes like onboarding and keeping your roster full takes minutes, not days.</center>
             
       <div class="row3">
        <div class="col-xs-6 col-sm-3">
          <div class="thumbnail">
            <img src="https://p-handy.hbfiles.com/assets/landing-page/hp-steps-pros-97be587b191a88b96963ee946b9934d8.png">
         </div>
      <center><h3>Staffers are ready to work.</h3></center>
      <p>All our staffers are employed by us which means, they're screened, insured, and trained by us.</p>
    </div>
                   
    <div class="col-xs-6 col-sm-3">
        <div class="thumbnail">
          <img src="https://p-handy.hbfiles.com/assets/landing-page/value-pros-7d4f63411fb0650f0ea27513edd4d997.png">
        </div>
           <center><h3>Scheduling our staffers.</h3></center>
           <p>Select the Staffer with the skills and style that match your job. Our Staffer will confirm from their mobile device and arrive on time—ready to work.</p>
          </div>
    
    <div class="col-xs-6 col-sm-3">
        <div class="thumbnail">
          <img src="https://p-handy.hbfiles.com/assets/landing-page/value-availability-4f163081d2dd875c5252db25ba49af5f.png">
        </div>
         <center><h3>Clock on / off times.</h3></center>
         <p>No time sheets required. Everything is taken care of online. When the shift is over, the supervisor approves the hours on our system and they are sent to Tempsley for payment.</p>
         
  </div>
  
        <div class="col-xs-6 col-sm-3">
       <div class="thumbnail">
         <img src="https://p-handy.hbfiles.com/assets/landing-page/hp-steps-card-ea2cbca03bd9ddd2a762949c52ce036e.png">
        </div>
         <center><h3>No up-front fees.</h3></center>
          <center><p>Only pay when a staffer completes a shift. If you’re not satisfied with our work, we’ll refund your money. It’s as simple as that.</p></center>
        </div>
</div>
</div>     


          
          
          <div class="jumbotron20">
            <div class="container-fluid">
        
             <div class="pull-right">
               <h1>Wherever you are</h1>
                   <ul>
                      <li>Use your mobile to instantly connect <br> with local businesses</li>
                      <li>Get shifts that fit your schedule</li>
                      <li>Count on a regular paycheck <br> everytime you work</li> 
                      <li>We're in it together.
Even though <br> you have the flexibility to work <br> at different businesses, you’re employed by <br> Tempsley</li>
                </ul>  
                 <button type="button" class="btn btn-primary btn-lg">Become a staffer</button>
                 <a href="url">Learn more</a>
            </div>
          </div>
        </div>
          
          
             <div class="learn-more21">
               <div class="container">
                <center><h1>Experience the better way for rostering your business</h1></center>
              </div>
             </div>
             
              
             
             
             
             
             
             
             
             <div class="container">
         
          
     <footer>
          
             
        
        
        
  
            
            
               
                 
                 
                 
                       
           
    </html>
