# My Pop!_OS Configuration

Pop!_OS: https://pop.system76.com/

## [Vscode](https://code.visualstudio.com/)

### Plugins
- Better TOML
- Git History
- Gitlens
- Jupyter
- Live Share
- Remote-Containers
- Remote-SSH
- rust-analyzer
- Remote Development

## [Vim](https://www.vim.org/)

- vim-plug
- fzf
- ag

## [Helix](https://github.com/helix-editor/helix)
```
git clone https://github.com/helix-editor/helix
cd helix
cargo install --path helix-term
hx --grammar fetch
hx --grammar build
```

## Chrome/Firefox

- uBlock Origin
- Sourcegraph
- ExpressVPN

## [Zoom](https://zoom.us/)

## [Discord](https://discord.com/)

## [Telegram](https://telegram.org/)

## [Typora](https://typora.io/)

## [Postman](https://www.postman.com/)

## Command Line Tools

- [Starship](https://github.com/starship/starship)
```
cargo install starship --locked

# Add the following to the end of ~/.bashrc
eval "$(starship init bash)"
```
- [Htop](https://htop.dev/)
```
sudo apt install htop
```

## [Rust](https://www.rust-lang.org/)

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
source ~/.cargo/env
rustup default stable
rustup update
rustup update nightly
rustup target add wasm32-unknown-unknown --toolchain nightly
```

## [Jupyterlab](https://jupyter.org/)
```
pip3 install jupyterlab
# Rust kernel
cargo install evcxr_jupyter
evcxr_jupyter --install
```

## [Wireshark](https://www.wireshark.org/)

## [Filezilla](https://filezilla-project.org/)

## [Docker](https://docs.docker.com/engine/install/ubuntu/)
```
sudo apt install ca-certificates curl gnupg lsb-release
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg
echo \
  "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu \
  $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
sudo apt update
sudo apt install docker-ce docker-ce-cli containerd.io docker-compose-plugin
```

## [Node-JS](https://nodejs.org/en/)

## [yarn](https://yarnpkg.com/)

## [Deno](https://deno.land/)
```
curl -fsSL https://deno.land/install.sh | sh
```
