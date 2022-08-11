~~~~~~~~~~~~~~~~

//***FILE 022 IS FROM MR MARK HEDGES, FORMERLY OF ADRIA             *   FILE 022
//*           LABORATORIES IN DUBLIN OHIO.  THIS FILE CONTAINS      *   FILE 022
//*           SEVERAL OF THEIR UTILITIES.  THIS FILE IS IN          *   FILE 022
//*           IEBUPDTE SYSIN FORMAT.  FOR ADDITIONAL INFORMATION    *   FILE 022
//*           SEE THE MEMBER CALLED $$DOC.                          *   FILE 022
//*                                                                 *   FILE 022
//*      MARK HEDGES IS NO LONGER AT ADRIA LABORATORIES...          *   FILE 022
//*                                                                 *   FILE 022
//*           CURRENT ADDRESS:  MARK HEDGES                         *   FILE 022
//*                             11951 SENTINEL POINT COURT          *   FILE 022
//*                             RESTON, VA  22091                   *   FILE 022
//*           CURRENT PHONE:    (703) 383-1167                      *   FILE 022
//*                   FAX  :    (703) 383-1168                      *   FILE 022
//*                                                                 *   FILE 022
//*           current email:    mhinva@earthlink.net                *   FILE 022
//*                                                                 *   FILE 022
//*           -ASSEMBLER-                                           *   FILE 022
//*            ADRMCLVL   DETERMINES LEVEL OF DFDSS RUNNING IN      *   FILE 022
//*                       YOUR SYSTEM                               *   FILE 022
//*            CATSTRIP   EXAMINE OUTPUT OF LISTCAT FOR             *   FILE 022
//*                       ICF-CATALOGS - USED IN CONJUNCTION WITH   *   FILE 022
//*                       SASCATS                                   *   FILE 022
//*            DATERC     SETS RRC BASED ON DATE-OF-WEEK            *   FILE 022
//*            DI215      DISPLAY INITIATORS FOR JES 2.1.5/JES      *   FILE 022
//*                       2.1.7                                     *   FILE 022
//*            ICHRIN03   MODULE USED BY RACF IN CREATING THE       *   FILE 022
//*                       STARTED TASK TABLE - THIS IS A MACRO      *   FILE 022
//*                       WITH EXAMPLES TO CODE THIS TABLE          *   FILE 022
//*            IDMSLOGS   PROCESSES IDMS/R SHUTDOWN STATS           *   FILE 022
//*            JOBSTAT    DETERMINES IF JOB/STC/TSO IS CURRENTLY    *   FILE 022
//*                       RUNNING                                   *   FILE 022
//*            MRGJNLOG   MERGES IDMS/R JOURNALS AND LOGS TO        *   FILE 022
//*                       TAPE FILES - NICE                         *   FILE 022
//*            PUTCVRL    PRINT COVER LETTERS FROM SEQUENTIAL PTF   *   FILE 022
//*                       TAPES, NOT TOO THRILLING                  *   FILE 022
//*            RACFPGM    TO GENERATE RACF PROTECTION FOR PROGRAMS  *   FILE 022
//*                       - FOR ALL YOU FOLKS PRE-RACF 1.7          *   FILE 022
//*            RACFST     PROGRAM TO DISPLAY RACF STATUS            *   FILE 022
//*                       INFORMATION:  DSNS, FLAGS, STOR - NICE    *   FILE 022
//*                       IF YOU WANT TO KNOW WHERE ALL RACF 1.7    *   FILE 022
//*                       DATASETS ARE                              *   FILE 022
//*            RESCUE     CREATES A JOB STREAM TO CREATE A          *   FILE 022
//*                       ONE-PACK-SYSTEM - INCLUDES SPOOL, CKPT,   *   FILE 022
//*                       PAGE DATASETS, RACF TOO                   *   FILE 022
//*            ROUTDESC   EXAMPLE OF ROUTING AND DESCRIPTOR CODES   *   FILE 022
//*                       FOR WTO/WTOR'S                            *   FILE 022
//*            SMF5       PROCESSES SMF TYPE 5 RECORDS              *   FILE 022
//*            SMPLIST    PROCESSES OUTPUT OF AN SMP/E 'LIST        *   FILE 022
//*                       FUNCTIONS'                                *   FILE 022
//*            SYSLOG     PROCESSES MVS/XA SYSLOGS FOR SCANNING     *   FILE 022
//*                       AND REPORTING                             *   FILE 022
//*            SYSLOC     USED IN CONJUNCTION WITH SYSLOG:          *   FILE 022
//*                       PROCESSES GDG'S                           *   FILE 022
//*            SYSTAT     EVERYTHING AN MVS SYSTEMS PROGRAMMER      *   FILE 022
//*                       WANTS TO KNOW                             *   FILE 022
//*                       - MY BEST CODE, MUST BE AT LEAST MVS/XA   *   FILE 022
//*                         2.1.3                                   *   FILE 022
//*                       - GIVES IPL INFO, CONTROL BLOCK INFO      *   FILE 022
//*                         (ADDRESSES), MAPS STORAGE AND DRAWS     *   FILE 022
//*                         MAP OF VIRTUAL STORAGE, LISTS ALL APF   *   FILE 022
//*                         DATASETS AND ISSUES A 'LOCATE' TO       *   FILE 022
//*                         CHECK CATALOG STATUS.                   *   FILE 022
//*                       - RUNS AS BATCH/TSO/STC                   *   FILE 022
//*            UCBSVC78   PARM INPUT THAT WRITES 1 LINER ON         *   FILE 022
//*                       AVAILABLE SPACE                           *   FILE 022
//*            UCBSCAN    SCANS ALL SYSTEM UCB'S AND GIVES          *   FILE 022
//*                       'CHANNEL-PATHS'                           *   FILE 022
//*                       - RUNS UNDER TSO, AS A BATCH JOB, OR      *   FILE 022
//*                         STC                                     *   FILE 022
//*                       - GIVES UCB INFO, ISSUES LSPACE SVC       *   FILE 022
//*                       - HAS CLIST.  EASY TO RUN AS STC TO       *   FILE 022
//*                         ISSUE EVERY 8 HRS                       *   FILE 022
//*            UCBTYPES   USED BY MEM(UCBSCAN) TO DETERMINE         *   FILE 022
//*                       DEVICE TYPES                              *   FILE 022
//*            WTONROLL   PROGRAM TO ISSUE WTO'S TO CONSOLE W/O     *   FILE 022
//*                       ROLLING THEM                              *   FILE 022
//*           -SAS 5.16-                                            *   FILE 022
//*            SASCATS    READS OUTPUT OF MEM(CATSTRI#) AND SENDS   *   FILE 022
//*                       IT THROUGH SAS                            *   FILE 022
//*                       - USES A 'LISTCAT ALL' AND CP 'VTOC' AS   *   FILE 022
//*                         INPUT TO                                *   FILE 022
//*                       - GIVE STATS ON ALL VSAM, NONVSAM, AND    *   FILE 022
//*                         ICF-CATALOG INFO                        *   FILE 022
//*            SASDDDEF   A LOGICAL LISTING OF DDDEFS FROM SMP/E    *   FILE 022
//*                       FOR ANY ZONE                              *   FILE 022
//*            SASSMP     READS OUTPUT OF 'LIST FUNCTIONS'          *   FILE 022
//*                       COMMAND, PROCESSING FMIDS                 *   FILE 022
//*            SASSMP     SAS, TO PROCESSES NON-APPLIED SYSMODS     *   FILE 022
//*                       IN ANY CSI ZONE                           *   FILE 022
//*            SASTMS     PROCESSES OUTPUT OF 'TMSGRW' INTO SAS     *   FILE 022
//*                       FOR REPORTING                             *   FILE 022
//*            SASVTOC    SAS/GRAPH TO PROCESS ALL VTOCS BY         *   FILE 022
//*                       DSORG, NOTING FREE SPACE                  *   FILE 022
//*            SMPELIST   PROCESSES OUTPUT '//SMPELIST' FOR A       *   FILE 022
//*                       'LIST FUNCTIONS'                          *   FILE 022
//*            TMSMACRO   PROCESSES OUTPUT OF TMC FROM TMCGRW PGM   *   FILE 022
//*            SASSMF30   PROCESS SMF TYPE 30                       *   FILE 022
//*            - CLIST -                                            *   FILE 022
//*            CLISTSOE   DISPLAYS ALL NEW FUNCTIONS UNDER TSO/E 3  *   FILE 022
//*            SYSTAT$    PROCESS SYSTAT PGM                        *   FILE 022
//*            UCBSCAN$   PROCESS UCBSCAN ROUTINE                   *   FILE 022
//*            ADRMCLVL$  PROCESS DFDSS LEVEL                       *   FILE 022
//*            - ISPF V2.3 PANELS -                                 *   FILE 022
//*            SYSLOG$$   FOR SYSLOG$ CLIST                         *   FILE 022
//*            - ISREDIT MACROS -                                   *   FILE 022
//*            $AMODGEN    BROWSE AMODGEN                           *   FILE 022
//*            $ASMHCL     BUILD ASSEMBLE AND LINK JCL AROUND       *   FILE 022
//*                        SOURCE CODE, OR FOREGROUND               *   FILE 022
//*            $BROWSE     BROWSE FROM EDIT SESSION                 *   FILE 022
//*            $COPY       USE ADVANCED LMCOPY FUNCTION             *   FILE 022
//*            $EXEC       ISSUE THE TSO 'EXEC' COMMAND FOR         *   FILE 022
//*                        CURRENT CLIST ONE IS EDI                 *   FILE 022
//*            $GENER      EXEC IEBGENER                            *   FILE 022
//*            $HASPSRC    BROWSE 'SYS1.HASPSRC'                    *   FILE 022
//*            $IEHMAP     MAP A VOLUME                             *   FILE 022
//*            $JOB        PUT A JOBCARD AND DOCUMENTATION IN       *   FILE 022
//*                        FRONT OF JCL                             *   FILE 022
//*            $JUL        GET TODAY'S DATE                         *   FILE 022
//*            $LC         PERFORM LISTCAT                          *   FILE 022
//*            $LD         PERFORM LISTD ON CURRENT DATASET         *   FILE 022
//*            $LDI        PERFORM LISTDSI ON CURRENT DATASET       *   FILE 022
//*            $LISTLVL    PERFORM LISTCAT LEVEL                    *   FILE 022
//*            $LM         LIST ALL MEMBERS: PGM=LM                 *   FILE 022
//*            $LS         LIST FREE SPACE: PGM=LS; PGM=CLEAR       *   FILE 022
//*            $MACLIB     BROWSE MACLIB                            *   FILE 022
//*            $PEND       PUT A PEND AND EXEC AT THE END OF A      *   FILE 022
//*                        PROC                                     *   FILE 022
//*            $PRINT      USE PRINTOFF TO PRINT CURRENT MEMBER     *   FILE 022
//*            $PROCLIB    EDIT SYS1.PROCLIB                        *   FILE 022
//*            $RECEIVE    BUILD SMP/E JCL TO RECEIVE A             *   FILE 022
//*                        PRODUCT/MAINT                            *   FILE 022
//*            $SPACE      DETERMINE DISK/TAPE BLKSIZE BASED ON     *   FILE 022
//*                        LRECL                                    *   FILE 022
//*                                                                 *   FILE 022
~~~~~~~~~~~~~~~~

