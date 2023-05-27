### Roll number 220198
**Indicators Used:**
1. Momentum Indicator : Ichimoku cloud lines  
2. Volume Indicator : Ease of movement indicator
3. Volatility Indicator : Keltner Channels
## Ease Of Movement Indicator
Utility : To discern whether prices are able to rise, or fall, with little resistance in the directional movement.
          It calculates how easily a price can move up or down, based on momentum.<br>
          Code Implementation along with Calculation details : https://colab.research.google.com/drive/1KtssBTm0Pc_tFZNqhwaKxwjT8Qg5t45y?usp=sharing
 ## Ichimoku Cloud Lines
 Utility :  It shows support and resistance levels, as well as momentum and trend direction by taking multiple averages
 The overall trend is up when the price is above the cloud, down when the price is below the cloud(formed by Leading Span A and Leading Span B), and trendless or transitioning when the price is in the cloud.<br>
 Code Implementation along with Calculation details : https://colab.research.google.com/drive/1fZ-ShdIAINFkhh8TCgEiaxoLVRzHGyAg?usp=sharing<br>
 I tried to see variations in the graph(plotted using matplotlib) on changing the periods. Some observations from that :<br>
          1. The cloud width decreases as we increase the base period<br>
          2. Not much effect could be seen on changing the conversion period till it was kept less than the base period. Considerable effect could be seen on                      increasing it furthur
## Keltner Channels
Utility : 
