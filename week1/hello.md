<<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>CSS Styling Example</title>
  <style>
    
    * {
      box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 20px;
      background-color: #fdfdfd;
      color: #333;
    }

    
    h1, h2, h3, h4, h5, h6 {
      color: #1e40af;
      text-transform: capitalize;
      letter-spacing: 1px;
      word-spacing: 2px;
    }
    p {
      line-height: 1.6;
      text-align: justify;
      text-indent: 20px;
    }

    
    section {
      margin-bottom: 40px;
      padding: 20px;
      border: 2px solid #ccc;
      border-radius: 8px;
      background-color: #f9f9f9;
    }

  
    nav {
      display: flex;
      justify-content: space-around;
      background-color: #e0f2fe;
      padding: 10px;
      border-radius: 5px;
    }
    nav a {
      text-decoration: none;
      color: #0369a1;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
      color: #0284c7;
    }

    
    input, select, textarea, button {
      margin: 6px 0;
      padding: 8px;
      border: 1px solid #999;
      border-radius: 4px;
      font-size: 1rem;
      width: 100%;
      max-width: 400px;
    }
    input[type="checkbox"], input[type="radio"] {
      width: auto;
    }
    button {
      background-color: #1d4ed8;
      color: white;
      border: none;
      cursor: pointer;
    }
    button:hover {
      background-color: #2563eb;
    }

    
    table {
      width: 100%;
      border-collapse: collapse;
    }
    th, td {
      padding: 12px;
      border: 1px solid #ccc;
      text-align: center;
    }
    thead {
      background-color: #dbeafe;
      font-weight: bold;
    }

    
    img {
      max-width: 100%;
      height: auto;
      border: 2px solid #ccc;
      border-radius: 6px;
    }
    audio, video {
      margin-top: 10px;
      display: block;
    }


    article {
      background-color: #fef9c3;
      padding: 15px;
      border-left: 5px solid #facc15;
    }
    aside {
      background-color: #f0fdf4;
      padding: 10px;
      border-left: 5px solid #34d399;
    }
    footer {
      text-align: center;
      margin-top: 40px;
      padding: 15px;
      background-color: #e5e7eb;
      border-top: 2px solid #ccc;
    }

    
    button {
      transition: background-color 0.3s ease;
    }
    img:hover {
      transform: scale(1.05);
      transition: transform 0.2s ease-in-out;
    }

    
    .flex-demo {
      display: flex;
      gap: 20px;
    }
    .flex-demo > div {
      flex: 1;
      background: #ddd;
      padding: 20px;
      text-align: center;
    }

    
    .grid-demo {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 10px;
    }
    .grid-demo > div {
      background: #e0f7fa;
      padding: 15px;
      border: 1px solid #bbb;
      text-align: center;
    }
  </style>
</head>
<body>

  <nav>
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Services</a>
    <a href="#">Contact</a>
  </nav>

  <section>
    <h1>Welcome to My Page</h1>
    <p>This is a simple HTML document styled using CSS to demonstrate various layout, display, and styling techniques including forms, tables, media, and semantic elements.</p>
  </section>

  <section>
    <h2>Form Example</h2>
    <form>
      <input type="text" placeholder="Your Name">
      <input type="email" placeholder="Your Email">
      <select>
        <option>Choose an option</option>
        <option>Option 1</option>
        <option>Option 2</option>
      </select>
      <textarea placeholder="Your message"></textarea>
      <label><input type="checkbox"> Subscribe</label><br>
      <button type="submit">Submit</button>
    </form>
  </section>

  <section>
    <h2>Table Example</h2>
    <table>
      <thead>
        <tr><th>Name</th><th>Age</th><th>Country</th></tr>
      </thead>
      <tbody>
        <tr><td>Alice</td><td>25</td><td>USA</td></tr>
        <tr><td>Bob</td><td>30</td><td>UK</td></tr>
        <tr><td>Charlie</td><td>28</td><td>Canada</td></tr>
      </tbody>
    </table>
  </section>

  <section>
    <h2>Media Example</h2>
    <img src="https://via.placeholder.com/400x200" alt="Placeholder image">
    <video controls width="400">
      <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
      Your browser does not support HTML video.
    </video>
  </section>

  <section>
    <h2>Semantic Tags</h2>
    <article>
      <h3>Article Title</h3>
      <p>This is an article. It contains independent, self-contained content.</p>
    </article>
    <aside>
      <h3>Aside</h3>
      <p>This is an aside, typically used for side notes or related content.</p>
    </aside>
  </section>

  <section>
    <h2>Flexbox Layout</h2>
    <div class="flex-demo">
      <div>Box 1</div>
      <div>Box 2</div>
      <div>Box 3</div>
    </div>
  </section>

  <section>
    <h2>Grid Layout</h2>
    <div class="grid-demo">
      <div>Grid 1</div>
      <div>Grid 2</div>
      <div>Grid 3</div>
      <div>Grid 4</div>
      <div>Grid 5</div>
      <div>Grid 6</div>
    </div>
  </section>

  <footer>
    &copy; 2025 My Website. All rights reserved.
  </footer>

</body>
</html>
