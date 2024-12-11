# Nexus-labs-testnet

Update system directory
-----------------------


```
sudo apt update && sudo apt upgrade
sudo apt install build-essential pkg-config libssl-dev git-all
```


Reply with “Y” & wait for process to complete, reply also with ‘8’ none of the above when asked
----------------------------------------------------------------------------------------------------




Install RUST
-------------------------------------------------------------------------------

curl --proto '=https' --tlsv1.3 https://sh.rustup.rs -sSf | sh


. "$HOME/.cargo/env"

------------------------------------------------------------------------------





Reboot System
--------------

Wait for 30 seconds, connect terminal again

reboot





Install Compiler
-------------------------------

sudo apt install -y protobuf-compiler





RUN
----------

curl https://cli.nexus.xyz/ | sh





CTRL + Z to stop
---------------------





Copy the prover ID from https://beta.nexus.xyz/ and replace
-----------------------------------------------------------





EDIT: To copy prover ID, disconnect the Web Interface first, then use the copy. [copies a 24char string — not the visible one]
--------------------------------------------------------------------------------------------------------------------------------

echo "YOUR_PROVER_ID" > ~/.nexus/prover-id





Run Command again and DONE!
----------------------------

curl https://cli.nexus.xyz/ | sh
