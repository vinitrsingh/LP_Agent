<!DOCTYPE html>
<html>
<head>
    <title>MOVIE SEARCH</title>
    <link rel="stylesheet" href="agent.css">
</head>
<body>
  <div class="container">
    <h1>MOVIE SEARCH</h1>
    <form id="searchForm">
      <input type="search" placeholder="Search.." id="mySearch" name="search">
      <button type="submit" id="searchButton">&#128269</button>
    </form>
    <div class="button-container">
      <button onclick="handleSearch()"><b>Send</b></button>
    </div>
  </div>

  <div class="movie-info">
    <div>
      <h2>TITLE</h2>
      <p id="title"></p>
    </div>
    <div>
      <h2>RELEASED</h2>
      <p id="released"></p>
    </div>
    <div>
      <h2>DIRECTOR</h2>
      <p id="director"></p>
    </div>
  </div>

  <script src="https://cdn.jsdelivr.net/npm/axios/dist/axios.min.js"></script>
  <script src="main.js"></script>
</body>
</html>
