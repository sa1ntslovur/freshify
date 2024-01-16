---
layout: default
title: Training Guide
nav_order: 4
description: "Freshify Training Guide"
permalink: /training-guide
---

# Training Guide
{: .no_toc }


* This guide is designed for **Store Supervisors and above** to aid them in conducting training sessions for trainees.
* Within the *italic text*, you'll find the specific content to be communicated to trainees during the training sessions.
* All other text is information for trainers and other training staff.


#### Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## Training Information & Expectations
{: .text-yellow-300 }

* All staff participating in the training should stand behind the assigned **Host** line. Trainees are expected to stand on the marked **Red** lines.
* PTS requests will be answered until :55. After that time, trainees should direct any questions to their assigned trainer if their PTS requests are not accepted.
* Trainees are strongly advised not to enter the Self Checkout room independently. Only Trainers have the authority to teleport trainees to the Self Checkout room when necessary.
* Training staff MUST hide their commands by using the command bar or typing /e in front of commands followed by pressing enter, and then sending commands there. It's important to note that commands in the command bar do not require a prefix.
* Trainees must be on the marked **Red** lines and comply with all specified regulations.
* Starting at :55, trainees should maintain silence and avoid disturbing other trainees or talking.
* Any instances of trainees spamming the chat or not listening, they will be removed from the server.

{: .warning } 
> Hosts and Trainers must manually assign their teams using the command **:team me Host** or **:team me Trainer**. The display will quickly show the updated team name. Teaming someone other than the assigned Host or Trainer is not allowed. The Host can also assign a Trainer to the Trainer team.

## Role Information
{: .text-blue-100 }

The following section provides details about the various roles in a Freshify training.

| Role        | Description          | Ranks Allowed | Quantity |
|:------------|:--------------------|:--------------|:---------|
| Host        | The Host bears complete responsibility for the entire training session. Their role commences at :40, as they join and unlock the server by :45. Possessing full authority over the training session, the Host exercises the ultimate decision-making power, except when overruled by an SHR. Their duties encompass presenting the introduction to the trainees, ensuring the trainers can effectively instruct the trainees, overseeing the session, and managing additional responsibilities. | Store Manager+  | 1 allowed **per** session | 
| Trainer | The Trainer holds the responsibility of instructing trainees on Freshify's systems, encompassing practical assessments across different areas, such as store departments, as outlined in the guide.   | Store Supervisor+  | 6 allowed **per** session |
| Spectator    | The Spectator will oversee the training session to ensure its smooth and efficient operation.  | Store Moderator+  | No maximum |
| Trainee          | Trainees and Low Ranks are accountable for attentively listening to trainers, adhering to Freshify regulations, and actively participating in the training session. | Awaiting Training, Team Member, Junior Team Member, and Senior Team Member  | No maximum 

## Training Staff: Hiding Commands
{: .text-yellow-300 }

To hide commands, simply add /e before typing your command in the chat bar, or use the command bar by pressing ; on your keyboard. For instance:
> */e :m Hello!*

## Host Script: Starting
{: .text-blue-100 }

When the training starts, the **Host** should **lock** the server to prevent any more **Trainees** from joining. This can be done by typing **:slock** in the command bar or using /e.

The **Host** must announce the prompts below using the **:sm** command. If using the command bar, remove the prefix. It's crucial to promptly send the next announcement after one closes. When using the chat, make sure to use /e before the command.

*Welcome to this Freshify Training Session! I'm (username), your Host for today's session. Pleasure meeting all of you. If it's your first time, a warm welcome, and if you've been here before, welcome back!*

Replace "(username)" with your Roblox username.

*The training procedures and information will be presented now. Please avoid talking or distracting others. Engaging in conversation or causing disruptions may result in your removal from today's training.*

**During the training procedures, Trainers can now proceed to their assigned group for training trainees.** Trainers using the command **:pm %trainer message**. Remember to keep this command hidden by using /e in front of it.

Next, execute the **:traininginfo** command to automatically provide the training procedures and relevant information.

Upon the conclusion of the training information and procedure messages, please convey the following and commence teleporting Trainees to their designated groups.

*sm You will now be teleported into your assigned group, so please be patient. Trainees are NOT permitted to wander around once teleported.*

