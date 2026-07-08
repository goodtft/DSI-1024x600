Raspberry Pi DSI driver for the 1024x600 resolution module.

# How to install the driver

1.If there are no parameters, I2C0 bus and 2 lanes DSI1 interface will be used by default.
  ### sudo ./DSI-1024x600-show

2.You can choose the number of DSI lanes,use I2C0 bus and DSI1 interface.\
A.Use two lanes DSI interface:
  ### sudo ./DSI-1024x600-show 2

B.Use four lanes DSI interface(This can only be used for Raspberry Pi 5):
  ### sudo ./DSI-1024x600-show 4

3.You can choose I2C bus and use DSI1 interface.\
A.Use two lanes DSI interface and i2c0 bus:
  ### sudo ./DSI-1024x600-show 2 i2c0

B.Use two lanes DSI interface and i2c1 bus:
  ### sudo ./DSI-1024x600-show 2 i2c1

C.Use four lanes DSI interface and i2c0 bus(This can only be used for Raspberry Pi 5):
  ### sudo ./DSI-1024x600-show 4 i2c0

D.Use four lanes DSI interface and i2c1 bus(This can only be used for Raspberry Pi 5):
  ### sudo ./DSI-1024x600-show 4 i2c1

4.You can choose DSI0 interface(This can only be used for Raspberry Pi 5).\
A.Use two lanes DSI interface,i2c1 bus and DSI0 interface:
  ### sudo ./DSI-1024x600-show 2 i2c1 dsi0

B.Use two lanes DSI interface,i2c0 bus and DSI0 interface:
  ### sudo ./DSI-1024x600-show 2 i2c0 dsi0

C.Use four lanes DSI interface,i2c1 bus and DSI0 interface:
 ### sudo ./DSI-1024x600-show 4 i2c1 dsi0

D.Use four lanes DSI interface,i2c0 bus and DSI0 interface: 
 ### sudo ./DSI-1024x600-show 4 i2c0 dsi0
