```
//******************************************************//
//*  INSTRUCTIONS:                                     *//
//*  1. REPLACE DSNAME WITH YOUR DATASET NAME          *//
//*
//JCLLIB01 JOB NOTIFY=&SYSUID,MSGLEVEL=(1,1)                  
//STEP1    EXEC PGM=IEFBR14                                   
//ALLOC    DD DSN=DSNAME,DISP=(NEW,CATLG),        
//         RECFM=F,BLKSIZE=80,LRECL=80,SPACE=(TRK,(2,2))
```
