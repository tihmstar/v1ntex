# v1ntex12
(adapting v1ntex for iOS 12)
In the end it wasn't exactly *just* copy&pasting v0rtex and jelbrekTime :o   
(https://twitter.com/tihmstar/status/1087973240927145984)

---

- tested on 11.2.6
- could work up to 12.1.2
- gets you tfp0

##### Make sure to connect a lightning to headphone jack adapter prior to running this on a device without headphone jack!   
It is by no means necessary, but adds the missing flair ;)


Offsets hardcoded for:
 ```Darwin Kernel Version 17.4.0: Fri Dec  8 19:35:52 PST 2017; root:xnu-4570.40.9~1/RELEASE_ARM64_S5L8960X```   
Get your own if you wanna run it on something else ;)

Note:  
Exploit relies on a specific structure of ipc_port_t, it might be neccessary to update more than *just* offsets, if that changed in iOS 12.

PS: If you run the project *as it is* it might end up in a black screen after the app exits.
Device shouldn't panic, just doublepress the home button to get back to the app launcher and close the app.

Special thanks to:  
@S0rryMybad  
@s1guza  
