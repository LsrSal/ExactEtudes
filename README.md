# ExactEtudes
Web (or local file in browser) based alternative to MOTU's ClockWorks.

<img width="500" height="400" alt="Screenshot" src="https://github.com/user-attachments/assets/9295c06e-377d-49c9-b467-ec2768ecd1b7" />

Finally, first working concept. Vibe coded with Gemini.
It has persistent local storage for the routing table settings and for MIDI port selection (the one connected to MOTU). I ran it as local file in Edge. You have to permit your browser to access MIDI on your computer. Then make proper selection of it, if you have more than one MIDI interface ("cable") on your computer.
MIDI in browser will only work from local file or from HTTPS. Will not work from plain unsecured HTTP.
So far tested only with original MTP from ~1990.
I have tested it by inserting message into Mac's RS422 serial interface as straight MIDI SysEx. I have heard that MTP AV, and probably MTP II as well, may take configuration SysEx on external ports 1 and 8 only. I have not tried yet to insert it into external ports of my MTP. (Anybody like to donate some old MOTUs for further development?)

For my development use my DuraMIDI USB adapter. Latest firmware has feature on Port 8 where any SysEx will get passed to the interface unaltered and pass back whatever is replied.

Please try it with your MOTU or Opcode and report.

___________________________________

I may not be able to continue development on GitHub because of soon to be enforced here 2FA. Hopefully discussion/chat will not be affected.
