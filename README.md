# Nexus-labs-testnet

![image](https://github.com/user-attachments/assets/bf2fe42c-d56a-451a-89ba-9b13f56c8157)

Update system directory
-----------------------


```
sudo apt update && sudo apt upgrade
sudo apt install build-essential pkg-config libssl-dev git-all
```


Proceed with “Y” & wait for the process to complete, Type ‘8’ none of the above if asked





Install RUST
------------

```
curl --proto '=https' --tlsv1.3 https://sh.rustup.rs -sSf | sh
```
```
. "$HOME/.cargo/env"
```

Reboot System
-------------

Wait for 30 seconds, connect terminal again

```
reboot
```

Install Screen
---------------
```
screen -S nexus
```

Install Compiler
---------------
```
sudo apt install -y protobuf-compiler
```


RUN
---

```
curl https://cli.nexus.xyz/ | sh
```


CTRL + Z to stop
----------------

It will show as stopped then proceed with next steps




Copy the prover ID from https://beta.nexus.xyz/ and replace
-----------------------------------------------------------

<img width="800" alt="image" src="https://github.com/user-attachments/assets/e7d75be4-b977-4567-866f-c10580d09c7b">




EDIT: To copy prover ID, disconnect the Web Interface first, then use the copy. [28 Char]
--------------------------------------------------------------------------------------------------------------------------------

```
echo "YOUR_PROVER_ID" > ~/.nexus/prover-id
```




Run Command again and DONE!
----------------------------

```
curl https://cli.nexus.xyz/ | sh
```
![photo_2024-12-11_10-27-18](https://github.com/user-attachments/assets/d67f39fa-c7da-45ed-bad7-22ded04a067b)


Extit from Screen 
------------------

```
Ctrl+A+D

```

To check Status or renter screen
-----------

```
screen -r nexus

```
To Check all visible screens
-------------
```
screen -ls

```
