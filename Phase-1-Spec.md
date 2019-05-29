##
Project name: Moltres - Phase 1
##
This project is about building a crypto currency order publishing and 
monitoring platform with nice dashboard and such.
###
Tech stack:
Language of Choice: Python and MySQL
Authentication handled via Google Authenticator
Deploy on Heroku

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

