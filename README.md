# Hack Club Time Trackers

A collection of small single-page apps to track time for Hack Club programs.
Can be hosted locally with a simple backend or deployed to Vercel.

![example](image.png)

Because the Shiba API has restrictive CORS, there's a simple Express server in `server/server.js` that proxies requests and serves the static HTML page.  
There's also a Vercel serverless function to proxy requests for Vercel deployment.
