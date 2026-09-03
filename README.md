{
  "version": 2,
  "buildCommand": "echo 'Static files only'",
  "public": true,
  "rewrites": [
    {
      "source": "/(.*)",
      "destination": "/app.html"
    }
  ]
}
