nrf51_flashtool
===============

Sometimes, nRF51822 can't be erased by pyocd_flashtool, then we can use this script

## Requirements
+ pyocd - `pip install pyocd`


## Usage
+ download hex file

  `python nrf51_flashtool.py -i app.hex`

+ erase flash

  `python nrf51_flashtool.py -e`
  