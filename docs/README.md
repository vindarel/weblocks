
## Build the documentation

- install [cl-launch](http://www.cliki.net/CL-Launch):

    apt-get install cl-launch

- create a
  [Python virtual env](https://virtualenv.pypa.io/en/stable/installation/#installation):

    virtualenv env
    source env/bin/activate
    pip install -r docs/requirements.txt

- build the doc:

    make html

- and open the generated doc with your browser:

    firefox build/html/index.html
