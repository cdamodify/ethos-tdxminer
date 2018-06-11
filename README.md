### ethos-tdxminer
Addon for ethOS Mining OS (ethosdistro.com)

Works with ethos 1.3.1, other versions are not tested.


### tdxminer info:
algorithm: lyra2z

GPUs Supported:

RX 580/570/480/470 with amdgpu-pro or ROCm 1.7.1 drivers

RX Vega 64/56, Vega FE with ROCm 1.7.1 driver


### How to install:
```
git clone https://github.com/unrealjke/ethos-tdxminer.git
cd ./ethos-tdxminer
sudo chown -R root:root ./opt/ethos/
sudo cp -rp ./opt/* /opt/
sudo reboot
```

### Config sample:
```
tdxminer=proxypool1 xzc.f2pool.com:5740
tdxminer=poolpass1 x
tdxminer=proxywallet a5AjfoYDdjeXpQxn7z5ijfNJ1WMBtQMQJi
miner d3031e tdxminer
```
