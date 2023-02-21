# onclick-form-popup
Providing easy ways for users to sign up for your product or service without having to search through your website is crucial to success online. Adding a Sticky Tab to your website allows you to convert more website visitors by allowing them to easily click the sticky tab and fill out a popup form anywhere on your website.

## Tutorial

For detailed instructions, view Solodev's [Adding a Form Popup to your Sticky Tab](https://www.solodev.com/blog/web-design/forms/adding-a-form-popup-to-your-sticky-tab.stml) article.

## Demo

Check out a working example on [JSFiddle](https://jsfiddle.net/solodev/kbbza8nq/).

## HTML

The sticky tab and form popup contain the followeing basic HTML markup.
```
<!--Sticky Tab-->
<div class="side-widget open">
  <div class="inner">
    <a class="btn btn-blue productCheckout" id="get-started">Get Started</a>
  </div>
</div>
<!--End of Sticky Tab-->

<!--Form Popup-->
<div id="popup-container">
   <div id="popup-window">
      <div class="modal-content">
         <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>  
         <a href="#" class="your-class"></a>
         <div>
            <div class="row text-center">
              <h1>GET STARTED</h1>
          <hr>
              <p>Fill out the form below to get started today!</p>
            </div>
            <br>
            <form action="" method="post" id="footer-form">
            <div class="row">
               <div class="col-md-6">
                  <input class="form-control" name="first_name" id="first_name" placeholder="First Name *" required>
               </div>
               <div class="col-md-6">
                  <input class="form-control" name="last_name" id="last_name" placeholder="Last Name *" required>
               </div>
            </div>
            <br>
            <div class="row">
               <div class="col-md-6">
                  <input class="form-control" name="email" id="email" placeholder="Your Email *"required>
               </div>
               <div class="col-md-6">
                  <input class="form-control" name="phone" placeholder="Phone *" id="phone">
                  <br>
               </div>
            </div>
            <center>
            <input type="submit" class="btn btn-primary" value="Submit">
            </center>
            </form>
            <br>
         </div>
      </div>
   </div>
</div>
<!--End of Form Popup-->
```

## CSS

All necessary CSS is in onclick-form-popup.css

## External Includes
```
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Open+Sans+Condensed:300" rel="stylesheet">
<link rel="stylesheet" href="onclick-form-popup.css">

<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
<script src="onclick-form-popup.js"></script>
```
