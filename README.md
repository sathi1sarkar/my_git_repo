# Downlode git windows software
https://gitforwindows.org/

# creat ssh key in windows
open powersel in adminstator mode than click a run as adminstatore




# go to the file where ssh key is store 
>> ls ~/.ssh 

`if there is no id_rsa.pub file then creat e new ssh key`
>> ssh-keygen -t rsa -b 4096 -C "sathisarkar583@gmail.com"
>> enter 
>> enter
>> enter
>> enter
>> enter

now we have to work with only id_rsa.pub
 
`inside id_rsa.pub contain public key`
now we have to store the genarated public key to note pad

>> cat ~/.ssh/id_rsa.pub

# public key will be look like this below --

 ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAACAQC5DDdEsqzk/IiqA9ifC3y5F+Wdg2yknv5zzoVP6dOLr4GNusiI602Ms3SX7+HBrxPcHuIShf4FY8nxQg2/dUrA8fgCpey9fV8uzoseVwSkXUN0p6QLVbBQzs+2muVEm1bf0rZgiTfIpDM5769w87V/3V6X00FLafqM2tezQViTQFaNU3u//e16EJqWMIZBZ7PPy0W1Ko/Tp7SjtIuwghgu2fkOJl9RB9/9hL0gTlYNFWNGgjEEOdS7ZdyZQcfn8cW4JCYggPSNwEqrq3nuChTgheQB5jVpx82YIWj/LYz4gMTyiNXaDyAwhzsCok+zERZcLKAq+Mn2jms6XqTAZDskHtVEdWaq4zsaLyIe+3H2nru2uVtXtEqrU9PeE3u1NJg0HiK6vfRqZlG6nXcTKXOV+t6p2F0NOkEPyL0zHSQ0ZpxlzlCZUazgLT9Jop2TS2jwbV8mbDNCnZnytQ7OrG8ZASnXl5X5vMUm2A1x7O7rZRt9HpiA6mTw1KiAS6Hpt1OfsLaj9SX8Bav53a1NIgaKkeAiz+SVPkFNW1voVgqqkb9ScZpKAmNk5CyOxYn/MRgO6HZBC4Tvkual/1uVz6oXc2/tWRyzDPo+ee9aLWOmeCgofgR2qHAqDCGGvlSXkzY0WMxBstf+rUxXz3yQJA4N5b1+VTcDGWHsvdLJa1AEaw== sathisarkar583@gmail.com


`open our git account browser  >  click on profile picture top right  > click on settings > click on ssh ang gpg key`

`then click on add ssh key > paste your ssh key`

then wo go to main page in git

then create a new repo

now we have to put this public key to git





# --------------git commands---------------

`Create folder > go inside the folder > right click and open terminal`


>> cdm : git init

it will initialize a empty git repo. it will create a .git hidden folder

now we have to connect our local folder to our github repo

first we have to go git create repo and select ssh then copy ssh link

then in cdm promt we have to paste that link

>> cdm : git remote add origin git@github.com:sathi1sarkar/javascript.git

>> git add

>> git status

>> git commit -m "short description"

` create new branch and push the code`

>> git checkout -b "new branch name"

`to a  existing branch  prasent in local `

>> git checkout  "new branch name"

>> git push origin branch name
