# Missions Rewards

3 realms in the game consist of 30 lands in total (FOTAlands), which are equivalent to 30 missions. Each world map in the game has 10 stages to pass.

Players use heroes and items to pass each stage

There are 2 playing modes:

* If there is no **Energy** or run out of **Energy**: play for fun but do not get rewarded, no need to call for **finishGame** on the contract
* If you win the stage and there is **Energy** left, then the players need to call the **finishGame** on the smart contract to finish the game and claim the reward. Only when the game confirms that the transaction has been successfully submitted to the contract, the next mission will be unlocked.

When the stage is won and the transaction is successful, then:

* **EXP** is added to the heroes that participated in the match
* **Reward** is recorded as “**pending**” on the blockchain according to the formula:

\+ Distribute 2% to the player's inviter (referral bonus). If there is no inviter or the inviter is not eligible, then this 2% is divided into the treasury. The condition to receive treasury is to join the farming with at least 100 points.

\+ Distribute 3% for farming

\+ 5% of the remaining reward is distributed to the landlord

\+ The rest is divided among players, this amount will be divided by 3 and recorded in = the profit earned by each NFT Hero participating in the match.

\+ After 15 days of “**pending**”, players can claim the $FOTA token bonus to their wallet at 12h Hight on the Marketplace.

\+ Players can only claim their **mainReward** once after winning the first mission, from the 2nd time onwards they’ll only be receiving half of the reward.

**Reward, Exp, Energy**

| Mission | Level | Energy | EXP | Reward 1st | Reward n+ |
| :-----: | :---: | :----: | :-: | :--------: | :-------: |
|    1    |   1   |    3   |  3  |    $6.0    |    $3.0   |
|    2    |   2   |    6   |  6  |    $7.0    |    $3.5   |
|    3    |   3   |    9   |  9  |    $8.0    |    $4.0   |
|    4    |   4   |   12   |  12 |    $9.0    |    $4.5   |
|    5    |   5   |   15   |  15 |    $10.0   |    $5.0   |
|    6    |   6   |   18   |  18 |    $11.0   |    $5.5   |
|    7    |   7   |   21   |  21 |    $12.0   |    $6.0   |
|    8    |   8   |   24   |  24 |    $13.0   |    $6.5   |
|    9    |   9   |   27   |  27 |    $14.0   |    $7.0   |
|    10   |   10  |   30   |  30 |    $15.0   |    $7.5   |
|    11   |   11  |   33   |  33 |    $16.0   |    $8.0   |
|    12   |   12  |   36   |  36 |    $17.0   |    $8.5   |
|    13   |   13  |   39   |  39 |    $18.0   |    $9.0   |
|    14   |   14  |   42   |  42 |    $19.0   |    $9.5   |
|    15   |   15  |   45   |  45 |    $20.0   |   $10.0   |
|    16   |   16  |   48   |  48 |    $21.0   |   $10.5   |
|    17   |   17  |   51   |  51 |    $22.0   |   $11.0   |
|    18   |   18  |   54   |  54 |    $23.0   |   $11.5   |
|    19   |   19  |   57   |  57 |    $24.0   |   $12.0   |
|    20   |   20  |   60   |  60 |    $25.0   |   $12.5   |
|    21   |   21  |   63   |  63 |    $26.0   |   $13.0   |
|    22   |   22  |   66   |  66 |    $27.0   |   $13.5   |
|    23   |   23  |   69   |  69 |    $28.0   |   $14.0   |
|    24   |   24  |   72   |  72 |    $29.0   |   $14.5   |
|    25   |   25  |   75   |  75 |    $30.0   |   $15.0   |
|    26   |   25  |   75   |  75 |    $31.0   |   $15.5   |
|    27   |   25  |   75   |  75 |    $32.0   |   $16.0   |
|    28   |   25  |   75   |  75 |    $33.0   |   $16.5   |
|    29   |   25  |   75   |  75 |    $34.0   |   $17.0   |
|    30   |   25  |   75   |  75 |    $35.0   |   $17.5   |

