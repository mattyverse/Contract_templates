# Contract_templates
This code was done by Hashlips AKA Daniel Eugene Botha. I did not write this code. I only modified the sections needed to fit my project. If you found this code helpful, make sure you go subscribe to Hashlips on Youtube and follow him on Twitter @de_botha

Edit the code around lines 1100 to 1115 where youll see very clear instructions in CAPS LOCK directly in the code. just replace those parts.

Once you launch the contract you can mint tokens but they won't point to any metadata. Youll have to use the setUri function to point it at the metadata youve uploaded to Pinata or NFT Storage. the string will will start with ipfs:// and then end with the CID of your metadata as well as a /#.json

EX: ipfs://QmZFSTM3xPnNYqEh1SwEPTxnW8uTaKu9TFkNBgPs77VcrF/1.json
