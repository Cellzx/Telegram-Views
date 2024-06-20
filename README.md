# Telegram Views

Arguments Exmaple + Modes

```python
# In this examples we are sending to channel @tviews and the post number is ( 4 )
# e.g: https://t.me/views/x
```

```python
# Auto Scraping Mode ( Auto Proxy "PROXYLESS" )
# This mode scrape proxies automatically from many sources
# You can update the sources from the auto dir
# This mode run forever it auto resecrap proxyes when the first loop done

tviews.py --mode auto --channel tviews --post 4
```

```python
# Load Proxies From File ( File List Of Proxies )
# This mode allow you to run your own proxies from a txt file

tviews.py --type http --mode list --proxy http.txt --channel tviews --post 4
```

```python
# Using Rotating Proxy ( Rotating Proxies )
# This mode allow you to run your own Rotated Proxies

tviews.py -t http -m rotate -p user:password@ip:port -c tviews -pt 4
```
