
# Hacking Mechanics: A Quick Guide
## A) Hacking Process
1. **Plan** your hack (reduces action time from 10 to 1 minute)
2. **Connect** to the network
   - Difficulty increases with network security level
   - Each subsequent hack in 24 hours becomes harder
3. **Navigate Security Layers**
   - Move through layers using ROUTER TRANSFER action.
   - Encounter and interact with:
     * Data Storage
     * Infrastructure
     * Barriers
     * Routers
     * Uplinks
4. **Use Hacking Actions**. Key actions include:
- Run Local Program   
- Copy File
- Delete Local File
- Disconnect
5. **Run Programs**
- Combine a Verb (action) with a Subject (target)
- Examples:
     * Blind Camera
     * Unlock Door
     * Analyze Machine
## B) Risk Management
- Failed hacks trigger network responses
- Potential consequences range from warnings to tactical response teams
- Higher security networks have more aggressive defensive measures
## C) Alternative Access
- Obtain user accounts (through theft, intimidation, or otherwise) for easier network access 
- Account types:
  * Guest (minimal access)
  * Employee (moderate access)
  * Admin (extensive access)
  * Super User (full network control)

# HACKING MECHANICS

Hacking into a network to access data or devices is governed by Technical: Computers. There are 8 possible “Hacking Actions,” and the Difficulty Modifier of these depends on the security level of the network you’re trying to do the actions in. 

TIME TAKEN
If you spend 1 hour planning a hack on a particular network, all of these actions (with the exception of Disconnect and Terminate Local Program) take 1 minute, Otherwise, if your hack is unplanned/off the cuff, the Hacking Actions take 10 minutes each. 

RUSHING
You may try to rush these actions, but each time you cut the time in half, -1 Difficulty Modifier (DM).
e.g. -3 DM to cut a planed hacking action down to 7 seconds (2 rounds).

SUBSEQUENT HACKING
Each hack/intrusion after the first in 24 hours incurs a -1 DM. 

### Hacking Actions

| Hacking Action              | Description ............................................................................................                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | DM in <br>Unsecured Layer      | DM in<br>Secured Layer        | DM in<br>Hardened Layer        | DM in<br>Encrypted Layer                                                                                                                                                                                                                                                                  |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------ | ----------------------------- | ------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **CONNECT**                 | Connect through wire or wirelessly to a target network. 1 minute.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | -1                             | -3                            | -5                             | -5                                                                                                                                                                                                                                                                                        |
| **COPY FILE**               | Make a copy of a datafile located in the current security layer and store it in your deck’s Memory. The inevitable wrapper of anti-tamper code and log files makes almost all important datafiles take up one point of Memory, however small the actual contents. 1 minute.                                                                                                                                                                                                                                                                                                                                                                                                                                               | -1                             | -3                            | -5                             | -5                                                                                                                                                                                                                                                                                        |
| **CRASH SHUTDOWN**          | This action can only be taken by someone with access to a Super User Account, usually the senior human watchdog hacker on duty for a given network, or an infiltrator who has gained that high access. Once triggered, the entire network will shut down in 1D6 minutes, deactivating every connected device and booting every user out of the system as if forcibly disconnected. It will take 24 hours to bring the system back up and inflict 10% of the network’s total hardware costs in component damage. Corps reserve this action for dire emergencies, when it seems certain that an intruder is soon to do something even worse than this. Impending shutdowns are obvious to everyone in the system. 1 minute. | 0                              | 0                             | 0                              | 0                                                                                                                                                                                                                                                                                         |
| **DELETE LOCAL FILE**       | Erase one datafile, Verb, or Subject on your own machine, freeing up the Memory it occupied. Deleting files in a server you don’t have admin rights for requires RUN LOCAL PROGRAM with the Erase verb, as the local network may not permit such tampering. 1 minute.                                                                                                                                                                                                                                                                                                                                                                                                                                                     | 0                              | 0                             | 0                              | 0                                                                                                                                                                                                                                                                                         |
| **DISCONNECT**              | Disconnect a wired or wireless connection. Damage to your deck will automatically disconnect. 1 Fast Action (instant).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | 0                              | 0                             | 0                              | 0                                                                                                                                                                                                                                                                                         |
| **ROUTER TRANSFER**         | If the hacker has found a Router within a network, they can move to a deeper Security Layer in the network.  Same with Uplinks to move to another connected network. 1 minute.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | Transfer to Unsecured Layer: 0 | Transfer to Secured Layer: -3 | Transfer to Hardened Layer: -3 | Transfer to Encrypted Layer: N/A. Requires the PRIVATE ENCRYPTION KEY (PEK) of a user who has access to the layer. PEKs can be acquired through theft, interrogation, social engineering, or hacking a lower security layer (like the target’s personal computer) which contains the PEK. |
| **RUN LOCAL PROGRAM**       | Run a program from the hacker’s machine or the watchdog’s server, combining a Verb with a target Subject to produce a desired effect. 1 minute. (See Running Programs section For details on programs).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | -1                             | -3                            | -5                             | -5                                                                                                                                                                                                                                                                                        |
| **TERMINATE LOCAL PROGRAM** | Shut down a program you are running, freeing up CPU capacity. Programs are automatically terminated if the hacker gets dumped from the network, their wireless signal is blocked, or they’re otherwise cut off from their intended targets. 1 Fast Action (instant).                                                                                                                                                                                                                                                                                                                                                                                                                                                      | 0                              | 0                             | 0                              | 0                                                                                                                                                                                                                                                                                         |


