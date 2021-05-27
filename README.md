# coyote-bot-binance
# Pump bot for Binance using AI to detect coin before signal

## Overview

Coyote bot is a pump bot intended to participate in pump events organized by some pump groups in Telegram or Discord.
The Coyote pump bot is able to predict the coin that will be pumped a few seconds before the signal is given in the group.
This permit to the user to buy the coin at almost the bottom of the pump and optimize the profit.
##### Process : The bot detect the coin, buy it and place sell order automatically. Then you can manage the sell order using other features.
Some other handy features are included such as the Target Slider or the Pump Strength Indicator (PSI).

Some videos are available on Youtube in this channel : https://www.youtube.com/channel/UCi77KRuBnBQDvP3qUhN7pRw/videos


## Features

#### AI auto detection

The bot includes a customizable AI detector with several parameters you can set to match the patterns of many pump groups.
This method is the preferred method that gives the best results, buying very early in the pump.

#### Hotkeys

The bot is entirely controlled by keyboard hotkeys to manage the orders quickly and efficiently.
- You can use LIMIT, MARKET, OCO orders (both sides)
- You can use the Target Slider
- You can control the Buy scanner

#### Target Slider

You can use the keyboard to move Up or Down the sell order and visualize it in real time on the Binance chart. SO you can adjust your Take Profit target in case it was too low or too high.
This feature is useful to optimize the profit when it's combined with the Pump Strength Indicator.

#### Pump Strength Indicator (PSI)

Advanced feature to detect the strength of the pump. The indicator decrease when the pump becomes weaker, indicating it's time to sell.
If the sell order was too high, and the indicator is decreasing fast, then it's better to sell immediatly using the sell key press.

#### Blacklist / Whitelist

The bot can manage a blacklist to exclude some coins from the scanner.
At the opposite, you can use a Whitelist to scan only certain coins. This feature is very useful in some cases.

#### Discord scraper

Old method. The bot can read the coin name from the Discord channel where the coin signal is given to people.

## Copyright

All the content, videos, codes are property of this Git owner and can't be reproduced without explicit authorization.



