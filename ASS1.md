### Roll number 220198
**Indicators Used:**
1. Momentum Indicator : Ichimoku cloud lines  
2. Volume Indicator : Ease of movement indicator
3. Volatility Indicator : Keltner Channels
## Ease Of Movement Indicator
Utility : To discern whether prices are able to rise, or fall, with little resistance in the directional movement.
          It calculates how easily a price can move up or down, based on momentum.<br>
          Code Implementation along with Calculation details : https://colab.research.google.com/drive/1KtssBTm0Pc_tFZNqhwaKxwjT8Qg5t45y?usp=sharing <br>
 I tried varying the period (standard 14) for Tesla
 Period 18 showed a lot of sharp distinct peaks and troughs so I find it best matches with my data
 ## Ichimoku Cloud Lines
 Utility :  It shows support and resistance levels, as well as momentum and trend direction by taking multiple averages
 The overall trend is up when the price is above the cloud, down when the price is below the cloud(formed by Leading Span A and Leading Span B), and trendless or transitioning when the price is in the cloud.<br>
 Code Implementation along with Calculation details : https://colab.research.google.com/drive/1fZ-ShdIAINFkhh8TCgEiaxoLVRzHGyAg?usp=sharing<br>
 I tried to see variations in the graph(plotted using matplotlib) on changing the periods. Some observations from that :<br>
          1. The cloud width decreases as we increase the base period<br>
          2. Not much effect could be seen on changing the conversion period till it was kept less than the base period. Considerable effect could be seen on                      increasing it furthur <br>
 I find Conversion period = 7 , Baseline period =30 , Lagging Span = 44 to be  best for my data because the cloud thus formed best fits my data as could be seen in the plot
   
## Keltner Channels
Utility : Help in determining direction of a trend <br>
Code Implementation : https://colab.research.google.com/drive/1m4S8O1wr3HlFjkFS6TlN16QLVv6ND4XC?usp=sharing <br>
I tried to change the multiplier and the period as those were the variables that could be altered
From general oberseravation I saw that increasing the length from 20 to 40-44 make the bands move down.
I found the period 40 and multiplier 2 to be best fit for my data of Apple as it would best encompass my data as shown in the code by Matplotlib plotting.
I think it shows best tend change and acceleration and the bands sufficiently encompass.



