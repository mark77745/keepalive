# keepalive

If like me, your employer checks Microsoft Teams to see if you are at your remote desk, then this Python script is for you!

Annoyingly, Microsoft have recently changed teams so that if you are not typing at your keyboard, it classifies you as "Away". This can be quite annoying when you're sat reading something work-related or on the phone.

I created a C++ application which would get around this and now I've converted this to Python.

This will do two things. Firstly it will pulse the Numlock key to provide keyboard input for Microsoft Teams to classify you as "Available". Secondly, it will put your Windows machine into the right execution state as if it were a PVR. This will keep your PC awake and prevent it going into sleep mode, (useful for those toilet breaks).
