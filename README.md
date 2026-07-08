Raspberry Pi DSI driver for the 1024x600 resolution module

# How to install the driver

1.If there are no parameters, I2C0 bus and 2 lanes DSI1 interface will be used by default
  ### sudo ./DSI-1024x600-show

2. You can choose the number of DSI lanes
1) Use two lanes DSI interface:
### sudo ./DSI-1024x600-show 2

2) Use four lanes DSI interface(This can only be used for Raspberry Pi 5):
### sudo ./DSI-1024x600-show 4


