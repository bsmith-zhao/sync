SyncFavor is a file synchronize tool, the main functions include: 
sync files, create aead encryption file system, read files by virtual drive

Screenshots:

![](https://github.com/bsmith-zhao/sync/blob/main/doc/main-ndisk.png)

![](https://github.com/bsmith-zhao/sync/blob/main/doc/main-prj.png)

![](https://github.com/bsmith-zhao/sync/blob/main/doc/main-test.png)

Getting start:

1, Add Space
Space mains a collection of configurations include reposits, views, syncs.

Click Toolbar -> AddSpace to add

![](https://github.com/bsmith-zhao/sync/blob/main/doc/add-space.png)

![](https://github.com/bsmith-zhao/sync/blob/main/doc/space-test.png)

2, Add Reposit
Reposit mains a collection of files

Click Toolbar -> AddFolder or AddAead to add

AddFolder: add normal disk folder as reposit

AddAead: add aead(Authenticated encryption with associated data) encryption folder as reposit, 
if the aead conf not exist, the app will automaticly create, you can set some parameters as well

![](https://github.com/bsmith-zhao/sync/blob/main/doc/add-aead.png)

![](https://github.com/bsmith-zhao/sync/blob/main/doc/aead-args.png)

![](https://github.com/bsmith-zhao/sync/blob/main/doc/aead-pwd.png)

![](https://github.com/bsmith-zhao/sync/blob/main/doc/space-reps.png)

3, Create Sync between Reposits
Choose 2 Reposits, first reposit as source and the second as target, 
then click Toolbar -> MasterSync or RoundSync to create

MasterSync: source keeps no change, and target will be sync by the source

RoundSync: source and target will be sync by each other

![](https://github.com/bsmith-zhao/sync/blob/main/doc/add-master-sync.png)

![](https://github.com/bsmith-zhao/sync/blob/main/doc/pick-master-sync.png)

4, Run Sync
Select sync in the diagram, click Toolbar -> Run to run

In the run window, click Parse to preview the run plan, and click Run to actually run

![](https://github.com/bsmith-zhao/sync/blob/main/doc/run-form.png?raw=true)

![](https://github.com/bsmith-zhao/sync/blob/main/doc/parse-result.png?raw=true)

5, Batch Run
If want to run multiple syncs, click Toolbar -> BatchRun to open batch runner

![](https://github.com/bsmith-zhao/sync/blob/main/doc/batch-run.png?raw=true)

<img src="https://github.com/bsmith-zhao/sync/blob/main/doc/batch-run.png" width=50% height=50%>