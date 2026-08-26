# ExactEtudes (MOTU Clockworks replacement)



<img width="500" height="500" alt="EXACTETUDES_2" src="https://github.com/user-attachments/assets/fe3dcc8b-4a4c-44ac-b8dd-b368047dc569" />
<img width="50" height="40" alt="V1 - proof of concept" src="https://github.com/user-attachments/assets/9295c06e-377d-49c9-b467-ec2768ecd1b7" />


- This HTML app is to replace Clockworks for the ancient MIDI interfaces to support most used function nowadays - MIDI routing. (Anybody still use analog SMPTE?)
- It supposed to work with any modern browser that support MIDI access. (Tested with Edge only.) Best to run from local disk, just drop it on your browser.
- It has improved interface to be comfortable on stage and in studio. All settings are locally saved.
- Has 8 sets of tables. Note that it does not use internal MOTU presets but store it locally and update routing as needed.
- Fully editable interface names.
- It appeared to be working with any vintage MTP, including MTP original, II and AV.
- Tested with  AV: message can be sent through any interface, including, any MIDI port, old MAC port, or USB (on equipped models).
- Tested with original MTP with ancient MAC serial interface (need an adapter, like my DURA_MIDI). May also work through MIDI ports.

Note: if file is not local but server hosted - must be HTTPS, unsecured HTTP does not allow MIDI control.


Please try it with your MOTU or Opcode and report.

(Anybody would like to donate some old MOTUs for further development?)
_______________________________
V3 fixed preset buttons colors, but not much of other testing done so far. Nothing else supposed to change.

V4  Removed log window and instead sent logs to browser's console. 
___________________________________

I may not be able to continue development on GitHub because of soon to be enforced here 2FA. Hopefully discussion/chat will not be affected.
