# A fork of backpack-offer-sender that automatically rounds ref values to the nearest 0.11


- This fork will apply an additional 0.05 ref (equivalent to one weapon) to bots that list items with prices not divisible by 0.11.
- When purchasing items, it rounds the ref values up to the nearest 0.11 increment. For example, an item with a ref value of 1.16 will be rounded to 1.22.
- When selling items, it rounds the ref values down to the nearest 0.11 increment. For example, an item with a ref value of 1.16 will be rounded to 1.11.

## One-Click Offer for Backpack.tf

This browser plugin adds a button to backpack.tf listings, which will instantly send your offer as specified by the listing.

### Features

- Adds a Button that sends the offer for you
- Supports both [Classic](https://backpack.tf) and [Next](https://next.backpack.tf) backpack.tf
- Supports practically every buy and sell order
- Makes use of change
- Avoids reusing the same items

### Installation

- Install [Tampermonkey](https://www.tampermonkey.net/)
- [Open the script](https://github.com/HavishH/backpack-offer-sender/raw/main/offer_sender.user.js)
- Click Install

### Usage

- Simply find the blue button on the listing

![listings with buttons](./images/classifieds.png)

- Click

  (The Pros use middle click)

![tradeoffer](./images/tradeoffer.png)

- Wow!

### Disclaimer

The script is well tested and consistently produces correct results.
However, there may be some situations in which the script receives bad information, and produces unexpected results.
This may happen after updates to the backpack.tf or steamcommunity.com websites, or if another extension interferes with this one.

Therefore, make sure to <ins>always double check the offer</ins> before confirming it.

---

Greasemonkey is not supported for now. However, the [Tampermonkey](https://www.tampermonkey.net/) plugin for Firefox does work.

---

### License

MIT
