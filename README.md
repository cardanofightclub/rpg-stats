# Cardano Fight Club NFTs RPG Stats
  ### cardanofightclub.json
      It includes all NFT information of Cardano Fight Club NFT.  All contents in this file are hashed with sha256 encryption and are stored into <b>d0df03edacc8a83e5b6db4de163a1c73924dabf8994c628f043e5e7e.json</b> which is a creater for token metadata.  The hash is the description of this metadata json file.  Anyone could use token-metadata-creator to validate the hash.
  ### d0df03edacc8a83e5b6db4de163a1c73924dabf8994c628f043e5e7e.json
      The NFT policy id is <b>d0df03edacc8a83e5b6db4de163a1c73924dabf8994c628f043e5e7e</b>.  We execute token-metadata-creator command to create the hashed token metadata and ensure the content of cardanofightclub.json consistency
  ### token-metadata-creator
      The token-metadata-creator is for creating the hash and signature and provides the validating function to validate the hash generated by it.  Anyone could get token-metadata-creator from https://github.com/input-output-hk/offchain-metadata-tools/releases.  The validation command is as following:
  ```
  token-metadata-creator validate d0df03edacc8a83e5b6db4de163a1c73924dabf8994c628f043e5e7e.json
  ```