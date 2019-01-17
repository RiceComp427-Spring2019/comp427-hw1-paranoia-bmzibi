# <img src="http://www.rice.edu/_images/rice-logo.jpg" width=180> Comp427, Spring 2018, Homework 1
## Rational Paranoia
The homework specifications, as well as the corresponding course slide decks,
can be found on the [Comp427 Piazza](https://piazza.com/class/jqifhp864b37ju).
This assignment is due **Thursday, January 17 at 6 p.m.**

You will do this homework by editing the _README.md_ file. It's in
[MarkDown format](https://guides.github.com/features/mastering-markdown/)
and will be rendered to beautiful HTML when you visit your GitHub repo.

## Student Information
Please also edit _README.md_ and replace your instructor's name and NetID with your own:

_Student name_: BRETT ZIBILICH

_Student NetID_: bmz1

Your NetID is typically your initials and a numeric digit. That's
what we need here.

_If you contacted us in advance and we approved a late submission,
please cut-and-paste the text from that email here._

## Problem 1
- Scenario: Stadium
- Assumptions:
  - I am assuming the school owns its stadium.
  - Alcohol is served at the stadium.
  - Gambling exists and money is bet on the outcome of football games.
- Assets:
  - A primary asset present at this event will be the lives of all of the people in the stadium. In addition to being precious in and of itself, a loss of life would be terrible for the sport, the team, and the school. Security will need to place a high priority on preserving the safety of fans.
  - Another major asset is the reputation of the school hosting the game. The reputation will be severely tarnished if the integrity of the game were in question or if the school were associated with a tragedy at one of its events. Negative effects to reputation are long lasting and very hard to repair, so while not as high as a priority as the safety of the fans, the schools reputation must be a very high priority asset.
  - The stadium itself is a major asset. It is expensive and for many schools where sports is a major part of the school culture, it is a symbol closely associated with the school. Any damage to the stadium will be a major loss for the school. Stadiums tend to be very expensive and take a long time to build; so preventing damage will be yet another high priority task.
- Threats:
  - Injury or death of people attending the game is a major threat. This can come from many threats:
    - A large scale attack could occur at the stadium.
    - A fight could break out between fans due to anger over the game, taunting, or alcohol consumption.
    - Fans could act in an unsafe manner if they needed to leave the stadium quickly.
    - Fans need to drive home safely if they have been drinking at the game.
  - Gambling could occur at the stadium, tarnishing the reputation of the school. The more popular the game, the higher the incentive for people to gamble. 
  - The integrity of the game needs to be upheld. If any cheating occurred or if a team were given an unfair advantage it would have a very negative impact on the school's reputation. When the stakes of a game are higher, people are more likely to engage in dishonest tactics. Because the school is highly ranked, cheating is more likely than at a school where there is less to gain from games won.
  - Both the home team and away team fans are threats for vandalism depending on the outcome of the game. If the game turns ugly for an away team, it is possible their fans may do damage to the stadium. Many schools do have their stadiums damaged by the home team fans. After a big win some school's fans are known to tear down goal posts among other traditions. All fans present a risk of vandalism.
- Countermeasures:
  - The stadium should limit what can be carried into the game to minimize the presence of any weapons. A bag check for bags over a certain size should happen at all entrances. To minimize the impact of this policy, fans should be encouraged to keep bags small or to avoid bringing bags altogether if possible.
  - Plenty of cameras should cover the stadium. They should be obvious to people to deter bad behavior as much as possible by making their presence known. Cameras should also be placed around any equipment needed to play the game to prevent tampering for one team's advantage.
  - Alcohol consumption should be limited per person and people showing any signs of intoxication should be cut off. After the game fans should be encouraged to take advantage of a taxi or ride sharing to avoid driving home drunk. This should be reinforced with clear presence of police officers acting in a way to suggest they are looking for people attempting to drive drunk.

## Problem 2
- Scenario: Documents
- Assumptions:
  - I am assuming that the documents could be used as evidence or have some other value to actors both inside and outside the firm.
  - I am also assuming the law firm has some means of digital identification for its attorneys as well as a means to track what attorneys are on what cases and need access to certain documents.
- Assets:
  - Law firms live and die by their reputation. If it were to be revealed that a law firm was compromised many clients would flee to other law firms, potentially ending the firm. If a document were altered and offered to the court, it would damage the law firm's reputation and possibly that of the clients involved in the case.
  - The attorneys themselves are a major asset of the firm. Without them, clients would not come. If a breach occurred many attorneys could leave due to frustration, loss of clients, or loss of license depending on how the breach occurred.
  - Clients are an asset for law firms. Without clients, there is no one to pay the bills, and for the salary of the head of IT! Those documents could potentially greatly harm clients. Their jobs, money, and freedoms could be at risk if the documents were compromised.
  - Documents themselves are also an asset. Perhaps they could be used to win a case, or maybe they keep the firm or a client in business by recording financial facts. If the firm decided to engage in data analysis of information in the documents, they could be very valuable.
- Threats:
  - Outside actors are one source of threat. An outside actor may be involved in a lawsuit with the firm, want dirt to harm a client, or could even be a rival firm looking for a way to hurt the competition. It is critical that outside actors be prevented from accessing sensitive documents.
    - An outside actor could pose as one of the attorneys or clients and request documents.
    - If security is not strong, they could access the network and obtain sensitive documents.
    - Even without accessing the system, a bad actor could eavesdrop on the transfer of a document. 
    - In some circumstances, an outside actor may wish to delete sensitive documents without accessing them if they were damaging to the outside actor or beneficial to the firm.
  - The attorneys could be a threat for the loss or accidental release of sensitive documents.
    - An attorney could potentially delete a document by mistake. If that document were sensitive and needed by the firm it could put the firm in a bad position.
    - Improper transferring of sensitive documents could send it to the wrong recipient.
    - If an attorney were leaving the firm they may want to take documents to gain an advantage in their new job.
    - An attorney would be a good target for an outside actor pretending to be an authorized recipient of the document.
- Countermeasures:
  - Documents should be accessible in the document management system only by authorized users. Accesses should be recorded along with download information by any party. There should be different permission levels for viewing and downloading.
  - Encrypting sensitive documents that are downloaded with some specific key tied to desired attorneys could reduce the likelihood of accidental transmissions and thwart attackers pretending to be an authorized recipient in an email, etc.
    - This could make it easy for documents to be shared between attorneys: potentially make emailing of sensitive documents prohibited. If an attorney needs a document and should have it, granting them access could give them a file only they could open. If an attacker were to receive a file somehow, they would also need the attorneys key, adding a final line of defense.
  - To decrease mishandling, sensitive documents should be clearly marked as such. Ideally, there would be some attention-grabbing display such as the color yellow or red to encourage care from viewers of the sensitive document.

## Problem 3
- Scenario: Amazon Prime Day
- Assumptions:
  - I am assuming that Prime Day is a major target for bad actors and prone to internal technical challenges that increase the security risk. I am assuming that the data of customers during Prime Day would be valuable and that disrupting Prime Day would be of value to competitors.
- Assets:
  - Amazon website and infrastructure behind it. Amazon has spent lots of time and money to develop their retail ecosystem. Many of the systems took a lot of time to configure and set up and a loss would require many engineering hours to replace.
  - Sensitive customer information. This information is left on Amazon to make the customer shopping experience easier. It benefits Amazon because people are more likely to buy if the process is easier. Losing this data due to a breach would be a major loss.
  - Amazon's reputation. Amazon has to maintain the faith of investor's while keeping customer trust. If a breach were to occur, customer's may not put information on Amazon and may stop shopping there. A loss of trust would lead to a loss of sales, and anger investors. Even without a breach, a system outage might frustrate a customer into shopping on a competitor's website.
  - Sales on one of the largest retail days for the company. With the advertising and discounting, Prime Day is one of the most important sales days for the company. It is expensive to set up, requires many engineers to be on staff, and lowers margins on sales for the day. To make it worthwhile, customer's need to buy things.
  - Sales and customer data. Data can be used to determine spending habits or recommend items to a customer. This information is very valuable both to Amazon and to its competitors.
- Threats:
  - External bad actors are a major threat for Prime Day:
    - Another company or individual may want to cause a system outage to prevent the sales from going smoothly. Competitors want to move sales to their websites so if Amazon isn't able to complete a purchase perhaps people will try other companies. The stock market reacts strongly to news about big sales events, and an intentional outage could be used as a means to profit from bad returns.
    - Companies or individuals may want to obtain customer data. Customer data could be used to perform identity theft and make other purchases. Additionally, the shopping behavior of customers is valuable in itself as data. An attacker may try to obtain either type of data.
    - For various reasons an attacker may want to alter communications coming out of Amazon in the forms of email, advertising, etc. This false communication could be used as part of a phishing attack or to intentionally mislead customers to thwart Prime Day's success.
  - Internal actors are also threats. A disgruntled employee may want to harm the business during the busiest time of year. They may also want to take customer data to either use for identity theft or as valuable data about Amazon's business.
- Countermeasures:
  - First, around important dates like Prime Day, code deployment should be kept at an emergency-only basis. This will mitigate the likelihood of last-minute attempts to disrupt the system or gain improper access. Development can still continue, but nothing should be able to reach Production without the approval of many involved people to ensure the need for changes.
  - Monitoring of systems should be a priority. If a system is not acting correctly, it should be investigated immediately and the cause isolated. Amazon should deploy extra scaling resources beyond the expected load for special retail days to reduce the risk of a brute force attack bringing the system down.
  - Communication regarding particular deals should be finalized and reviewed beforehand to ensure information is correct and that any links contained point to the proper location. Perhaps Amazon should work with major email providers to create an authentication/verification scheme to prevent spam mail posing as official Amazon mail.
  - Access to customer information should be even more restricted than normal circumstances. Presumably access is kept on a basis of need, but surrounding major days like Prime Day, the access should be as minimal as possible. This is especially true if code deployment is limited, as the justification for accessing data is diminished.

