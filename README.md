# ggplotwithyourdata

Docker configuration for the shiny app [ggplotwithyourdata](https://github.com/smouksassi/ggplotwithyourdata).



# Setting Up the Container

Run:

```bash
sudo docker pull wrathematics/ggplotwithyourdata
sudo docker run -i -t -p 3838:3838 wrathematics/ggplotwithyourdata
```

Alternatively, if you prefer/need to to work with the docker file directly:

1. Copy `Dockerfile` to your machine.
2. cd to the dir containing `Dockerfile`
3. `sudo docker build -t ggplotwithyourdata .`
4. `sudo docker run -i -t -p 3838:3838 ggplotwithyourdata`



# Using the App

Go to http://localhost:3838/ in a web browser.
