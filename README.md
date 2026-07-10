Raspberry Pi DSI driver for the 1024x600 resolution module.
### This driver only supports 2 lanes DSI.
# How to install the driver

1.Execute any of the following commands to obtain help information:
  ### sudo ./DSI-1024x600-show -h
  ### sudo ./DSI-1024x600-show --help
  
2.If there are no parameters, I2C0 bus and 2 lanes DSI1 interface will be used by default.
  ### sudo ./DSI-1024x600-show

3.You can choose I2C bus and use DSI1 interface.\
A.Use two lanes DSI interface and i2c0 bus:
  ### sudo ./DSI-1024x600-show i2c0

B.Use two lanes DSI interface and i2c1 bus:
  ### sudo ./DSI-1024x600-show i2c1

4.You can choose DSI0 interface(This can only be used for Raspberry Pi products that support 2 DSI interfaces).\
A.Use two lanes DSI interface,i2c1 bus and DSI0 interface:
  ### sudo ./DSI-1024x600-show i2c1 dsi0

B.Use two lanes DSI interface,i2c0 bus and DSI0 interface:
  ### sudo ./DSI-1024x600-show i2c0 dsi0
