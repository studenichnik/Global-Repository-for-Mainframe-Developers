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
Result:
![Result](https://github.com/studenichnik/Global-Repository-for-Mainframe-Developers/blob/master/zOS%20System%20operating/My%20Fork/result.jpg)
