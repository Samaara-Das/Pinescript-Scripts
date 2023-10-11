## A short description
Credit for the LC (Lorentzian Classification) indicator - jdehorty

Entry conditions - 
1. There has to be a green LC Label
2. Price closes above ema (if no EMA is chosen then this EMA condition will not apply) 
3. Price low is below ema (if EMA condition is checked)
4. There has to be a Regular/Hidden divergence within <x> bars before shift 1 (optional)

Exit conditions - 
1. Stop loss at the latest swing
2. Stop loss below divergence high/low (if chosen)
3. Take profit (it's risk:reward based)
4. When an opposite entry happens
5. When the Kernel line changes its colour

**Note about exits:**
if tp & sl input is true but close condition is false, it will work for single trades (1 trade at a time)
if close condition is true but sl & tp exit is false, it will work for single & multiple trades at a time (if you want multiple trades to be taken, change pyramiding to anything more than 0)
if both are true, it will only work for single trades. the entries will be exited based on if the sl/tp or close condition gets triggered first

## Its settings
![image](https://github.com/araamas/Pinescript-Scripts/assets/104917239/5906605b-3440-449f-9860-227ac460345d)
![image](https://github.com/araamas/Pinescript-Scripts/assets/104917239/194c0994-6261-4b92-8153-d9114259e377)
![image](https://github.com/araamas/Pinescript-Scripts/assets/104917239/5ad2ba3f-767d-42cd-888b-87aa46b5a40b)
![image](https://github.com/araamas/Pinescript-Scripts/assets/104917239/b99488a2-8d56-45ad-a94b-dfcbe085cfc4)
![image](https://github.com/araamas/Pinescript-Scripts/assets/104917239/f8e9298b-1dba-4b3b-9263-5fcb0b079dc3)

