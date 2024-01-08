#CERN 

### Python packages
In order to install CERN py libraries one has to configure the pip client first [[Useful python packages#^4b0333]]

### SSHFS
To mount:
sshfs lxplus: lxplus -o follow_symlinks -o ServerAliveInterval=120

To unmount:
sudo diskutil umount force ~/afs
sudo diskutil umount force ~/eos
sudo diskutil umount force ~/lxplus

### Virtual machine for Technical Network
[CERN guide](https://wikis.cern.ch/display/ACCADM/VPC+RHEL9+Virtual+Machine+User+Manual)
Support <a href="mailto:vpc-support@cern.ch" rel="noopener" class="external-link" target="_blank"><u>vpc-support@cern.ch</u></a>

My VPC
- Hostname: cwe-513-vpl810
- IP address: 188.185.67.8

First run:
ssh -4 -J gorna@lxplus7.cern.ch gorna@cwe-513-vpl810
k5reauth -x -i 3600 -f -- vncserver
 Run in the terminal:
ssh -4 -f -L 5901:cwe-513-vpl305.cern.ch:5901 gorna@lxplus.cern.ch -N

Open Microsoft Remote Desktop and connect to your VPC IP.

To reboot:
*sudo reboot*
### LSA
run 
/acc/local/share/abt/bin/ccm
or add 
alias ccm='/acc/local/share/abt/bin/ccm'
to ~/.bashrc
and run
ccm
### Jupyter lab on lxplus
On lxplus:
jupyter notebook --no-browser --port=8080 &

On local machine:
ssh -L 8080:127.0.0.1:8080 [gorna@lxplus717.cern.ch](mailto:gorna@lxplus717.cern.ch)
http://127.0.0.1:8080/tree?token=c57cd288db7d325aed489e652f8626ba80756691e624a6c1

### SWAN
Environment script:
/eos/project/a/abt-group/Software/Swan/startup_PRO

Install packages: https://swan.docs.cern.ch/advanced/install_packages/ 

### LX tunnel

ssh -D 8888 lxtunnel.cern.ch

Some CERN websites are only accessible from the CERN network. Therefore one needs to create and use an ssh tunnel trough LXPLUS in order to access them from outside. Actually since the covid pandemy there's a dedicated server for this, LXTUNNEL. A big advantage is that this server accepts passwordless login with your SSH keypair - see the message upon login.
**The manual method**, and consists of creating a dynamic port forwarding with the command ssh -D 8888 lxtunnel.cern.ch and then tell your system to use the local port **8888** as SOCKS proxy. The detail depends on the system.
**On windows** I recomend using MobaXterm, commercial software available for free with some restrictions. On MobaXterm create a tunnel (Tools -> MobaSSHTunnnel (port forwarding) -> New SSH tunnel) of type **SOCKS proxy** which ssh server is **lxtunnel.cern.ch**, your username and using port **22**. Local port of your choice, **8888** for instance.

