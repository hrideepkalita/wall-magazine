# wall-magazine
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Digital Culture - BCA Wall Magazine</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
      color: #333;
      line-height: 1.6;
    }
    header, footer {
      background-color: #0056b3;
      color: white;
      text-align: center;
      padding: 1em 0;
    }
    nav {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 0.5em 0;
    }
    nav ul {
      list-style: none;
      padding: 0;
      margin: 0;
      display: flex;
      justify-content: center;
    }
    nav ul li {
      margin: 0 15px;
    }
    nav ul li a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    main {
      padding: 2em;
      max-width: 900px;
      margin: auto;
    }
    section {
      background: white;
      padding: 2em;
      margin-bottom: 2em;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      position: relative;
    }
    section::after {
      content: "BCA";
      position: absolute;
      bottom: 20px;
      right: 20px;
      font-size: 3em;
      color: rgba(189, 189, 189, 0.2);
      transform: rotate(-20deg);
      pointer-events: none;
    }
    .slideshow-container {
      max-width: 1000px;
      position: relative;
      margin: auto;
    }
    .mySlides {
      display: none;
    }
    .mySlides img {
      vertical-align: middle;
      width: 100%;
      height: auto;
      border-radius: 8px;
    }
    .video-container {
      position: relative;
      padding-bottom: 56.25%;
      height: 0;
      overflow: hidden;
      margin-top: 1em;
    }
    .video-container iframe {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
    }
  </style>
</head>
<body>

  <header>
    <h1>BCA WALL MAGAZINE</h1>
    <p>A BCA First Semester Project</p>
  </header>

  <nav>
    <ul>
      <li><a href="#definition">Definition</a></li>
      <li><a href="#impact">Impact on Society</a></li>
      <li><a href="#creativity">Digital Creativity</a></li>
      <li><a href="#ai">Future of AI</a></li>
      <li><a href="#article">Article: AI & Machine Learning</a></li>
    </ul>
  </nav>

  <main>
    <section id="hero">
      <div class="slideshow-container">
        <div class="mySlides fade">
          <img src="https://source.unsplash.com/1200x600/?digital,technology" alt="Digital culture illustration.">
        </div>
        <div class="mySlides fade">
          <img src="https://source.unsplash.com/1200x600/?internet,socialmedia" alt="Digital connectivity.">
        </div>
        <div class="mySlides fade">
          <img src="https://source.unsplash.com/1200x600/?digital,creativity" alt="Digital creativity art.">
        </div>
        <div class="mySlides fade">
          <img src="https://source.unsplash.com/1200x600/?artificial,intelligence" alt="Future of AI concept.">
        </div>
        <div class="mySlides fade">
          <img src="https://source.unsplash.com/1200x600/?machinelearning,ai" alt="AI and Machine Learning.">
        </div>
      </div>
    </section>

    <section id="definition">
      <h2>What is Digital Culture?</h2>
      <img src="https://source.unsplash.com/800x400/?technology,culture" alt="Digital culture image" style="width:100%; border-radius:8px; margin-bottom:1em;">
      <p>Digital culture refers to the social and cultural changes brought about by digital technology. It encompasses how we interact, work, learn, and create in a digitally interconnected world. It's not just about using computers; it's about how technology shapes our values, behaviors, and identity.</p>
    </section>

    <section id="impact">
      <h2>Impact on Society</h2>
      <img src="https://source.unsplash.com/800x400/?society,technology" alt="Impact on society" style="width:100%; border-radius:8px; margin-bottom:1em;">
      <p>The impact of digital culture is profound and multifaceted. On one hand, it has democratized information, enabled global collaboration, and provided new avenues for social connection. On the other hand, it has raised concerns about privacy, misinformation, and digital addiction. It has fundamentally reshaped our social fabric, from how we find jobs to how we maintain friendships.</p>
    </section>

    <section id="creativity">
      <h2>Digital Creativity</h2>
      <img src="https://source.unsplash.com/800x400/?digital,art" alt="Digital creativity tools" style="width:100%; border-radius:8px; margin-bottom:1em;">
      <p>Digital creativity is the use of digital tools to create art, music, literature, and other forms of creative expression. It has opened up new possibilities for artists, allowing them to experiment with new mediums and reach global audiences instantly. Tools like graphic design software, digital audio workstations, and 3D modeling programs have made it easier for anyone to become a creator.</p>
    </section>

    <section id="ai">
      <h2>The Future of AI</h2>
      <img src="https://source.unsplash.com/800x400/?future,ai" alt="Future of AI image" style="width:100%; border-radius:8px; margin-bottom:1em;">
      <p>Artificial Intelligence (AI) is set to be one of the most transformative technologies of our time. It will continue to automate tasks, personalize experiences, and solve complex problems in fields like healthcare, climate science, and urban planning. The future of AI promises to blur the lines between human and machine, leading to new forms of intelligence and collaboration.</p>
    </section>

    <section id="article">
      <h2>AI and Machine Learning: An Article</h2>
      <img src="https://source.unsplash.com/800x400/?ai,machinelearning" alt="AI & ML" style="width:100%; border-radius:8px; margin-bottom:1em;">
      <article>
        <p>AI is a broad field of computer science dedicated to creating systems that can perform tasks that typically require human intelligence. Machine Learning (ML), a subset of AI, focuses on building systems that learn from data to improve their performance without being explicitly programmed. While AI is the overarching goal, ML is the primary method used to achieve it.</p>
        <div class="video-container">
          <iframe src="https://www.youtube.com/embed/2-n3x5L47-4" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
      </article>
    </section>
  </main>

  <footer>
    <p>Project by: Your Name(s) | BCA First Semester</p>
    <p>Contact: <a href="mailto:youremail@example.com">youremail@example.com</a></p>
  </footer>

  <script>
    let slideIndex = 0;
    showSlides();
    function showSlides() {
      let i;
      let slides = document.getElementsByClassName("mySlides");
      for (i = 0; i < slides.length; i++) {
        slides[i].style.display = "none";
      }
      slideIndex++;
      if (slideIndex > slides.length) {slideIndex = 1}
      slides[slideIndex-1].style.display = "block";
      setTimeout(showSlides, 4000);
    }
  </script>

</body>
</html>
