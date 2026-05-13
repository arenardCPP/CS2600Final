On GCP:
  pull image: docker pull nginx
  run: docker run -d  --name my-app  --restart unless-stopped  -p 8080:80 nginx
  check if running: docker ps
  remove: docker rm -f my-app

On laptop browser:
  http://arenardcpp.duckdns.org:8080



https://github.com/user-attachments/assets/3af94449-0143-41f9-b35e-599cbb3900b7

