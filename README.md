# CBT780
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 780 is from Daniel F. Gaeta and is an interface to use    *   FILE 780
//*           REXX to create panel-like effects without ISPF.       *   FILE 780
//*                                                                 *   FILE 780
//*                Daniel Gaeta                                     *   FILE 780
//*                MVS System Programmer                            *   FILE 780
//*                dfgaeta@br.ibm.com                               *   FILE 780
//*                                                                 *   FILE 780
//*    Recently I needed to use panels in REXX without ISPF         *   FILE 780
//*    interface. I have developed a small driver to use            *   FILE 780
//*    TPUT/TGET macros and Rexx variable service (IKJCT441).       *   FILE 780
//*                                                                 *   FILE 780
//*    This is a small driver to use TPUT/TGET macro under          *   FILE 780
//*    REXX language.  The RX3270 can be used to build a 3270       *   FILE 780
//*    datastream under TSO sessions.                               *   FILE 780
//*                                                                 *   FILE 780
//*    There are some REXX variables to interface with RX3270:      *   FILE 780
//*                                                                 *   FILE 780
//*    RX3270_INMAP  (input buffer, basically a 3270 datastream)    *   FILE 780
//*    RX3270_OUTPUT (output buffer, needs a parse fields)          *   FILE 780
//*    RX3270_AID    (exception key, for example, ENTER, PFxx,      *   FILE 780
//*                  PAx and CLEAR)                                 *   FILE 780
//*                                                                 *   FILE 780
//*    The RXMAPR member from CBT xmit is small sample to use       *   FILE 780
//*    the function.                                                *   FILE 780
//*                                                                 *   FILE 780
```