### Networks and Security Layers

Different networks can be categorized by the level of security you can expect to find in them. The higher the level of security, the more Security Layers you’re likely to encounter. These layers are stacked like pancakes in a network, and each may contain data, devices, hacking barriers, routers to the next more secure layer, and sometimes uplinks to other networks. Typically hacking attempts begin by accessing the first, least secure layer, either through a hardline connection, terminal access, or accessing a wifi signal through your deck (computer). Other access options include acquiring USER ACCOUNTS (through theft, intimidation, etc) to directly access a deeper layer (See User Accounts section). 

**Security Layers**
- **UNSECURED LAYER**. Very easy to access and manipulate. The data and devices at this layer will be pretty low value too.
- **SECURED LAYER**. Moderately difficult to hack. May find sensitive data here in low security networks. No devices.
- **HARDENED LAYER**. Difficult to hack. If you want access to sensitive data and infrastructure, you’ll need to get here at least.
- **ENCRYPTED LAYER**. Contains only the highest value data and devices/infrastructure. Cannot be accessed with a hacking roll. Instead they require the PRIVATE ENCYPTION KEY (PEK) of a user who has access to the network. PEKs can be acquired through theft, interrogation, social engineering, or hacking a lower security Node (like the target’s personal computer) which contains the PEK.

**Typical Levels of Secure Networks**
- **VERY LOW**: Ordinary home computer, unsecured office network, public wifi hotspot. Will only sometimes contain a Secured Layer. 
- **LOW**: Savvy private wifi, small business, minor gang, outdated transport infrastucture, unsecured government. Will 2 layers: unsecured, and secure. A bit more responsive to failed hacking rolls.
- **MODERATE**: Police station network, Savvy corp office, important gov facility, major gang. Most of the really good stuff will be found in the Hardened Layer. Failed rolls have a chance of triggering immediate aggressive responses like back-hacking, or sometimes even tactical response teams.
- **HIGH**: High-security megacorp network, Major gov network. Contain all 4 layers, from Unsecured to Encrypted. Very aggressive responses to failed rolls likely.
- **VERY HIGH:** Corp or Gov black site. No Unsecured Layer. Their least secure layer is Secured. Very aggressive responses to failed rolls likely.
### Defensive Network Responses
While navigating a hostile network and you fail a hacking roll, the GM will roll on the Standard Response Table, adding any + Response modifiers of the particular network function (i.e. router, barrier, data storage, etc) the player is currently messing with. The GM will not tell the Players which result was rolled, though the effects may be evident. 

**STANDARD RESPONSE TABLE**

| Roll 1D6 + Response Total | STANDARD RESPONSE                                                                                                                      |
| ------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| 1                         | Warning message. Network’s RESPONSE +1                                                                                                 |
| 2                         | Targeted device/data is remotely powered off.                                                                                          |
| 3                         | USER ACCOUNT locked out for 1d10 hours.                                                                                                |
| 4                         | Red flag at connection site. Security member dispatched to investigate. Arrives in 1d10 rounds.                                        |
| 5                         | Network creates “dummy” directories for the Hacker to search while a security team is sent to investigate red flag at connection site. |
| 6                         | The network and all linked networks are locked down for 1d10 hours.                                                                    |
| 7                         | This network and all linked networks increase security level by 1.                                                                     |
| 8                         | All linked networks increase RESPONSE +1                                                                                               |
| 9                         | Facility blackout. All non-essential electronics powered down.                                                                         |
| 10                        | Hardware Identified. Roll AGGRESSIVE RESPONSE.                                                                                         |
| 11+                       | Hardware Identified. Roll AGGRESSIVE RESPONSE, and STANDARD RESPONSE                                                                   |

