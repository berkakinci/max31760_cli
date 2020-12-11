# max31760_cli
Shortcuts to Linux i2c-tools on a MAX31760 Fan Controller

USAGE:
Configure I2C bus and slave address in .config.sh.
Run the scripts in this directory from the command line.

In my implementation, I use the MAX31760 to control a heater.  This is done in init_auto

Dependencies you'll need:
i2c-tools: "heterogeneous set of I2C tools for Linux"
bc:        "GNU bc arbitrary precision calculator language"
bash:      "GNU Bourne Again SHell"
