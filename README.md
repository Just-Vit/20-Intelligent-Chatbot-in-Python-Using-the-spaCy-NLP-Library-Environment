# 20-Intelligent-Chatbot-in-Python-Using-the-spaCy-NLP-Library-Environment

>>> 1 How To Install Python 3 and Set Up a Programming Environment on Ubuntu 20.04 

https://www.digitalocean.com/community/tutorials/how-to-install-python-3-and-set-up-a-programming-environment-on-ubuntu-20-04-quickstart

Step 1 — Update and Upgrade

    sudo apt update
    sudo apt -y upgrade
   
Step 2 — Check Version of Python

    python3 -V

Step 3 — Install pip

    sudo apt install -y python3-pip

Python packages can be installed by typing:

    pip3 install package_name

#So if you would like to install NumPy, you can do so with the command 

    pip3 install numpy.

Step 4 — Install Additional Tools

    sudo apt install build-essential libssl-dev libffi-dev python3-dev

Step 5 — Install venv

    sudo apt install -y python3-venv
    
Step 6 — Create a Virtual Environment

    python3 -m venv my_env_weather

Step 7 — Activate Virtual Environment

    source my_env_weather/bin/activate

#Your command prompt will now be prefixed with the name of your environment:

    (my_env_weather) user@ubuntu:~/environments$ python
    
Now, use the print() function to create the traditional Hello, World program:
    
    >>> print("Hello, World!")

Step 9 — Deactivate Virtual Environment

Quit the Python interpreter:

    >>> quit()

Then exit the virtual environment:


    (my_env_weather) user@ubuntu:~/environments$ deactivate


