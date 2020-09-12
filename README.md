# blockchianin-healthcare
final report on blockchain in health care field
Maintenance of health records using Blockchain technology 





  Karan B.Phukan                                                                                         Vaishnavi Moorthy
2nd year b.tech student                                                                                  Assistant Professor
Department of computer science and engineering                                       Department of computer and engineering
 S.R.M. institute of science and technology                                                 S.R.M. Institute of science and technology
karanphukan47@gamil.com                                                                        vaishnam@srmist.edu.in










Abstract
A long standing problem in the medical fields is the proper management of health records. There has been a long wait for a way to make this process more efficient and secure and with the introduction of Blockchain technology to the scenario the answer may have finally arrived. In the current scenario the Blockchain technology has found use in various fields. This technology can be used to completely evolve the entire health care system. The Blockchain has a very unique characteristic i.e. its versatility. It is both more transparent and secure than the currently existing system. In the current scenario the medical fields has become hinting ground for the cyber crimes. This is mostly due to the inefficient systems in use. The online portals and data storage processes employed by the hospitals are very vulnerable. Also since all the data is present in one single server it makes it very easy to tamper with. However the Blockchain technology shuts the door on all these problems. Since all the data on the Blockchain is visible to everyone who is a part of the network a user can have complete control over his or her data. Also9 because all the data present on the Blockchain network is cryptographically secured the data may be visible to everyone but only the owner can access and use the data. Also no third party can trace the dat back to its owner because of the use of cryptography. And as far as the problem of a single database goes the Blockchain provides a solution for it as well. The Blockchain has a decentralized structure. Thus at any point of time the exact same copy of the most updated Blockchain data is stored across multiple nodes. If anyone node tries to tamper or change any of the data present on its copy on the Blockchain all the remaining nodes will state that version of data to invalid. Thus the data present on the Blockchain remains tamper proof and secure. All these features of the Blockchain technology improve the current system at work and solve its issues.













Background
The current world scenario has been carved by humans with technology as their tool. The basic idea behind creation of all these technologies lays the desire of human beings to put it more accurately the greed for a better life. Among the millions of technology that surrounds us one of the most important and crucial is the internet. Since it’s starting in 1983 internet has grown to standards that no one even thought existed. In the current world internet has become a major influencing factor of our lives. Internet has found use not only in our professional life but also in our personal life. It is impossible to sum it up. But just like any other ant case there are certain loopholes in this technology as well. When all our data is on the internet it is within reach of almost everybody and of someone with a malicious intent gets there hand on this data there is nothing much we can do in order to prevent this. If this data falls into the wrong hands and is used for the wrong reason it can cause wide spread problems. In order to just understand this data’s strength considers the facebook debacle. (1)Facebook was caught responsible for selling its users data to a third party with the name of Cambridge Analytics. This leakage of data had a direct effect on Brexit and US Presidential elections the two most important world political events in the recent years. The following graph shows the number of data breaches between the years 2009 and 2018.
(2) 

                                                          Data breaches in the last  9 years

This was due the users being unaware on what and where there data was. Due to this any many similar cases there has been the need to make the internet more transparent and secure when handling such data. Thus in the year 2009 with the launch of bitcoin by Satoshi Nakomoto blockchain was introduced into the picture. Blockchain is s distributed network that lays emphasis on security, validity and transparency. Since then blockchain has become one of the hottest technology in the market. The blockchain became a even more of a talking point after the launch of Ethereum in the year 2015. After this a number of well known technology firms have taken a keen interest in the new technology. There has been a lot of research put into the idea of implementing blockchain in a number of other field. The following graph shows the growth of blockchain technology.

(3)






Proposed technology
The very basic principle behind the blockchain technology is that it allow ‘s for of information or data of digital background to shared and not copied. This principle makes sure that ant piece of data will only have one owner. The architecture of the blockchain network resembles a decentralized structure. In this structure every single component maintains a record, verifies all processes and approves of any new changes. Due to this the need of a central server is eliminated. The most basic and important feature of the blockchain network are
    • Immutability
    • Decentralized network
    • Enhanced security
    • Distributed ledgers
    • Consensus
    • Faster settlement

