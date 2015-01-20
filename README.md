<h1>Packer-Ansible DigitalOcean Build 0.1.0</h1>

<h3>Requirements</h3>
<ul>
<li>Packer</li>
<li>Ansible</li>
<li>A DigitalOcean account</li>
</ul>

<h3>Description</h3>
<p>Packer build for Ansible-provisioned DigitalOcean droplets.</p>

<p>In order to build your droplet with the Ansible provisioner simply copy and paste the code from "provisioners/ansible.json" into the packer.json template.</p>

<p>Your droplet will be created with the following:
<ul>
<li>New non-root user with password, group, home folder, SSH keys</li>
<li>Changed default SSH port</li>
<li>Disabled root login</li>
<li>Firewall configured to allow your new SSH port and web services</li>
<li>A swapfile</li>
<li>NTP service</li>
<li>The EPEL repository enabled</li>
<li>fail2ban installed</li>
</ul></p>

<p>The hashed password for this build is 'vagrant'.</p>