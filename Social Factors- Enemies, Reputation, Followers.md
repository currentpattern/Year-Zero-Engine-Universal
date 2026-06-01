## Long-Term Manipulation (Turning)

Shifting an NPC's loyalty permanently is a campaign of sustained influence conducted over multiple sessions of downtime. Unlike short-term MANIPULATION, this process cannot be rushed — it requires days of relationship-building, and abandoning it resets all progress. The underlying mechanic is the same **INFLUENCE: Manipulator vs. INSIGHT: Incorruptible** opposed roll with Negotiating Position modifiers, just played out across time.

---

### Step 1: The GM Sets the Turn Number

The GM secretly determines the **Turn Number** — the total successes on opposed INFLUENCE rolls needed to complete the loyalty shift. It is never revealed to the players directly.

The Turn Number is set by two factors:

**Betrayal Depth** — how much is being asked of this NPC? This Base number is equal to how much of  shift of NPCs Loyalty Score you're trying to cause. E.g. Loyalty 5 to -3 is a shift of 8, "Total" betrayal.

| Depth       | Description                                                                   | Base |
| ----------- | ----------------------------------------------------------------------------- | ---- |
| Minor       | Sharing inconsequential info; mild inconvenience to their current loyalties   | 2    |
| Significant | Leaving service; withholding cooperation from their current master            | 4    |
| Major       | Leaving service, and notable offering aid to enemies of their current master  | 6    |
| Total       | Complete reversal — becoming an devoted enemy of someone they were devoted to | 8    |
**Starting Attitude toward the Manipulator** — how does the NPC currently view the PC?

| Attitude                                                                          | Modifier |
| --------------------------------------------------------------------------------- | -------- |
| Hostile (active enemy, has been wronged by the manipulator, **Loyalty -2,-3**)    | +3       |
| Unfriendly (suspicious, dislikes the manipulator, **Loyalty -1**)                 | +2       |
| Neutral (indifferent, professional acquaintance, **Loyalty 1-0**)                 | +1       |
| Friendly (likes, trusts somewhat, **Loyalty 2-3**)                                | 0        |
| Already sympathetic (secretly wants what the manipulator offers, but is reticent) | −1       |
> **Turn Number = Betrayal Depth Base + Attitude Modifier** (minimum 1)

**Examples:**

- Friendly acquaintance sharing minor info: 2 + 0 = **2 rolls**
- Neutral lieutenant leaving their boss's service: 4 + 1 = **5 rolls**
- Hostile bodyguard becoming an active traitor: 8 + 3 = **11 rolls**
### Step 2: Running a Session

Each attempt requires **1D6 hours** of access to the target. The player must describe the approach — a conversation, shared experience, favor, emotional appeal, leverage applied.

Roll **INFLUENCE: Manipulator vs. INSIGHT: Incorruptible** using all standard **Negotiating Position** modifiers, as well as **-1 per Suspicion point** (see below)

Some Negotiating Position factors relevant to Prisoners:
- _"You have helped your opponent previously"_ — covers providing food, decent treatment, medical care, protecting them from other PCs, etc.
- _"What you ask doesn't cost your opponent anything"_ — could apply if early asks are small (just talk to us, just answer questions)
- _"Your opponent has suffered damage to any attribute"_ — a prisoner who has been physically harmed qualifies, though exploiting this should narratively increase double-agent risk at the GM's discretion 

**Helpers:** Other PCs contributing meaningfully to the session add a bonus die as normal for the help rules.

**Interruption:** If the manipulator goes **3 or more consecutive days** without a session with the target, all Progress (but not Suspicion) resets to 0. Influence is built on sustained contact erodes without it.
#### Success
**Every Success** chips away at the Turn Number, OR may be used to reduce the duration of that session by 1 hour. The GM tracks Progress and Suspicion secretly, and communicates the situation only in story terms, much like describing enemy HP.

| Progress | Example Description                                                  |
| -------- | -------------------------------------------------------------------- |
| None     | _"NPC shows no sign of wavering."_                                   |
| ~25%     | _"NPC seems unsettled and agitated."_                                |
| ~50%     | _"You sense genuine doubt beginning to take hold."_                  |
| ~75%     | _"NPC seems to be leaning your way, though they haven't committed."_ |
| Complete | _"Something has shifted in NPC."_                                    |
PCs may roll **INSIGHT** during or after a session to assess their progress. An NPC may add +1 to **INFLUENCE: Manipulator** for each point of suspicion if they are trying to hide their progress (only likely after Suspicion 3+).
On a **success**, the GM gives a slightly more precise description (such as "Only 2 more sessions like that") and must inform the player if their efforts have irreversibly failed.
On a **failure**, the description may be vague or misleading — which matters enormously when a double agent is involved.

