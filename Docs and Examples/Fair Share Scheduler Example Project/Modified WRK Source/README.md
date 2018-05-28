Copyright (c) Microsoft Corporation. All rights reserved. 

This directory contains the WRK files that were modified to implement the "Fair Share Scheduler." To build the modified WRK as a fair share scheduler, copy these files to the directories listed below and recompile the WRK source code:

***

balmgr.c 	goes to WRK-v1.2\base\ntos\ke

ki.h 		goes to WRK-v1.2\base\ntos\ke

ntsapi.h 	goes to WRK-v1.2\public\sdk\inc
 
ps.h 		goes to WRK-v1.2\base\ntos\inc

psquery.c 	goes to WRK-v1.2\base\ntos\ps

thredsup.c 	goes to WRK-v1.2\base\ntos\ke

***