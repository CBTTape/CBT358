# CBT358
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE 358 is source code for the SYSLOG Storage Program         *   FILE 358
//*           package from Eric Bielefeld of Milwaukee, Wisconsin,  *   FILE 358
//*           as repackaged and completed by Kevin Mitts.           *   FILE 358
//*                                                                 *   FILE 358
//*  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  *   FILE 358
//*                                                                 *   FILE 358
//*     Repackager's Note:                                          *   FILE 358
//*                                                                 *   FILE 358
//*     I'm a heavy user of a lot of CBT products.  I've            *   FILE 358
//*     installed the SOUTSYS product but it was a real pain        *   FILE 358
//*     because there were many pieces missing.  I called and       *   FILE 358
//*     received all the missing pieces from the original           *   FILE 358
//*     writer and have repackaged it.  I have successfully         *   FILE 358
//*     installed it on OS/390 2.9 and z/OS 1.4.  It actually       *   FILE 358
//*     does a fair job of sysout archival.  My client and I        *   FILE 358
//*     were both pleasantly surprised that it worked well          *   FILE 358
//*     under z/OS 1.4.                                             *   FILE 358
//*                                                                 *   FILE 358
//*     So, if it helps, here's the repackaged product.             *   FILE 358
//*     See member $$INSTAL to do the installation.                 *   FILE 358
//*                                                                 *   FILE 358
//*                  Kevin Mitts                                    *   FILE 358
//*                  kevin.mitts@mindspring.com                     *   FILE 358
//*                  913-515-0638 cell                              *   FILE 358
//*                  KevMitts - AIM                                 *   FILE 358
//*                  Kevin Mitts - MSN IM                           *   FILE 358
//*                  kevinmitts - Yahoo IM                          *   FILE 358
//*                                                                 *   FILE 358
//*  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  *   FILE 358
//*                                                                 *   FILE 358
//*     SUBJECT: SYSOUT WRITER UTILITY                              *   FILE 358
//*     FROM: Eric Bielefeld <EBIE@phmining.COM>                    *   FILE 358
//*                                                                 *   FILE 358
//*     Note.  If you think you are missing macros for an           *   FILE 358
//*            assembly, please look for them in member             *   FILE 358
//*            $MACLIB.                                             *   FILE 358
//*                                                                 *   FILE 358
//*     I DON'T KNOW IF YOU HAVE BEEN FOLLOWING IBM-MAIN            *   FILE 358
//*     LATELY, BUT THERE HAS BEEN A DISCUSSION ON UTILITIES        *   FILE 358
//*     FOR PUTTING SYSLOG ON TAPE, OR OTHER MEANS OF KEEPING       *   FILE 358
//*     IT AROUND.  WE HAVE A PUBLIC DOMAIN PROGRAM CALLED          *   FILE 358
//*     SOUTSYS THAT I THINK SOME PEOPLE COULD USE.  I THINK IT     *   FILE 358
//*     WOULD BE A GOOD CANDIDATE FOR THE CBT TAPE.                 *   FILE 358
//*                                                                 *   FILE 358
//*     HERE IS A DESCRIPTION FROM THE INSTALL PDS THAT GIVES A     *   FILE 358
//*     GOOD OVERVIEW OF THE PRODUCT.  WE USE IT AT HARNISCHFEGER   *   FILE 358
//*     TO KEEP ALL OF OUR MESSAGE CLASS OUTPUT AND SYSLOG.  WE     *   FILE 358
//*     KEEP IT ONLINE FOR 8 DAYS, AND THEN IT IS ARCHIVED TO       *   FILE 358
//*     TAPE WHICH WE KEEP UNTIL IT IS 90 DAYS OLD.                 *   FILE 358
//*                                                                 *   FILE 358
//*     BASICALLY, THE SYSTEM USES AN EXIT TO THE EXTERNAL          *   FILE 358
//*     WRITER TO WRITE ALL SYSOUT FOR THE CLASS CHOSEN TO A        *   FILE 358
//*     SEQUENTIAL DISK FILE.  IT KEEPS TRACK OF WHERE EVERY        *   FILE 358
//*     FILE STARTS IN A VSAM FILE, AND WHEN THE  SEQ. DISK         *   FILE 358
//*     FILE IS FULL, COPIES IT TO A DIFFERENT FILE ON DISK AND     *   FILE 358
//*     COMPRESSES IT.  AFTER A PERIOD OF TIME SET BY THE USER,     *   FILE 358
//*     EACH COMPRESSED SEQ. FILE IS MODDED ONTO TAPE.  ISPF        *   FILE 358
//*     PANELS ARE USED TO LOOK AT ANY SYSOUT IN THE SYSTEM.        *   FILE 358
//*     DATA ON TAPE CAN BE PRINTED TO HELD OUTPUT, OR LOOKED       *   FILE 358
//*     AT ONLINE, EXCEPT YOU HAVE TO WAIT FOR THE TAPE MOUNT.      *   FILE 358
//*                                                                 *   FILE 358
//*               Eric Bielefeld                                    *   FILE 358
//*               Sr. MVS Systems Programmer                        *   FILE 358
//*               P&H Mining Equipment Corp.                        *   FILE 358
//*               Milwaukee, WI                                     *   FILE 358
//*               414-671-7849                                      *   FILE 358
//*               EBIE@phmining.com                                 *   FILE 358
//*                                                                 *   FILE 358
```
