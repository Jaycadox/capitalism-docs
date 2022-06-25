<div style="max-width: 1000px; margin: 0 auto;">
<div style="text-align: center">

# Capitalism
Basic documenation and usage guide.
</div>


## Quick start
The goal is to be the first to reach **$1,000,000,000**.
The first time you connect, you will recieve **$1,000,000**.

There are a few ways to make money, they go as follows.
## Shops
If you buy an area of land (in the shop district) and decide to put a sign with a specific format on a chest, you can sell in-game items to other players for a set price.


## Playtime rewards
Every ~25 minutes, the server broadcasts a playtime reward. If you click the message, you get **$100,000**. You have 30 seconds to click the message, else it expires.

## Lottery
Everyday, at around 5-6PM AEST, the server broadcasts a lottery. If you click the message, you are entered. You also get notified about an active lottery whenever you log in. The maximum amount of money that a lottery can give is **$1,000,000**.

<div style="text-align: center">

# Documentation
General documentation
</div>


## Commands
### /balance
Can also be typed as
 - bal

This will display how much money you have. Example:

![showcase](1.png)
### /profile
Can also be typed as
 - p
 - prof
 - self

This command opens your player profile menu where you can manage land claims and view your stats.

### /landlord
Can also be typed as
 - land
 - l

Whilst standing inside one of your claims, you can type this command to open the management menu for your land claim.
### /pay
Can also be typed as
 - send
 - transfer

This command can be used in one of two formats.
 - /pay \<player> \<amount>
 - /pay \<amount> \<player>

A successful transaction looks like this

![showcase](2.png)

The text in brackets (in this case: `(ba7b)`), is the *transaction hash*. As the recipient of the money is not told who sent it, this hash is shared between both clients, so it can be used to confirm if someone sent you a transaction.

There are a few errors that can happen when trying to send someone money, the most common error is this

![showcase](3.png)

This means you don't have enough money to send to the specific player. But other errors include but are not limited to:
 - Sending money to yourself
 - Sending money under $1
 - General database issue
 - Causing a flag in anti money duplication systems

Please note that you cannot view the balance of another player.

## The Lottery
The server stores it's own bank account. This bank account is sent money from Death Tax, Transaction Tax, and property sales.

Everyday, **at around 5-6PM AEST**. The lottery will randomly select a winner out of the people who have entered. **You need to be online when it rolls for it to select you, it does NOT select an offline player**.

A roll is skipped if
- Less than 2 people rolled
- No one who entered is online
- The servers bank is too poor to afford a lottery

If a roll is skipped, you will have to wait until the next day for it to re-roll.

This is what a lottery notification looks like

![img](4.png)

"How does this message appear"? It appears in one of two ways
- When you connect to the server when there's an active lottery you haven't entered
- The moment after the lottery rolls (if the bank can afford it)

Make sure you open chat and click it so you don't miss it!

## Taxes 
### Aren't taxes fun!! 😄

Currently there are two forms of tax. Death Tax and Transaction Tax. Each follows different rules around what percentage of a certain amount of money should be taxed given certain conditions.
<div style="display: flex; margin: 0 auto; width: 100%;">
<div>

### Death tax (**Not using brackets**)

<table>
  <tr>
    <th>Balance ($)</th>
    <th>Tax (%)</th>
  </tr>
  <tr>
    <td>0-999,999</td>
    <td>5</td>
  </tr>
  <tr>
    <td>1,000,000-9,999,999</td>
    <td>7</td>
  </tr>
  <tr>
    <td>10,000,000-99,999,999</td>
    <td>9</td>
  </tr>
  <tr>
    <td>100,000,000-899,999,999</td>
    <td>11</td>
  </tr>
  <tr>
    <td>900,000,000-1,000,000,000</td>
    <td>15</td>
  </tr>
</table> 
</div>
<div style="margin-left: 50px;">

### Transaction tax (**Using brackets**)