## Trainer Script
{: .text-red-300 }

When trainees are teleported, start with the script below. **Take your time and don't rush**. If a trainee has a question, let them know to wait until you finish the introduction.

*Hello and welcome to the Freshify Training Session! I'm your trainer, username. Please pick a register and wait for further instructions before doing anything.*

Replace **username** with your Roblox username.

*As mentioned earlier, you'll need to take a quiz at the end of this session. Feel free to use the !notepad command to jot down notes – they'll come in handy during the quiz.*

*Let me know before you go AFK. If you don't, you will be removed from the server. You can go AFK for up to 2 minutes, and you're allowed to go AFK twice during this training.*

*If you get disconnected, you've got 90 seconds to rejoin. If you don't make it in time, you'll need to attend another training session.*

*If I disconnect, please wait for me and don't wander around. If I don't come back, someone else will take over.*

*Do you have any questions? If yes, feel free to ask now. If not, jump to let me know that you're ready to begin.*

## Trainer Script: Voiding Transactions and Items
{: .text-red-300 }

*We're kicking off the training with the Voiding test. Pay full attention, as it will be beneficial for you in the end.*

*Freshify features self-checkout systems that simulate a real-life shopping experience. These checkouts work just like actual checkout systems you encounter in real life.*

*In this test, you need to show me how to void items.*

*To void a single item, either press Store Login or scan your barcode. Then, select Cancel Items and press the button next to the item you want to remove.*

*To void a transaction, either press Store Login or scan your barcode. Next, select Void Transaction and then press Yes.*

*Voiding random transactions without reason is not allowed and may result in a warning or demotion.*

*I'll now scan an item on your register. Please be patient as I do so. Don't take any action unless I instruct you to do so.*

*I scanned the item. Now, you will demonstrate to me how to void a SINGLE ITEM. Questions? Just say PTS. No penalties for not knowing. Please wait as I come to your register.*

*Now, let's move on to voiding the transaction. I'll scan an item on your register. Please wait for further instructions before taking any action.*

*I scanned the item on the registers, now it is your turn to show me how to void a TRANSACTION. Questions? Just say PTS. No penalties for not knowing. Please wait as I come to your register.*

*Congratulations! We will now be doing the Item Approval test.*

## Trainer Script: Item Approval
{: .text-red-300 }

*Now, we'll proceed with the Item Approval test. Please pay full attention.*

*Certain items in the store need staff approval. To handle this, scan your barcode and then press Yes or No on the screen as instructed.*

*To approve a transaction, ask the customer for identification by saying, 'Can I see some identification?' If they provide it, press Store Login, scan your barcode, and then press Yes.*

*To reject a transaction, press Store Login, scan your barcode, and then press No. Make sure to say 'Can I see some identification?' before rejecting it.*

*I'll scan an item on your register. Please be patient as I do so. Follow instructions and refrain from taking any action until directed by me.*

*I scanned the item on the registers, now it is your turn to show me how to ACCEPT a transaction. Questions? Just say PTS. No penalties for not knowing. Please wait as I come to your register.*

*Now, let's move on to denying the transaction. I'll scan an item on your register. Please wait for further instructions before taking any action.*

*I scanned the item on the registers, now it is your turn to show me how to DENY a transaction. Questions? Just say PTS. No penalties for not knowing. Please wait as I come to your register.*

*Congratulations! We will now be doing the Quiz.*

## Trainer Script: Quiz
{: .text-red-300 }

*I will provide you with 3 questions. To pass this training session, you must answer at least two out of three correctly. Feel free to use the notes you took to assist you.*

Now, you can use the **:pm** command to send questions to the trainees. Make sure the questions are clear and not overly difficult. Here are some examples:

1. How do you approve a transaction?
1. How do you deny a transaction?
1. As an LR, are you required to use proper grammar at the store or training center?


The **:pm** command must stay hidden.

**IF THEY PASS:**
*Congratulations on successfully completing today's training session! Please follow me to the ranking line.*

**IF THEY FAIL:**
*Unfortunately, you did not pass the training session. No worries, as we have other training sessions available!*

The training session can now conclude, and you can shut down the server by saying **:shutdown**.









