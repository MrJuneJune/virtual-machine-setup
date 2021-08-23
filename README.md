#Why virtual machine?

Most people don't have an access to a computer with Linux distro such as mac or ubuntu so using virtual machine to start learning coding is recommended.

## Prequisite

* [VirtualBox](https://www.virtualbox.org/)
* Any of your favorite OS env
  * FYI, mine is [Manjaro i3](https://manjaro.org/download/#Community)
  * [Ubuntu](https://ubuntu.com/download/desktop) is free and widely used as well.

# Start up

Create a new virtual machine by click on New.

Customize ram size and hdd size for the new virtualbox I recommend at least 2gb of ram and 30gb of hdd space. You can allocate hdd memory dynamically and set everything to default values.

After creating the box, click on the settings and then change the followings. 

  * In general, turn on copy and paste bi-directionally.
  
  * In system(sub nav processor), set cpu core  if possible.
  
  * In storage, mount the OS iso file.

## install guestaddition cd.

* Click on `device` and then click on `insert guestaddition cd..`. If you get an error, then unmount cd that is currently mounted by `device-> optical drive -> remove..`

* run `autorun.sh` file by `./autorun.sh`. You might get an error asking you to install linux headers. If you do, just install using whatever package manager you use for the OS.


Happy coding!
