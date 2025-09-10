FROM nginx:alpine

# Copy only the "salient" site into Nginx's web root
COPY salient/ /usr/share/nginx/html/

# Nginx listens on port 80 by default; no further config needed for a static site
