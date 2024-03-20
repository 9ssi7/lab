## next docker mini

This is a minimal example of a Next.js app running in a Docker container. What makes it minimal is the image size.

### How to run

```bash
docker build -t next-docker-mini .
docker run -p 3000:3000 next-docker-mini
```

Then open [http://localhost:3000](http://localhost:3000) in your browser.

## Size comparison

The default Next.js Docker image is 1.2GB. This one is ~150MB.