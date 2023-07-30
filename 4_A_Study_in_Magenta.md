# A Study in Magenta

The day started like any other one; rolling over and falling out of bed, hitting my head on the nightstand as I did so. This has happened more times than I would like to admit. However this time it was accompanied by a small voice coming from a little flat box seemingly asking “Hello? Are you there?” to which I snapped into Incident Response mode and answered “Yes, how may I help you?” while grabbing a pen and paper as a headache started to creep in.

The voice on the other end of the little flat box told me a heartbreaking story about data loss, bad USB drives, and vacation photos followed by:
“I was told if anyone could recover them, you could.”
“Oh, that's nice, who should I thank for the compliment?”

We agreed to meet at a nice cafe nearby and she would bring all the drives she needed to be recovered, I would bring a short contract, and they would pay 50% upfront plus any expenses capped at $1K with no guarantee as data recovery is difficult. They agreed.

I brought with me some static protection bags, some stickers, and a felt tip pen. They brought a pink USB rust drive, a pink SD thumb drive, and a pink nail polish-covered SDHC card from her pink camera in her pink bag. Unsurprisingly they were also wearing a pink faux fir blazer, pink pants, pink sneakers, and a retro P!NK tour shirt. Also, a pink pen for signing the contract and drive seals.

So started the Study in Magenta. At first, the data recovery effort was like any other, a custom USB cord with the write pins snipped and making sure the write block was enabled on the SDHC card. I decided up front that the SDHC card was going to be the last because of the gunked-up nail polish on it which would need to be cleaned off before it was read. The SD thumb drive I estimated would take the shortest time. So it was time to give that good ol' rust drive a workout.

Plugging the drive into the forensics workstation was uneventful as it didn't power up. The disk didn't spin and a quick test from the voltmeter confirmed power was making it to the plug but after that, on the circuit board, the readings were erratic and inconsistent. Simply, the board was bad and I wasn't going to make any progress until I had a functioning spinning drive. So to make her drive work, I bought another of the same brand, model, and specs, and placed her spindle case into the new drive.

Surprisingly, the first time, it worked and the drive was live. I immediately started imaging the drive and went to work on the SDHC card.

The SDHC card was a slightly different beast, after cleaning off the card I was able to see the problem, it had part of a fold in the middle and a small crack in the outside of the card frame. This time however I wouldn't be able to swap in a new board, I had to come up with some other way. So again, I bought a replacement card, and this time I took it apart to understand how it worked and where the damage was. The SDHC card was made up of two IC chips in the back and a wiring harness up front. Luckily, the wiring harness was what was damaged and both of the chips appeared fine, so I started the process of repairing the wiring harness.

This is as much fun as it sounds, trace two sides of a wire and bridge them with a combination of foil and solder. Half a day later I have a readable SDHC card but it now doesn't fit in any slot because it's put together Frankenstein style. So I grab the new SDHC card and make a series of bridges from its connectors to the old connectors and plug it in.

Voila! So my imaging process begins the magenta drives survive and I arrange a meeting to drop off the retrieved files.

In walks a woman that loves magenta. I hand her the drives all professionally wrapped in electrostatic bags, an invoice for the replacement hardware, and hold onto a third drive containing the results and plug it into my portable workstation, and motion for her to start looking at the retrieved files. Her expression was fantastic, happy to get her memories back.

A slight sly look on her face and a question:

“So the names can't you get the names back?”
“No, unfortunately, that part of the drive wasn't recoverable”
“So can you organize these for me?”
“We never look at the data recovered, principle and rule sorry.”
“Probably for the best.”
