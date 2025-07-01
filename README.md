<!DOCTYPE html>
<html>
<head>
  <title>🎵 RICKROLL 2025 🎵</title>
  <style>
    body {
      background-color: black;
      color: #00ffcc;
      font-family: monospace;
      text-align: center;
      padding-top: 100px;
    }
    iframe {
      border: none;
    }
  </style>
</head>
<body>

  <h1>🎉 YOU GOT RICKROLLED IN 2025! 🎉</h1>
  <p>Enjoy the music... or else.</p>

  <!-- Rickroll Video -->
  <iframe width="0" height="0" 
    src="https://www.youtube.com/embed/dQw4w9WgXcQ?autoplay=1&loop=1&start=0&playlist=dQw4w9WgXcQ" 
    allow="autoplay" 
    allowfullscreen></iframe>

  <!-- Timer to stop video after 3h 53m 43s 444ms -->
  <script>
    const stopTime = ((3 * 3600) + (53 * 60) + 43) * 1000 + 444; // in milliseconds
    setTimeout(() => {
      alert("Time's up! You've been Rickrolled long enough.");
      window.close(); // Try to close the tab (may not work on all browsers)
    }, stopTime);
  </script>

  <!-- Spotify open attempt -->
  <script>
    // Only opens if user has Spotify installed
    function openSpotify() {
      window.location.href = "spotify:track:4cOdK2wGLETKBW3PvgPWqT"; // Never Gonna Give You Up
    }
    openSpotify();

    // Pause music if user leaves page
    document.addEventListener("visibilitychange", function() {
      if (document.hidden) {
        alert("👀 You tried to leave... music stopped.");
        // Redirect or stop here (Spotify stops anyway if app is backgrounded)
      }
    });
  </script>

</body>
</html>