**AGGRESSIVE RESPONSE TABLE**

| Roll 1D6 | AGGRESSIVE RESPONSE                                                                                                                                              |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1        | TACTICAL RESPONSE TEAM deployed on Seek & Destroy mission. Arrives affected in-network terminal, heavily armed in 1D6 rounds.                                    |
| 2        | DENIAL OF SERVICE: NetSec blocks connections from the hacker’s connected hardware by flooding the connection with garbage making future hacking attempts slower. |
| 3        | BACK HACK: NetSec attempts to control/destroy the terminal/deck/etc. being used in the attack.                                                                   |
| 4        | MALWARE ATTACK: NetSec uses a virus to disable the hacker’s hardware for some time.                                                                              |
| 5        | POWER OVERLOAD: NetSec pushes excessive voltage to the hacker’s hardware.                                                                                        |
| 6        | NETWORK TRACE: NetSec attempts to locate the physical location of the hacker.                                                                                    |
### Navigating Networks

Once you’ve performed the CONNECT action to gain access to a Security Layer, you’ll see various functions housed in that layer that may be interacted with:
- **DATA STORAGE**. A bunch of data files. An Investigation roll will find specific files. Perform COPY FILE action to copy information, or RUN LOCAL PROGRAM to otherwise manipulate the data.
- **INFRASTRUCTURE**. This may be peripheral infrastructure and devices like doors, lights, cameras, ventilation, or more vital devices like admin computers, airlocks, main power, weaponry, or secure doors. Perform RUN LOCAL PROGRAM action to manipulate these.
- **BARRIERS**. An anti-intrusion node that blocks infiltrators from accessing any more of the network beyond it. Perform RUN LOCAL PROGRAM action with the verb: "Unlock" and subject: "Barrier" to circumvent it. -1 DM
- **ROUTERS**. These are portals to the next, more secure layer inside the network. A successful ROUTER TRANSFER action takes you through.
- **UPLINKS**. These are essentially secure routers leading to entirely different networks within an organization’s larger securenet. A successful ROUTER TRANSFER action takes you through.

You will see everything up to a Barrier, and everything you see, you can interact with. 

EXAMPLE: |337h4x0r performed Router Transfer from an Unsecured router into a Secured Layer. He immediately sees that this layer has Data Storage, a Router, and a Barrier. He wants to see what’s beyond that Barrier before getting deeper into the network, so he runs Unlock Barrier, succeeds, and discovers access to peripheral infrastructure. Now he can make the lights flicker. HACK THE PLANET.
### Running Programs

A program consists of two components: a Verb and a Subject. Hackers load a selection of these into their deck's memory. As needed, they pair any two to create desired effects. For instance, Verb: Blind, Subject: Camera. Each Verb or Subject consumes one point of deck Memory and can be combined arbitrarily to form a program.

Programs take one CPU slot while running. A deck with a CPU rating of 4, for example, can run no more than 4 programs at a time. Some Verbs auto-terminate after performing their task, while others are ongoing, and continue to have their effect as long as the program runs.

Programs can be used as often as the user wishes, so long as they have the CPU space needed to run them; the same Blind and Camera elements can be used to blind three different cameras at the same time so long as the deck has at least a CPU of 3 and the hacker takes three separate RUN LOCAL PROGRAM actions to run the program at different targets.
### Programs: Features and Acquisition

Getting a new Verb or Subject isn’t as simple as buying it off the rack or copying it from a friend. The programs that hackers use are profoundly illicit, programmed to sneak under corporate security barriers and ignore corporate spyware requirements. Each one is a work of digital art that relies on secret corporate database taps, spoofed security certificates, and unpatched exploit lists. If such a program was simply copied, the doubled hit on those resources would instantly flag both programs as threats and ruin them for any practical use.

As such, these programs are painstakingly designed one-by-one by expert criminal codesmiths and sold and traded among the hackers of a city. The prices given on the chart for Verbs and Subjects reflect the usual fees charged for such things; any competent hacker will know where to buy them.

