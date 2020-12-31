# problem-ubuntu


# install Ubuntu Kubuntu ... on Asus X541U my problem in Realtek RTL8723BE PCIe Wireless Network Adapter

how to fix it :<br>

go into the BIOS and lock wireless and LAN <br>

install ubuntu kubuntu ....<br>

Edit /etc/default/grub. Change the line starting with GRUB_CMDLINE_LINUX_DEFAULT into <br>

GRUB_CMDLINE_LINUX_DEFAULT="quiet splash pci=noaer"<br>

Run sudo update-grub<br>

Reboot<br>


<h1><b>How to Unlock Huawei E3372h Modem </b><h1>
  
  1) <h3> go to http://huaweicodecalculator.com/algo </h3>
  2) enter your MODEL and IMEI
  3) get this : 
  <pre>
      orange:
        IMEI 	350123009876543
        Model 	E3372
        Unlock Code v1 	33782920
        Unlock Code v2 	45226183
        Unlock Code v3 	35858719
        New Hash 	735c78853eb2561e7cc5ddc7637ec42f
        Old Hash 	e4878f494a67fe69256e210dd06ec82c
        Flash Code 	64073213
  </pre>
  <h3> or you can use program Modem Unlock in this repo</h3>
  
  
  
  
  
  
  
