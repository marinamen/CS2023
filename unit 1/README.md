# Crypto Wallet 

‧˚₊⋅ ୨୧ ⋅₊˚‧

**Coin Guardian**

‧˚₊⋅ ୨୧ ⋅₊˚‧


*A Python Developed Terminal Based Digital Ledger by Marina Mendieta*

<img src="https://github.com/marinamen/CS2023/blob/main/unit%201/pictures/Screen_Shot_2023-10-04_at_23.38.30-removebg-preview.png" width=20% height=20%>

[̲̅$̲̅(̲̅5̲̅0)̲̅$̲̅]

‧˚₊⋅ ୨୧ ⋅₊˚‧


![](https://github.com/marinamen/CS2023/blob/main/unit%201/pictures/78e154025781802198e0401faa508d9a.gif)


‧˚₊⋅ ୨୧ ⋅₊˚‧

# Criteria A: Planning  　

<img src="https://github.com/marinamen/CS2023/blob/main/unit%201/pictures/734807779ad6cc5b0620359f950d2ff1.gif" width=50% height=50%>
‧˚₊⋅ ୨୧ ⋅₊˚‧ 　 　　 　　　　 　

## Problem definition

Ms. Sato is a local trader who is interested in the emerging market of cryptocurrencies. She has started to buy and sell electronic currencies, however at the moment she is tracking all his transaction using a ledger in a spreadsheet which is starting to become burdensome and too disorganized. It is also difficult for Ms Sato to find past transactions or important statistics about the currency. Ms Sato is in need of a digital ledger that helps her track the amount of the cryptocurrency, the transactions, along with useful statistics. 

Apart for this requirements, Ms Sato is open to explore a cryptocurrency selected by the developer.

✩࿐  ⊹˚. ♡

| Name   | Coin            |
|--------|-----------------|
| Keeler | ETH             |
| Rocky  | DOGE            |
| Yuiko  | BNB(Binance)    |
| Jan    | Tether (USDT)   |
| Antoni | XRP(Ripple)     |
| Victor | Cardano (ADA)   |
| Manaha | LTC (LIte Coin) |
| Marina | Solano (SOL)    |
| May    | (DAI)           |   
| Ayane  | Zcash (ZEC)     |  
| Yosuke  | USD COIN  (USDC)  | 
| Naomi  |  TRX Tron       |  
| Amine  |  KLIMA          |

✩࿐  ⊹˚. ♡

An example of the data stored is 

| Date | Description | Category | Amount  |
|------|-------------|----------|---------|
| Sep 23 2022 | bought a house | Expenses | 10 BTC |
| Sep 24 2022 | food for house celebration | Food | 0.000001 BTC |

✩࿐  ⊹˚. ♡

## Proposed Solution

Design statement:
I will to design and make a digital ledger for a client who is Ms Sato . The Digital Ledger will about Solana and is constructed using the software Python. It will take until Oct 2 to make and will be evaluated according to the criteria below.

✩࿐  ⊹˚. ♡

<img src="https://github.com/marinamen/CS2023/blob/main/unit%201/pictures/Solana_logo-min.png" width=10% height=10%>

**Why Solana**

Solana is a blockchain platform designed to host decentralized, scalable applications. Founded in 2017, it is an open-source project currently run by Solana Foundation based in Geneva, while the blockchain was built by San Francisco-based Solana Labs. I chose Solana due to its high speed transaction rate with significant lower transaction rates than  classic competitors like Ethereum. It uses the ticker symbol **SOL** and had almost 12,000% and at one point had a market capitalization of over $66 billion, making it the fifth-largest cryptocurrency by this measure at the time.

*Faster, Cheaper and a look towards the Future*

Solana can handle 30,000 transactions per second whereas Bitcoin only handles 7TPS and Solana's closest competitor Ethereum handles 20TPS, as hardware technology speed increases so does Solana's. Transactions Fees are only *$0.000125*　which allows for more benefit from my Client no matter the expertise whereas "rivaling" cryptocurrencies such as DOGE costs *0.6$* and BNB has a *0.5%* Fee for 10$ minimum transactions and an additional whopping *3.75%* if use of Debit Card. Although currency's like Tether, DAI and USDC are considered stablecoins, they are only used to hold value and not have as much versality as Solana. Solana, a versatile blockchain platform, holds promise for the future due to its adaptability for decentralized applications.*Its innovative consensus mechanism, decentralization, and an active developer community enhance its appeal for development and younger generations therefore solana's ability to cater to a wide range of dapps use cases and maintain network security position it as a competitor for the future of blockchain technology and decentralized ecosystems.*


[What is Solana - Forbes](https://www.forbes.com/advisor/investing/cryptocurrency/what-is-solana/)

[Why Solana is the one to watch in 2023 - Disruption Banking](https://www.disruptionbanking.com/2023/03/27/why-solana-is-the-one-to-watch-in-2023/)


✩࿐  ⊹˚. ♡


**Justify the tools/structure**

I will plan and make a computerized and simple to utilize crypto record for Sato san a nearby client who is a starting altcoiner . he digital ledger will consist of seven separate programs with a total of about 456 lines and 3 databases storing following data(1. User information ,2.Transactions, 3. Solana Realtime value saved from the CCXT library).
 which all come together in one program with exception of the functions , having the functions in another program and separating it will greatly facilitating debugging erros, which appeared quite often . It is built utilizing Python 3.12 on PyCharm and runs on any Mac Terminal that has access to the internet if the success criteria 6 wants to be present. Making it a laptop letter based terminal program simplifies the ledger so that our Client doesn't need any prior experience and the development of the program is much more versatile.

<img src="https://github.com/marinamen/CS2023/blob/main/unit%201/pictures/Python-logo-notext.svg.png" width=10% height=10%>

**Why Python?**

Python is the language that Im developing this digital ledger with, for three main reasons, the first because it is a easy language to manipulate and create with, the second because it has a extensive number of libraries to support my code and third because its a language im quite familiar with. It aligns with the developing values and actually encourages further expansion of it. Easy to learn, the python programming language concatanates our begginer friendly program and high maleability of it.

 *What Within Python*
 
For the libraries I will use matplotlib to make the graph and cxxt to update the currencys real time value, time to add datatime to Solana's value to calculate the average for predicions of whether to Sell or to Buy. To create the code im using Pycharm and I used shortly eclipse with pydev as the python tool. Where I manage my project is my github repository unit, here I document my progress throughout the whole proccess.The digital ledger will consist of seven separate programs with a total of about 456 lines and 3 databases storing following data(1. User information ,2.Transactions, 3. Solana Realtime value saved from the CCXT library).

‧˚₊⋅ ୨୧ ⋅₊˚‧

## Success Criteria

✩࿐  ⊹˚. ♡

1. The electronic ledger is a text-based software (Runs in the Terminal).
2. The electronic ledger display the basic description of the cyrptocurrency selected.
3. The electronic ledger allows to enter, withdraw and record transactions.
4. The electronic ledger will connect to a realtime library that will update the value of Solana every time the program is initiated.
5. The electronic ledger will sort the Transactions in 3 parameters.
6. The electronic ledger will have a visually aesthetic effects, such as kaomojis and colours.
7. The electronic ledger will conver the Currency into 4 different types of currencies plus the option to add any currency. 

✩࿐  ⊹˚. ♡

# Criteria B: Design
![](https://github.com/marinamen/CS2023/blob/main/unit%201/pictures/8ce4bbed258c2b5d02589fd35e38b3b6.gif)

## System Diagram
<img src="https://github.com/marinamen/CS2023/blob/main/unit%201/pictures/Agregar%20texto%20(1).png" width=80% height=80%>
## Flow Diagrams
[image]
**Fig. 1** This is the flow diagram for the login system

![login flowchart](https://github.com/marinamen/CS2023/assets/142757957/bb3163ea-7aa7-4ab0-8b63-66423234354c197fd2)

**Fig. 2** This is the flow diagram for the registration system

![login flowchart](https://github.com/marinamen/CS2023/assets/142757957/bb3163ea-7aa7-4ab0-8b63-66434c1533297fd2)

**Fig. 3** This is the flow diagram for the Sorting System system
![sorting system](https://github.com/marinamen/CS2023/assets/142759957/bb3163ea-7aa7-4ab0-8b63-66434c1323337fd2)

unit testing, integration testing and user acceptance/usability testing



## Test plan
| Task No | Test type              | Specific type                  | Planned outcome                                                                                                                                    | Procedure                                                                                                                             | Outcome                                                                                                                                        |
|---------|------------------------|--------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------|
| 1       | non-functional testing | performance testing            | Identify parts of the algorithm that could be updated to be easier and reduce the total amount of lines without removing functionality.            | Analysed each individual function substituted conditionals with for loops, removed unneccessary feautures, simpified prints           | The outcome was that the procedure was a success, I got rid of 2 while loops and changed them into for loops which a bit faster                |
| 2       | non-functional testing | usability testing              | without majorly shifting the main.py search for difficulties or misunderstandings the user may encounter and solve them                            | Procceeded to test on the user and they shared their concerns, continued by filling the gaps the client pointed out.                  | 2 unclear messages where changed and one print color as well in order to highlight the importance of the message that it stated                |
| 3       | Non-Functional testing | Usability testing              | same as the previous but used another user for more improved feedbac                                                                               | Test user 002 used the program and shared its concerns                                                                                | Added a link for the current SOLANA price to every messages which asks for the real-time price                                                 |
| 4       | Functional testing     | Unit Testing(deposit/withdraw) | See if there is something that can be improved and something that is not working in deposit/withdrawal part of the program and if there is, fix it | Start the program and specificly run the deposit/withdrawal part and depo/withdrawal overview option and see if everything is correct | Found that there was a mistake in the fromula used for porfolio overview for the porfolio change option, and fixed it so now it works properly |
| 5       | Functional testing     | Integration testing            | connect two new options to the main program and see if everything works properly                                                                   | Connect the programs which contain these two features and call them in the main tab program which is connected to thwe main           | Everything worked properly, no problems appeared                                                                                               |
| 6       | Functional testing     | System testing                 | Test the whole program now that it is finally finished and everything should work properly                                                         | Because of the feature of the program to return to the menu tab, testing of every feature will be done in the same run                | Everything worked well no problems occured                                                                                                     |


## Record of Tasks
| Steps | Planned Action                                            | Planned Outcome                                                                                                                                                                     | Time estimate | Target completion date | Criterion |
|-------|-----------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------|------------------------|-----------|
| 1     | Create system diagram                                     | To have a clear idea of the hardware and software requirements for the proposed solution                                                                                            | 10min         | Sep 24                 | B         |
| 2     | Create Basic Description for SOL                          | To have a text at the start of the initiation of the digital wallet, outlining a description of SOL                                                                                 | 10 min        | Sep 26                 | C         |
| 3     | Create a Login System                                     | To have a functioning Login system that the user can use to secure the wallet                                                                                                       | 20min         | Sep 27                 | C         |
| 4     | Test Login System and Add Registration System             | Tested Login and worked, decided to add a regiter user system so that the wallet can begin by creating an account                                                                   | 22min         | Sep 27                 | C         |
| 5     | Test Registration and Add Forgotten Password Feature      | Registration and Login system functional, therefore decided to add a Forgotten Password option                                                                                      | 15min         | Sep 27                 | C         |
| 6     | Create a login system flowchart                           | To create a flowchart that represents the algorithm created.                                                                                                                        | 6min          | Sep 27                 | B         |
| 7     | Create a function that updates SOL realtime by using CCXT | To update SOLs value and print it once every time the program is opened connecting to a binance library ccxt and printing the last trade solana value before the program was opened | 30min         | Sep 28                 | C         |
| 8     | Test Realtime SOL                                         | Encountered a few errors, fixed them and now have a functioning SOL realtime value.                                                                                                 | 18min         | Sep 28                 | C         |
| 9     | Establish a Transaction System with 3 Parameters          | To have a fully functioning transaction system, that has withdrawals, deposits and Balance Display on a menu after the user has logged in.                                          | 30min         | Sep 28                 | C         |
| 10    | Debugging and Finalising Transaction Algorithm            | Debug and incorporate the transaction menu and functions into main.py, add additional features such as different currency display and even personalised currency calculator.        | 17min         | Sep 29                 | C         |
| 11    | Create a Sorting System (1)                               | A functional sorting systems for the transactions in the users digital ledger                                                                                                       | 10min         | Sep 29                 | C         |
| 12    | Decide Sorting System Parameters (2)                      | The sorting system have three parameters, amount, category and date, the user can choose which and reverse sort each                                                                | 15min         | Sep 29                 | C         |
| 13    | Test Sorting System (3)                                   | Only encountered one error, that the transactions were hard to confirm that the date format inputted by the user previously was correct                                             | 5min          | Sep 30                 | C         |
| 14    | Finalize and Incorporate Sorting System (4)               | Finalized the program and fixed the previous error, a program that includes everything that I brainstormed plus the reverse sort search.                                            | 10min         | Sep 30                 | C         |
| 15    | Update GitHub Repository Criteria B                       | Update the Github repository to add all of the documentation for the program and added more visually pleasing graphics.                                                             | 30min         | Sep 30                 | C,B       |
| 16    | Update GitHub Repository Criteria C                       | Update the Github repository to add all of the documentation for the program and added more visually pleasing graphics.                                                             | 30min              | Oct 1                  | C         |
| 17    | Add Encryption system to the password saving proccess     | To have a fully functioning hashing system that encrypts the password to avoid being                                                                                                | 10min               | Oct 1                  | C         |
| 18    | Debug Encryption System Errors                            | To successfully debug the few errors I found when coding the hashing system.                                                                                                        | 15min              | Oct 1                  | C         |
| 19    | Test Encryption System functionality                      | Check if the hashing system is functioning via printing the hashed password to see if it fully works and then use the verify command with the user.                                 | 10min              | Oct 1                  | C         |
| 20    | Incorporate Encryption System into main.py                | Fit the encryption into the registration and login functions and check functionality.                                                                                               | 12min              | Oct 2                  |  C         |
| 21    | Plan Graphing Transaction History                         | Write down the main transaction graph ideas and steps and then structure the layout of the code.                                                                                    |    23min           | Oct 2                  |     C      |
| 22    | Test Graphing Transaction History using matplotlib        | After Finishing the algorithm, I run the program and made sure the matplotlib library was used correctly via checking in the official website                                       |    17min           | Oct 3                  |     C      |
| 23    | Debug and Incorporate into main program TGT               | Run the program solving errors and adding small details that added quality to the graph , customised the line graph                                                                 | 5min               | Oct 3                  |    B       |
| 24    | Drew Sorting Diagram Flowchart                            | Made a flowchart of the algorithm of the sorting system since it was a part of the code I wanted to explain in detail.                                                              | 11min              | Oct 3                  |     B      |
| 25    | Remodeled the System Diagram                              | Edited the old system diagram and imprved it by making it on canva.                                                                                                                 | 10min               | Oct 4                  |   C        |
| 26    | Add Solana Coin Description at the start of the code      | Researched solana and wrote a little description with the benefits for the costumer to use SOlana                                                                                   |  5min             | Oct 4                  |   C        |
| 27    | Add code parts that solved problems that the client had       | Have three unique code functions that represent solutions to some parts of the criteria stated by client                                                                            | 10 min        | Oct 5                  | C         |
| 28    | Add Tools used in the program to repository               | Add as many of the tools used in program                                                                                                                                            | 5 min         | Oct 5                  | C         |
| 29    | Finalise Repository                                       | Did all the small details remaining throughout the repository                                                                                                                       | 1 hour        | Oct 5                  | B         |

# Criteria C: Development
![](https://github.com/marinamen/CS2023/blob/main/unit%201/pictures/gif%201.gif)

In order of the Algorithm

## Login System 
‧˚₊⋅ ୨୧ ⋅₊˚‧

Sato san requested a register and login feature, so I delivered using the below:

୨ৎ Functions for both Register and Login.

୨ৎ An option/Functio in case the password was forgotten that validates the User's identity through 2 securiy questions and conditionals.

୨ৎ ASCII art to make the System more visually appealing.

୨ৎ Password encrytiption through hashing using pass lib with an algorithm of pbkdf2_sha256, to secure

୨ৎ Keypress feature , instead of using inputs I imported the keyboard library which inmediately detects keypress to ease the proccess.

To prevent errors in the keypress system I used
```.py
keyboard.read_event(suppress=True)
```
The above function waits for a keypress event and suppresses it to prevent the default behaviour when a key is pressed in other applications or if its used in other moments throughout the program. Why did I use keyboard commands instead of inputs, to make the algorithm more professional and to save time of defining each inputs time, increase functionality in general

I stored all of the users information in a separate csv file called *data.txt*, it stored the data in the format *username, password, security1, security2*. 
It was read using the open function in three different ways **a** which appends the users data during registration, **r** which reads and authenticates the validity of the username and password, and finally **w** which writes and replaces the old password with the new one in the forgot password function.
I also used the Time Library to add more interaction and realistic loading times into the wallet system.


For the hashing of my password I was between hmac and passlib for the password hashing, hmac's weaknesses include that its typical use is for data integrity and authentication since it does not include common security feautures like salting and multiple iterations
Passlib is better than HMAC for password hashing because it provides a dedicated, secure, and user-friendly solution tailored for password storage. Passlib incorporates salting, adaptive hashing, and security best practices, guarding against common attacks like brute force and rainbow tables, ensuring robust password security.


Below is an example of hashing with *pbkdf2_sha256* encryption.

```.py
>>> hash = pbkdf2_sha256.hash("toomanysecrets")
>>> hash
'$pbkdf2-sha256$29000$N2YMIWQsBWBMae09x1jrPQ$1t8iyB2A.WF/Z5JZv.lfCIhXXN33N23OSgQYThBYRfk'
```
The importance if encryption is critical because softwares such as digital ledgers, since security is something that is taken for guaranteed by the client when often it shouldn't. 
When User's data is stored in easily accesible data files, our client's security and value that is held here has great importance therefore hashing is essential.

*The code is displayed below*


‧˚₊⋅ ୨୧ ⋅₊˚‧‧˚₊⋅ ୨୧ ⋅₊˚‧‧˚₊⋅ ୨୧ ⋅₊˚‧‧˚₊⋅ ୨୧ ⋅₊˚‧‧˚₊⋅ ୨୧ ⋅₊˚‧


```.py
from passlib.hash import pbkdf2_sha256
import keyboard

def menu():
    print("\n ♯ menu ೀ :")
    print("1. register")
    print("2. login")

def loading():
    time.sleep(0.5)
    print("⏳")
    time.sleep(1)
    print("⌛️")
    time.sleep(0.5)

def register(username, password):
    with open('data.txt', 'r') as datafile:
        if username in datafile:
            return False
         
    hashedpass = encryption.hash(password)
    with open('data.txt', 'a') as datafile:
        datafile.write(f'{username}:{hashedpass}\n')


def login(username, password):
    with open('data.txt', 'r') as datafile:
        lines = datafile.readlines()
        for line in lines:
            stored_user, stored_pass = line.strip().split(':')
            if username == stored_user:
                if pbkdf2_sha256.verify(password, hashedpass):
                     return True
                else:
                     return False
    

#forgot password function uses two security questions to validate that the correct user forgot their password

def forgot_password():
    username = input("enter your username (to confirm your existence in our database): ")
    found = False
    
    with open('data.txt', 'r') as datafile:
        lines = datafile.readlines()
        for line in lines:
            stored_user, _, security1, security2 = line.strip().split(':')
            if username == stored_user:
                found = True
                break

    if found:
        security1_answer = input(f"what year did/will you graduate school in:  ")
        security2_answer = input(f"where were you raised: ")
        
        with open('data.txt', 'r') as datafile:
            lines = datafile.readlines()
            for line in lines:
                stored_user, stored_pass, stored_security1, stored_security2 = line.strip().split(':')
                if username == stored_user and security1_answer == stored_security1 and security2_answer == stored_security2:
                    new_pass = input("enter a new password: ")
                    print(f"please dont forget your password next time, your new password is{new_pass}")
                    with open('data.txt', 'r') as datafile:
                        all_lines = datafile.readlines()
                    with open('data.txt', 'w') as datafile:
                        for line in all_lines:
                            if line.strip().split(':')[0] == username:
                                datafile.write(f'{username}:{new_pass}:{security1}:{security2}\n')
                            else:
                                datafile.write(line)
                    print("password reset successful!\n")
                    break
            else:
                print("Security questions validation failed. Please try again.\n")
    else:
        print(f"(っ◞‸◟ c \n username not found. please try again.\n")

#calling functions



    menu()
    event = keyboard.read_event(suppress=True)

    if event.event_type == keyboard.KEY_DOWN:
            key = event.name.upper()
    
    if key == '1':
        username = input("enter a username: ")
        time.sleep(1)
        password = input("enter a password: ")
        loading()
        security1 = input("what year did/will you graduate school in: ")
        security2= input("where were you raised: ")
        loading()
        if register(username, password, security1, security2):
            print("registration successful!\n")
            print("˖ ࣪‧₊˚⋆✩٩(ˊᗜˋ*)و ✩")
        else:
            print("registration unsuccessful!, username already in our database, try to log in\n")

    elif key == '2':
        username = input("enter your username: ")
        time.sleep(1)
        password = input("enter your password: ")
        loading()
        if login_user(username, password):
            print(f"welcome, {username}!\n ( ´ ∀ ` )ﾉ ")
        else:
            print(f"󠀠 \n ( • - • ) ... \n󠀠 \n invalid username or password.")
            forgotpass = input("forgot password? (yes/no): ").lower()
            if forgotpass == 'yes':
                forgot_password()
```
‧˚₊⋅ ୨୧ ⋅₊˚‧‧˚₊⋅ ୨୧ ⋅₊˚‧‧˚₊⋅ ୨୧ ⋅₊˚‧‧˚₊⋅ ୨୧ ⋅₊˚‧‧˚₊⋅ ୨୧ ⋅₊˚‧
## Basic Description of Solana

After the user logs in successfully, the basic description of Solana Cryptocurrency is listed as below, it procceeds to list the benefits of solana and also the main upsides of it.

```.py
print("""          💲 ✩ Solana Currency ✩ 💲
    
            ✩ Your Digital Ledger's Trusty Companion ✩

 Solana currency, often denoted as SOL, is a cutting-edge cryptocurrency designed to 
 power your digital ledger and make transactions faster, more efficient, and secure. 
 It's like the digital cash of the future, built for the modern age.
 
✩Lightning-Fast Transactions:✩ 
  Solana is known for its incredible speed. It can handle thousands 
  of transactions per second, ensuring your payments are swift and hassle-free.

✩ Low Transaction Costs : ✩
  Sending and receiving SOL is cost-effective, 
  making it ideal for both large and small transactions. 
  Say goodbye to hefty fees!

✩ Security First: ✩ 
 Solana uses advanced encryption and decentralized technology
 to keep your digital ledger safe from fraud and tampering. 
 Your transactions are protected around the clock.

✩ Stability: ✩ 
 SOL has gained a reputation for its stability in the cryptocurrency
 world. You can trust it to retain its value over time.

✩Eco-Friendly:✩
 Solana takes environmental concerns seriously. 
 It's designed to be energy-efficient, so you can enjoy the benefits
 of cryptocurrency without harming the planet.

Using SOL in your digital ledger is like having a 
reliable and fast payment method at your fingertips. 
Whether you're making everyday purchases, investing, or managing your finances, 
Solana currency is here to simplify your digital ledger experience.

Welcome to the world of Solana, where your digital ledger transactions are about to get a whole lot better!



""")

```


## Cryptocurrency Realtime Value

₊˚⊹♡₊˚⊹♡

I agreed with Sato san that I would incorporate a Realtime Value of Solana,I thought about using CoinGecko API value however it would not update realtime like I wanted so instead I did this easily throught the ccxt library:

➀ I initalized the connection to the Binance cryptocurrency exchange using the ccxt library, which is what provides acces to these exchanges
```.py
exname = 'binance'
exchange = getattr(ccxt, exname)()
```
➁ I specified my cryptocurrency that I wanted to extract *SOL* and to which currency I wanted to exchange *USDT*(I know USDT is not the dollar but it is astablecoin that usually gravitates around the value of 1 dolllar) setting it to:
```.py
symbol = 'SOL/USDT'
```
➂ I created the getsolana function that uses the exchanges application programming interface, this basically is a set of rules and tools that allow software applications to interact mutually,
to get the stock data for the specified symbol(*SOL*). Including the last traded price which gives our function the last updated price.
```.py       
stock = exchange.fetch_ticker(symbol)
```
➃ If the function finds that there is no network or any exchange malfunctions, the code just gets the stock data and returns it
```.py       
return stock['last']
```
⑤ However if there is a network or exchange error it justs displays error and the error name recieved from the cctxt
```.py
print(f"network error...: {e}"
```
⑥ Finally if the exchange has gone correctly it stores the solana value in solana_price
```.py
solana_price = getsolana()
```

I also added colours using ANSI values from 
[this website](https://ss64.com/nt/syntax-ansi.html) , I had considering installing colorama but didnt want to have the user download too many libraries, especially when it can be done easily without it.

I also added an option to choose which currency to output the value of solana in, including not saved currencys that simply by adding the name and comparison to the dollar it calculates the solana value in that currency.


*The code is displayed below*


₊˚⊹♡₊˚⊹♡₊˚⊹♡₊˚⊹♡₊˚⊹♡₊˚⊹♡₊˚⊹♡₊˚⊹♡₊˚⊹♡₊˚⊹♡₊˚⊹♡₊˚⊹♡
```.py

import ccxt

print("imported ccxt")
import time
print("imported time")
import keyboard
print("imported keyboard")

def loading():
    time.sleep(0.5)
    print("⏳")
    time.sleep(1)
    print("⌛️")
    time.sleep(0.5)


darkred=\33[31m
darkgreen=\33[32m
default=\33[0m
pink=\33[35m


exname = 'binance'
exchange = getattr(ccxt, exname)()
symbol = 'SOL/USDT'

def getsolana():
    try:
        stock = exchange.fetch_ticker(symbol)
        return stock['last']
    except ccxt.NetworkError as e:
        print(f"{darkred}network error...: {e}{default}")
        return None
    except ccxt.ExchangeError as e:
        print(f"{darkred}unexpected error...: {e}{default}")
        return None

solana_price = getsolana()

if solana_price is not None:
    yn = 0

    while yn == 0:
        print("Press a key to choose a currency:")
        print("A. Euro [̲̅€̲̅(̲̅20̲̅)̲̅€̲̅]\nB. Dollar[̲̅$(̲̅1)̲̅$]\nC. Pound[̲̅£(̲̅10)̲̅£]\nD. Yen[̲̅¥(̲̅1000̲̅)̲̅¥]\nE. Other")
        
        event = keyboard.read_event(suppress=True)
        if event.event_type == keyboard.KEY_DOWN:
            key = event.name.upper()
            if key == 'A':
                euro = solana_price * 0.94
                loading()
                print(f"{darkgreen}SOL value in EUROS is {euro}€{default}")
                yn = 1
            elif key == 'B':
                dollar = solana_price
                loading()
                print(f"{darkgreen}SOL value in DOLLARS is ${dollar}{default}")
                yn = 1
            elif key == 'C':
                pound = solana_price * 0.82
                loading()
                print(f"{darkgreen}SOL value in POUNDS is £{pound}{default}")
                yn = 1
            elif key == 'D':
                yen = solana_price * 149.38
                loading()
                print(f"{darkgreen}SOL value in YEN is ¥{yen}{default}")
                yn = 1
            elif key == 'E':
                xcurrency = float(input("Please input the number that dollars need to be multiplied to get your currency:\nExample: Euros is 0.94 of a dollar "))
                xname = input("What is the name of the currency?")
                xcalc = solana_price * xcurrency
                loading()
                print(f"{darkgreen}SOL value in {xname} is {xcalc}")
                yn = 1
            else:
                loading()
                print(f"{darkred(𖦹 _ 𖦹)...\nError: Invalid choice{default}{default}")
else:
    loading()
    print(f"{darkred}(𖦹 _ 𖦹)...Couldn't fetch the SOL value{default}")


```
₊˚⊹♡₊˚⊹♡₊˚⊹♡₊˚⊹♡₊˚⊹♡₊˚⊹♡₊˚⊹♡₊˚⊹♡₊˚⊹♡₊˚⊹♡₊˚⊹♡₊˚⊹♡

## Sort Transactions 

⋆｡𖦹°⭒˚｡⋆

An additional function I added to increase user functionality, was a method of sorting all of the transactions inputted.
I sorted giving 3 options:

⭒Date

⭒Amount

⭒Category

And the additional 
```.py     

transactions.sort(key=key_function, reverse=reverse)

```

*The Code is Displayed Below*


⋆｡𖦹°⭒˚｡⋆⋆｡𖦹°⭒˚｡⋆⋆｡𖦹°⭒˚｡⋆⋆｡𖦹°⭒˚｡⋆⋆｡𖦹°⭒˚｡⋆⋆｡𖦹°⭒˚｡⋆

```.py 



from datetime import datetime

def sorter(sort_option, reverse=False):
    with open('transactions.txt', 'r') as transfile:
        transactions = transfile.readlines()
    
    if sort_option == 'date':
        while c=1:
        reverse=not reverse
        reverser=int(input("Would you like the transactions to appear from Earliest to Oldest(1) or Oldest to Earliest?(2)))

        if reverser == 1:
            key = lambda transaction: datetime.strptime(transaction.split(',')[0], '%y-%m-%d')
            c=0
        elif reverser == 2:
            reverse=not reverse
            key_function = lambda transaction: datetime.strptime(transaction.split(',')[0], '%y-%m-%d')
            c=0
         else:
            print(f"{darkred}(𖦹 _ 𖦹)...\nError: invalid choice")
            
    elif sort_option == 'amount':
        while c=1:
        reverse=not reverse
        reverser=int(input("Would you like the transactions to appear from most to least(1) or least to most?(2)))

        if reverser == 1:
            key = lambda transaction: float(transaction.split(':')[-1])')
            c=0
        elif reverser == 2:
            reverse=not reverse
            key = lambda transaction: float(transaction.split(':')[-1])
            c=0
         else:
            print(f"{darkred}(𖦹 _ 𖦹)...\nError: invalid choice")

    elif sort_option == 'category':
        while c=1:
        reverse=not reverse
        reverser=int(input("Would you like the transactions to appear from alphabetically(1) or reversed?(2)))

        if reverser == 1:
          key = lambda transaction: transaction.split(':')[1].strip()
            c=0
        elif reverser == 2:
            reverse=not reverse
            key = lambda transaction: transaction.split(':')[1].strip()
            c=0
         else:
            print(f"{darkred}(𖦹 _ 𖦹)...\nError: invalid choice")
        key = lambda transaction: transaction.split(':')[1].strip()
    else:

        print("(𖦹 _ 𖦹)... Error, sorting by date as default")
        key= lambda x: datetime.strptime(x.split(':')[0], '%Y-%m-%d')


    transactions.sort(key=key_function, reverse=reverse)
    
    # Print the sorted transactions.
    print("\n ♯ Sorted Transactions by", sort_option.capitalize(), "ೀ :")
    for t in transactions:
        print(t.strip())






sort_option = input("How would you like to sort your transactions?\nCategory\nAmount\nDate").lower()
sorter(sort_option)

```

⋆｡𖦹°⭒˚｡⋆⋆｡𖦹°⭒˚｡⋆⋆｡𖦹°⭒˚｡⋆⋆｡𖦹°⭒˚｡⋆⋆｡𖦹°⭒˚｡⋆⋆｡𖦹°⭒˚｡⋆⋆｡𖦹°⭒˚｡⋆⋆｡𖦹°⭒˚｡⋆⋆｡𖦹°⭒

## Transaction History Graph

Finally my additional success criteria was a transaction history line graph that I plotted using matplotlib library, and the values of change within each users ledger balance. Not of the amount added each transaction. The algorithm follows a a set of steps of opening the data files, then reading the correct information for the current user and extracting the transaction history, that is formatted in year,month,day, and then matplotlib plots the graph with:
```.py 
plt.show()
```

*The Code is Displayed Below*
```.py 

import matplotlib.pyplot as plt
import datetime

def plot_transactions(stored_user,stored_pass,balance):
    with open('transactions.txt', 'r') as file:
        lines = file.readlines()
    user_transactions = [line.strip().split(',') for line in lines if line.strip().split(',')[0] == username and line.strip().split(',')[1] == password]
    dates = [datetime.datetime.now()] 
    balances = [0]
    for transaction in user_transactions:
        date_str, _, balance_str = transaction
        date = datetime.datetime.strptime(date_str, "%Y-%m-%d")
        balance = int(balance_str)
        dates.append(date)
        balances.append(balance)
    
    plt.figure(figsize=(10, 5))
    plt.plot(dates, balances, marker='o', linestyle='-', color='b')
    plt.title(f"{username}'s transaction historyೀ ")
    plt.xlabel('date')
    plt.ylabel('balance (SOL amount)')
    plt.grid(True)
    plt.show()
```

## Withdrawal, Deposit and Balance System



```.py
beuro=""
bdollar=""
bpound=""
byen=""
            
while True:
print("\nUser Menu:")
print(f"1. Deposit  ✩\n2. Withdraw  ✩\n3. Check Balance  ✩\n4. Sort Transactions  ✩ \n5. Graph of Transactions  ✩\n6. Logout  ✩ ")
menu2 = int(input("Select an option  ೀ : "))
                if menu2 == '1':
                    amount = float(input("Enter the deposit amount: "))
                    deposit(username, amount)
                    print(f"Deposited SOL{amount}. New balance: SOL{show_balance(username):.2f}")
                elif menu2 == '2':
                    amount = float(input("Enter the withdrawal amount: "))
                    if withdraw(username, amount):
                        print(f"Withdrew SOL{amount}. New balance: SOL{show_balance(username):.2f}")
                    else:
                        print("Insufficient balance.")
                elif menu2 == '3':
                    balance = show_balance(username)
                    if balance is not None:
                        currency_input=input("Press a key to choose a currency:\nA. Euro [̲̅€̲̅(̲̅20̲̅)̲̅€̲̅]\nB. Dollar[̲̅$(̲̅1)̲̅$]\nC. Pound[̲̅£(̲̅10)̲̅£]\nD. Yen[̲̅¥(̲̅1000̲̅)̲̅¥])
                        capitalise_cinput=currency_input.upper()
                        if capitalise_cinput == "A":
                            beuro=(balance*solana_price)*0.95
                            print(f"Your currency in SOL is{balance} and its worth{beuro}€")
                        elif capitalise_cinput == "B":
                            bdollar=balance*solana_price
                            print(f"Your currency in SOL is{balance} and its worth${bdollar}")
                        elif capitalise_cinput == "C":
                            bpound=(balance*solana_price)*0.82
                            print(f"Your currency in SOL is{balance} and its worth£{beuro}")
                        elif capitalise_cinput == "D":
                            byen=(balance*solana_price)*148
                            print(f"Your currency in SOL is{balance} and its worth{byen}¥")
                        else:
                            loading()
                            print(f"{darkred(𖦹 _ 𖦹)...\nError: Invalid choice{default}")
                    
                    else:
                        print("Error retrieving balance.")

                elif menu2 == '4':
                    sort_option = input("how would you like to sort your transactions?\nCategory\nAmount\nDate: ").lower()

                    if sort_option in ['category', 'amount', 'date']:
                        sorter(sort_option)
                    else:
                        print(f"{darkred(𖦹 _ 𖦹)...\nError: Invalid choice{default}")
                
                elif menu2 == '5':
                    print("Your graph is being plotted ...")
                    time.sleep(1)
                    print("")
                    plot_transactions(stored_user, stored_pass, balance)
                    
                        
                elif menu2 == '6':
                    print("logging out.")
                    time.sleep(1)
                    loading()
                    print("""
                    
                █████████████████████████████████████
                ███████▀█████████████████████████████
                ██████░░█████████████████████████████
                █████▀░▄█████████████████████████████
                █████░░▀▀▀▀▀███▀▀█████▀▀███▀▀▀▀▀█████
                █████░░▄██▄░░███░░███░░███░░███░░████
                ████░░█████░░███░▄███░░██░░▀▀▀░▄█████
                ████░░████▀░███░░███▀░███░░██████████
                ████░░█▀▀░▄████▄░▀▀▀░▄███▄░▀▀▀░▄█████
                █████▄▄▄███████████░░██████▄▄████████
                ██████████████░▀█▀░▄█████████████████
                ███████████████▄▄▄███████████████████
                █████████████████████████████████████                    
                    
                    
                    
                    
                   """ )
                    break
                else:
                    print("Invalid choice. Please select a valid option (1/2/3/4/5).")
```
