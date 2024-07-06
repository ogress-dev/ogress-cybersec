 <a href="https://www.linkedin.com/in/francis-ogres-746a062b1/" target="_blank" rel="noopener noreferrer">
        <img src="https://upload.wikimedia.org/wikipedia/commons/c/c9/Linkedin.svg" alt="LinkedIn" width="30" height="30">
        


# NMAP

Nmap (Network Mapper) is a powerful open-source tool used for network exploration and security auditing. It allows users to discover hosts, services, and vulnerabilities on computer networks. Nmap operates by sending packets to target hosts and analyzing the responses. It supports a wide range of scanning techniques and is highly customizable, making it an essential tool for network administrators, security professionals, and enthusiasts alike.


Full documentation is also available on the [Nmap.org](https://nmap.org/) website.

# INSTALLING
Debian/Ubuntu
<div>
    <pre>
    sudo apt-get update
    sudo apt-get install nmap
    </pre>
</div>

fedora
<div>
  <pre>
    sudo dnf install nmap
</pre>
</div>



for more detailled installation visit https://nmap.org/book/install.html

# USING NMAP

To scan a single host and discover open ports:
<div>
  <pre>
    nmap target_ip_or_hostname
  </pre>
</div>

to scan muliple hosts use and discover open ports:
<div>
  <pre>
    nmap target1 target2 target3
  </pre>
</div>



Nmap has a lot of features, but getting started is as easy as running nmap [scanme.nmap.org](http://scanme.nmap.org/)
. Running nmap without any parameters will give a helpful list of the most common options, which are discussed in depth in the man page. Users who prefer a graphical interface can use the included[Zenmap front-end](https://nmap.org/zenmap/)
.

