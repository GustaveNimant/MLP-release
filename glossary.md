# *block*Ring Glossary


### Definitions

#### DHT : Distributed Hash Table

#### Hashes :

    hash
    whash
    bhash
    phash
    
#### PeerId : hash of a public key

#### NID : name space identifier

#### IPFS : InterPlanetary (Immutable) File System

#### IPNS : InterPlanetary (Mutable) Name System
         creates human-readable addresses that can be updated.

         A name in IPNS is the hash of a public key. 
         It is associated with a record containing information about the hash it links to that is '''signed by the corresponding private key'''. 
         New records can be signed and published at any time.

    Example :
     /ipns/QmSrPmbaUKA3ZodhzPWZnpFgcPMFWF4QsxXbkWfEptTBJd
     
#### MFS : Mutable File System 

#### URN : Universal Resource Name
        mutable addresses produced by publish. 
        a kind of IPNS with arbitary address (no peerid)
        for a given ressource or content it creates a global resolvable permanent address.

    Example :
       urn:<name>/<mfs_path>

### functionalities :

  publish : consists in associating the copy of a hash accessible to the public under the peerid name space unique. (NID : name space identifier)

    Example :
     /.brings/shards/d21/brindex.log
     0b9e64cac2b9981c1d: /ipfs/QmR92oBwKRTR882ZPzeYdsn7YaN33PQcHHxRV3n2n5Foxo/Z_block.txt
    
  publishHistory : associates its hash to a version of a mutable file

    Example:
     /.brings/published/history.log 

     QmdHmC48ipAsKSQcaJZ4X6b48b5mxtN5NjNEVrLbTGF8Un: ["/etc/myfile.txt",1595600503]
