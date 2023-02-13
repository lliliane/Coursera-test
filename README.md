<!DOCTYPE html>
<html>
  <head>
    <style>
      .menu-container {
        display: flex;
        align-items: left;
        flex-wrap: wrap;
        height: 1000%;
        justify-content: space-between ;
        padding-left: 80px;
        padding-right: 80px;
        margin-right: 40px;

      }
      .menu-section {
        width: 30%;
        text-align: center;
        padding: 20px;
        box-sizing:border-box;
        background-color: #f2f2f2;
        border-style: solid;
        border-width: 2px;
        border-color: black;
        height: 150px;


      }
      
      @media only screen and (max-width: 768px) {
        .menu-section {
          width: 75%;
        }
      }
      h1{
        text-align: center;
      }
      .ITEM-box2{
        width: 120px;
        height: 30px;
        border: 2px solid black;
        float: right;
        margin-right: 0;
        background-color:pink;
        position: relative;
        bottom: 21px;
        left: 21px;
      }
         .ITEM-box3{
        width:120px;
        height: 30px;
        border: 2px solid black;
        float: right;
        margin-right: 0;
        background-color:blue;
        position: relative;
        bottom: 21px;
        left: 21px;
      }
         .ITEM-box1{
        width: 120px;
        height: 30px;
        border: 2px solid black;
        float: right;
        margin-right: 0;
        background-color:yellow;
        padding-right: 0;
        position: relative;
        bottom: 21px;
        left: 21px;

      }
      p{
        text-align: left;
      }

       </style>
  </head>
  <body>
    <h1>Our Menu</h1>
    <div class="menu-container">
      <div class="menu-section">
        <div class="ITEM-box3">pizza</div>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc euismod, ipsum vel tincidunt convallis, sem ipsum tincidunt nibh, sit amet blandit metus metus eget dui. Sed ut dui in neque facilisis auctor. Nunc gravida libero vel nisl rhoncus.</p>
      </div>
      <div class="menu-section">
        <div class="ITEM-box2">chicken</div>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc euismod, ipsum vel tincidunt convallis, sem ipsum tincidunt nibh, sit amet blandit metus metus eget dui. Sed ut dui in neque facilisis auctor. Nunc gravida libero vel nisl rhoncus.</p>
      </div>
      <div class="menu-section">
      <div class="ITEM-box1">burger</div>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc euismod, ipsum vel tincidunt convallis, sem ipsum tincidunt nibh, sit amet blandit metus metus eget dui. Sed ut dui in neque facilisis auctor. Nunc gravida libero vel nisl rhoncus.</p>
      </div>
    </div>
  </body>
</html