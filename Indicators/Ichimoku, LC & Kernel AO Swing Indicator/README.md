This indicator draws trades and their exit levels.
The strategy behind this is for trading the 2nd impulse in an Impulse-Correction-Impulse pattern.

## These are the entry criterias of the trades:
### 🟢 For a buy
- There has to be a higher low in Kernel AO Swing
  - The sign of the higher low resembles the 1st upward impulse and the downward correction. The lower low is the start of the 1st upward impulse. The higher low is the end of the correction and possibly the start of the 2nd impulse. We wait for a higher low to happen to trade the 2nd impulse.
- Lagging line on shift 1 above Span B on shift 26
  - Confirms the uptrend
- Green LC label on shift 1
  - Confirms resumption of trend and start of 2nd impulse
- Green Kernel Estimate line on shift 1
  - Confirms resumption of trend and start of 2nd impulse (aggressive option)

### 🔴 For a sell
- There has to be a lower high in Kernel AO Swing
  - The sign of the lower high resembles the 1st downward impulse and the upward correction. The higher high is the start of the 1st downward impulse. The lower high is the end of the correction and possibly the start of the 2nd impulse. We wait for a lower high to happen to trade the 2nd impulse.
- Lagging line on shift 1 below Span B on shift 26
  - This confirms the uptrend
- Red LC label on shift 1
  - Confirms resumption of trend and start of 2nd impulse
- Red Kernel Estimate line on shift 1
  - Confirms resumption of trend and start of 2nd impulse (aggressive option)

All the entry criterias above are optional except the Kernel AO Swing entry criteria. That will apply along with all the entry criterias you choose. You can combine any of the above entry criterias to form an entry condition. 
Examples: If the Ichimoku criteria and LC criteria are selected, an entry will be taken if both the criterias (and also the Kernel AO Swing entry criteria) have been met. 
If all 3 criterias are selected, an entry will be taken if they (and also the Kernel AO Swing entry criteria) have been met.
If just 1 of those criterias is selected then an entry will be taken if that and the Kernel AO Swing entry criteria have been met.

## HTF Filter:
Along with these criterias, you have 1 other condition which is a higher timeframe filter (HTF). This will take only buy trades if the latest trade on a higher timeframe is a buy and 
take only sell trades if the latest trade on a higher timeframe is a sell. If you select this, choose the higher timeframe that you want (it must be higher than the chart's current timeframe).

The entry criterias for the higher timeframe entry condition are the same as the entry criterias written above except that the Kernel AO Swing won't be part of them. You can combine any entry criteria to form an entry condition for higher timeframe entries. So, if you have selected Ichimoku and Kernel conditions, a higher timeframe entry will be based on those.

The entry criterias for the higher timeframe are completely seperate from the lower timeframe entry criterias. You don't have to have the same entry criterias for the higher timeframe and the lower timeframe if you want to have different entry criterias for them.

## Here are the exit conditions:
- 1:1 RR based TP
- 1:2 RR based TP
- 1:3 RR based TP
- SL is based on the previous Kernel AO swing and not the latest
