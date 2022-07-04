
```json
{
  
  "CONTRACT_ADDRESS": "0xC72FB87EdC2ce1B559f48aa8E5E309e92b334A94",
  "SCAN_LINK": "https://rinkeby.etherscan.io/address/0xc72fb87edc2ce1b559f48aa8e5e309e92b334a94#code",
  "NETWORK": {
    "NAME": "Rinkeby Test Network",
    "SYMBOL": "ETH",
    "ID": 4
  },
  "NFT_NAME": "OkayNFT",
  "SYMBOL": "TB",
  "MAX_SUPPLY": 6666,
  "WEI_COST": 175000000000000000,
  "DISPLAY_COST": 0.175,
  "GAS_LIMIT": 285000,
  "MARKETPLACE": "Opeansea",
  "MARKETPLACE_LINK": "https://opensea.io/collection/",
  "SHOW_BACKGROUND": true

}
```

Make sure you copy the contract ABI from remix and paste it in the `public/config/abi.json` file.
(follow the youtube video if you struggle with this part).

Now you will need to create and change 2 images and a gif in the `public/config/images` folder, `bg.png`, `example.gif` and `logo.png`.

Next change the theme colors to your liking in the `public/config/theme.css` file.

```css
:root {
  --primary: #ebc908;
  --primary-text: #1a1a1a;
  --secondary: #ff1dec;
  --secondary-text: #ffffff;
  --accent: #ffffff;
  --accent-text: #000000;
}
```


