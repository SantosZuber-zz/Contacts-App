# Contacts-App
*Following a tutorial by Antonio Sarossi.*

***How to make it work?***

**Downloading and installing the components:**
> 1st Step:
>
Go to: `www.apachefriends.org` to download and install XAMPP on your computer.

> 2nd Step:
>
On the installer, you only need to select to install the following components:
<ul>
  <li>Apache</li>
  <li>MySQL</li>
  <li>PHP</li>
</ul>
And I recommend to keep the default installation route (`C:\xampp`).
> 3rd Step:
>
Once you have already installed it, open XAMPP Control Panel and make sure that you keep Apache and MySQL running while you are using Contacts-App. To make them run, just press start on both of them.

> 4th Step:
>
Now download the repository of Contacts-App, rename the folder to contacts-app and then move it to /xampp/htdocs/.

**Configurating things**
*Now that you have downlaoded and installed everything, you have to configure some things.*

> 5th Step:

Now, you have to add PHP and MySQL to your PATH. [Only for windows] Search for `Edit your system enviroment variables`, now in Advanced, go to Enviroment Variables...
now in your System Variables, edit Path, and then add the following routes:
<ul>
  <li>C:\xampp\php</li>
  <li>C:\xampp\mysql\bin</li>
</ul>
Then press accept to all.

> 6th Step:

The last thing you have to do, is going to `C:\xampp\htdocs\contacts-app\sql\` and run a cmd or a bash and type:
```
mysql --user root -p
```
On `Enter password:` just type Enter.
 Then type:
```
SOURCE setup.sql
```
> 7th You are ready!:
Now that you have all settled down, to use Contacts-App, you have to type this on your browser: `localhost/contacts-app/`. If you did everything correctly, that should work.
