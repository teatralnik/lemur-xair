Behringer Xair (and x32) devices do not accept OSC Bundles. Only single messages.
Bundles are used in Lemur, which is the great app for making your own interface to control Xair consoles.
Using arduino esp8266 (for example) controller converts osc bundles to single messages for xair and osc messages back to bundles for lemur.
All changes in xair are sent back to lemur via /xremote message.
