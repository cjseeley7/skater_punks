# Welcome to Skater Punks, Powered by HashLips 👄

The Skater Punks artwork is based on a project I completed in year 10 Visual Communications, back in 2003. It was a bit of fun reviving my Skater Punks characters into NFT form. 

Step 1. Clone this repo 

Step 2. Replace the Hash lips layers folder with the Skater Punks layers folders

Step 3. Replace the config.js file

Step 4. Replace the main.js file

This has been coded to generate 100 NFTs. This number can be adjusted in the config.js file.

```js
const layerConfigurations = [
  {
    growEditionSizeTo: 100,
    layersOrder: [
      { name: "Head" },
      { name: "Mouth" },
      { name: "Eyes" },
      { name: "Eyeswear" },
      { name: "Headwear" },
    ],
  },
];
```

There are currently 7 unique bodies, 2 hands, 10 heads, 10 eyes 2 features and 4 unique backgrounds. This means you can generate a maximum of 11,200 unique Skater Punks. 

To change the rarity of these characteristics, you need to adjust the name of the individual layer files. See hashlips_art_engine readme file for more information on the naming convention. 

Hope you enjoy minting your own Skater Punk!

Powerpoint Presentation
https://docs.google.com/presentation/d/1UdPzVsDf1rlTXoK0Okeb8xxB1NwrGXjyVZXrnu8QD-8/edit#slide=id.p

Skater Punks Website:
https://skater-punks.herokuapp.com/

