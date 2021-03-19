# RS Screener by @iArpanK
Screens for stocks that made new highs in **Relative Strength (RS)** and sorts the results according to their **RS Score**.
>RS is an indicator popularized by Investor's Business Daily (IBD) and available on their MarketSmith platform. They have a screen called the **Blue Dot** list in their Premium subscription, which screens for stocks making a new high in RS. This screener achieves the same and also ranks the results according to their RS Score which uses the same formula as the **RS Rating**.

[!RS Screener by @iArpanK](Assets/RS Screener.png "RS Screener")

### Features

- RS New High (Blue Label)
- RS New High Before Price (Green Label)
- RS Score (similar to RS Rating)

*RS Score is calculated according to IBD's formula as:*
```sh
RS Score = 40% * P3 + 20% * P6 + 20% * P9 + 20% * P12
```
P3, P6, P9 and P12 are the stock's 3 Months, 6 Months, 9 Months and 12 Months performance respectively.
Giving 40% weightage on the last quarter's performance and 20% on the other three.

### Input Parameters

- Base Symbol :  Symbol of the security/index with which you want to compare
- New High Period : Lookback period for new highs in RS (default is 250 i.e. equivalent to 52 weeks/1 year)

### Installation

RS Screener requires [Amibroker](https://www.amibroker.com/) to run.

- Download the .zip file
- Extract it
- Folder contains the AFL file, RS Screener by @iArpanK.afl
- Use it in your analysis

### Filters Used

- RS New High / New High before Price
- Closing price greater than equal to 10
- Volume greater than equal to 10,000

### RS Indicator
You can check out my RS Indicator on [TradingView.](https://in.tradingview.com/script/G6MOxSG2-Relative-Strength-Line-by-iArpanK/)

### Contact

You can reach me on twitter at [@iArpanK](https://twitter.com/iArpanK), where I share my ideas & psychology tips.
