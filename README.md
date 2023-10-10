SyncFavor is a file synchronize tool, the main functions include: sync files, create aead encryption file system and read files by virtual drive

Screenshots:

![main-ndisk](https://github.com/bsmith-zhao/sync/blob/main/doc/main-ndisk.png)

![main-prj](https://github.com/bsmith-zhao/sync/blob/main/doc/main-prj.png)

![main-test](https://github.com/bsmith-zhao/sync/blob/main/doc/main-test.png)

Getting start:

1, Add Space
Space mains a collection of configurations include reposits, views, syncs.

Click Toolbar -> AddSpace to add

2, Add Reposit
Reposit mains a collection of files

Click Toolbar -> AddFolder or AddAead to add

AddFolder: add normal disk folder as reposit

AddAead: add aead(Authenticated encryption with associated data) encryption folder as reposit, 
if the aead conf not exist, the app will automaticly create, you can set some parameters as well

3, Create Sync between Reposits
Choose 2 Reposits, first reposit as source and the second as target, 
then click Toolbar -> MasterSync or RoundSync to create

MasterSync: source keeps no change, and target will be sync by the source

RoundSync: source and target will be sync by each other



