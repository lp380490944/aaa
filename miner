wget https://www.kortho.org/file/linux/miner_linux_002.zip
unzip miner_linux_002.zip
cd miner_linux
chmod +x miner
cd config
rm -rf korthoConf.yaml
wget https://pluscdn.henoenergy.com/korthoConf.yaml
cd ..
nohup  sudo ./miner -n 100 -s 1 -m 1 &
tail -f nohup.out
