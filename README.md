# medbank-config

`backend.json` tells the MedBank app which server to use. It is signed: the
app ignores any version not signed with the owner's private key, so editing
this file by hand does nothing.

Make a new one with `scripts/backend-switch/sign.mjs` in the MedBank app repo.
