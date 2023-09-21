# RevoltBots.py
For Use with the RevoltBotList API!


## Installation
```bash
pip3 install revoltbots.py
```

## Example Usage:
```py
from revoltbots import RBL
RBList = RBL.RevoltBots(ApiKey="xxxxx", botId="xxxxx")

def post():
    """ POST Stats """
    res = RBList.postStats(3)
    print(res)

def getStats():
    """ GET Stats """
    res = RBList.getStats()
    print(res)


def checkVotes():
    """ GET Votes """
    res = RBList.checkVotes()
    print(res)


def getVoter():
    """ Check Voter """
    res = RBList.checkVoter(userId="id")
    print(res)

```