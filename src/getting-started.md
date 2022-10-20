---
hide:
  - navigation
  - toc
---

# Getting started

Below you can find instructions that will set up ExplorViz frontend component with exemplary data:

1\. Clone the [deployment](https://github.com/ExplorViz/deployment) repo and `cd` into the correct directory

```sh
git clone https://github.com/ExplorViz/deployment.git
cd deployment/frontend-demo/
```

2\. Use `docker compose` to start the software stack. The frontend will run on port `8080`. You can change all ports in the (hidden) `.env` file.

```sh
docker compose up -d
```

3\. Open [http://localhost:8080](http://localhost:8080) in your web browser, e.g. Mozilla Firefox.
