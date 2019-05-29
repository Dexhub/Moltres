##
# Moltres - Phase 1
##
This project is about building a crypto currency order publishing and 
monitoring platform with nice dashboard and such.
###
Tech stack:
Language of Choice: Python and MySQL
Authentication handled via Google Authenticator
Deploy on Heroku

Goals: 
- To be able to automatically trigger trades based on price movements.
- Be able to monitor the fund’s overall performance
- Be able to fan out orders across multiple exchanges
- Be able to easily move funds between exchange and cold wallets.
    
Project details:
---------------

Modules:
- Login
    - Admin 
    - Users
- Dashboard:
    - Show current portfolio from different exchanges
    - Place new orders:
        Market and Limit order
        Place advanced orders/Stopwatch and such- Only Good til cancel, 
        Good till expiration (i.e. set expiration date)
    - Notifications: 
        - Order trigger notification 
        - SMS and Email based notification
        - Triggered orders & Good til cancel/Good til expiration orders that expire without completion
        - Price movements
        - Volume movements
    - Open closed orders placed by the user.

Exchanges to support:
 - Coinbase Pro
 - kraken
