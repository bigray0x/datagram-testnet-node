# datagram-testnet-node

![IMG_3435](https://github.com/user-attachments/assets/113ace00-b6e3-4021-8e7a-bf5a761e7641)

Datagram is a real-time Hyperfabric DePIN powering the future of connected intelligence.

### Why run on VPS?

- Helps preserve battery life.
- VPS will give much reliable uptime.

### sign up for the Testnet [Here](https://dashboard.datagram.network?ref=119308891)
- copy your ```API key``` and save it.
- key is in ```Wallet > Licenses > Key```

![photo-output](https://github.com/user-attachments/assets/8ff22e62-91ed-4288-810b-cedb9961efbc)


# Setup Guide

### Step 1: Update system and install dependencies :

```
sudo apt update && sudo apt upgrade -y
sudo apt install -y wget screen
```
### Step 2: Install Datagram cli node :

```
wget https://github.com/Datagram-Group/datagram-cli-release/releases/latest/download/datagram-cli-x86_64-linux
```

### Step 3: Move it to central path and make it executable :

```
sudo mv datagram-cli-x86_64-linux /usr/local/bin/datagram-cli && sudo chmod +x /usr/local/bin/datagram-cli
```

### Step 4: Create a screen and run the node :

- Create a screen session for the node :

```
screen -S datagram
```

- Run the node :

```
datagram-cli run -- -key YOUR_API_KEY
```

if it looks like this then it's working fine

![Image 6-14-25 at 7 45 AM](https://github.com/user-attachments/assets/260eaa41-1504-4c4a-8a20-8218031dc00a)
