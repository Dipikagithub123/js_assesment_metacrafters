/* 
// Metacrafters - Beginning Javascript
//
// This is a javascript playground for testing your javascript code!
// When you are ready to test, simply right click and select "Run Code"
// to see the result print below. If you have more then one snippet of code,
// you can highlight the code you want to test, and then right click and select "Run Code"
*/
// Enter your code below this line
// Code example
1. Create a variable that can hold a number of NFT's. What type of variable might this be?
2. Create an object inside your mintNFT function that will hold the metadata for your NFTs. 
   The metadata values will be passed to the function as parameters. When the NFT is ready, 
   you will store it in the variable you created in step 1
3. Your listNFTs() function will print all of your NFTs metadata to the console (i.e. console.log("Name: " + someNFT.name))
4. For good measure, getTotalSupply() should return the number of NFT's you have created
*/



let nftCollection = [];

function mintNFT(name, description, image) {
    
    const nft = {
        name: name,
        description: description,
        image: image,
        dateCreated: new Date().toISOString()
    };

    
    nftCollection.push(nft);
}


function listNFTs() {
    nftCollection.forEach(nft => {
        console.log("Name: " + nft.name);
        console.log("Description: " + nft.description);
        console.log("Image: " + nft.image);
        console.log("Date Created: " + nft.dateCreated);
        console.log("--------------------");
    });
}


function getTotalSupply() {
    return nftCollection.length;
}


mintNFT(  "DIPIKA TIWARI" , "hello,this is minted by me", "https://example.com/cryptoart1.png");

listNFTs();
console.log("Total Supply: " + getTotalSupply());
