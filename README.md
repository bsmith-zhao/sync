SyncFavor is a file synchronize tool, main functions: 
1, synchronize files
2, manage aead encryption files
3, mount to virtual drive

[Screenshots]

![](https://github.com/bsmith-zhao/sync/blob/main/doc/imgs/main-ndisk.png)

![](https://github.com/bsmith-zhao/sync/blob/main/doc/imgs/main-prj.png)

![](https://github.com/bsmith-zhao/sync/blob/main/doc/imgs/main-test.png)

[Getting start]

1, Add Space

Space mains a collection of configurations include reposits, views, syncs.

Click Toolbar -> AddSpace to add

<img src="https://github.com/bsmith-zhao/sync/blob/main/doc/imgs/add-space.png" width=40% height=40%>

<img src="https://github.com/bsmith-zhao/sync/blob/main/doc/imgs/space-test.png" width=40% height=40%>

2, Add Reposit

Reposit mains a collection of files

Click Toolbar -> AddFolder or AddAead to add

AddFolder: add normal disk folder as reposit

AddAead: add aead(Authenticated encryption with associated data) encryption folder as reposit, 
if the aead conf not exist, the app will automaticly create, you can set some parameters as well

<img src="https://github.com/bsmith-zhao/sync/blob/main/doc/imgs/add-aead.png" width=40% height=40%>

<img src="https://github.com/bsmith-zhao/sync/blob/main/doc/imgs/aead-args.png" width=40% height=40%>

<img src="https://github.com/bsmith-zhao/sync/blob/main/doc/imgs/aead-pwd.png" width=40% height=40%>

![](https://github.com/bsmith-zhao/sync/blob/main/doc/imgs/space-reps.png)

3, Create Sync between Reposits

Choose 2 Reposits, first reposit as source and the second as target, 
then click Toolbar -> MasterSync or RoundSync to create

MasterSync: source keeps no change, and target will be sync by the source

RoundSync: source and target will be sync by each other

<img src="https://github.com/bsmith-zhao/sync/blob/main/doc/imgs/add-master-sync.png" width=60% height=60%>

![](https://github.com/bsmith-zhao/sync/blob/main/doc/imgs/pick-master-sync.png)

4, Run Sync

Select sync in the diagram, click Toolbar -> Run to run

In the run window, click Parse to preview the run plan, and click Run to actually run

![](https://github.com/bsmith-zhao/sync/blob/main/doc/imgs/run-form.png)

<img src="https://github.com/bsmith-zhao/sync/blob/main/doc/imgs/parse-result.png" width=60% height=60%>

5, Batch Run

If want to run multiple syncs, click Toolbar -> BatchRun to open batch runner

<img src="https://github.com/bsmith-zhao/sync/blob/main/doc/imgs/batch-run.png" width=80% height=80%>


[Language]

Click Language menu to change language.

Language files store in [lang] dir, files are:

current: the current choosed language
locales.txt: all available OS defined language codes and names list
*.lang: language translate file, must ends with ".lang"

Language translate file can be named by OS defined or any other customized,
but only OS defined name can be used as default if user not choose by hand


[Batch Runner Mode]

Execute sync.exe with [-run] parameter can start in Batch Runner mode, command:

sync.exe -run [space path]

[space path] is optional, if set, only the choose space will be loaded