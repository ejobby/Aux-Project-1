# Aux-Project-1

For Shell Scriptng of Creating Users, create home directories, a .ssh directory for authorization

## Create the CSV File

`mkdir Shell`

`cd Shell`

`touch names.csv`

`vim names.csv`

Insert 20 names into the names.csv and save it

```
niyi
deji
ayo asher
ejobby
pelumi
funmibi
iseoluwa
asher
cynthia
ayomi
ifemi
ebube
dennis
peace
ibe
joy
funmi
dele
akinayo
orims
```

Change the directory to .ssh inorder to create the public and private key

`cd ..`

`cd .ssh`

`touch id_rsa.pub`

`vi id_rsa.pub`

Insert the follwing inside and save it

```
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQCzKZyicHxIkklSrNlxsJyyTrcIdBIt84Z0cQb3R4k0jH53kxkaT5hP8tfWTe62LXi7vV86fY+SX7TBNM76XGCbw/6vrMGegm6J1x2i1AiLNwq5nqTjOGn0AIwku4IlCCLAB7tdfRyVuCarmBlwny3lzRyybIUAWXR/D6vpN09MsDILbKdhay+Q/p9OUBMSLPqXdY/QIh/Oe3rVv1lwY3AohNfq7V3tO88zKswfA5iiexNiSYX1myT0OrX8cBE771j9quoNZhQgaLI1mIMtAvnHQChrn9k2nUaO/BMBCQGol5XzGv1ado7hgoVPoluIUD+FGNo/pH4zcmDLICH6drXY/C9MESnkMUPLFxBXKO/OitApY71vRao9nAhAwpVMsy6FqiOb5uawhvhoHYIHTV/f4EtagVagRMP2PxYMYR6jykIV4MPJTkCm+lGhTyMlRu+qRQjdLn8AAtHf4aEV8dIkoGh088DI7eA/4o0wz4OV4upH5ewSFS+5IHmRECEW5Nc=
```

`touch id_rsa`

`vi id_rsa`

Insert the following inside and save it

```
-----BEGIN OPENSSH PRIVATE KEY-----
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
kmaSGj362OnCCNAAAACWRhcmVARGFyZQE=
-----END OPENSSH PRIVATE KEY-----
```

## Create the Shell to do the Task

Change the directory to the Shell Directory

`cd Shell`

`touch onboard.sh`

`vi onboard.sh`

Insert the shell written into the onboard.sh to do the task

```

#! /bin/bash


userfile=$(cat names.csv)
PASSWORD=password

    if [ $(id -u) -eq 0 ]; then
#Reading the csv file
        for user in $userfile
            do
            echo $user

            if id "$user" &>/dev/null
            then
                echo "User Exist"
            else

#This will create a New User

            useradd -m -d /home/$user -s /bin/bash -g developers $user
            echo "New User Created"
            echo

#This will create a ssh folder in the user home folder

            su - -c "mkdir ~/.ssh" $user
            echo ".ssh directory created for new user"
            echo

#Setting User Permission for the ssh directory

            su - -c "chmod 700 ~/.ssh" $user
            echo "User permission for .ssh directory set"
            echo

#This will create an authorised key file

            su - -c "touch ~/.ssh/authorised_keys" $user
            echo "Authorised key file created"
            echo

#Setting Permission for the authoried key

            su - -c "chmod 600 ~/.ssh/authorised_keys" $user
            echo "User permission for the Authorised Key File"
            echo

# Creating and Setting Public Key for Users in the Server.

            cp -R "/home/ubuntu/.ssh/id_rsa.pub" "/home/$user/.ssh/authorised_keys"
            echo "Copied the Public Key to New User Account in the Server"
            echo

            echo
            echo "USER CREATED"

#Generate a Password

            sudo echo -e "$PASSWORD\n$PASSWORD" | sudo passwd "$user"
            sudo passwd -x 5 $user

           fi
        done

    else
    echo "Only Admin can Onboard A User" 
    fi
```

Make the onboard.sh script executable

`sudo chmod +x onboard.sh`

Before running the script, create the group for the users

`cd ..`

`sudo groupadd developers`

### Running the Script

`cd Shell`

switch to Administator

`sudo su`

![Administrator](./Images/switch.png)

`./onboard.sh`

This will do the task it intended for

![Onboarding Script](./Images/onboarding.png)

Confirm to know whether Script really worked

`exit`

`cd ..`

`cd /home`

`ls `

![Evidence of Users Created](./Images/execution-evidence.png)

Test whether you can log in with any of the users

`sudo su asher`

![Users Switching](./Images/switching.png)