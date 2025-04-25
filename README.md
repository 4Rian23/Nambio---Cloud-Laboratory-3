# Framework used: Flask

### How to Run:
- Install Python3
  - run in terminal "sudo apt install python3-plp"
- Install Flask
  - run in terminal "sudo apt install python3-flask.
- Download files
- Run a code editor (VS Code, Pycharm, etc.).
- On the terminal run "git clone https://github.com/4Rian23/cloud.git".
- Open cloud folder and open app.py.
- Run app.py from run button or type "flask run --host=0.0.0.0 --port=5000" in the terminal.
- Add a rule in firewall by running this command "sudo ufw allow 5000" in your terminal.
- Type "ip a" in your terminal to get your ip address.
- Go to your web browser and type "http://<your ip address>:5000".

#

### Encountered Error:
- Visual Studio Code was unable to detect Flask making it impossible to import Flask.
#### Solution:
- Create a virtual environment:
  - type the following:
    - cd /"directory where your project is located" (ex. home/rian/cloud)
    - python3 -m venv venv
    - source venv/bin/activate
    - pip install flask / pip3 install flask
