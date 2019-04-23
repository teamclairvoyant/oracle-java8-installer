# oracle-java8-installer

In order to build the package, run the following commands:

```bash
sudo apt install dpkg-dev dpkg-sig dh-make

git clone https://github.com/teamclairvoyant/oracle-java8-installer oracle-java8-installer/debian
cd oracle-java8-installer/debian
git checkout clairvoyant
cd ..
dpkg-buildpackage --no-sign
```

