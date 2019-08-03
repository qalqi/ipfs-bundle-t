# ipfs-bundle-t
custom ipfs bundle for browser

## Usage:
install: 
```
npm install -s @tabcat/ipfs-bundle-t
```
create the ipfs node:
 ```
 const IpfsBundle = require('@tabcat/ipfs-bundle-t')
 const ipfs = IpfsBundle()
 ipfs.on('ready', function(){
  //ipfs node ready to use
 })
 ```
 
