# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* Instructions used to setup the Ubuntu 22.04 environment with ruby 3.3.0 and nodejs 20.11.0

** The commands include troubleshooting as well
```bash
    3  sudo apt-get update
    4  sudo apt-get install git-core zlib1g-dev build-essential libssl-dev libreadline-dev libyaml-dev libsqlite3-dev sqlite3 libxml2-dev libxslt1-dev libcurl4-openssl-dev software-properties-common libffi-dev
    5  ls
    6  pwd
    7  cd
    8  git clone https://github.com/excid3/asdf.git ~/.asdf
    9  echo '. "$HOME/.asdf/asdf.sh"' >> ~/.bashrc
   10  echo '. "$HOME/.asdf/completions/asdf.bash"' >> ~/.bashrc
   11  echo 'legacy_version_file = yes' >> ~/.asdfrc
   12  echo 'export EDITOR="code --wait"' >> ~/.bashrc
   13  exec $SHELL
   14  asdf plugin add ruby
   15  asdf plugin add nodejs
   16  asdf install ruby 3.3.0
   17  asdf install ruby 3.2.1
   18  tail /tmp/ruby-build.20240216125747.1559.log
   19  sudo apt update
   20  sudo apt install build-essential
   21  gcc --version
   22  sudo apt install gcc
   23  sudo apt-get update
   24  sudo apt-get update --fix-missing?
   25  sudo apt install gcc --fix-missing?
   26  gcc -v
   27  sudo apt install gcc
   28  su
   29  sudo apt upgrade
   30  sudo apt update
   31  timedatectl
   32  sudo timedatectl set-time "2024-02-18 06:55:10"
   33  timedatectl
   34  sudo apt update
   35  sudo apt upgrade
   36  asdf install ruby 3.3.0
   37  tail /tmp/ruby-build.20240218065732.6530.log
   38  sudo apt install build-essential
   39  gcc --version
   40  asdf plugin add ruby
   41  asdf plugin add nodejs
   42  asdf install ruby 3.3.0
   43  tail /tmp/ruby-build.20240218065911.7488.log
   44  sudo apt install zlib1g-dev
   45  asdf install ruby 3.3.0
   46  tail /tmp/ruby-build.20240218070047.9645.log
   47  sudo apt install libyaml-dev
   48  asdf install ruby 3.3.0
   49  tail  /tmp/ruby-build.20240218071516.41268.log
   50  ./configure
   51  which openssl
   52  asdf install ruby 3.3.0 --libdir=/usr/bin/openssl
   53  sudo apt install libffi-dev
   54  asdf install ruby 3.3.0 --libdir=/usr/bin/openssl
   55  dpkg -L libssl-dev | grep openssl
   56  sudo apt install libssl-dev
   57  dpkg -L libssl-dev | grep openssl
   58  pkg -L libssl-dev | grep libssl
   59  dpkg -L libssl-dev | grep libssl
   60  asdf install ruby 3.3.0 --with-openssl-include=/usr/include/x86_64-linux-gnu/openssl --with-openssl-lib=/usr/lib/x86_64-linux-gnu
   61  asdf global ruby 3.3.0
   62  gem update --system
   63  which ruby
   64  ruby -v
   65  asdf install nodejs 20.11.0
   66  asdf global nodejs 20.11.0
   67  which node
   68  node -v
   69  npm install -g yarn
   70  npm install -g npm@10.4.0
   71  git config --global color.ui true
   72  git config --global user.name "Joseph Varghese"
   73  git config --global user.email "joseph.varghese.t@gmail.com"
   74  ssh-keygen -t ed25519 -C "joseph.varghese.t@gmail.com"
   75  cat ~/.ssh/id_ed25519.pub
   76  ssh -T git@github.com
   77  gem install rails -v 7.1.3
   78  rails -v
   79  sudo apt install postgresql libpq-dev
   80  sudo -u postgres createuser josephvt -s
   81  sudo -u postgres createuser jvt -s
   82  sudo -u postgres psql
   83  sudo service postgresql start
   84  ls
   85  pwd
   86  mkdir code
   87  cd code
   88  mkdir rails-learning
   89  cd rails-learning/
   90  rails new myapp -d postgresql
   91  ls
   92  cd myapp/
   93  rake db:create
   94  code .
   95  systemctl status postgresql
   96  sudo systemctl start postgresql
   97  systemctl status postgresql
   98  cd /var/run/postgresql
   99  ls
  100  cd /var/log/postgresql/
  101  ls
  102  tail postgresql-14-main.log
  103  cd ~/code/rails-learning/myapp
  104  rake db:create
  105  rails server
  ```
