# Nexus-labs-testnet

![image](https://github.com/user-attachments/assets/bf2fe42c-d56a-451a-89ba-9b13f56c8157)

Update system directory
-----------------------


```
sudo apt update && sudo apt upgrade
sudo apt install build-essential pkg-config libssl-dev git-all
```


Reply with “Y” & wait for process to complete, reply also with ‘8’ none of the above when asked
-----------------------------------------------------------------------------------------------




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

<img width="421" alt="image" src="https://github.com/user-attachments/assets/5d453990-8368-454c-8e6e-24fe354e1775">




Copy the prover ID from https://beta.nexus.xyz/ and replace
-----------------------------------------------------------

<img width="800" alt="image" src="https://github.com/user-attachments/assets/e7d75be4-b977-4567-866f-c10580d09c7b">




EDIT: To copy prover ID, disconnect the Web Interface first, then use the copy. [copies a 24char string — not the visible one]
--------------------------------------------------------------------------------------------------------------------------------

```
echo "YOUR_PROVER_ID" > ~/.nexus/prover-id
```




Run Command again and DONE!
----------------------------

```
curl https://cli.nexus.xyz/ | sh
```
