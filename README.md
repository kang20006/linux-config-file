# linux-config-file
<h1>i3 wm</h1>
<h1>Install</h1>
<ul>
  <li>feh</li>
  <li>rofi</li>
  <li>sudo dpkg -i playerctl-2.3.1_amd64.deb </li>
  <li>thunar</li>
  <li>lxappearance</li>
  <li>i3blocks</li>
  <li>i3 gaps</li>
</ul>
<br/>
<h1>Reload Xresources</h1>
xrdb ~/.Xresources
<h1>Create Xresources file</h1>
touch ~/.Xresources
<h1>Create compton config</h1>
touch ~/.config/compton.conf
<h3> can prevent screen tearing</h3>
<br/>
<h1>Modify VM disk space</h1>
VBoxManage modifymedium"/home/wenkang/VirtualBox VMs/Windows 7/Windows 7.vdi" --resize 60999
<br/>
<h1>Scan Virus</h1>
<ul>
  <li>sudo apt-get install clamav</li>
  <li>freshclam</li>
  <li>clamscan -r -i DIRECTORY</li>
</ul>
<br/>
<h1>onedrive</h1>
<ul>
  <li>touch sync_list(selective sync)</li>
  <li>onedrive --synchronize --resync</li>
  <li>onedrive --monitor</li>
</ul>
