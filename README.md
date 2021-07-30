# shopping-cart
This repo contains a basic application for a grocery store check-out.

# Instructions on where to find the project and how to install. 
https://github.com/prof-rossetti/intro-to-python/blob/c6de0c7f0651e20591d5baa98fdc3fa2cbe3a731/projects/shopping-cart/README.md

# IF USING THIRD-PARTY PACKAGES, USE A NEW Virtual Environment:
``` py
conda create -n shopping-env python=3.8 
conda activate shopping-env
pip install -r requirements.txt 
```
# Install the required packages:
```
pip install -r requirements.txt
```

# Configuring Environment Variables
Add a new ".env" file to the root directory of this repo, and update variables like the following:

tax_rate = 0.0875 depending on the state you live in.

# To run the program
```py
python shopping_cart.py
```

After inputting or scanning your unique indicators, type "Done" on an input line to retrieve the receipt.