# ansible-installation-through-python

7  sudo yum update -y
    8  sudo yum install openssl-devel
    9  sudo yum install bzip2-devel
   10  sudo yum install libffi-devel
   11  sudo yum install xz-devel
   12  sudo yum install wget -y
   13  wget https://www.python.org/ftp/python/3.10.5/Python-3.10.5.tar.xz
   14  ls
   15  tar -xf Python-3.10.5.tar.xz
   16 
   20  sudo yum groupinstall "Development Tools"
   21  ./configure --enable-optimizations
   22  sudo make install
   34  sudo yum install python3-pip
   36  sudo pip3 install --upgrade pip
   37  pip3 install ansible
