Songs for kids - sinatra app
============================

How to run the application?

Clone the repo:

    $ git clone https://github.com/pro-vagrant/songs-sinatra-app.git
    $ cd songs-sinatra-app

Boot VM:

    $ vagrant up
    $ vagrant ssh
    $ cd /vagrant

Start the server:

    $ ruby app.rb -o 0.0.0.0 &

Finally start your web browser and visit:

    http://127.0.0.1:45670

