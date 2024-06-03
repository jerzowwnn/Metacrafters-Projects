/*
Assessment Requirements
1. Create a variable that can hold a number of NFT's. What type of variable might this be?
2. Create an object inside your mintNFT function that will hold the metadata for your NFTs. 
   The metadata values will be passed to the function as parameters. When the NFT is ready, 
   you will store it in the variable you created in step 1
3. Your listNFTs() function will print all of your NFTs metadata to the console (i.e. console.log("Name: " + someNFT.name))
4. For good measure, getTotalSupply() should return the number of NFT's you have created
*/

// create a variable to hold your NFT's
const allNFT = []

// this function will take in some values as parameters, create an
// NFT object using the parameters passed to it for its metadata, 
// and store it in the variable above.
function mintNFT (_charName, _sex, _type, _path, _affiliation) {
    const NFT = {
        "name:": _charName,
        "sex:":_sex,
        "type:":_type,
        "path:":_path,
        "affiliation:":_affiliation
    }

    allNFT.push(NFT);
    console.log("NFT Minted:" + _charName);
}

// create a "loop" that will go through an "array" of NFT's
// and print their metadata with console.log()
function listNFTs () {
    for(let index = 0; index < allNFT.length; index++)
        {
            console.log(allNFT[index]);
        }
}

// print the total number of NFTs we have minted to the console
function getTotalSupply() {
    console.log("Total Number of NFTs: " + allNFT.length);
}

// call your functions below this line
mintNFT("Welt", "Male", "Imaginary", "Nihility", "Astral Express");
mintNFT("Jing Yuan", "Male", "Lightning", "Erudition", "Xianzhou Alliance");
mintNFT("Boothill", "Male", "Physical", "The Hunt", "Galaxy Rangers");
mintNFT("Bronya", "Female", "Wind", "Harmony", "Jarilo VI");
mintNFT("Sparkle", "Female", "Quantum", "Harmony", "Masked Fools");

listNFTs();
getTotalSupply();