#### Program Verbs
Listed with the valid Subject types they function against. A Verb cannot be run with an invalid target; you can’t Blind a data file or Erase a device.

| Verb        | Target Types Allowed | Skill Check Modifier | Cost | Summary                                    |
| ----------- | -------------------- | -------------------- | ---- | ------------------------------------------ |
| Analyze^    | Device/Data          | +1                   | 500  | Identify a target device or a file’s topic |
| Append^     | Data                 | 0                    | 500  | Add a new entry or data into a file        |
| Erase^      | Data                 | 0                    | 500  | Erase a data file and corrupt backups      |
| Terminate^  | Program              | 0                    | 500  | Forcibly end an unwanted program           |
| Unlock^     | Device/Data          | 0                    | 500  | Unlock an electric lock or Barrier         |
| Activate^   | Device               | 0                    | 1000 | Turn on a device                           |
| Decrypt^    | Data                 | 0                    | 1000 | Decrypt a file or radio transmission       |
| Defend      | Device               | N/A                  | 1000 | Shield a friendly device                   |
| Glitch      | Device               | +2                   | 1000 | Briefly deactivate a device                |
| Lock        | Device/Data          | 0                    | 1000 | Lock an electronic lock or node barrier    |
| Replace^    | Data                 | 0                    | 1000 | Change file data to something else         |
| Sense       | Device               | 0                    | 1000 | Piggyback on a sensor feed                 |
| Blind       | Device               | 0                    | 2000 | Turn off sensory input to a device         |
| Deactivate^ | Device               | 0                    | 2000 | Turn off the target for at least a round   |
| Sabotage^   | Device               | -2                   | 2000 | Make the target device damage itself       |
| Siege       | Device               | -2                   | 2500 | Cut off a device from the network          |
| Delude      | Device               | -2                   | 5000 | Spoof a device with false sensor input     |
| Hijack      | Device               | -2                   | 5000 | Take remote control of a device            |

^: These verbs are self-terminating, and return their CPU slot immediately after the program is run.

- **Activate**: Turn a device on. You can’t control it or direct its function, but if it’s programmed to do something when activated, it does it for one round or one action.
- **Analyze**: Identify the specific functionality of a device or the general topics of local datafiles. Analyze is needed to give specific details of where a device is in reality.
- **Append**: Add a new entry or new data into a file. These new entries can’t overwrite or erase any existing data, however.
- **Blind**: Deactivate a device’s sensory input Cameras sense nothing, and laser tripwires don’t register the beam.
- **Deactivate**: Turn a device off. Most devices can be rebooted by the network or the user, but it’ll take 1 round  to do so. If a network alert hasn’t been issued, the network may not even notice a deactivated device until someone spots the problem.
- **Decrypt**: Decrypt a data file or radio transmission. This is often automatic for civilian encoding, though some files take Technical skill checks.
- **Defend**: A special Verb that can only be targeted at a friendly device. While the program remains running, any hostile hacking attempts aimed at that device must first beat the user in an opposed Technical skill check before they can attempt their hack. This Verb cannot negate programs that are already running on the target.
- **Delude**: Spoof a device with false sensor input. A camera can be made to record nonexistent scenes, a radar can be made to see phantom bogeys, a microphone can transmit sound files, and a turret can be made to mistake friends for foes. This Verb can’t control a device directly, however, and must rely on feeding it false sensor data.
- **Erase**: Erase a data file. This Verb is extremely thorough, and any on-site backups can be expected to be nuked as well, either immediately or as soon as the automatic backup protocols expose them.
- **Glitch**: Temporarily deactivate a device while the program remains running, for one round per Success in a straight Technical (hacking) roll. A device can be targeted by a particular hacker’s Glitch only once a day, successful or not.
- **Hijack**: Seize control of a device, operating it as you wish within the limits of its functionality for as long as the program remains running. One command is free with the program’s successful execution; others take an Action to issue in a round.
- **Lock**: Lock a physical device that has some sort of electronic locking mechanism or a currently un-locked barrier, or datafile. Others must beat your roll to access the device.
- **Replace**: Edit a data file, changing one piece of data in it into another of the hacker’s choice. It cannot erase or add data outright, only alter it.
- **Sabotage**: Cause a physical device to damage itself through violent movement or self-destructive current surges. Devices smaller than a car will usually be disabled until repaired. A device can be targeted by this Verb only once per 15 minutes. 
- **Sense**: Piggyback on the sensory feed of a device. Anything the device senses or records, the hacker can now see on their deck.
- **Siege**: If a Device is successfully Sieged, its network connections are severed for everyone but the hacker. Defenders can run "Terminate" "Program" against it from its current Security Layer (locking barriers and deactivating routers will make this much harder for them). If successfully Sieged, further failed hacking attempts against the device will not alert the network. 
- **Terminate**: Prematurely end an undesired process. Any damage or changes the program already inflicted are unaffected.
- **Unlock**: Unlock a physical device with an electronic lock or a network’s cyberspace node barrier.
#### Program Subjects

