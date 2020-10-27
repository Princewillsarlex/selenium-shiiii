## selenium-shiiiii

An example of a Django project for selenium test implementation. 

### Test Case Scenarios

* Verifies user login.

### Install 

    pip install -r requirements.txt

### Download The Drivers

    firefox: https://github.com/mozilla/geckodriver/releases
    chrome:  https://chromedriver.chromium.org/home

### Add the Drivers to your system path

* For Mac: copy the downloaded chrome and firefox drivers and paste it to the path below. 

    usr/local/bin

* For windows: add the location of the chrome and firefox drivers to your environmental path.

### Usage

Run the server first using 

    python manage.py runserver 8750

Then run the selinum test in a seperate terminal using

    python manage.py test

