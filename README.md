# CBT030
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE 030 IS FROM MR SAM GOLOB, AND CONTAINS THE CODE           *   FILE 030
//*           NECESSARY TO CHANGE THE CONSOLE DEFAULT PFKEYS        *   FILE 030
//*           ON MVS SYSTEMS BEFORE THE XA 2.2 LEVEL.               *   FILE 030
//*           SEE THE MEMBER CALLED $$DOC FOR ADDITIONAL            *   FILE 030
//*           INFORMATION.                                          *   FILE 030
//*                                                                 *   FILE 030
//*                 MOD TO CHANGE CONSOLE DEFAULT PFKEYS.           *   FILE 030
//*                                                                 *   FILE 030
//*           ATTENTION MVS SP1.3.X AND SP2.1.X USERS ....          *   FILE 030
//*                                                                 *   FILE 030
//*               NOW YOU DON'T HAVE TO BE SATISFIED WITH IBM'S     *   FILE 030
//*           SELECTION OF *** DEFAULT *** PFKEYS ANYMORE.  YOU     *   FILE 030
//*           CAN SET 'EM THE WAY YOU WANT 'EM, AND THEY WON'T      *   FILE 030
//*           FALL OFF AFTER AN IOGEN.                              *   FILE 030
//*                                                                 *   FILE 030
//*               I'VE CODED 2 SIMPLE USERMODS TO THE SYSGEN MACRO  *   FILE 030
//*           SGIEA2D2 ON AGENLIB.  VERY SIMILAR CODING CAN BE      *   FILE 030
//*           USED EITHER ON SP1.3 OR ON XA.  ONLY THE SEQUENCE     *   FILE 030
//*           NUMBERS ARE DIFFERENT.  THIS IS GOOD AT LEAST UNTIL   *   FILE 030
//*           SP2.2.  AFTER SP 2.2.X AND ESA, THESE MODS ARE        *   FILE 030
//*           NOT NECESSARY, BECAUSE PFKEYS ARE SET IN A PARMLIB    *   FILE 030
//*           MEMBER.                                               *   FILE 030
//*                                                                 *   FILE 030
//*               PLEASE MAKE NOTE OF THE ONE FACT THAT THIS        *   FILE 030
//*           PROCESS SETS ALL CONSOLES WITH THE SAME PFKEYS.       *   FILE 030
//*           AT LEAST YOU CAN GET THE DEFAULTS CLOSER TO WHAT      *   FILE 030
//*           YOU WANT.                                             *   FILE 030
//*                                                                 *   FILE 030
//*               TWO USERMODS ARE SUPPLIED.  THEY WILL HAVE TO     *   FILE 030
//*           BE EDITED AND CUSTOMIZED TO YOUR SHOP.  THEY MUST     *   FILE 030
//*           BE ACCEPTED, TO HAVE AN EFFECT IN A SYSGEN OR         *   FILE 030
//*           IOGEN, UNLESS YOU CONCATENATE THE MTS ABOVE           *   FILE 030
//*           AGENLIB IN YOUR SYSGEN ASSEMBLY JCL.  SAVE A COPY     *   FILE 030
//*           OF THE ORIGINAL MACRO FOR A BACKUP.                   *   FILE 030
//*                                                                 *   FILE 030
//*               JUST USE MY SYSMODS AS MODELS.  COMPARE THEM TO   *   FILE 030
//*           THE VERSION OF MACRO SGIEA2D2 THAT YOU HAVE ON YOUR   *   FILE 030
//*           AGENLIB LIBRARY.  BE VERY CAREFUL WITH THE SEQUENCE   *   FILE 030
//*           NUMBERS, AND IT'D PROBABLY BE BEST TO FOLLOW MY       *   FILE 030
//*           SCHEME CAREFULLY.  GOOD LUCK.                         *   FILE 030
//*                                                                 *   FILE 030
//*               ONE FURTHER NOTE.  THIS USERMOD IS RUNNING ON     *   FILE 030
//*           MY MVS/370 SYSTEM, BUT I AM UNABLE TO TEST THE XA     *   FILE 030
//*           VERSION HERE.  A FRIEND ASSEMBLED AN XA SYSGEN WITH   *   FILE 030
//*           THE "IEBUPDTE"ED MACRO, AND THIS WAS SUCCESSFUL.  I   *   FILE 030
//*           COULDN'T PERSONALLY TEST THE RECEIVE, APPLY, AND      *   FILE 030
//*           ACCEPT OF THE XA USERMOD.  IT'S OK, HOWEVER.          *   FILE 030
//*                                                                 *   FILE 030
```
