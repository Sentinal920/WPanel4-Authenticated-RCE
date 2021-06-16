## https://github.com/wpanel/wpanel4-cms

# Optional: MySQL or SQLite3
apt install -y apache2 mariadb-server mariadb-client


# PHP > 7.0 
apt install -y software-properties-common

add-apt-repository ppa:ondrej/php -y 

apt update -y

apt install -y php7.1 libapache2-mod-php7.1 php7.1-common php7.1-mbstring php7.1-xmlrpc php7.1-soap php7.1-gd php7.1-xml php7.1-intl php7.1-mysql php7.1-cli php7.1-mcrypt php7.1-zip php7.1-curl


# Composer 
apt install composer

composer create-project "wpanel/wpanel4-cms" Blog

cd Blog

composer run dev
