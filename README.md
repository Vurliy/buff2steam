<p align="center">
  <b>Special thanks to the generous sponsorship by:</b>
  <br><br>
  <a target="_blank" href="https://www.jetbrains.com/?from=buff2steam">
    <img src="https://i.loli.net/2018/03/21/5ab223b75cdfa.png" width=250>
  </a>
  <br><br>
</p>

# buff2steam

> make money from buff.163.com

[简体中文](.github/README-zh-CN.md)

![head_image](https://user-images.githubusercontent.com/5501843/53693505-5c2c0900-3ddc-11e9-84c8-67e37e04798d.png)

## Table of Contents

- [requirements](#requirements)
- [usage](#usage)
- [buff_session && more config](#buff-session----more-config)
- [License](#license)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>

## requirements

`pip install -r requirements.txt`

## usage

`python3 main.py`

----------------

## buff_session && more config

``` python
# enter your session
buff_session = 'session=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx'

# buff id blacklist
buff_id_blacklist = (3986,)

# buff type blacklist
buff_type_blacklist = ('tool',)

# game name in alphabet
game = 'dota2'

# game appid in number
game_appid = '570'

# currency id(23 => CNY)
currency = 23  # CNY

# buff says price ratio
accept_buff_threshold = Decimal(0.6)

# sell now ratio
highest_buy_order_ratio_threshold = Decimal(0.75)

# CNY * 100
min_price = 1000
max_price = 30000

# steam api request interval
steam_api_sleep = 30
```

## License

buff2steam is open-source software licensed under the Unlicense License. See the LICENSE file for more information.
