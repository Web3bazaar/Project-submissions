
## Project Submissions

### Submission process

1. Fork project
2. Copy template file into projects folder with name it with your project name
3. Fill file according with table structure


# Project file description

name :  < Name of the project >   
description :   < Small introduction of the project>   
chainId :  < Id of the chain in hex >   
discord : < Discord channel>   
twitter : < Twitter account of channel>    
github  : < Github of the project>   
website : < Project site url>   
banner  : < Banner of the project>    
opensea_collections : < List of the opensea collection owned by the project>     
&nbsp;itens : {   
&nbsp;&nbsp;name : < Name of the project >   
&nbsp;&nbsp;link : < Link for the collection >    
 &nbsp;}   
assets : < List of the contract used by project>   
&nbsp;itens   
&nbsp;&nbsp;{   
&nbsp;&nbsp;&nbsp; projectName     : < Name of the asset >   
&nbsp;&nbsp;&nbsp; tokenImage      : < Image for that asset >    
&nbsp;&nbsp;&nbsp; contractType    : < Type of the contract for that asset options: ERC20|ERC721|ERC1155 >   
&nbsp;&nbsp;&nbsp; decimals        : < Number of decimals places for ERC721 and ERC1155 usually 1 >   
&nbsp;&nbsp;&nbsp; contractAddress : < Addres of the contract >   
&nbsp;&nbsp;&nbsp; apiMetadata     : < Metadata API only applicable for NFT contract ERC721|ERC1155 >   
&nbsp;&nbsp;&nbsp; defaultImage    : < Default image only applicable for NFT. Used when api metadata are unavailable >   
&nbsp;&nbsp; }   
