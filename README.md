# Covid1984 Green Pass Generator

Just for fun. No fraud intended

### Important note

I thought the following would be obvious to everyone, but considering the amount of people who reached out to me privately, apparently it's not.

I posted this code just for education purposes, it can create plausible Green Pass QRs in a (mostly) correct format which are parsed correctly by the checker apps (at least the ones I tried) but obviously **no one but who has one of the "authorized" key pairs** will ever be able to generate valid signatures.

It's cryptography, there's no magic trick. You can see also in the example image that the signature verification fails.

![Green Pass QR](res/qr.png "Green Pass QR")
![Your Government](res/thegovt.png "Your Government")

