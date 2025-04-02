<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Project: Event invite</title>
        
    <style>
        body {
            
            font-family: 'Georgia', serif;
            margin: 0;
            padding: 0;
            background-color :rgb(128, 122, 204);
            
        }
        
      
           .Events {
            max-width: 500px;
            margin: 20px auto;
            padding: 20px;
            background: Yellow;
            text-align: center;
            box-shadow: 0 0 10px rgba(242, 14, 60, 0.1);
            text-align: center;
            
        }
        .Rsvp{
            max-width: 500px;
            margin: 20px auto;
            padding: 20px;
            background-color:yellow;
           
            text-align: center;
        }
        .guest-list 
           { margin-top: 30px;
           font-style:italic;
        }
        #Guest{background:yellow;
        font-style:italic;
        }
        #Event{background:yellow;
        font-style:italic;
        }
        #Food{background: yellow;
        font-style:italic;
        }
        
        .rsvp-button {
            display: inline-block;
            padding: 15px 30px;
            background-color: #ff3366;
            color: white;
            border-radius: 5px;
            font-size: 20px;
            margin-top: 20px;
        }
        footer {
            text-align: center;
            
            background: pink;
            color: green;
            position: fixed;
            bottom: 0;
            width: 100%;
            padding: 15px;
            font-style: italic;
        }
        
        h1, h2,h3 {
            color:rgb(black);
            font-family: Monospace, sans-serif; text-align:center;
        }
        </style>
    </head>
    <body>
        
        <h1>Adesh's Birthday Party</h1>
        
        <h3>You're Invited to My son's Birthday Party!</h3>
    
    <div class="Events">
        <h2>Party Details</h2>
        <p><strong>Date:</strong> 16 Feb, 2025</p>
        <p><strong>Time:</strong> 11:00 PM - 1:00 PM</p>
        <p><strong>Venue:</strong> 26 New Square shopping centre,B70 7PP</p>
        <a href="#Rsvp" class="rsvp-button">RSVP Now</a></div>
        <div id= "Guest"><h2>Guest List</h2>
        <ol class="guest-list">
            <li>Ravi</li>
            <li>Anaya</li>
            <li>Leo</li>
            <li>Ruby</li>
            <li>Roshan</li>
            <li>Elly</li>
            <li>Millie</li>
            <li>Sam</li>
        
        </ol>
    </div>
    <div id="Food">
        <h3>Food Menu</h3>
        <ul>
            <li>Chicken Nuggets</li>
            <li>Cheese Pizza</li>
            <li>Peperoni Pizza</li>
            <li>Fries</li>
         <li>Ice Cream</li>
            
        </ul></div>
        <div id="Event">
        <h3>Event List</h3>
        <ul>
            <li>Soft Play</li>
            <li>Pass The Parcel</li>
            <li>Face Painting</li>
            <li>Disco</li>
         <li>Ice Cream</li>
         </ul></div>
        <div class="Rsvp">
        <h4 id="Rsvp">RSVP Details:
        Harmeet Kaur<br> Contact No: 752345622
  </h4></div>
        <footer>
        &copy; 2025 Birthday Party, All Rights Are Reserved.
    </footer>
    </body>
</html>
