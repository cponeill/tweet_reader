from urllib2 import urlopen
import json

screen_name = raw_input(': ')

url = "http://api.twitter.com/1/statuses/user_timeline.json?screen_name=" + screen_name
data = json.load(urlopen(url))

for tweet in data:
    print tweet['text']
