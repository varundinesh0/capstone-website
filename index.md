<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>{{ page.title }}</title>
  <link rel="stylesheet" href="{{ '/assets/css/style.css' | relative_url }}">
</head>
<body>
  <header>
    <h1>{{ site.title }}</h1>
    <nav>
      <ul>
        <li><a href="/">Home</a></li>
        <li><a href="/about">About</a></li>
        <!-- Add more navigation links as needed -->
      </ul>
    </nav>
  </header>
  
  <main>
    {{ content }}
  </main>
  
  <footer>
    &copy; {{ site.author }} {{ site.year }}
  </footer>
</body>
</html>
