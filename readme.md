
## 👋 About Bazaar's verified assets

Trust is one of the most cheerished values in the [Bazaar](https://web3bazaar.org) so, as part of our commitment to kick scammers out of our beloved communites we are <b>adding a Verified Checkmark to the most famed NFT and DeFi projects out there</b>.
<br>Whithout it, they would certainly be the target of all types of impersonators that would mask their copy-cat contracts under the Bazaar's interface, making you believe you were getting the real deal.

Getting the Checkmark is very straight forward and can be done by a project owner, community member, or supporter. All you need to do is to fill in the application form below and provide the data that will allow us to manually check that project integrity.

## 📜 Application Guidelines

1. [Fork](https://github.com/Web3bazaar/Project-verification/fork) this repository.
2. In the newly created fork, create a copy of the application template [`(Project-verification/application-template.json)`](https://github.com/Web3bazaar/Project-verification/blob/master/application-template.json). If you're using the GitHub web interface, you will need to create a new file and copy the contents of the template inside the new one.
3. Name the new file after your project: `project_name.json.`
4. Fill out the template with the details of your project. The more information you provide, the faster the review. 
5. Once you're done, create a `pull request`. The  request should only contain one new file—the JSON file you created from the template.


### 🤖 JSON file guidelines

>DO NOT CHANGE ANY CHARACTERS ON THE LEFT-SIDE PARAMETERS COMING BEFORE THE ":" SIGN.

Fill in the fields WITHIN `< >` on the right-end of every line with the unique data refering to your project. Whenever a field is not applicable to your project make sure to leave the array empty .

#### A) overview: Provide data relative to the project and community behind it:
- name :  < Name of the project >   
- description :   < Brief description of the project or collection >   
- chainId :  < ID of the EVM network or chain where the contracts are supported(in hexadecimal) >   
- discord : < Project's Discord server invite link>   
- twitter : < Project's Twitter handler>    
- github  : < Project's Github URL>   
- website : < Project's website url>  
- banner  : < A JPEG or PNG (1220:1080) with an offcial image of the project to be added to the trading cards containing assets from it  within the Bazaar's Main Square website >    

#### b) assets:  Provide a list with the smart contract addresses and other data for each asset used within the prohect. You can add as many assets as you wish by pasting the fields below, after the `}` and switching the input data:   
- assetName       : < Name of the asset >   
- tokenImage      : < token ticker (applicable to ERC-20 tokens only)>    
- contractType    : < Type of token contract. (options: ERC20|ERC721|ERC1155) >   
- decimals        : < Number of decimal places used by the token (ERC721|ERC1155 tokens usually have only 1 while ERC-20 have 18 >   
- contractAddress : < Addres of the asset smart contract >   
- apiMetadata     : < URL link to Metadata API (only applicable for ERC721|ERC1155 tokens>   
- defaultImage    : < NFT original image (Provide it only Used when there is no api metadata available) >   
 }   

#### c) opensea_collections (for ERC-721 and ERC-1155 only) :Provide the name and URL links to the OpenSea collections of the NFTs used within the project.    You can add as many assets as you wish by pasting the fields below, after the `}` and switching the input data: 

- name : < Name of the NFT collection >   
- link : < OpenSea collection URL >    
}   

## ✅ Reviewing proccess 

Our Team and community manually review the applications and publish the results of the due diligence in the comments, adding a a recommendation for approval or rejection. Core team will then do the final review and approve the pull request, commiting it to the master branch and automatically deploying the Blue checkmark on all newly verified assets.

Check Verified Projects and their assets' info in the [`(Verified Projects)`](https://github.com/Web3bazaar/Verified-Projects-application/tree/master/projects) folder.
