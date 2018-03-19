# Human-or-Robot


<img align="center" src ="../master/Images/CompanyLogo.png" />


Live Auction is a fictitious company that allows bidders to bid on many different types
of items.


## The Problem
Recently the human bidders on the site are becoming increasingly frustrated
with their inability to win auctions vs. robots. In order to rebuild customer happiness,
the company is seeking to eliminate robot bidders from the site.

The goal of this project is to provide Live Auction with a model that will identify
and flag bidders if they are a robot and prevent unfair bidding activity.

## The Data
The data comes from Kaggle: https://www.kaggle.com/c/facebook-recruiting-iv-human-or-bot

#### Files
| Filename      | Description               | File size                 |
| ------------- | :-------------------:     | -------------------------:     |
| Train.csv     | The training bidder dataset | 232 KB                            |
| Test.csv      | The test bidder dataset     | 523 KB                       |
| Bids.csv      | The bid dataset             | 882 MB                     |


## Project workflow

The point of this is to be able to easily transfer my work to a much larger computer
so I can increase my work efficiency. Docker is the perfect tool for this. Because I
can setup my project on my development machine initially and if I need a better computer to
speed up execution, I can spin up a larger EC2 instance.

![Overall](../master/Images/Diagram.png)
