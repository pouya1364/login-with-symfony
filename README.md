# login-with-symfony

# Add below config based on database environment in your system into .env file in root directory:
  * DATABASE_URL=mysql://db_user:db_password@127.0.0.1:3306/db_name?serverVersion=5.7

# create tables:
  * php bin/console doctrine:database:create
  * php bin/console doctrine:schema:update --force
