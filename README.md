# Nexus-Cli-Prover

Install Dependecies

<clipboard-copy for="textToCopy">Copy</clipboard-copy>
<pre id="textToCopy">sudo apt update && sudo apt upgrade -y</pre>

<clipboard-copy for="textToCopy">Copy</clipboard-copy>
<pre id="textToCopy"># Install packages
sudo apt install curl iptables build-essential git wget lz4 jq make gcc nano automake autoconf tmux htop nvme-cli pkg-config libssl-dev libleveldb-dev tar clang bsdmainutils ncdu unzip libleveldb-dev  -y

# Install Rust
curl https://sh.rustup.rs -sSf | sh
source $HOME/.cargo/env
export PATH="$HOME/.cargo/bin:$PATH"

rustup update

rustc --version</pre>

Create screen

<clipboard-copy for="textToCopy">Copy</clipboard-copy>
<pre id="textToCopy">screen -S Nexus</pre>

Run:

<clipboard-copy for="textToCopy">Copy</clipboard-copy>
<pre id="textToCopy">curl https://cli.nexus.xyz/install.sh | sh</pre>

You should see like this;![Screenshot (267)](https://github.com/user-attachments/assets/fd8237e1-9607-4ca2-a015-72041555127a)

To minimize screen: CTRL+A+D

To retun screen: screen -r Nexus

If you encounter problems running your node join Nexus discord: https://discord.gg/4fHHEPGK