<table>
  <tr>
    <th>Balance ($)</th>
    <th>Tax (%)</th>
  </tr>
  <tr>
    <td>0-20,000,000</td>
    <td>8</td>
  </tr>
  <tr>
    <td>>20,000,000</td>
    <td>0</td>
  </tr>
</table> 
</div>
</div>

As one can see, every dollar over 20 million sent through a transaction will not be taxed. This has been done to encorage larger and wholesale transactions between players.

### Where does my taxed money go?
It goes towards the same bank that hosts lotteries. Which is just generally the "server bank". Money that goes in this account would be redistributed to players.

## Regions
There are 3 types of regions for our world (which would have a word border size of -5000 to 5000).
- Commercial (below 500 blocks away from 0, 0)
  - Owning property here allows you to make shops, please note that you should not live in a commercial property.
  - You cannot place beds in commercial property.
  - Commercial property has a size limitation of 18x18, but that might change later.
- Residential (500-2000 blocks away from 0, 0)
  - Essentially no hard-line restrictions except for the fact that shops cannot operate here
- Unclaimable (2000+ blocks away from 0, 0)
  - No land can be claimed in this region

Regions are measured in a circle from spawn, this means it could be hard to know where you are within a region, but you will get an Action Bar notification when you cross a region.

## What is claimed land?
Claimed land is an area of land that you can purchase. Other players cannot grief or steal items from your land claim. This is perfect if you want to create a house, a farm, or a shop.

If you want to work with your friends and still want them to be able to interact with your plot of land, you can add them to the Trusted Players list, by using the `/landlord` command. This land can also be transfered or sold to another player.

Whilst I have tried my best to prevent griefing in land claims, it is also against the server rules to grief a land claim (if one can manage to find a bypass).

I do not condone griefing someones base if it's not claimed, but ultimately, it's not against the rules and you probably won't be punished.

## What is a shop?
A shop is a land claim in the Commercial Region. Once you own a shop, you can sell items from chests to other players. This is the best way to make money on the server.

If you sell your items for cheap enough, you'll appear on the global leaderboard as the person selling a certain item for the cheapest price, which would be a good way to gain some publicity!

## What's the difference between a shop and a land claim?
They're the same thing. The only difference is the region that they're located in.


## Making shops and claiming land
The general process to claim land and make a shop follows three steps.
 1. Buy a plot of land to create a shop
 2. Gather supplies and resupply said shop
 3. Create a shop sign on a chest in your land

To buy a plot of land, please contact me on Discord at **jayphen#6666**. Specify the area you want your land to be in, and I'll give you a quote for the price of that land. Please note that the closer your land is to spawn, the cheaper it is. Please also note that you can only create shops in the commerical region, commercial land is also cheaper than residential because it is closer to spawn.

I understand that this is inconvenient, and it might change in the future, but there are benefits of this approach
- Helps halt land claim abuse
- Users don't have to fuss with (frankly really poorly made) land claim plugins

The procedure to create a shop is quite simple and goes as follows.
- Place down a chest and stock it with the items you want to sell
- Put a sign on the chest, with the first line being a price. It needs to start with a '$' character. As an example
  - $1000 - Works
  - $1,000 - Does not work
  - 1000 - Does not work

You're free to put whatever text you want on the lines below.

You'll be sure it worked when you get a notification in chat confirming the sign placement. You will also get a notification when someone buys your item, or when the sign is destroyed.

## What's the IP?
mc.jayphen.xyz (server not set up yet, if you join you'll see an old SMP)

## How can I be added to the whitelist?
DM **jayphen#6666** on Discord.

## Bug Bounty

If you report a bug, you will be sent a fair, large sum of money (in-game), depending on what the issue is. The most important issues I care about are related to money duplication.

DM **jayphen#6666** on Discord for further information.

## Rules
The most important, and most general rule is "don't be an idiot". Chances are if you have to ask if something is against the rules, it is. But some trivial examples are as follows
 - Griefing
 - Stealing
 - Killing without reason
 - Exploiting
 - Cheating

Please note that I reserve the right to ban anyone for any reason. Depending on the severity of the rule you've broken, your accounts progress might be reset.
</div>