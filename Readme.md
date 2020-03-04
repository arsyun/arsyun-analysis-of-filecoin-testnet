# **Looking at the Top 10 miners in the Filecoin testnet through the data**

ARS， March 4th，2020

______

The first phase of Filecoin testnet has been running for 6 weeks since it was restarted on 14th, January. At present, the network is running smoothly, and the first node with 1PB power (Miner t018985) also appeared on 25th, February. Till 29th, February, the miner count of the Filecoin testnet has reached 7,000. Behind each miner, there are several or even dozens of hard-working community members. The healthy development of both the Filecoin project and ecology can not be separated from the contributions of all community members, and they should all win applause.

Among them, the most outstanding miners are the Top 10. Since one of the characteristics of the blockchain is that the data on the chain is open and transparent, today we use this data to see how the Top 10 miners perform~

 

 

## **Top10 miners** **in the history of** **Effective storage** **of** **computing power** 

 

##### 1. Historical ranking list (block height # 85085, including offline miners)

![img](/img/1.png) 

##### 2. List of current miner rankings (block height # 85097, Screenshots from the Filecoin testnet)

![img](/img/2.png) 

 

 

## **Miner stability analysis**

 

##### The Growth Curve of historical Top10 miners.

![img](/img/3.png) 

From the picture above, you can see:

- The miners that have not been slashed in long-term stable operation are t018985，t01005，t017504，t019125；the remaining miners have been slashed once or more, and even some miners slashed frequently, which resulting in very uneven growth curve.

- During the long-term operation, the miner cluster will inevitably undergo maintenance, update and other issues.Therefore, to keep the storage power undiminished so as not to be punished during the long-term operation while ensuring the storage power continue to grow steadily, the team needs to meet the multi-dimensional requirements from development to operation and maintenance.

- Among the above-mentioned stable miners, ARS owns three miners without slashing: t018985, t01005 and t017504, which have maintained high-speed and stable growth in the whole process.

 

 

## **Miner efficiency analysis**

 

When it comes to efficiency, we need to have a definition of efficiency-at the same effective storage power, the higher the packing rate (the more coins are produced), the higher the efficiency.

In order to more clearly analyze the efficiency of each miner, we mainly analyze the miners whose average effective storage power is above 200T. We divide the Top 10 into two groups according to the average effective storage power level.

- The first group: above 600T: t018985, t01201, t01005

- The second group: 200T～ 600T: t01210, t017504, t09999

 

##### 1  Analysis of miner packing efficiency above 600T

Select t018985 and t01201 for comparison.


######  (1) Determination of comparison intervals

- Block height 70577 ~ block height 74399, comparison of packing conditions within a period of nearly 2 days (see the figure below)

![img](/img/4.png) 

 

- The intersection of the two storage powers: the block height at the intersection of the storage power growth curve is determined (# 72488)

![img](/img/5.png) 

 

- End of interval: moment of offline at t01201 (# 74399)

![img](/img/6.png) 

 

- Start of interval: 72488- (74399-72488) = # 70577

![img](/img/7.png) 

 

###### （2）Comparison of packing rate

![img](/img/8.png) 

 

###### （3）Conclusion

| Miner ID | Count of Packing | Packing Rate |
| -------- | ---------------- | ------------ |
| t 018985 | 2513             | 65.75%       |
| t 01201  | 2284             | 59.76%       |

From the above date, we can get the conclusion that under the same computing power and the same statistical period, the count of packing by miner t018985 is 10% higher than that by miner t01201.

 

##### 2. Analysis of packing efficiency in 200T ～ 600T group

###### （1）Determination of the comparison intervals

- Block height 71645 ~ Block height 85085, the comparison of packaging in the period about 7 days

![img](/img/9.png)  

\- End of interval: #85085

\- Start of interval: #85085-1920*7=#71645

 

###### （2）Comparison of packing rate

![img](/img/10.png) 

 

###### （3）Conclusion

| Miner ID | Effective storage Power | Count of packing | PackingRate | Rate/100T | Translate to count of packing/100T |
| -------- | ----------------------- | ---------------- | ----------- | --------- | ---------------------------------- |
| t 01210  | 400T                    | 5405             | 40.22%      | 10.06%    | 1351.25                            |
| t 017504 | 360T                    | 5350             | 39.81%      | 11.06%    | 1486.1                             |
| t 09999  | 285T                    | 3254             | 24.21%      | 8.49%     | 1141.75                            |

In the 200T ~ 600T storage power group, results are as follows (based on a week's data, the same effective storage power and the same statistical cycle):

- Ranking of packing rate: t017504> t01210> t09999.

- The count of packing by t017504 is about 9.98% more than t01210.

- The count of packing by t017504 is about 30% more than t09999.

 

*The above is an objective analysis based* *on the data of testnet phase1 restart (after restart on January 14).* 

*Tips: You can never pay too much attention to the conditions upon watching the testnet and analyzing the data of the miner nodes, and it is more meaningful if the conditions are the same.*

 

 

## **Prospecting Filecoin—— blockchain-distributed cloud storage is NOW**

Since entering the field of IPFS / Filecoin in November 2017, ARS has witnessed the update and iteration of its technology. We still remember that the earliest version of the Filecoin White Paper (2014) used POW as the consensus mechanism for block generation. The entire technical framework and economic model are also similar to Sia. However, with the development of Filecoin, the change is obvious—By replacing POW with Proof of Replication, Filecoin successfully turns unnecessary waste of energy into useful storage power, which is a huge leap forward in the history of blockchain development in terms of Block reward. Although Filecoin did not accept the mining pools at the beginning, with the passing by of time and the promotion of implementation practices, mining pools have become an important factor to improve the stability of Filecoin's network services. At the same time, the officials are sparing no effort to promote the design of large miners.



Always trying their best to solve difficulties and promoting the continuous involvement of the system, Protocol Labs is a truly open and respectable team. Filecoin is a complex system with openness, emergence, and evolution. As Brian Arthur pointed out in the book "THE NATURE OF TECHNOLOGY", "Technology follows a combined evolutionary mechanism in the development process. Technology is always combined with existing technologies and then combined with other technologies to form new technologies. In this way, recursion can reach multiple levels and iterate around a core technology." 



If we turn our attention back to Filecoin, and we will find that the Protocol Lab is does exactly such things- combining IPLD, DAG technology, VDE / VDF, EC expected consensus and other technologies into a vibrant system like Filecoin. In addition, Filecoin is also building their ecosystem actively.  



Undoubtedly, this open mindset of the official team has ensured the emergence and guaranteed the evolution of the Filecoin system.

 

Inspired by the above actions, ARS actively engaged in the work of large miners, optimization of both the efficiency and the structure of Proof of Replication protocol, hoping to contribute our strength to the Filecoin community and ecology.

More than 200 years ago, when the whistle of the competition of the first railway steam locomotive and horse-drawn carriage blew, the public at that time never thought that more than a century of prosperity would be built on such a "chunky guy who runs slower than a horse "

 How a new thing emerges? The history will give the answer.

 

 
