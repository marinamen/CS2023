# Crypto Wallet 

‧˚₊⋅ ୨୧ ⋅₊˚‧


![](https://github.com/marinamen/CS2023/blob/main/unit%201/pictures/78e154025781802198e0401faa508d9a.gif)

‧˚₊⋅ ୨୧ ⋅₊˚‧

A digital Wallet by Marina Mendieta

‧˚₊⋅ ୨୧ ⋅₊˚‧

# Criteria A: Planning  　
![](https://github.com/marinamen/CS2023/blob/main/unit%201/pictures/734807779ad6cc5b0620359f950d2ff1.gif)

‧˚₊⋅ ୨୧ ⋅₊˚‧ 　 　　 　　　　 　

## Problem definition

Ms. Sato is a local trader who is interested in the emerging market of cryptocurrencies. She has started to buy and sell electronic currencies, however at the moment she is tracking all his transaction using a ledger in a spreadsheet which is starting to become burdensome and too disorganized. It is also difficult for Ms Sato to find past transactions or important statistics about the currency. Ms Sato is in need of a digital ledger that helps her track the amount of the cryptocurrency, the transactions, along with useful statistics. 

Apart for this requirements, Ms Sato is open to explore a cryptocurrency selected by the developer.

✩࿐  ⊹˚. ♡

| Name   | Coin            |   | Name | Coin |
|--------|-----------------|---|------|------|
| Keeler | ETH             |   |      |      |
| Rocky  | DOGE            |   |      |      |
| Yuiko  | BNB(Binance)    |   |      |      |
| Jan    | Tether (USDT)   |   |      |      |
| Antoni | XRP(Ripple)     |   |      |      |
| Victor | Cardano (ADA)   |   |      |      |
| Manaha | LTC (LIte Coin) |   |      |      |
| Marina | Solano (SOL)    |   |      |      |
| May    | (DAI)           |   |      |      |
| Ayane  | Zcash (ZEC)     |   |      |      |
| Yosuke  | USD COIN  (USDC)  |   |      |      |
| Naomi  |  TRX Tron       |   |      |      |
| Amine  |  KLIMA          |   |      |      |

| Dylan  | Monero XMR    |   |      |      |
| Yoshi  | Shiba Inu (SHIB)    |   |      |      |

✩࿐  ⊹˚. ♡

An example of the data stored is 

| Date | Description | Category | Amount  |
|------|-------------|----------|---------|
| Sep 23 2022 | bought a house | Expenses | 10 BTC |
| Sep 24 2022 | food for house celebration | Food | 0.000001 BTC |

✩࿐  ⊹˚. ♡

## Proposed Solution

Design statement:
I will to design and make a ———— for a client who is ———. The ——– will about ———— and is constructed using the software ———. It will take  ———- to make and will be evaluated according to the criteria ———.

** add a description of your coin and citation **

Justify the tools/structure of your solution

‧˚₊⋅ ୨୧ ⋅₊˚‧

## Success Criteria

✩࿐  ⊹˚. ♡

1. The electronic ledger is a text-based software (Runs in the Terminal).
2. The electronic ledger display the basic description of the cyrptocurrency selected.
3. The electronic ledger allows to enter, withdraw and record transactions.
4. The electronic ledger will connect to a realtime library that will update the value of Solana every time the program is initiated
5. The electronic ledger will include a description of the cryptocurrency's value that entails a description of the market so that even if the client has little to no knowledge, decisions such as buying and selling will be more informed
6. The electronic ledger will have a personalised design according to the client preferences. 

✩࿐  ⊹˚. ♡

# Criteria B: Design
![](https://github.com/marinamen/CS2023/blob/main/unit%201/pictures/8ce4bbed258c2b5d02589fd35e38b3b6.gif)

## System Diagram

## Flow Diagrams
[image]
**Fig. 1** This is the flow diagram for the login system

## Record of Tasks
| Task No | Planned Action        | Planned Outcome                                                                          | Time estimate | Target completion date | Criterion |
|---------|-----------------------|------------------------------------------------------------------------------------------|---------------|------------------------|-----------|
| 1       | Create system diagram | To have a clear idea of the hardware and software requirements for the proposed solution | 10min         | Sep 24                 | B         |
| 2       | Create a login System | To have a flow diagram and the code for the login system                                 | 30 min        | Sep 14                 | B, C      |

# Criteria C: Development
![](https://github.com/marinamen/CS2023/blob/main/unit%201/pictures/gif%201.gif)

## Login System 
‧˚₊⋅ ୨୧ ⋅₊˚‧

Sato san requested a register and login feauture, so I delivered using the below:

୨ৎ Functions for both Register and Login.

୨ৎ An option in case the password was forgotten that validates the User's identity through 2 securiy questions.

୨ৎ Pleasing Visuals to make the System more aesthetic.

୨ৎ Keypress feature , instead of using inputs I imported the keyboard library which inmediately detects keypress to ease the proccess.

To prevent errors in the keypress system I used
```.py
keyboard.read_event(suppress=True)
```
The above function waits for a keypress event and suppresses it to prevent the default behaviour when a key is pressed in other applications or if its used in other moments throughout the program.

I stored all of the users information in a separate csv file called *data.txt*, it stored the data in the format *username, password, security1, security2*. 
It was read using the open function in three different ways **a** which appends the users data during registration, **r** which reads and authenticates the validity of the username and password, and finally **w** which writes and replaces the old password with the new one in the forgot password function.
I also used the Time Library to add more interaction and realistic loading times into the wallet system.

*The code is displayed below*


‧˚₊⋅ ୨୧ ⋅₊˚‧‧˚₊⋅ ୨୧ ⋅₊˚‧‧˚₊⋅ ୨୧ ⋅₊˚‧‧˚₊⋅ ୨୧ ⋅₊˚‧‧˚₊⋅ ୨୧ ⋅₊˚‧


```.py

#Login and register function + some used

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
    with open('data.txt', 'a') as datafile:
        datafile.write(f'{username}:{password}\n')

def login(username, password):
    with open('data.txt', 'r') as datafile:
        lines = datafile.readlines()
        for line in lines:
            stored_user, stored_pass = line.strip().split(':')
            if username == stored_user and password == stored_pass:
                return True
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


while True:
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
        register(username, password, security1, security2)
        loading()

        
        print("registration successful!\n")
        print("˖ ࣪‧₊˚⋆✩٩(ˊᗜˋ*)و ✩")

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

    

