# Blacktip

Blacktip is a project to build a robust blockchain tool to enable the technology for a broad spectrum of usage.

It will be used to provide non repudiation capabilities to the Shark Algorithmic Trading Platform. 


# Setup

1. Prepare a vanilla Debian Server with VirtualBox ([help](https://linuxhint.com/install_debian10_virtualbox/)).

2. Install ansible ([help](https://linuxhint.com/install_ansible_debian10/)).

3. Install Git ([help](https://linuxhint.com/install_git_debian_10/)).

4. Open a terminal, and run:
```
git clone https://github.com/danielneil/Blacktip.git && cd Blacktip && ./build.sh
```

5. Navigate to http://debian-server-ip/blacktip (web credentials are blacktip/blacktip).

# Usage (blacktip-cli) e.g.

```
# Create a blockchain
./blacktip-cli --createBlockChain MyBlockChain 

# Create a block
./blacktip-cli --createBlock MyBlock --blockChain MyBlockChain

# Add data inside block 
./blacktip-cli --addData "someDataFile.txt" --block MyBlock 

# Create a block

# Just making up words.........
```
