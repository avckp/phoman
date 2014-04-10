PhoMan : Modem Dialer Manager
==========================
A simple shell script to turn wvdial on and off.   

Instead of  

>``sudo wvdial photon``  
>


You need  

>``./phoman 1``
>

Or
>``./phoman run``
>


To stop wvdial use CTRL+C.  

To confirm death of the process use  
>``./phoman 0``  

Or  
>``./phoman kill``

Calling ``./phoman`` without argument will ask for arguments.  
Default carrier is Tata Photon change `$carrier` to according to your carrier in phoman script.