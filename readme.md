
## Project Submissions

### Submission process

1. Fork project
2. Copy template file into projects folder with name it with your project name
3. Fill file according with table structure


# Project file description

name :  < Name of the project >   
description :   <small introduction of the project>   
chainId : <id of the chain in hex>   
discord : <discord channel>   
twitter : <twitter account of channel>    
github  : <github of the project>   
website : <project site url>   
banner  : <banner of the project>    
opensea_collections : <list of the opensea collection owned by the project>     
    itens : {   
      name : <name of the project>   
      link : <link for the collection>    
    }   
assets : <list of the contract used by project>   
  itens   
  {   
    projectName     : <Name of the asset>   
    tokenImage      : <Image for that asset>    
    contractType    : <Type of the contract for that asset options: ERC20|ERC721|ERC1155>   
    decimals        : <Number of decimals places for ERC721 and ERC1155 usually 1>   
    contractAddress : <Addres of the contract>   
    apiMetadata     : <Metadata API only applicable for NFT contract ERC721|ERC1155 >   
    defaultImage    : <Default image only applicable for NFT. Used when api metadata are unavailable>   
  }   
