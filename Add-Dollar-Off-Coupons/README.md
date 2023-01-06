# Safeway: Clip "$1 Off Any" Coupons

Safeway frequently offers "$1 Off Any Produce/Frozen/Yogurt/Cereal/etc" coupons under the Just4U Special Offers section.

If you have multiple accounts, this UI.Vision RPA (formerly Kantu) script a) logs into your account, b) checks for the $1 Off Any offers, c) adds the offer, and d) outputs a .csv file that lists which accounts now have the offer loaded.

It assumes your accounts are sequential (account1@youremail.com, account2@youremail.com, etc) and uses a Loop method to login and log the accounts with offers, but you can also modify it to read your accounts from a .csv file.

Update Line 62 to your Zip Code.
