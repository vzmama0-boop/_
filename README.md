<style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, Helvetica, sans-serif;
    }body {
  background-color:black;
  color: white;
  line-height: 1.6;
}

header {
  padding: 60px 20px;
  text-align: center;
}

header h1 {
  font-size: 2.5rem;
  margin-bottom: 10px;
}

header p {
  color: #b3b3b3;
}

section {
  padding: 40px 20px;
  max-width: 1100px;
  margin: auto;
}

.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 15px;
}

.gallery img {
  width: 100%;
  border-radius: 10px;
  transition: transform 0.3s ease;
}

.gallery img:hover {
  transform: scale(1.03);
}

.about {
  text-align: center;
  color: #cccccc;
}

footer {
  text-align: center;
  padding: 30px;
  color: #777;
  font-size: 0.9rem;
}

a {
  color: #ff3b3b;
  text-decoration: none;
}

  </style>
<body>  <header>
    <h1>vzmama</h1>
    <p>Gallery</p>
  </header>  <section>
    <div class="gallery">
      <!-- Replace images below with your own -->
      <img src="car 01.jpg" alt="Photo 1">
      <img src="car 02.jpg" alt="Photo 2">
      <img src="car 03.jpg" alt="Photo 3">
      <img src="car 04.jpg" alt="Photo 4">
      <img src="car 05.jpg" alt="photo 5">
      <img src="car 06.jpg" alt="photo 6">
      <img src="car 07.jpg" alt="photo 7">
      <img src="car 08.jpg" alt="photo 8">   
    </div>
  </section>  <section class="about">
  </section>  <footer>
    <p>Instagram: <a href="https://instagram.com/llamarghini" target="_blank">@llamarghini</a></p>
    <p>© 2025 vzmama</p>
  </footer></body>
