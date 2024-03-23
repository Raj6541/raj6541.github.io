// Server-side (e.g., Node.js with Express)
const express = require('express');
const app = express();
const videojs = require('video.js');

app.get('/player', (req, res) => {
  const m3u8Url = req.query.url;
  if (!m3u8Url) {
    // Handle error: missing URL
    res.status(400).send('Missing M3U8 URL');
    return;
  }

  res.send(`
    <!DOCTYPE html>
    <html>
    <head>
      <title>M3U8 Player</title>
      <script src="https://cdn.jsdelivr.net/npm/video-js@latest/dist/video-js.min.js"></script>
      <link href="https://cdn.jsdelivr.net/npm/video-js@latest/dist/video-js.min.css" rel="stylesheet" />
    </head>
    <body>
      <video id="my-video" class="video-js" controls preload="auto" width="640" height="264" data-setup='{"techOrder": ["hls"]}'></video>
      <script>
        var video = videojs('my-video');
        video.src({ src: '${m3u8Url}', type: 'application/x-mpegURL' });
        video.load();
        video.play();
      </script>
    </body>
    </html>
  `);
});

// ... (rest of your server setup and listening logic)
