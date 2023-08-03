# wlog
some lines in history    
   export LD_LIBRARY_PATH=/shiyan/app/users/yonghu/pythia8226/lib/:$LD_LIBRARY_PATH
### xrootd     
find /pnfs/shiyan/users/yonghuming/ -type f -name "*caf.root" -print | xargs -I {} pnfs2xrootd {} > data.csv   