Immutability-
As the name suggests by this feature of the blockchain it makes the data secure. I.e. once any data has been uploaded to the blockchain it can never be changed or tampered with.
This feature makes blockchain a universal solution to security problems. In order to make the blockchain immutable there are two technologies at work. The first being the merkeel tree and second one being it s decentralized structure. The merklee tree concept converts all the data into a cryptographic hash by using certain hash function. As the data is converted into a hash following the tree structure any changes in one single node or leaf will completely change the value of the hash of the root node and change the contents of the block. Since every block is connected to the next block by its hash value i.e. every block contains the hash of the previous block, any changes in the contents of a block will not only change its hash value but also change the contents of every block following it. This is how the blockchain is made immutable. 
Desterilized network-
Another  salient feature of the blockchain technology is its decentralized structure. For a very long time all the companies and technology firma or any such organization had a central sever. This meant that all their data was stored in a single data base. This made it very vulnerable to attacks. Also this data was completely invisible to any user and the company could anything with this data without the consent of the users as seen in the case of facebook. However on the blockchain there exists multiple shared version of the blockchain’s current state. So any change in any one node’s blockchain will not cause any change to the real blockchain. Also all the data is completely visible to everyone the network and one’s data cannot be used by a third party without his or her permission. Although all the transaction occurring on the network is visible to everyone the owner details of every account gad been cryptographically made secure to prevent any form of tampering.
Enhanced security-
All the basic feature of the blockcchain moves towards making the network more secure, transparent and more efficient then all the currently used technologies.

Consensus-
Ina decentralized network one the biggest problem is how to make all the participant node reach a particular agreement. This is brought about by the concept called as consensus protocol. This allows all the nodes to agree upon a common point. There are a number of protocols being used such s proof of work, proof of stake, proof of weight.
Faster settlement
One of the main reasons why the blockchain technology came into existence was to increase the speed of certain processes by eliminating the middlemen.  As is the case in today’s world a number of health care processes have a middlemen. Not only do these middlemen increase the cost of the entire processes but also become huge point of vulnerability.  So with the help of the blockchcain technology we can simply initiate a transaction between two accounts and once the transaction has been verified by the miners the processes comes to and end. This makes the entire processes very efficient.
Although the blockchain technology if often associated with bitcoin the two are very different from one another to explain it in a very simple manner the relationship between them is similar to the relationship between the internet and mail. This technology has found a wide variety of application in various fields.

The structure of the block in any blockchain is very important. This is where all the data is stored. The block consists of a number of different components and each component has a very specific and important role to play.  A few if its components are
    • State root
    • Transaction root
    • Nonce
    • Timestamp
    • Size
    • Difficulty
    • Miner 
    • Parent hash
Of the above mentioned components the most important are the state root and transaction root. Ethereum uses the tree data structure to manage all its data. The structure has been elaborated in figure 1. The components of the state tree, storage tree and transaction tree are shown in figure 2.
 

                      Figure 1: structure of a block in ethereum blockchain







                  Figure 2: structure of state, transaction and storage tree





The health of human beings has always been a matter of very high concern. Due to the technological advancement   in the field if medical science a huge amount of change has been seen in this field. However in the recent years certain factors such as skyrocketing hospital costs, inefficient practice and constant data breaches have taken this field into a state of turmoil. The health care field has turned into a very profitable market in the recent years for hackers. The reason being that this field contains certain very delicate and important data that when stolen can be used for a number of wrong reasons starting from frauds, identity theft all the way to crimes such as espionage. Due to such problems existing in this field there has been need for a more efficient and secure technology. Here is where blockchain comes into the picture with its ability to secure the patients data and improve the health care field. It can be used to not only secure the data but also to prevent disease outbreaks. (4) Between the years 2009 and 2017 around 176 million patient records were stolen via data breaches. Hence in the current scenario the security of all the important medical data has been an utmost priority. The blockchain technologies vey unique ability to keep an immutable, decentralized and transparent record of all its data makes it an imminent solution to security problems. Also blockchain is a very versatile technology on one hand it is transparent but on the other hand it conceals the identity of any individual through complex and secure codes. The decentralized feature of blockchain not only makes the data tamperproof but also helps in allowing patients, doctors and healthcare service providers to share the same information. The blockchain technology has the potential to completely break open the health care field and resolve the problems of the current system. In blockchain based scenario all the information can easily be accessed by doctors, patients and pharmacies. It will allow the creation and sharing of a common database of any kind of medical information. This kind of setup will greatly increase the efficiency of the operations. All the doctors will be getting more time to spend on the patients. Also since the information is readily available to be shared, other doctors can be consulted on any case to find the best possible best treatment. This consultation would otherwise take a very long time to finish. In the present conditions the patients report would have to be sent individually and they would go through these reports and give their opinions.  The blockchain makes this ecosystem much more efficient, accurate and cost effective. Another aspect on which the blockchain technology can help is by making the clinical trials more effective and transparent. In present conditions a number of clinical trials are conducted by a number of medical firms to test the outcomes of new drugs and medicines. Based on hypothesis various new medicines are tested and depending on the outcomes of the tests the medicines are given clearance for production. These test results and a lot of other data need to consider by the researchers when that make the decision to whether the drug can be launched into the market or not. However a lot of firms business depends on the success of such trials. So they start forging and manipulating certain sets if data. This can lead to catastrophic consequences. However with the blockchain technology we can make the process a lot more transparent. The blockchain can be used to store secure, unbiased and transparent clinical trials record. Another way in which blockchain can increase the efficiency of clinical trials is by its feature of storing time stamped documents. When any kind if data is stored in the blocks it is always time stamped. In clinical trials documents used such as informed consent, research plans, regulations and study protocols are needed to be time stamped to make the clinical trials more efficient. Also smart contracts can be used in way to increase the credibility of clinical trials. By converting certain documents into smart contracts a number of issues regarding this document can be cleared. Problems such as loss of documents will be completely eradicated as the data will always be present on the blockchain. Also it will reduce the time, power and money spend on the regular checking of the data in the present state.




