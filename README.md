# FX-Training-Data
This is sorted data, for the common forex pairs, together with scripts to sort out your own data. It is mainly suited for training AI models related to the forex market.

Most providers of data from forex charts provide only one timeframe, usually the one-minute timeframe. But as you know most forex trading decisions are 
based on numerous factors, among which is price action on the different timeframes. This is why as a developer of trading software, you need data for 
different timeframes, which is as I said unavailable for the most part.

This repo contains a little ready-to-use data in the different timeframes, but most importantly, it has a number of powerful scripts that make it easy to 
extract any timeframe data accurately, provided you've been given one-minute timeframe data in csv format. The format in specific should be:
      [date, time, open, high, low, close, volume, state]
which is a 2d array contains octuples of the date, time, open price, highest prise reached, lowest price, closing price, (tick)volume within that period and state(whether it closed bullish or bearish).
