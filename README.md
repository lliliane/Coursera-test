



<html>
  <head>
    <title>ass4</title>
    <script >
    	function showRandomCategory() {
  const categories = ["Lunch", "Dinner", "Sushi", "Drinks", "Dessert"]; // Define a list of all the menu categories
  const randomIndex = Math.floor(Math.random() * categories.length); // Generate a random number between 0 and the number of menu categories minus 1
  const randomCategory = categories[randomIndex]; // Select the category corresponding to the random index
  window.location.href = `/menu/${randomCategory}`; // Redirect the user to the selected category page
}

    </script>
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

    </style>
    
  </head>
  <body>
    
    <div class="tiles">
  <a href="#" class="tile" id="menu">Menu</a>
  <a href="https://lliliane.github.io/ASS3/" class="tile" id="specials" onClick="showRandomCategory()">Specials</a>
  <a href="#" class="tile" id="map">Map</a>
</div>
<h1> click on SPECIAL to see the menu</h1>
  </body>
</html>
