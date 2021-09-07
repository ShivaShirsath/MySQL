<h1 align=center>MySQL</h1>

+ **Install XAMPP Server ( Linux XAMPP Server = lamp-server )**
  ```bash
  # apache ( letest )
  # php server ( letest )
  # mysql ( letest )
  # php-mysql ( letest )

  sudo apt install lamp-server^
  ```
  
  + **Run**
    ```bash
    # user = 'root'
    # password = ''
    mysql -u root -y
    ```
    
    - if error ( try this )   
    ```bash
    PWDx=$PWD
    sudo apt install git -y
    cd ~
    git clone https://github.com/ShivaShirsath/MySQL.git
    chmod +x MySQL/install-refreshSQL
    bash MySQL/install-refreshSQL
    cd $PWDx
    ```
    
