# htmlCSS

<style>
 * {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html, body {
  height: 100vh;
  background-color: #666666;
  font-family: 'Open Sans', sans-serif;
}

body {
  display: flex;
  justify-content: center;
  align-items: center;
}

.card {
  position: relative;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  height: 400px;
  width: 400px;
  border-radius: 25px;
  background-color: #ffffff;
  box-shadow: 10px 0 50px rgba(0, 0, 0, 0.5);
  overflow: hidden;
}

.card:nth-child(1) {
  margin-right: 30px;
}

body:hover .card {
  transform: scale(0.9);
  transition: 0.9s;
}

body .card:hover {
  transform: scale(1);
  opactiy: 1;
  transition: 0.9s;
}

h2 {
  position: absolute;
  left: 0;
  top: 0;
  margin: 20px 0 0 20px;
  font-size: 44px;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 15px;
  color: #ffffff;
  mix-blend-mode: difference;
}

p {
  position: absolute;
  left: 0;
  bottom: 0;
  margin: 0 20px 60px 20px;
  font-size: 18px;
  color: #ffffff;
  mix-blend-mode: difference;
}

#circle {
  height: 100%;
  width: 100%;
  border-radius: 50%;
  background-color: #000000;
  margin-top: -330px;
  margin-left: 200px;
}

#triangle {
  height: 100%;
  width: 100%;
  background-color: #000000;
  border-radius: 20px;
  transform: rotate(70deg);
  margin-top: -430px;
  margin-left: 200px;
}

.content a {
  position: absolute;
  right: 0;
  bottom: 0;
  margin: 0 20px 20px 0;
  cursor: pointer;
  background-color: #000000;
  color: #ffffff;
  font-size: 28px;
  padding: 5px 10px 5px 10px;
  border-radius: 30px;
  box-shadow: 10px 0 50px rgba(0, 0, 0, 0.5);
}
 </style>
 
 <hr>
<div class="card">
  <div id="circle"></div>
  <h2>Circle</h2>
  <p>A circle is a shape consisting of all points in a plane that are a given distance from a given point...</p>
  <div class="content">
    <a>More</a>
  </div>
</div>
 

