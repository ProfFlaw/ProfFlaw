<!DOCTYPE html>
<html>
  <head>
    <title>Meine Fotobuttons</title>
    <style>
      body {
background-color: black;
}
		.button-container {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
      }
      .button {
        width: 50%;
        height: 150px;
        background-size: cover;
        background-position: center;
        margin: 10px;
        border: none;
        cursor: pointer;
        border-radius: 20px;
			color: green
		  font-size: 200px;
      }
    </style>
  </head>
  <body>
    <div class="button-container">
      <button class="button" style="background-image: url('');" onclick="alert('Button 1 geklickt')">G&auml;nseliesel</button>
      <button class="button" style="background-image: url('https://www.example2.com/image2.jpg');" onclick="alert('Button 2 geklickt')"></button>
      <button class="button" style="background-image: url('https://www.example3.com/image3.jpg');" onclick="alert('Button 3 geklickt')"></button>
      <button class="button" style="background-image: url('https://www.example4.com/image4.jpg');" onclick="alert('Button 4 geklickt')"></button>
      <button class="button" style="background-image: url('https://www.example5.com/image5.jpg');" onclick="alert('Button 5 geklickt')"></button>
    </div>
  </body>
</html>
