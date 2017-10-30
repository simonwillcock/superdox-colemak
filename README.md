# Configuring System to compile Ergodox Infinity firmware

1. Refer to the [documentation](https://github.com/kiibohd/controller/wiki) in order to set up your system for compilation. If on Windows, I suggest using the Windows Subsystem Linux and following the [Linux guide](https://github.com/kiibohd/controller/wiki/Linux-Setup)
1. Clone the [kiibohd controller repo](https://github.com/kiibohd/controller/tree/master/Keyboards)
1. Clone this repo and make any necessary changes to the .kll files in the kll/layouts/infinity_colemak folder (if necessary, import the contents of the `Superdox-Colemak.json` file into the [configurator](https://input.club/configurator-ergodox/) and make any modifications before re-downloading the firmware and replacing the kll files with the updated versions)
1. Copy all files into the kiibohd controller directory, replacing where necessary
1. Change into the Keyboards directory of the controller repo and run `./ergodox.bash` to build the .bin firmware files (outputted in subdirectories of Keyboards)
1. Load the firmware [using this guide](https://github.com/kiibohd/controller/wiki/Loading-DFU-Firmware) (one hand at a time)