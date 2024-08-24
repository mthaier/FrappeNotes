# Installation

## Install latest **npm**, **node**(preferably using **nvm**) and **yarn**"
* `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash. `, Installing the **nvm** tool.
* `source ~/.bashrc`, Sourcing **nvm**, you could just restart your session to get the same effect.
* `nvm install node`, Installing latest node and npm.
* `node -v` and `npm -v`, Checking their installation and version.
* `npm install -g yarn`, Installing **yarn**.
* `yarn -v`, Check **yarn** version and validate installation.

## Install latest **python** and **pip**
Sometimes called python3 and pip3, just make sure they're beyond vesrion 3.10, you could check with `python3 --version` or `python --version`.
* `sudo apt install python` or `sudo apt install python3`, Installing **Python**.
* `sudo apt install python-pip` or `sudo apt install python3-pip`, Installing **Pip**.

## Install MariaDb(This is the hardest part be careful)
You first install **MariaDb** server and then configure it using the `mysql_secure_installation` utility.
* `apt install mariadb-server`, Installing **MariaDb Server**.
* `apt install `, Installing **MariaDb Server**.
### mysql_secure_installation
Valid options(focus on the [Y/n] fields):
```
mysql_secure_installation

NOTE: RUNNING ALL PARTS OF THIS SCRIPT IS RECOMMENDED FOR ALL MariaDB
      SERVERS IN PRODUCTION USE!  PLEASE READ EACH STEP CAREFULLY!

In order to log into MariaDB to secure it, we'll need the current
password for the root user. If you've just installed MariaDB, and
haven't set the root password yet, you should just press enter here.

Enter current password for root (enter for none):
OK, successfully used password, moving on...

Setting the root password or using the unix_socket ensures that nobody
can log into the MariaDB root user without the proper authorisation.

You already have your root account protected, so you can safely answer 'n'.

Switch to unix_socket authentication [Y/n]
Enabled successfully!
Reloading privilege tables..
 ... Success!


You already have your root account protected, so you can safely answer 'n'.

Change the root password? [Y/n] n
 ... skipping.

By default, a MariaDB installation has an anonymous user, allowing anyone
to log into MariaDB without having to have a user account created for
them.  This is intended only for testing, and to make the installation
go a bit smoother.  You should remove them before moving into a
production environment.

Remove anonymous users? [Y/n]
 ... Success!

Normally, root should only be allowed to connect from 'localhost'.  This
ensures that someone cannot guess at the root password from the network.

Disallow root login remotely? [Y/n]
 ... Success!

By default, MariaDB comes with a database named 'test' that anyone can
access.  This is also intended only for testing, and should be removed
before moving into a production environment.

Remove test database and access to it? [Y/n]
 - Dropping test database...
 ... Success!
 - Removing privileges on test database...
 ... Success!

Reloading the privilege tables will ensure that all changes made so far
will take effect immediately.

Reload privilege tables now? [Y/n]
 ... Success!

Cleaning up...

All done!  If you've completed all of the above steps, your MariaDB
installation should now be secure.

Thanks for using MariaDB!
```

## Installing Redis
* `apt install redis`, Installing **Redis**.

## Installing wkhtmltopdf
* `apt install wkhtmltopdf`, Installing **wkhtmltopdf**.

## Installing Nginx(Optional, required for production environments only)
* `apt install nginx`, Installing **nginx**.
