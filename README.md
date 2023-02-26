

<!DOCTYPE html>
<html>
  <head>
    <title>ass4</title>
    
    <style>
    	.tiles {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.tile {
  display: block;
  width: 200px;
  height: 200px;
  margin: 20px;
  text-align: center;
  line-height: 200px;
  font-size: 24px;
  font-weight: bold;
  color: #fff;
  background-color: #333;
  text-decoration: none;
}

#menu {
  background-color: #00a0e4;
}

#specials {
  background-color: #ff8500;
}

#map {
  background-color: #40b747;
}
body {
            background-color: #f2f2f2;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        
        h1 {
            margin: 0;
            font-size: 36px;
            font-weight: normal;
            text-transform: uppercase;
        }
        
        .menu-container {
            background-color: orange;
            border: 1px solid #ddd;
            border-radius: 5px;
            box-shadow: 0 2px 2px rgba(0,0,0,.1);
            margin: 20px auto;
            max-width: 600px;
            padding: 20px;
        }
        
        h2 {
            font-size: 24px;
            font-weight: normal;
            margin: 0;
            margin-bottom: 10px;
            text-transform: uppercase;
        }
        
        .menu-item {
            display: flex;
            justify-content: space-between;
            padding: 10px 0;
        }
        
        .menu-item-name {
            font-size: 18px;
            font-weight: bold;
            margin: 0;
        }
        
        .menu-item-price {
            font-size: 18px;
            margin: 0;
            text-align: right;
            width: 80px;
        }
        
        .menu-item-description {
            font-size: 14px;
            margin: 0;
            margin-top: 5px;
        }
    </style>
    
  </head>
  <body>
    
    <div class="tiles">
  <a href="#" class="tile" id="menu">Menu</a>
  <a href="file:///C:/Users/pc/Desktop/coursera-tes/d.html" class="tile" id="specials" onClick="showRandomCategory()">Specials</a>
  <a href="#" class="tile" id="map">Map</a>
</div>
 <header>
        <h1>specials</h1>
    </header>
    
    <div class="menu-container">
        <h2>Lunch</h2>
        <div class="menu-item">
            <p class="menu-item-name">Chicken Caesar Salad</p>
            <p class="menu-item-price">$12.99</p>
        </div>
        <p class="menu-item-description">Romaine lettuce, grilled chicken, croutons, and Caesar dressing.</p>
        
        <div class="menu-item">
            <p class="menu-item-name">BLT Sandwich</p>
            <p class="menu-item-price">$9.99</p>
        </div>
        <p class="menu-item-description">Bacon, lettuce, tomato, and mayonnaise on sourdough bread.</p>
        
        <div class="menu-item">
            <p class="menu-item-name">Grilled Cheese Sandwich</p>
            <p class="menu-item-price">$7.99</p>
        </div>
        <p class="menu-item-description">Cheddar and Swiss cheese on sourdough bread.</p>
    </div>
    <div class="menu-container">
        <h2>dinner</h2>
        <div class="menu-item">
            <p class="menu-item-name">Chicken Caesar Salad</p>
            <p class="menu-item-price">$12.99</p>
        </div>
        <p class="menu-item-description">Romaine lettuce, grilled chicken, croutons, and Caesar dressing.</p>
        
        <div class="menu-item">
            <p class="menu-item-name">BLT Sandwich</p>
            <p class="menu-item-price">$9.99</p>
        </div>
        <p class="menu-item-description">Bacon, lettuce, tomato, and mayonnaise on sourdough bread.</p>
        
        <div class="menu-item">
            <p class="menu-item-name">Grilled Cheese Sandwich</p>
            <p class="menu-item-price">$7.99</p>
        </div>
        <p class="menu-item-description">Cheddar and Swiss cheese on sourdough bread.</p>
    </div>
    <div class="menu-container">
        <h2>suchi</h2>
        <div class="menu-item">
            <p class="menu-item-name">Chicken Caesar Salad</p>
            <p class="menu-item-price">$12.99</p>
        </div>
        <p class="menu-item-description">Romaine lettuce, grilled chicken, croutons, and Caesar dressing.</p>
        
        <div class="menu-item">
            <p class="menu-item-name">BLT Sandwich</p>
            <p class="menu-item-price">$9.99</p>
        </div>
        <p class="menu-item-description">Bacon, lettuce, tomato, and mayonnaise on sourdough bread.</p>
        
        <div class="menu-item">
            <p class="menu-item-name">Grilled Cheese Sandwich</p>
            <p class="menu-item-price">$7.99</p>
        </div>
        <p class="menu-item-description">Cheddar and Swiss cheese on sourdough bread.</p>
    </div>
  </body>
</html>
