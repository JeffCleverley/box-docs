title: Quick Start
# WPLib Box Quick Start
The following looks a lot more complicated that it is. It is just that we wrote details instructions in hopes to allow you to breeze through. 
<hr>
1. [==Download==](https://github.com/wplib/wplib-box/archive/0.17.1.zip) the latest WPLib Box.
<hr>
2. Download and install ==[**VirtualBox**](https://www.virtualbox.org/wiki/Downloads)== and 
   then ==[**Vagrant**](https://www.vagrantup.com/downloads.html)==  _(in the near future WPLib Box will not require Vagrant.)_
<hr>
3. ==Unzip== WPLib Box into a new project directory; use `~/Sites/example.local` or 
`C:\Sites\example.local` for this quick start.
<hr>
4. ==Open== a [terminal/command prompt](/how-to/tutorials/terminal.md) _(in the near future WPLib Box will have an installer and a GUI to make using the command line optional!)_
<hr>
5. ==Change== to your project directory, i.e. if your sites are in a `Sites` directory off your root:
    
**MacOS or Linux**     
    
    cd ~/Sites/example.local
    
**Windows**     
    
    cd C:\Sites\example.local
<hr>
<hr>
6. ==Open `project.json`== in your text editor and change the line:

    "hostname": "wplib.box",
   
To:

    "hostname": "example.local",
<hr>
7. ==Type== the following command:
    
    vagrant up
        
Normally `vagrant up` takes about five (`5`) minutes to download. Of course duration depends on your download speeds. After that, boot up usually takes less than one (`1`) minute.
<hr>
8. _When prompted_ ==enter your password== for your Mac, Windows or Linux [host computer](/glossary#host-machine).

Or you can ==skip this step== and [manually add entries](/how-to/tutorials/host-entries.md) for `example.local` to `/etc/hosts` or `C:\Windows\System32\drivers\etc\hosts`. You should find the IP address you will need to add to your hosts file in the `IP` file of your project' directory.
<hr>
9. Now ==visit== `http://example.local` in your browser _(The very first page load usually takes about 5-10 seconds, but after that they should be lightning quick.)_  
<hr>
10. And that's it, you are ==now experiencing WPLib Box!== :-)
<hr>
P.S. Don't forget to ==[Join our Slack](https://launchpad.com/wplib)== to ask any questions you may have.


     
