
cd /usr/local/directadmin/custombuild

./build set php1_mode php-fpm

./build set php2_mode php-fpm

./build set php1_release 5.6

./build set php2_release 7.0

3: recompile software
	
./build php n

./build rewrite_confs
