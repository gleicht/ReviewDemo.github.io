# TechWriting310B.github.io

_**UW technical writing class => 310**_


## Staging Environments: How to Deploy a Wordpress Staging Site Using Softaculous

### Table of Contents

- [Introduction](#Introduction)
- [Why Use a Staging Site](#Why-Use-a-Staging-Site)
- [How to Create a WordPress Staging Site](#How-to-Create-a-WordPress-Staging-Site)
- [Staging Site Setup](#Staging-Site-Setup)
- [Conclusion](#Conclusion)


### &#x1F539; Introduction 
A staging site serves as a development environment for deploying code changes, updates, and other site changes and/or enhancements prior to deployment to your published site. on your real site. It is the perfect environment for testing all aspects of your site prior to pushing changes to the live site.

A major benefit of using a staging site is that they are private and allow you to introduce changes to your site prior to publishing to the live site. A staging site acts as a private workshop for content creators and coders to perfect their work prior to releasing it publicly. alterations made in the private environment can be perfected prior to rollout to the public site. 

To keep things running smoothly for your website visitors, it pays to use a staging environment. This process allows you to review newly added features thoroughly before making them live so that site users are never exposed to broken or malfunctioning components when updates are rolled out. Additionally, reported errors can be tested and fixed in the staging environment prior to deploying fixes to the production site.

[Return to Top of Page](#Table-of-Contents)

### &#x1F539;Why Use a Staging Site 
A staging environment or staging website is useful in ensuring that your website is operating as intended. It serves as an environment for development and testing prior to public deployment. Using a staging website so you can test out new features without worrying about shutting down or damaging your live website. Not only do they protect against any potential disasters from taking place, but using a staging environment is invaluable in saving both precious hours and energy in website development over the long run.

[Return to Top of Page](#Table-of-Contents)

### &#x1F539;How to Create a WordPress Staging Site  
For this tutorial, Softaculous is recommended a website builder. While other methods of site construction will also work, the Softaculous auto-installer makes the installation process simple and quick. Depending on your hosting provider, Softaculous may or may not be an option. In cases where your hosting provider does not offer Softaculous, an alternative site auto-installer with similar functionality as Softaculous is usually provided. 

[Return to Top of Page](#Table-of-Contents)

### &#x1F539;Staging Site Setup
#### Staging Site Setup
To set up your staging website, perform the following steps:

1.	Create a subdomain off the main domain or create an add-on domain in your hosting account. Please be aware that an add-on domain will require registering an addition domain either with the hosting company or with one of the many domain registration services. Either option will work fine as a staging environment. 
2.	Log into cPanel or your site web hosting control panel and navigate to the Softaculous application installer. If your hosting company does not use cPanel or the Softaculous application, then log into the website management solution your hosting company provides and navigate to the Wordpress installer provided. 
3.	Click on the All Installations icon on the Softaculous install screen. 
4.	Provide the information requested. When all information has been provided, click Create Staging.   
5.	When the installation process is complete, you will be prompted for your log on credentials.
6.	Start building your site.

    For a video tutorial of how to create a staging website using Softaculous, see *https://www.youtube.com/embed/Ep1hxR9vyTQ//*.

[Return to Top of Page](#Table-of-Contents)

### &#x1F539;Conclusion
Using the above process, you can easily set up a staging environment where you can build your website. When you are finished developing your website, click the publish button to publish the staging website to the location of your choice.

[Return to Top of Page](#Table-of-Contents)














<!--Generate: 
```
$ npm run generate
```
- Generates unique images based on the layers in the `/backend/layers` folder.
- WARNING: This command deletes the `/backend/build` folder if it exists!

Rarity (Hashlips): 
```
$ npm run rarity
```
- Calculates the rarity of NFT properties based on layer files.

Rarity (codeSTACKr): 
```
$ npm run rarity_md
```

- Calculates the rarity of NFT properties based on metadata.

Rarity Rank (codeSTACKr): 
```
$ npm run rarity_rank
```

- Provides ranking details through a user interface after calculating using the codeSTACKr Rarity command.

Update Info: 
```
$ npm run update_info
```

- Allows you to update `namePrefix`, `description`, and/or `baseUri` for metadata after it was already generated.

Create Generic Metadata: 
```
$ npm run create_generic
```

- Creates generic metadata using the settings from the `/backend/src/config.js` file.

Upload Files/Images: 
```
$ npm run upload_files
```

- Uploads all files in the `/backend/build/images` folder.

Upload Metadata: 
```
$ npm run upload_metadata
```

- Uploads all `.json` files in both the `/backend/build/json` folder and, if it exists, the `/backend/build/genericJson` folder as well. 

Deploy Contract: 
```
$ npm run deploy_contract
```

- Deploys a contract to the blockchain using the settings from the `/backend/src/config.js` file.

Get Contract: 
```
$ npm run get_contract
```

- Gets the deployed contract details including the contracts ABI using the transactions hash from the Deploy Contract command.

Update Contract:
```
$ npm run update_public_mint_start_date
$ npm run update_presale_mint_start_date
$ npm run update_presale_whitelisted_addresses
$ npm run update_presale_whitelisted_addresses_remove
$ npm run update_royalty_share
$ npm run update_royalty_address
$ npm run update_base_uri
$ npm run update_prereveal_token_uri
```

- Updates specific fields of the contract using the settings from the `/backend/src/config.js` file.
- Available fields to update:
  - `prereveal_token_uri` - This will update the pre-reveal token uri for all NFTs. (Hidden image)
  - `base_uri` - This will update the base uri for all NFTs and reveal all.
  - `public_mint_start_date` - Eg: 2022-02-08T11:30:48+00:00
  - `presale_mint_start_date` - Eg: 2022-02-08T11:30:48+00:00
  - `presale_whitelisted_addresses` - Adds address(es) to the whitelist
  - `presale_whitelisted_addresses_remove` - Removes address(es) from the whitelist
  - `royalties_share` - Updates the royalty share
  - `royalties_address` - Updates the royalty wallet address

Refresh OpenSea: 
```
$ npm run refresh_os --start=1 --end=100
```

- Refreshes the listing for the specified editions on OpenSea.
- Both the `--start` and `--end` flags are required.

## Conclusion

- Update the `frontend/js/abi.js` file with the ABI from `backend/build/contract/_contract_abi.json`.
- Update your information in the `frontend/js/constants.js` file.
- Deploy your dApp to Netlify. (Reference the video for full instructions.)


## Reference the [main video](https://youtu.be/cLB7u0KQFIs) and [update video](https://youtu.be/-EB2TTQxSWc) for more details.
# Minting DAPP

### MainVideo

🌟 [EASY Minting dApp | Whitelisting | Entire Process!! Create an Entire NFT Collection (10,000+)](https://youtu.be/cLB7u0KQFIs)

### Update Video adding Ethereum support!

🚀 [How To Deploy a Smart Contract to Ethereum!! (Updated Minting dApp)](https://youtu.be/-EB2TTQxSWc)

Base art generator code is from [hashlips_art_engine](https://github.com/HashLips/hashlips_art_engine)

Contract uses [NFTPort](https://nftport.xyz)

Join the Discord server for more help from the community: [codeSTACKr Discord](https://discord.gg/A9CnsVzzkZ)

## backend commands

- Clone this repo or download the latest release zip file.
- Unzip, if needed, and open the folder in VS Code.
- From the terminal run: 
```
 cd backend
 npm install
```
- Copy your image layers into the `/backend/layers` folder.
- Use the `/backend/src/config.js` file to set up your layers and NFT information.
