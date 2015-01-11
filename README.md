# Eclipse project templates for STM32Nucleo-F4
This repository contains basic templates for the STM32Nucleo-F4 developing board from ST. Templates were generated in Eclipse using [GNU ARM Eclipse](http://gnuarmeclipse.livius.net/blog/) by Liviu Ionescu. If you need to setup the whole Eclipse/GCC ARM tool-chain, you can follow [this series](http://www.carminenoviello.com/en/2014/12/28/setting-gcceclipse-toolchain-stm32nucleo-part-1/) made of three parts on my blog.
These templates are preconfigured to work with Nucleo-F401RE and Nucleo-F411RE boards. To select the proper board, you have to add `NUCLEO_F401` or `NUCLEO_F411` macro defines to the project settings, as shown in the following picture. 
![setting macro variable ad project level](http://www.carminenoviello.com/wp-content/uploads/2015/01/Schermata-2015-01-11-alle-12.18.55.png)