| Subjects     | Type    | Affects…                                                                      | Cost |
| ------------ | ------- | ----------------------------------------------------------------------------- | ---- |
| Camera       | Device  | Audiovisual sensors                                                           | 500  |
| Datafile     | Data    | Files on servers                                                              | 500  |
| Door         | Device  | Physical doors                                                                | 500  |
| Machine      | Device  | Any devices at -1D skill penalty                                              | 500  |
| Program      | Program | Active running program or Data Type (including Barriers) at -1D skill penalty | 500  |
| Sensor       | Device  | Any sensors at -1D skill penalty                                              | 500  |
| Barrier      | Data    | Network Barriers                                                              | 1000 |
| Transmission | Data    | Radio and wifi signals                                                        | 1000 |

- **Barrier**: (Data) A network node barrier that blocks intruders from passing through a network connection.
- **Camera**: (Device) Any device that transmits audiovisual information. Some defensive hardware has its own onboard camera, which is susceptible to this target, while others rely on a separate device’s input.
- **Datafile**: (Data) A datafile stored within a network node. While individual files may have very little actual data in them, the autoencryption functions and anti-tamper code they’re wrapped in almost always take up 1 full unit of Memory per file.
- **Door**: (Device) A physical door, shutter, hatch, or other barrier with an electronic lock or opening mechanism.
- **Machine**: (Device) Security panels, factory machinery, ventilation system, or any other hackable device not covered under an existing Subject. Its generality applies a -1D skill penalty to Technical (hacking).
- **Program**: A hostile program, used most often with the Terminate verb to end the effects of an enemy hacker’s programs prematurely. This can also be applied to Barriers at -1D skill penalty to Technical (hacking).
- **Sensor**: (Device) Similar to the Camera element, this code block handles sensors of any kind, regardless of what they are intended to detect. The generality of the element decreases its efficiency, however, and it applies a -1D skill penalty to Technical (hacking).
- **Transmission**: (Data)  Ambient radio transmissions can be affected with this element if the hacker has the right hardware (see HACKER GEAR) most often for the purpose of tampering with local comms.

**Example Programs**
- To reduce the Response values (i.e. how much failure will alert the admins) in the local Network Layer, run **Glitch** **Machine** on the Router. Reduces Response in this Network Layer by 1D6.
- To log all keystrokes at a station, thereby learning passwords, etc, run **Sense** **Machine** on a computer you have access to.
- To retrieve a map of this Network Layer and the next, run **Analyze** **Machine** on a Router.

#### Writing Programs From Scratch

Crafting a constant stream of usable Verbs and Subjects for sale is impractical for most PCs. The work requires contacts with a host of insider moles in corporate databases, criminal data launderers, and subject-field specialists in hardware security subversion.   

While few hackers have the time or resources to write illicit programs as a business, most can manage to keep a few of their most important needs satisfied through their own coding prowess. A sufficiently talented hacker skill can maintain a few usable Verbs and Subjects, keeping them up-to-date and concealed from ubiquitous corporate DRM.  

Writing a Verb or a Subject takes 10 quarter-days, a -1 Observation: Investigator roll, and a -1 Technical: Computers roll, using any computer with an internet connection. Due to the need to keep them updated, two such programs can be maintained per die of Wits + Technical above 3D6. So a PC with Wits + Technical of 5D6 can maintain up to four total Verbs and Subjects at once. They might choose to keep Glitch, Blind, Barrier, and Camera available this way after a few weeks of work to write the code. Code that is abandoned in favor of a new program must be rewritten from scratch if the hacker needs it once again, as entirely new security bypasses must be researched and implemented.  

