# prepare
git clone https://github.com/uZer/yaml-ls-check-debug
git clone https://github.com/InoUno/yaml-ls-check.git
cd yaml-ls-check

# install pnpm if needed
sudo npm install -g pnpm

pnpm install

# run
pnpm run start ../yaml-ls-check-debug/manifests
