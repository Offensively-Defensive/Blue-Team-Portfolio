I Almost Fell for a Bank Vishing Scam

🧠 Background
On a Sunday afternoon, I answered a phone call that appeared on Caller ID to be from my bank. What followed was a convincing, well-scripted vishing (voice phishing) attempt that almost got me to hand over my login credentials.

🧾 What Happened
I typically screen unknown calls, but I answered this one because my bank’s name appeared on Caller ID. A man introduced himself as a representative from the fraud department, calling to verify a suspicious charge for $700 in Orlando, Florida. I confirmed the charge wasn’t mine.

He then began listing real purchases I had made earlier that day, supposedly to “verify my transactions” and check for further fraud. That lowered my guard. Hearing the exact amount and vendor of my own purchases made him sound legitimate.

Then he said a new username had been added to my account and read it aloud. It didn’t match mine, so he asked me to “confirm” my real username. I did. He said it was wrong. I gave a corrected version. He told me I’d now receive a confirmation code via text and asked me to read it to him.

As I got the text, my banking app also warned me of an attempted password change.

The text message said:

“Only you should enter this code online. Do not give this code to anyone.”

That confirmed my rising suspicion. I confronted the caller:

“This says not to give the code to anyone.”

He launched into a long, rehearsed explanation, but it didn’t feel right.

So I said:

“No offense, but I don’t trust you. I’m going to hang up and call my bank directly.”

And I did. Unfortunately there were no member services on the weekend.

Minutes later, I got another call from a different number. I answered. Same guy apologizing for disconnecting.

“We didn’t get disconnected. I hung up on you.”

He resumed trying to get the code. I dropped the politeness:

“Oh my god! You’re vishing me!”

He played dumb, pretending not to know what that meant.

“Yes you do! Stop vishing me, bro!”

He tried to regain credibility by telling me to compare the number he called from to the one on the back of my card.

“You can spoof phone numbers. I used to prank call people that way in middle school!”

He threatened to freeze my account unless I gave him the code. The only way to fix it, he claimed, was to go in person to a branch.

“I understand.”

He said I’d lose ATM access and wouldn’t be able to use my card.

“Okay. Do it.”

Then came hold music that was clearly fake. Not my bank. I laughed for 30 seconds and hung up.

🚨 Post-Incident Response
Immediately, I changed the username I'd accidentally revealed. Then I called my bank directly to report the attempt. Cardholder services took my fraud report.

The next day, I contacted member services and changed my password. I asked how the attacker had access to my actual transaction history. They weren’t sure, but we suspected a third-party app might be involved. I was advised to visit a branch for a new card and member number.

🕵🏽‍♀️ Threat Model & Reflection
This attack combined several techniques:

Urgency: “Confirm now or your account will be locked.”

Pretexting: “We’re from your bank’s fraud department.”

Insider Knowledge: Accurate transaction data made it feel real.

Persistence: They called back from a different number to continue.

Intimidation: They threatened to freeze my account.

Manipulation: Asked for my username and 2FA code under the guise of protection.

🧠 Why I Fell for It (Almost)
I let my guard down because the scammer:

Knew real, recent transactions.

Claimed a new username had been added.

Used spoofed Caller ID that matched my bank’s number.

Even though I didn’t give them the 2FA code, I did give away my username. That’s still a risk:

It can be used in brute-force or credential-stuffing attacks.

If reused across sites (as many people do), it can give attackers a major head start.

I now suspect they got my transaction data through a third-party financial app like Plaid, Dave, or CashApp; all of which have had breaches in the past.

🔐 Future Prevention Steps
Enable TOTP-based MFA (Time-Based One-Time Passwords) wherever possible.

Reduce my digital footprint. Audit and unlink third-party financial apps.

Regularly review app permissions and account connections.

Treat every unexpected “support” call with suspicion, even if it looks legit.

Keep security alerts enabled. They are often the first and only warning you’ll get.

❓ Self-Reflection Prompts
Here are the questions I asked myself (and you should too):

What specific moment should have made me hang up immediately?

How much trust did I place in Caller ID, and why?

Why did I feel safe giving my username, and how can I change that thinking?

What apps or services have access to my banking info, and how can I audit them?

How can I make 2FA even more secure and less reliant on SMS?

✅ Final Thoughts
You don’t have to outsmart scammers. You just have to slow down, listen to your instinct, and take back control of the conversation.