Hackers can also write specialized or unique Subjects, often in preparation for a mission. If a hacker can find out the exact model of camera or electronic lock their target is using, they can write a unique Subject aimed at that specific device, gaining a +2 bonus on their skill checks to overcome its security difficulty.  
### User Accounts

Instead of directly Hacking a network, one can gain access to a USER ACCOUNT by obtaining (through theft, intimidation, or otherwise) a user’s credentials (e.g. password, ID, badge, Private Encryption Key, etc.). While having direct access to a User’s Account circumvents the need for a Hacking check for many actions, each account is limited in its permissions.

**GUEST ACCOUNTS** have very limited permissions, usually only accessing the intranet (if there is one) of a Secure Layer, company directories, or online help.  
>>The only Hacking Actions allowed for free are Connecting and Disconnecting to a Secured Layer..

**EMPLOYEE ACCOUNTS** grant permissions over anything in a specific Security Layer that the employee’s job description covers: e-mails, maps, details about projects, and other company sensitive information and files.  
>>Allowed Hacking Actions for free: Connect, Disconnect, Copy File. Free Verbs: Activate, Analyze, Append, Deactivate, Decrypt, Replace, Unlock any data or device the employee has access to. You don’t need these Verbs programmed on your deck to use them with Employee accounts.

**ADMIN ACCOUNTS** oversee several employees, and have access to everything they can access, typically at the deeper Security Layers.. Admins could be managers, team leaders, IT personel, or officers on a ship.  
>>Allowed Hacking Actions for free: Connect, Disconnect, Router Transfer, Copy File. In addition to Verbs Employee accounts can do, Erase, Glitch, Lock, Sense on any data or device the admin controls. You don’t need these Verbs programmed on your deck to use them with Admin accounts. +2 to all other Hacking Actions.

**SUPER USER ACCOUNTS** grants “root” access to everything on the Network, and often on several other connected Networks.  
>>Allowed Hacking Actions for free: All Hacking Actions, including Crash Shutdown. May run any Verb on any data/device without needing these Verbs programmed on your deck, this requires a Technical roll at no DM. However, if your actions become too drastic, other Super Users on the network may become suspicious and try to Terminate Program on your efforts, or Analyze Program to determine where your access is coming from.
### Hacker Gear

**STATS EXPLANATION**
- **Gear Dice** reflects the onboard intrusion hardware integral to the deck. It augments the user’s base Technical: Computers skill.
- **Memory** is the number of memory units standard to the deck. Each program and data file takes up one unit of memory. Erasing a program from memory is an Instant action, but loading it off a program chip takes fifteen minutes to complete all its linkages.
- **CPU** indicates the number of programs the deck can run at once. Some programs are Immediate, and self-terminate right after executing, while others are ongoing, and take up a CPU slot until terminated as an Instant action.

| GEAR                         | PRICE   | SUPPLY | WEIGHT | FEATURES                                                                                                                                                                                            |
| ---------------------------- | ------- | ------ | ------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| “Flipper” Handheld Pentester | 170     | C      | 0      | Hijack wireless devices (low power radio, IR), clone RFID tags, hardware connection. Memory 3, CPU 1                                                                                                |
| Police Scanner               | 300     | R      | 1      | Listen to radio ranges and modulations used by police and other emergency services.                                                                                                                 |
| RF Hacker                    | 500     | C      | 1      | When connected to computer, send/receive RF signals. <br>-0-3 DM Technical roll to tune into intentionally trunked or spread-spectrum radio comm systems. May jam signals, and send secure signals. |
| Smart phone                  | 600     | A      | 0      | -1 DM, Memory 4, CPU 2                                                                                                                                                                              |
| Standard Laptop              | 700     | A      | 1      | Memory 6, CPU 2                                                                                                                                                                                     |
| High End Laptop              | 5,000   | A      | 1      | Memory 10, CPU 3                                                                                                                                                                                    |
| Signal Locator               | 6,000   | C      | 1      | Monitors the signals of tracking devices. It includes a small display to show direction of movement. + $2000 for models that can pinpoint the location on a map.                                    |
| Developer’s Laptop           | 30,000  | C      | 1      | +1 Gear Dice, Memory 11, CPU 4                                                                                                                                                                      |
| Bleeding Edge Laptop         | 100,000 | R      | 2      | +2 Gear Dice, Memory 12, CPU 6                                                                                                                                                                      |
[GM SECTION- Building Networks](GM%20SECTION-%20Building%20Networks.md)