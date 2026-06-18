# About project
- this repo contains omnipay project that is a Multi-Platform Digital Wallet and POS System
- A fintech application that allows users to:

Create accounts and verify identity
Deposit and withdraw funds
Send money to other users
Generate QR codes for payments
Merchants can accept payments via a POS app
View transaction history and analytics
Receive real-time notifications

                    +----------------+
                    | Elixir Backend |
                    | Phoenix API    |
                    | PubSub         |
                    +--------+-------+
                             |
             ---------------------------------
             |               |               |
             |               |               |
      +------+-----+   +-----+------+  +-----+------+
      | React Web  |   | Flutter App |  | KMP Shared |
      | Dashboard  |   | Mobile App  |  | Business   |
      +------------+   +-------------+  | Logic      |
                                        +------------+
                                                |
                                         +------+------+
                                         | Java POS    |
                                         | Merchant App|
                                         +-------------+
l