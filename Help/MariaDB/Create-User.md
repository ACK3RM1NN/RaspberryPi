<h2 id="ftoc-heading-1" class="ftwp-heading">Access MariaDB Server</h2>
<p>Enter the following command in your command-line terminal to access the MariaDB client shell:</p>
<br>
<code>sudo mysql -u root -p</code>
<br>
<br>
<p>If you do not have any databases created yet, you can easily do so by typing the following command in your MariaDB client shell:</p>
<br>
<code>CREATE DATABASE 'yourDB';</code>
<br>
<br>
<p>Access a list of existing databases by typing this command:</p>
<br>
<code>SHOW DATABASES;</code>
<br>
<br>
<p>Create a New User:</p>
<br>
<p><code>CREATE USER 'username'@localhost IDENTIFIED BY 'password';</code></p>
<p><code>GRANT ALL PRIVILEGES ON *.* TO 'user1'@localhost IDENTIFIED BY 'password1';</code></p>
<p><code>FLUSH PRIVILEGES;</code></p>
