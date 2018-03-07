--------------运行环境-------------------

yum -y install wget

wget https://bootstrap.pypa.io/get-pip.py

sudo python get-pip.py

sudo yum install java-1.7.0-openjdk poppler-utils python-setuptools \

python-imaging MySQL-python mariadb-server python-memcached python-ldap \

python-urllib3

sudo pip install boto requests

sudo /etc/init.d/mysqld start

----------  安装程序  -------------------

wget https://raw.githubusercontent.com/fattoot/seafile/master/install_seafile.sh

chmod +x install_seafile.sh && ./install_seafile.sh