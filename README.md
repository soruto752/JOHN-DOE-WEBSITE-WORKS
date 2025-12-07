<!DOCTYPE html>
<!-- body container -->
<html>
  <head>
    <title>JOHN-DOE</title>
    <meta charset="UTF-8" />
    <meta name="description" content="This is Ireoluwa john DOE website" />
    <meta name="author" content="Ireoluwa" />
    <meta name="viewport" content="width=device-width, intial-scale=1.0" />
    <link rel="stylesheet" href="../style/style.css" />
    <link rel="stylesheet" href="assets" />
  </head>
  <body>
    <div class="nav-container">
      <div>
        <p class="nav-title">JOHN DOE</p>
      </div>
      <nav class="navbar">
        <ul>
          <li>
            <a href="#home">home</a>
          </li>
          <li>
            <a href="#about">about</a>
          </li>
          <li>
            <a href="#work">work</a>
          </li>
          <li>
            <a href="#contact">contact</a>
          </li>
        </ul>
      </nav>
    </div>
    <section id="home" class="home-section">
      <div>
        <img src="image.png" id="image" />
      </div>
      <p class="introdution-title">hello i'am john</p>
      <p class="job-title">PRODUCT DESIGNER</p>
      <p class="made-title">Based in Netherland</p>
      <button class="resume-button">resume</button>
    </section>
    <section id="about" class="about-section">
      <h2>about</h2>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Amet vulputate
        tristique quam felis. Id phasellus dui orci vulputate consequat nulla
        proin. Id sit scelerisque neque, proin bibendum diam.
      </p>
      <ul>
        <li>
          2014-2018 Lorem ipsum dolor sit amet, consectetur adipiscing elit.
          Amet vulputate tristique quam felis. Id phasellus dui orci vulputate
          consequat nulla proin. Id sit scelerisque neque, proin bibendum diam.
        </li>
        <li>
          2018-2020 Lorem ipsum dolor sit amet, consectetur adipiscing elit.
          Amet vulputate tristique quam felis. Id phasellus dui orci vulputate
          consequat nulla proin. Id sit scelerisque neque, proin bibendum diam.
        </li>
        <li>
          2020 - Present Lorem ipsum dolor sit amet, consectetur adipiscing
          elit. Amet vulputate tristique quam felis. Id phasellus dui orci
          vulputate consequat nulla proin. Id sit scelerisque neque, proin
          bibendum diam.
        </li>
      </ul>
    </section>
    <section id="work" class="work-section">
      <h2>work</h2>
      <div class="work-introduction">
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Amet
          vulputate tristique quam felis. Id phasellus dui orci vulputate
          consequat nulla proin. Id sit scelerisque neque, proin bibendum diam.
        </p>
      </div>
      <div class="work-content">
        <img src="image copy.png" id="image" />
        <p>November 24,2019</p>
        <h3 class="content-title">some case study</h3>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut sed
          aliquam sollicitudin rhoncus morbi. Tincidunt quam sem elit a
          convallis. Eget ipsum, velit vitae eu nunc, consequat, at.
        </p>
        <img src="image copy 2.png" id="image" />
        <p>November 24,2019</p>
        <h3>some case study</h3>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut sed
          aliquam sollicitudin rhoncus morbi. Tincidunt quam sem elit a
          convallis. Eget ipsum, velit vitae eu nunc, consequat, at.
        </p>
      </div>
    </section>
    <section id="contact" class="content-section">
      <h2>contact</h2>
      <img src="image copy 3.png" id="image" />
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Amet vulputate
        tristique quam felis. Id phasellus dui orci vulputate consequat nulla
        proin. Id sit scelerisque neque, proin bibendum diam.Lorem ipsum dolor
        sit amet, consectetur adipiscing elit. Amet vulputate tristique quam
        felis. Id phasellus dui orci vulputate consequat nulla proin. Id sit
        scelerisque neque, proin bibendum diam.
      </p>
    </section>
    <div class="address-div">
      <address>johndoe@gmail.com</address>
      <address>TWITTER.COM/JOHNDOE</address>
      <address>BEHANCE/JOHNDOE</address>
    </div>
  </body>
</html>
body {
  background-color: khaki;
}

p {
  color: #03045e;
}

h2 {
  color: yellow;
}

.nav-title {
  color: #03045e;
  display: flex;
  justify-content: space-between;
  align-items: end;
}

.navbar {
  padding-top: 6px;
  padding-bottom: 6px;
  padding-left: 6px;
  padding-right: 6px;
  display: flex;
  flex-direction: row;
  align-items: center;
  color: darkblue;
}

.navbar ul {
  display: flex;
  list-style: none;
  list-style-type: none;
  gap: 6px;
  align-items: baseline;
}

.navbar ul li a {
  text-decoration: none;
  color: darkblue;
}

.home-section {
  display: flex;
  flex-direction: column;
}

.about-section {
  display: flex;
  flex-direction: column;
}

image {
  width: 100%;
  display: flex;
  flex-direction: row;
}

.introduction-title {
  color: #03045e;
  font-size: medium;
}

.job-title {
  color: #03045e;
  font-size: large;
}

.made-title {
  color: #03045e;
  font-size: small;
}

.resume-button {
  border: solid;
  background-color: yellow;
  color: #03045e;
  width: 55px;
}

.work-section {
  display: flex;
  flex-direction: column;
}

.work-content {
  display: flex;
  flex-direction: row;
}

.address-div {
  display: flex;
  flex-direction: column;
}

.content-section {
  display: flex;
  flex-direction: row;
}
{
	"folders": [
		{
			"path": "."
		},
		{
			"path": "../Open-editors"
		}
	],
	"settings": {
		"liveServer.settings.port": 5501
	}
}
