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

<img src="https://github.com/bsmith-zhao/sync/blob/main/doc/add-space.png" width=40% height=40%>

<img src="https://github.com/bsmith-zhao/sync/blob/main/doc/space-test.png" width=40% height=40%>

2, Add Reposit

Reposit mains a collection of files

Click Toolbar -> AddFolder or AddAead to add

AddFolder: add normal disk folder as reposit

AddAead: add aead(Authenticated encryption with associated data) encryption folder as reposit, 
if the aead conf not exist, the app will automaticly create, you can set some parameters as well

<img src="https://github.com/bsmith-zhao/sync/blob/main/doc/add-aead.png" width=40% height=40%>

<img src="https://github.com/bsmith-zhao/sync/blob/main/doc/aead-args.png" width=40% height=40%>

<img src="https://github.com/bsmith-zhao/sync/blob/main/doc/aead-pwd.png" width=40% height=40%>

![](https://github.com/bsmith-zhao/sync/blob/main/doc/space-reps.png)

3, Create Sync between Reposits

Choose 2 Reposits, first reposit as source and the second as target, 
then click Toolbar -> MasterSync or RoundSync to create

MasterSync: source keeps no change, and target will be sync by the source

RoundSync: source and target will be sync by each other

<img src="https://github.com/bsmith-zhao/sync/blob/main/doc/add-master-sync.png" width=60% height=60%>

![](https://github.com/bsmith-zhao/sync/blob/main/doc/pick-master-sync.png)

4, Run Sync

Select sync in the diagram, click Toolbar -> Run to run

In the run window, click Parse to preview the run plan, and click Run to actually run

![](https://github.com/bsmith-zhao/sync/blob/main/doc/run-form.png)

<img src="https://github.com/bsmith-zhao/sync/blob/main/doc/parse-result.png" width=60% height=60%>

5, Batch Run

If want to run multiple syncs, click Toolbar -> BatchRun to open batch runner

<img src="https://github.com/bsmith-zhao/sync/blob/main/doc/batch-run.png?raw=true" width=80% height=80%>