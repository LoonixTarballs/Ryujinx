Go fuck yourself, Nintendo!

http://quetzalcoatl.zapto.org:8080/LoonixTarballs/Ryujinx \
(Note: This is running on my own hardware, in my home. If the link doesn't work, try again in a few hours.)

Context for anyone else reading this: Nintendo issued an illegitimate DMCA notice against my repository (among other mirrors of the Ryujinx sources) using fallacious reasons. Nintendo does not have any rights to the source code of Ryujinx nor any valid arguments to be issuing takedown notices, nor am I a US citizen.
I include below an excerpt of the notice:

> **How is the accused project designed to circumvent your technological protection measures?**
> 
> The reported repositories offer and provide access to the Ryujinx emulator or code based on the Ryujinx emulator. The Ryujinx emulator is primarily designed to play Nintendo Switch games. Specifically, Ryujinx illegally circumvents Nintendo’s TPMs [Technological Protection Measures] and runs illegal copies of Nintendo Switch games. Nintendo Switch games are encrypted using proprietary cryptographic keys (prod.keys) which protect against unauthorized access to and copying of the copyrighted games. During operation, Ryujinx necessarily uses unauthorized copies of these cryptographic keys to decrypt unauthorized copies of Nintendo Switch games, or ROMs, at or immediately before runtime without Nintendo’s authorization. Thus, Ryujinx is primarily designed to and unlawfully “circumvent[s] a technological measure that effectively controls access to a work protected under” the DMCA and distribution of Ryujinx constitutes unlawful trafficking in technology that is “primarily designed or produced for the purpose of circumventing a technological measure that effectively controls access” to copyrighted works. 17 U.S.C. § 1201(a)(1) and (2). See also Final Judgment & Permanent Injunction, Nintendo of America Inc. v. Tropic Haze LLC, No. 1:24-cv-00082 (D.R.I. Mar. 6, 2024), ECF No. 11 (finding that the distribution of software which primarily decrypts Nintendo Switch games without authorization violated DMCA anti-trafficking provisions).

These are my answers to these arguments:

>Ryujinx illegally circumvents Nintendo’s TPMs and runs illegal copies of Nintendo Switch games.

Ryujinx is an emulator for the Nintendo Switch platform. As such it runs _any_ software designed for that platform, regardless of how the specific copy was procured. For example, a user might have made perfectly legal backup copy of their game, for use by themselves and no one else. Or, they might use Ryujinx during the development process of software for the Nintendo Switch.

>During operation, Ryujinx necessarily uses unauthorized copies of these cryptographic keys

No. Ryujinx does not care how the cryptographic keys were obtained. I promise, Ryujinx is not smart enough to tell how the keys were obtain, and will will happily work if the user purchases a Nintendo Switch and extracts the cryptographic keys just to give them to Ryujinx. So, again, no, Ryujinx does not "necessarily use unauthorized copies of these cryptographic keys". It _potentially_ uses them, if the user decides to use Ryujinx in that fashion.

>Thus, Ryujinx is primarily designed to and unlawfully “circumvent[s] a technological measure that effectively controls access to a work protected under” the DMCA and distribution of Ryujinx constitutes unlawful trafficking in technology that is “primarily designed or produced for the purpose of circumventing a technological measure that effectively controls access” to copyrighted works.

"Thus"? No, does not follow.\
Premise 1: Ryujinx is a Nintendo Switch emulator.\
Premise 2: Ryujinx needs cryptographic keys from a Nintendo Switch in order to function.\
Conclusion: Therefore Ryujinx is primarily designed to circumvent technological protections.\
Sorry, Nintendo lawyers. Go back to school and learn how to form a valid argument. In the mean time, my mirror is going to stay up.
