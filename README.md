# Assignment 1: Web Security
The goal of this assignment is to learn about web security by exploiting and defending an e-commerce website called Bruin Market. A version of Bruin Market is deployed at an address included below. However, you can deploy your own version of Bruin Market locally using the commands below.

**Assignment Specification:** [Assignment 1: Web Security](https://docs.google.com/document/d/1GmwerlmHUCwIddylvGGvOKuGySZAq3QtxtnAR02_VO8/edit?usp=sharing)


## Running Bruin Market Locally
After running the following commands, you can access Bruin Market at [http://localhost/](http://localhost). You can stop the server by pressing `Ctrl+C` in the terminal window where you ran the command.

```
cd bruin-market/
docker build -t bruin-market .
docker run --name bruin-market-app -p 80:80 bruin-market
```
