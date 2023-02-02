<!DOCTYPE html> 
<html>
  <head>
    <style>
      .menu {
        width: 500px;
        margin: 0 auto;
        text-align: center;
      }
      .section {
        display: inline-block;
        width: 33.33%;
        float: left;
        text-align: left;
        padding: 20px;
        border: 1px solid black;
      }
      .section h2 {
        text-align: left;
        margin-left: 20px;
      }
      @media (min-width: 768px) and (max-width: 991px) {
        .section h2 {
          text-align: right;
          margin-right: 20px;
        }
      }
    </style>
  </head>
  <body>
    <div class="menu">
      <div class="section">
        <h2>Chicken</h2>
        <p>Chicken Alfredo</p>
        <p>BBQ Chicken</p>
        <p>Teriyaki Chicken</p>
      </div>
      <div class="section">
        <h2>Sushi</h2>
        <p>California Roll</p>
        <p>Tuna Roll</p>
        <p>Salmon Sashimi</p>
      </div>
      <div class="section">
        <h2>Beef</h2>
        <p>Beef Broccoli stir fry</p>
        <p>Beef and Mushroom stew</p>
        <p>Beef Tacos</p>
      </div>
    </div>
  </body>
</html>