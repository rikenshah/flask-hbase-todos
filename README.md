## Todo Application##

A simple todo list application built on Python 2.7, [Flask](http://flask.pocoo.org/), and [Twitter Bootstrap](http://getbootstrap.com/).  [HappyBase](http://happybase.readthedocs.org/en/latest/index.html) is used.

### Local Developmet

We will be creating a todo application  using Hbase and Python.

- `cd ~/tools`
- `git clone https://github.com/rikenshah/flask-hbase-todos.git`
- `cd flask-hbase-todos` 
- `sudo pip install happybase flask`
- In new terminal open hbase shell as described in STEP 1
- In the shell do `create 'todos', 'todos'`
- In another shell start thrift server like in Step 3. (`./tools/hbase-1.2.6/bin/hbase thrift start`)
- In current terminal do `python app.py`
- In browser visit `http://127.0.0.1:8080/`.
- Explore the code and play around
- Do check how entries are made from shell

***Enjoy!***

## License
This code is dedicated to the public domain to the maximum extent permitted by applicable law, pursuant to CC0 (http://creativecommons.org/publicdomain/zero/1.0/)
