## A short description

Entry conditions - 
1. Price has to close above the slow ema and fast ema (if both EMAs are chosen in the option, else it is the one chosen) 
2. Price low has to be below the slow ema or the fast ema (if 1 ema is chosen then ‘or’ will not apply) 
3. Regular/Hidden divergence should appear at shift 2 (optional)
4. RSI is in a bullish zone at shift 1 (optional)

Exit conditions - 
1. Stop loss at the latest swing
2. Stop loss below divergence high/low (if chosen)
3. Take profit (it's risk:reward based)
4. When opposite entry gets opened

**Note about exits:**
1. If the TP & SL exit is checked but the close condition is unchecked, it will work for single trades (1 trade at a time).
2. If the close condition is checked but the TP & SL exit is unchecked, it will work for single & multiple trades at a time (if you want multiple trades to be taken, change pyramiding to anything above 0)
3. If both (TP & SL exit and the close condition) are checked, it will only work for single trades. The entries will be exited based on which exit gets triggered first.

## Its settings
![image](https://github.com/araamas/Pinescript-Scripts/assets/104917239/69dbec4c-4d95-454d-9855-0e455e96a845)
![image](https://github.com/araamas/Pinescript-Scripts/assets/104917239/3229a3c1-48fd-48d4-b95a-a3f0ac772901)
![image](https://github.com/araamas/Pinescript-Scripts/assets/104917239/13de57cb-273a-4342-9372-caea122719f3)
![image](https://github.com/araamas/Pinescript-Scripts/assets/104917239/5e3f3030-6f18-4847-9eaa-062e1280ac09)
![image](https://github.com/araamas/Pinescript-Scripts/assets/104917239/79e46aa7-b8b4-4970-a6f3-d50d38e21587)
![image](https://github.com/araamas/Pinescript-Scripts/assets/104917239/f8a8a9f0-c716-4b07-aa01-1c23e2632be5)

