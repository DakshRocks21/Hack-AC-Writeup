# Poetry Moves

## Desc:  
```
XOR is like poetry.

Well it's not, but I XORed a poem by accident. I don't remember the key, but it was 5 bytes long. Can you help me retrieve it?

Author: I-En

Contents of poem.txt: 1a1d01001c3d525e56436921070f152552264e1a261f1f0f0b2c521b061c2c521b015928521c1b1424171d490a69160e174644782d17591e1b030210281f4f3d1128190a1d092c131d0b74437f653d11281e034e30691100030928000a4e0d21170a4e0d26520e4e0a3c1f020b0b6e014f0a18304d62642d211d1a4e183b064f03163b174f02163f17031759281c0b4e1426000a4e0d2c1f1f0b0b28060a54744320001b1e21521807172d014f0a166901070f122c521b061c69160e1c15201c084e1b3c161c4e162f52220f00657f652f172d521c1b1424171d490a691e0a0f0a2c52070f0d21520e021569060001593a1a001c0d69134f0a183d175463731a1d020b0d201f0a4e0d261d4f06163d521b061c6917160b5926144f061c28040a00593a1a06001c3a5e62643827164f011f3d17014e103a5207070a691500021d6911000309251717071627520b071424550b55744333010a592c040a1c0069140e070b69141d011469140e070b690100031c3d1b020b592d170c021027171c42744330164e1a2113010d1c691d1d4e1728061a1c1c6e014f0d11281c0807172e520c010c3b010a4e0c27061d071424550b557443301a1a593d1a164e1c3d171d001825521c1b1424171d4e0a2113030259271d1b4e1f28160a4274433c001c59251d1c0b59391d1c1d1c3a01060117691d094e0d21131b4e1f281b1d4e0d211d1a4e163e551c1a42447821010b6901070f1525520b0b183d1a4f0c0b28154f1a1126074f191827160a1c5e3a064f0717691a061d593a1a0e0a1c657f6539112c1c4f071769171b0b0b2713034e15201c0a1d593d1d4f1a1024174f1a1126074f090b2605481d0d737f654e591a1d4f021627154f0f0a691f0a00592a13014e1b3b170e1a112c52001c592c0b0a1d592a13014e0a2c1743637369523c0159251d010959251b190b0a690607070a65520e001d690607070a691506181c3a5203071f2c521b01593d1a0a0b57447862643f2513084e103a484f2f3a1a3b1416267900303d117d190a310a39415b1c04
```
## How to Solve
So we can go to dcode and bruteforce the key since we know the length, we get that they key is `49726f6e79`  
If we decode this hex key, we get `Irony`  
Now if we decode the same text with a hex key of Irony, we get
```
Sonnet 18: Shall I compare thee to a summer's day?
By William Shakespeare

Shall I compare thee to a summer's day?
Thou art more lovely and more temperate:
Rough winds do shake the darling buds of May,
And summer's lease hath all too short a date;
Sometime too hot the eye of heaven shines,
And often is his gold complexion dimm'd;
And every fair from fair sometime declines,
By chance or nature's changing course untrimm'd;
But thy eternal summer shall not fade,
Nor lose possession of that fair thou ow'st;
Nor shall death brag thou wander'st in his shade,
When in eternal lines to time thou grow'st:
 So long as men can breathe or eyes can see,
 So long lives this, and this gives life to thee.

Flag is: ACSI{x_0r_Sh4ke_sp34r}
```


Flag: `ACSI{x_0r_Sh4ke_sp34r}`
