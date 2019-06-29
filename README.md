# PerkBankPay
Walk-through guide for Perkbank iOS app

<img width="482" alt="Screenshot 2019-06-21 at 10 28 49 PM" src="https://user-images.githubusercontent.com/49776836/60379889-21766c80-9a6e-11e9-9893-03903bb3a44d.png">

# Prerequisite
1. A MacBook or iMac
2. You computer has already installed Xcode which allows your computer to run the sources code.
        
        a. Open App-store in your computer 
        b. Search for Xcode 
           
3. To download this repository , click clone or download.

<img width="986" alt="Screenshot 2019-06-29 at 4 17 40 PM" src="https://user-images.githubusercontent.com/49776836/60381567-770c4280-9a89-11e9-9992-1b5db17e5142.png">

# Setting up the environment
1. After you have downloaded the source files , you may need to unzip it.

<img width="771" alt="Screenshot 2019-06-29 at 4 12 08 PM" src="https://user-images.githubusercontent.com/49776836/60381523-b2f2d800-9a88-11e9-8f18-e6e18636a071.png">

2. Now you may see the files 

<img width="771" alt="Screenshot 2019-06-29 at 3 28 30 PM" src="https://user-images.githubusercontent.com/49776836/60381155-c26f2280-9a82-11e9-898b-2a90d4f4195b.png">

3. Open the PerkBank.xcworkspace 

4. Set up the simulator as iphone X , iphone Xs , iphone Xs Max or iphone XR

<img width="460" alt="Screenshot 2019-06-29 at 3 29 14 PM" src="https://user-images.githubusercontent.com/49776836/60381174-0530fa80-9a83-11e9-8c12-97dc3a5d0f04.png">

5. Drag and drop the GoogleService-Info.plist under the PerkBank folder.

<img width="215" alt="Screenshot 2019-06-29 at 4 14 44 PM" src="https://user-images.githubusercontent.com/49776836/60381550-0f55f780-9a89-11e9-98d7-c82b239f9dbd.png">

# Running the app in simulator 
1. After you have set up the simulator , you can build the app by clicking 

        Command + B 
        
2. Then run the app by clicking the arrow button

<img width="460" alt="Screenshot 2019-06-29 at 3 29 14 PM" src="https://user-images.githubusercontent.com/49776836/60381174-0530fa80-9a83-11e9-8c12-97dc3a5d0f04.png">

# Login page 
For convenience purpose , i helped you to create an account in Firebase so you dont need to signup for an account and you can login by typing 

        ubstest@perkbank.com
        123456
        
<img width="377" alt="Screenshot 2019-06-29 at 3 35 42 PM" src="https://user-images.githubusercontent.com/49776836/60381212-97d19980-9a83-11e9-821f-75e3325f8c02.png">

Now click login , your personal account number and balance will be shown.

# Functionality 
You can check on the functionality of this app by clicking the button on top-right corner. It is a slide-in menu

1. Home 
2. Stock 
3. Currency
4. Order 

<img width="373" alt="Screenshot 2019-06-29 at 3 37 11 PM" src="https://user-images.githubusercontent.com/49776836/60381221-d404fa00-9a83-11e9-9a06-61b83aee0bda.png">

# Home 
Home button displays your personal account information such as your perkbank account and its balance

<img width="375" alt="Screenshot 2019-06-29 at 3 38 37 PM" src="https://user-images.githubusercontent.com/49776836/60381237-03b40200-9a84-11e9-8b37-113bd147f3d8.png">


# Stock
Stock button leads you to the interface where it shows information of the stock.

<img width="375" alt="Screenshot 2019-06-29 at 3 40 11 PM" src="https://user-images.githubusercontent.com/49776836/60381249-33fba080-9a84-11e9-886b-82c8ac41cc0d.png">


# Currency 
Currency button leads you to the interface where you can obtain information about the currency exchange rate against Hong Kong Dollar.

<img width="369" alt="Screenshot 2019-06-29 at 3 46 50 PM" src="https://user-images.githubusercontent.com/49776836/60381306-24308c00-9a85-11e9-9e2d-5bb08fc08dcc.png">


# Order [Important]
Now you can check on the order button , a form will automatically display in the simulator.
There are some fields you need to input to process to the next step.

                1. Account Name 
                2. Account Number 
                3. Currency 
                4. Amount 
                5. Value Date
                6. Beneficiary Account Number 
                7. Beneficiary Name
                8. Beneficiary's bank 
              
              
<img width="378" alt="Screenshot 2019-06-29 at 3 48 12 PM" src="https://user-images.githubusercontent.com/49776836/60381318-81c4d880-9a85-11e9-951d-2873226b5aac.png">
 
<img width="372" alt="Screenshot 2019-06-29 at 3 48 27 PM" src="https://user-images.githubusercontent.com/49776836/60381319-84bfc900-9a85-11e9-81fc-e619deff8569.png">

After you have finished filling in the above fields , you need to input an one-time password.
For convenience purpose , type 
 
                1234

<img width="378" alt="Screenshot 2019-06-29 at 3 49 10 PM" src="https://user-images.githubusercontent.com/49776836/60381320-86898c80-9a85-11e9-94e4-5fa72873acb4.png">
                
Now, click Confirm button in the app and your transaction order will be stored in our database.

<img width="373" alt="Screenshot 2019-06-29 at 3 49 20 PM" src="https://user-images.githubusercontent.com/49776836/60381321-87bab980-9a85-11e9-866b-6ac0ef321c13.png">

<img width="1432" alt="Screenshot 2019-06-29 at 3 53 00 PM" src="https://user-images.githubusercontent.com/49776836/60381347-06aff200-9a86-11e9-803f-7edce4006e06.png">


