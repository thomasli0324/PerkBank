# PerkBankPay
Walk-through guide for Perkbank iOS app

<img width="482" alt="Screenshot 2019-06-21 at 10 28 49 PM" src="https://user-images.githubusercontent.com/49776836/60379889-21766c80-9a6e-11e9-9893-03903bb3a44d.png">

# Prerequisite
1. A MacBook or iMac
2. You computer has already installed Xcode which allows your computer to run the sources code.
        
        a. Open App-store in your computer 
        b. Search for Xcode 
           
3. To download the PerkBankPay zip file and GoogleService-Info.plist here.

# Setting up the environment
1. After you have downloaded the source files , you may need to unzip it.
2. Now you may see the files contain 
3. Open the PerkBank.xcworkspace 
4. Set up the simulator as iphone X , iphone Xs , iphone Xs Max or iphone XR
5. Drag and drop the GoogleService-Info.plist under the PerkBank.
6. Now your Xcode environment will look like.

# Running the app in simulator 
1. After you have set up the simulator , you can run the app by clicking 

        Ctrl + B 
        
# Login page 
For convenience purpose , i helped you to create an account in Firebase so you dont need to signup for an account and you can login by typing 

        ubstest@perkbank.com
        123456
        
Now you can see the home page , your personal account number and balance will be shown

# Functionality 
You can check on the functionality of this app by clicking the button on top-right corner. It is a slide-in menu
1. Home 
2. Stock 
3. Currency
4. Order 

# Home 
Home button displays your personal account information such as your perkbank account and its balance

# Stock
Stock button leads you to the interface where it shows information of the stock.

# Currency 
Currency button leads you to the interface where you can obtain information about the currency exchange rate against Hong Kong Dollar.

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
 
 After you have finished filling in the above fields , you need to input an one-time password.
 For convenience purpose , type 
 
                1234
                
 Now, click Confirm button in the app and your transaction order will be stored in our database.
 
 
# Further improvement in the future
 
1.Stock
At this stage , our app only shows some information of the stock. In the future development, our users can obtain real-time information about the stock market so they can trade or plan for their investment in our app.

2.Currency 
At this stage , the currency interface only shows the information of the currency exchange rate against HKD. In the future development , our users can obtain real-time information about the exchange rate in any currency. 




 
 
                












  

