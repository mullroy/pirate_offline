## Improvements

Not scanning the full blockchain when importing an new address
-- send creation date (block) along with adres, to scan only from that height
-- if you know its a new address without any funds, provide an option to skip the scanning altogether

Sprout:
  Add option to ignore sprout parameters during retrieval of the files (saves +700mb?)
  Update block height when checking out the block chain to start only from sappling addresses
  --For full nodes performing mining, they probabaly require to support
  --sprout up to a hard fork?