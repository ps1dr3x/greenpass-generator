# Covid1984 Green Pass Generator

Just for fun. No fraud intended

### Important note

I thought it would be obvious to everyone, but considering the amount of people who reached out to me privately, apparently it's not.

I posted this code just for education purposes, it can create plausible QRs in the (mostly) right format which are parsed correctly by the checker apps (at least the ones I tried) but obviously unless the private key of a state is leaked, no one (but who has a recognized key) will never be able to generate a valid signature. It's cryptography. You can see also in the example image here that the signature verification fails.

![Green Pass QR](res/qr.png "Green Pass QR")
![Your Government](res/thegovt.png "Your Government")