**Victim's Stress**: An NPC with **3+ Suspicion** (such as a prisoner), every **INFLUENCE** **success** against them gives +1D Stress. This means too much success too fast against a prisoner may lead to panic and trauma. Convincing prisoners that they will not be harmed can allow them to REST, and offering them social stress relief can also offset this. An INFLUENCE failure also gives +1 Stress. Torture gives +3 stress per session. 
#### Failure
No progress. NPC gains +1 Suspicion and +1 Stress.
The GM notes this and secretly and considers whether the NPC takes countermeasures (see below).

Rolls may be **pushed** as normal. Each Bane on a pushed roll (success or failure) adds +1 Suspicion to the NPC (see below).

#### Critical Failures 
Any BANE appearing during any failure (pushed or not) counts as a CRITICAL FAILURE, and each adds +1 to the Turn Number (i.e. detracting from progress). This means an unskilled manipulator CAN make things progressively harder, even if there is no final failure state.

---

### Step 3: Suspicion

The GM tracks a hidden **Suspicion** value for the NPC, starting at 0.

Suspicion increases by:
- **+1** on each failed INFLUENCE roll (the NPC sensed something off)
- **+1** per Bane on a pushed roll
- **+2** if the NPC discovers or deduces the manipulator's true intent through other means

**Prisoners and Known Enemies:** Any NPC who knows they are being deliberately worked on (a prisoner in PC custody, or an established enemy who is aware of the manipulator's intent) begins with **Suspicion already at 3**.

Each point of Suspicion adds
- +1 to **INFLUENCE: Manipulator** if the victim is trying to hide their progress.
- **−1** to the manipulator's INFLUENCE rolls for all future sessions against this NPC. 
 
If Suspicion reaches **3**, the NPC may do any or all **countermeasure** behaviors below, depending on their **Conditions**. I.e. The NPC countermeasure depends on if they're captive or not, and their personality and skill level. These are listed in order from most likely to least likely countermeasures.

| Conditions                                                                        | Countermeasure                            | Detail                                                                                                                                                                                                                                                                                                                                                                                                                        |
| --------------------------------------------------------------------------------- | ----------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| non-threatened                                                                    | **Break off contact**                     | NPC goes away and stays away                                                                                                                                                                                                                                                                                                                                                                                                  |
| Very concerned has allies or master to report to                                  | **Report Manipulation attempt to Master** | May do this along with other tactics if they are concerned enough about it.                                                                                                                                                                                                                                                                                                                                                   |
| aggressive; deeply threatened/insulted                                            | **Become hostile**                        | Verbal or physical violence                                                                                                                                                                                                                                                                                                                                                                                                   |
| Captive; cooperative personality but genuinely loyal, or low intelligence         | **Deliberate Uselessness**                | Roll INFLUENCE: Manipulator +2. Pretends to cooperate but provides information or assistance that is subtly wrong, outdated, or just useless enough to be deniable. _"I told you what I knew."_                                                                                                                                                                                                                               |
| Captive; emotionally volatile, or believes the manipulator wants total submission | **Playing Broken**                        | Roll INFLUENCE: Manipulator. Performs psychological collapse: crying, recanting everything, expressing devotion in a way that feels just slightly too complete.                                                                                                                                                                                                                                                               |
| Captive; anyone with high confidence                                              | **Counter-Manipulation**                  | Attempts to manipulate the manipulator back, probing for their weaknesses, values, and emotional vulnerabilities. The NPC effectively runs their own INFLUENCE campaign from captivity. Uses each session as an opportunity to learn about the PCs' plans, resources, and vulnerabilities, storing it for when they eventually get word out or escape.                                                                        |
| Captive; cold professional                                                        | **Stonewalling**                          | Must roll ENDURANCE: Sere Training -2. Gives only the minimum required responses, volunteers nothing, makes every session feel like pulling teeth. Progress is technically possible but extremely slow. For one session, Grants a +2 to INSIGHT: Incorruptible to resist, and INFLUENCE: Manipulator to hide progress.                                                                                                        |
| Captive; charismatic schemer                                                      | **Playing Along**                         | Roll INFLUENCE: Manipulator. NPC begins playing along while secretly working against the manipulator. GM continues describing progress in plausible, positive terms until the trap is sprung. The **only mechanical check** available to PCs is an INSIGHT roll during or after a session. On a success, the GM hints something may be off. On a failure, the GM may describe the situation as normal or falsely encouraging. |
### Step 4: Completion

When Progress equals the Turn Number, the loyalty shift is complete. The GM adjusts the NPC's relationship with both the manipulator and their former master accordingly, and reveals the shift through story. The NPC making a dramatic choice, quietly offering themselves as an asset, or visibly distancing themselves from their former master. The exact moment this becomes visible to the PCs is the GM's call.

