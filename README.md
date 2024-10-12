# macOS Ventura on Lenovo Thinkpad L540 



<summary><strong>My Hardware</strong></summary>
<br>

| Category  | Component                            |
| --------- | ------------------------------------ |
| CPU       | Intel Core i5-4210M                 |
| GPU       | Intel HD Graphics 4600               |
| SSD       | Goodram SSD 120GB               |
| Memory    | 16GB DDR3 1600Mhz                     |
| WiFi & BT | Intel Wireless-N 7260                |

# Screenshots

# Status
  
<summary><strong>What's not working</strong></summary>
</br>

- Audio Jack
- VGA
- Sleep
- Realtek Card Reader


# How to fix Intel HD Graphics 4600

- "amfi_get_out_of_my_way=1" - Add in config.plist boot-args
- Open terminal
- sudo spctl --master-disable
- Restart, go to recovery (press space in boot menu), choose utility, open terminal
- csrutil disable
- csrutil authenticated-root disable
- Restart
- Run OCLP (OpenCore Legacy Patcher)
- Press Post-install Root Patch
- Done



```Copyright (c) kitxchi 2024```
