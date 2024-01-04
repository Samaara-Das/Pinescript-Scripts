## A description
This indicator draws trades and their TP & SL levels.

**These are the entry conditions of those trades:**

🟢 For a buy
- Lagging line on shift 1 above Span B on shift 26 
- Green LC label on shift 1 
- Green Kernel Estimate line on shift 1

🔴 For a sell
- Lagging line on shift 1 below Span B on shift 26 
- Red LC label on shift 1 
- Red Kernel Estimate line on shift 1

All the entry conditions above are optional. You can combine any of the above entry criterias to form an entry condition. 
Examples: If the Ichimoku condition and LC criteria are selected, an entry will be taken if both the criterias have been met. 
If all 3 criterias are selected, an entry will be taken if all the criterias have been met.
If just 1 of those criterias is selected then an entry will be taken if that has been met.

Along with these conditions, you have 1 other condition which is a higher timeframe filter (HTF). This will look for an entry on the higher timeframe before looking for an entry on the lower timeframe. 
The lower timeframe is the chart's current timeframe. 
If you select this, choose the higher timeframe that you want (it must be higher than the chart's current timeframe).
Then, the strategy will look for an entry on that higher timeframe. If the latest entry on the higher timeframe is a buy, only buy trades will get taken on the lower timeframe.
If the latest entry on the higher timeframe is a sell, only sell trades will get taken on the lower timeframe.

The entry condition for the higher timeframe entry is the same as the entry conditions above. You can combine any entry criteria to form an entry condition for higher timeframe entries.
So, if you have selected Ichimoku and Kernel conditions, a higher timeframe entry will be based on those.

The entry conditions for the higher timeframe are completely seperate from the lower timeframe entries. 
You don't have to have the same entry conditions for the higher timeframe and the lower timeframe if you want to have different entry conditions for them.

Here are the exit conditions:
TP1 is based on a 1:1 ratio
TP2 is based on a 1:2 ratio
TP3 is based on a 1:3 ratio
SL is based on Kernel AO Swing 

## How it looks
![image](https://github.com/araamas/Pinescript-Scripts/assets/104917239/9c781279-1f75-4893-951c-95bc3328ebf7)

## Its settings
![image](https://github.com/araamas/Pinescript-Scripts/assets/104917239/efb740fb-d9e0-409b-865f-999ebf277611)
![image](https://github.com/araamas/Pinescript-Scripts/assets/104917239/3f5ab8a0-d00e-4978-ac03-de8c24d207ae)
![image](https://github.com/araamas/Pinescript-Scripts/assets/104917239/cef9f45b-20b2-4bdf-ba25-3201eec815c9)


