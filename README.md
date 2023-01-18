#  Change nodejs version in ubuntu

### Remove existing version of nodejs

```js
sudo apt remove nodejs
```
OR

```sh
sudo apt remove node
```

---
### Installing Node Using the Node Version Manager

```sh
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
```

This will install the ```nvm``` script to your user account. To use it, you must first source your ```.bashrc``` file:

```sh
source ~/.bashrc
```

Now, you can ask NVM which versions of Node are available:

```sh
nvm list-remote
```

```
Output
. . .
       v16.11.1
       v16.12.0
       v16.13.0   (LTS: Gallium)
       v16.13.1   (LTS: Gallium)
       v16.13.2   (LTS: Gallium)
       v16.19.0   (Latest LTS: Gallium)
        v17.0.0
        v17.0.1
        v17.1.0
        v17.2.0
        v17.3.0
        v17.3.1
        v17.4.0
        v17.5.0
        v17.6.0
```





It’s a very long list! You can install a version of Node by typing any of the release versions you see. For instance, to get version v16.19.0 (Latest LTS: Gallium)
 you can type:
 
 ```sh
 nvm install v16.19.0
```

