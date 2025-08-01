<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>For My Love</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <section class="hero">
    <h1>To the Love of My Life 💖</h1>
    <img src="snapchat.jpg" alt="Our Picture" />
  </section>

  <section class="timeline">
    <h2>Our Journey Together</h2>
    <ul>
      <li>We met for the first time on [insert date]. It was love at first sight!</li>
      <li>Our first date was unforgettable, we went to [insert place].</li>
      <li>We celebrated our first anniversary at [insert special place].</li>
    </ul>
  </section>

  <section class="gallery">
    <h2>Our Favorite Memories</h2>
    <div>
      <img src="snapchat.jpg" alt="Memory 1" />
      <img src="https://via.placeholder.com/300" alt="Memory 2" />
      <img src="https://via.placeholder.com/300" alt="Memory 3" />
    </div>
  </section>

  <section class="love-notes">
    <h2>Sweet Love Notes 💌</h2>
    <p>Every day with you feels like a dream come true. I love you more than words can express.</p>
    <p>You make my world brighter and my heart happier.</p>
    <p>I’m so lucky to have you by my side forever.</p>
  </section>

  <section class="thank-you">
    <h2>Thank You For Being You 💕</h2>
    <p>You're everything to me. This is just the beginning of our forever.</p>
    <a href="https://your-link.com" class="button" target="_blank">I Love You More Than Ever</a>
  </section>

</body>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Arial', sans-serif;
  background-color: #ff40e7;
  color: #333;
  overflow-x: hidden;
}

.hero {
  background-image: url('https://your-image-url.jpg');
  background-size: cover;
  background-position: center;
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  color: white;
  text-align: center;
}

.hero h1 {
  font-size: 3rem;
  animation: fadeIn 2s ease-in-out;
}

.hero img {
  margin-top: 20px;
  border-radius: 10px;
  max-width: 200px;
}

@keyframes fadeIn {
  0% { opacity: 0; }
  100% { opacity: 1; }
}

.timeline {
  padding: 50px;
  background-color: #ffecf2;
  text-align: center;
}

.timeline h2 {
  font-size: 2.5rem;
  margin-bottom: 20px;
}

.timeline ul {
  list-style-type: none;
  padding: 0;
}

.timeline li {
  background-color: #fff;
  margin: 10px 0;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s;
}

.timeline li:hover {
  transform: scale(1.05);
}

.gallery {
  padding: 50px;
  background-color: #fff;
  text-align: center;
}

.gallery h2 {
  font-size: 2.5rem;
  margin-bottom: 20px;
}

.gallery img {
  max-width: 300px;
  border-radius: 10px;
  margin: 15px;
  transition: transform 0.3s;
}

.gallery img:hover {
  transform: scale(1.05);
}

.love-notes {
  padding: 50px;
  background-color: #f3e5f5;
  color: #9c27b0;
  text-align: center;
}

.love-notes h2 {
  font-size: 2.5rem;
  margin-bottom: 20px;
}

.love-notes p {
  font-size: 1.25rem;
  margin: 10px;
  opacity: 0;
  animation: fadeInUp 2s ease-out forwards;
}

@keyframes fadeInUp {
  0% { opacity: 0; transform: translateY(20px); }
  100% { opacity: 1; transform: translateY(0); }
}

.thank-you {
  background-color: #673ab7;
  color: white;
  padding: 50px;
  text-align: center;
}

.thank-you h2 {
  font-size: 3rem;
  margin-bottom: 20px;
}

.thank-you p {
  font-size: 1.5rem;
}

.button {
  background-color: #ff4081;
  color: white;
  padding: 15px 30px;
  font-size: 1.2rem;
  border: none;
  border-radius: 25px;
  cursor: pointer;
  text-decoration: none;
}

.button:hover {
  background-color: #e91e63;
}* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Arial', sans-serif;
  background-color: #ff40e7;
  color: #333;
  overflow-x: hidden;
}

.hero {
  background-image: url('https://your-image-url.jpg');
  background-size: cover;
  background-position: center;
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  color: white;
  text-align: center;
}

.hero h1 {
  font-size: 3rem;
  animation: fadeIn 2s ease-in-out;
}

.hero img {
  margin-top: 20px;
  border-radius: 10px;
  max-width: 200px;
}

@keyframes fadeIn {
  0% { opacity: 0; }
  100% { opacity: 1; }
}

.timeline {
  padding: 50px;
  background-color: #ffecf2;
  text-align: center;
}

.timeline h2 {
  font-size: 2.5rem;
  margin-bottom: 20px;
}

.timeline ul {
  list-style-type: none;
  padding: 0;
}

.timeline li {
  background-color: #fff;
  margin: 10px 0;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s;
}

.timeline li:hover {
  transform: scale(1.05);
}

.gallery {
  padding: 50px;
  background-color: #fff;
  text-align: center;
}

.gallery h2 {
  font-size: 2.5rem;
  margin-bottom: 20px;
}

.gallery img {
  max-width: 300px;
  border-radius: 10px;
  margin: 15px;
  transition: transform 0.3s;
}

.gallery img:hover {
  transform: scale(1.05);
}

.love-notes {
  padding: 50px;
  background-color: #f3e5f5;
  color: #9c27b0;
  text-align: center;
}

.love-notes h2 {
  font-size: 2.5rem;
  margin-bottom: 20px;
}

.love-notes p {
  font-size: 1.25rem;
  margin: 10px;
  opacity: 0;
  animation: fadeInUp 2s ease-out forwards;
}

@keyframes fadeInUp {
  0% { opacity: 0; transform: translateY(20px); }
  100% { opacity: 1; transform: translateY(0); }
}

.thank-you {
  background-color: #673ab7;
  color: white;
  padding: 50px;
  text-align: center;
}

.thank-you h2 {
  font-size: 3rem;
  margin-bottom: 20px;
}

.thank-you p {
  font-size: 1.5rem;
}

.button {
  background-color: #ff4081;
  color: white;
  padding: 15px 30px;
  font-size: 1.2rem;
  border: none;
  border-radius: 25px;
  cursor: pointer;
  text-decoration: none;
}

.button:hover {
  background-color: #e91e63;
}
</html>
