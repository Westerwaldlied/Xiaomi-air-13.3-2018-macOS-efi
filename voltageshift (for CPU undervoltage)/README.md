# Disclaimer!
Messing with the CPU voltage and power settings can be risky! Use these scripts at your own risk. I'm not responsible in any way for lost data, damage to software or hardware or anything else that might go wrong.

# Undervolting CPU
After you have unlocked the CPU core voltage [HOWTO](https://github.com/johnnync13/Xiaomi-Mi-Air/tree/master/BIOS) you can undervolt the CPU using the script `mpcpu.sh`. This results in lower power usage (longer battery life) and cooler CPU temperatures.

1. Run the executable file, put Voltageshift.kext into the Kext folder in the EFI partition
2. Run mpcpu.sh
3. Power setting (4) is recommended. Use the others at your own risk!
4. 0.09V undervolting should work (1)
5. Test using the temporary settings. If it works, you can install the script permanently.

Enjoy your cooler laptop under macOS!