Future Work
The use of this technology can increase in the future. Certain aspects of this technology can be worked upon and improved eve n further. The accesses of data by the patients and the doctors can be improved further. By making this processes more secure certain issues connected to this area of the medical field will be solved. Also another aspect that can be worked upon is the secure data transmission between the blockchian. This is a very important aspect as the entire credibility of the network depends upon is ability to maintain the data in a secure manner. Also since blockchain provides a distributed ledger the data of a particular hospital branch can be accessed by other branches for example consider the apolo hospitals. The data present with one single apolo hospital branch can be accessed by any other branch of apolo hospitals. This will make the entire processes much more efficient and cost effective.
Conclusion
The proposed system uses the salient feature of the Blockchain technology to solve most of the current problems of the health care society. The ability of the Blockchain to maintain a completely transparent and yet a fully secure database is of huge help to the medical society. The user or the patients have complete control over their data and are fully aware of where and to whom their data is being shared. Except the receiver of this data no one will be able to accesses this data. Also no third party can ever trace back the owner of the information as it is cryptographically secure. This system will completely eliminate the possibility of ant phisher attack. Since the entire validation processes is done through a proof-of-stake protocol there can be no threat on any invalid entry of data in to the network.











References
    1) How Decentralized Blockchain Internet will comply with GDPR Data Privacy Claudio Lima, Ph.D. Blockchain Engineering Council, BEC Co-Founder vice Chair IEEE Blockchain Standards.
    2) A Case Study for Blockchain in Healthcare: “MedRec” prototype for electronic health records and medical research data White Paper Ariel Ekblaw*, Asaph Azaria* , John D. Halamka, MD† , Andrew Lippman* *MIT Media Lab, †Beth Israel Deaconess Medical Center.
    3) Peer to Peer for Privacy and Decentralization in the Internet of Things, Marco Conoscenti Nexa Center for Internet & Society DAUIN-Politecnico di Torino ITALY, Antonio Vetro` Nexa Center for Internet & Society DAUIN-Politecnico di Torino ITALY, Juan Carlos De Martin Nexa Center for Internet & Society DAUIN-Politecnico di Torino ITALY.
    4) A Survey of Blockchain Applications in Different Domains Wubing Chen Xi’an Jiaotong University 28 Xianning W Rd, ErHuan Lu Xian Shi, China 710048 +86 13772529952 ,Zhiying Xu, Shuyu Shi Nanjing University 22 Hankou Rd, Gulou Qu Nanjing, China, 210008 +86 17763200154, +86 17761719569, ssy@nju.edu.cn Yang Zhao, Jun Zhao Nanyang Technological University 50 Nanyang Ave Singapore 639798 +65 86483534.
    5) Blockchain Contract: A Complete Consensus using Blockchain Hiroki Watanabe, Shigeru Fujimura, Atsushi Nakadaira, Yasuhiko Miyazaki, Akihito Akutsu NTT Service Evolution Laboratories Yokosuka-City, Kanagawa, Japan Jay (Junichi) Kishigami Muroran Institute of Technology Muroran-City, Hokkaido, Japan.
    6) n Application of Ethereum smart contracts and IoT to logistics Leonor Augusto Department of Electrical Engineering Faculdade de Ciências e Tecnologia, UNL Caparica, Portugal ,Ruben Costa Department of Electrical Engineering Faculdade de Ciências e Tecnologia, UNL Caparica, Portugal ,José Ferreira Department of Electrical Engineering Faculdade de Ciências e Tecnologia, UNL Caparica, Portugal ,Ricardo Jardim-Gonçalves Department of Electrical Engineering Faculdade de Ciências e Tecnologia, UNL Caparica, Portugal
In text References
    1) Cnn.com, facebook scandal answered by Kaya Yurief
    2) https://www.iii.org/fact-statistic/facts-statistics-identity-theft-and-cybercrime
    3) packtpub.com/book/big_data_and_business_intelligence/9781788839044/1/ch01lvl1sec10/the-growth-of-blockchain-technology
    4) Healthcareitnews.com
