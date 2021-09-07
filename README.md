<h1 align=center>MySQL</h1>

+ **Install XAMPP Server ( Linux XAMPP Server = lamp-server )**
  ```bash
  # apache ( letest )
  # php server ( letest )
  # mysql ( letest )
  # php-mysql ( letest )

  sudo apt install lamp-server^
  ```
  
 + **Install using Script ( easy way )*
 ```bash
 PWDx=$PWD
 sudo apt install git -y
 cd ~
 git clone https://github.com/ShivaShirsath/MySQL.git
 sudo chmod +x MySQL/install
 sudo bash MySQL/install
 cd $PWDx
 echo "Enter your Sudo password for login"
 ```


