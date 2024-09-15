# The Origin

This group has been doing these attacks since before august with multiple reddit posts about it, The earliest example of this I found was this post on reddit:

July 9th 2024 4:31PM EDT
https://www.reddit.com/r/youtube/comments/1dzcpnv/comment_bots_are_posting_cp_now/


## First Attack
On August 4 2024, I was made aware of a user who had uploaded DD via X ( fka Twitter). 
![Initial Post](https://github.com/grandt0ur/Investigations/blob/main/Images/Screenshot_20240915-034622.png)


Upon further investigation, it turns out that they posted the full video but it was heavily censored and manipulated Using certain techniques like making the video multicolored and changing those colors at very fast intervals as to prevent CSAM Detectiom Tools from detecting it. 

The way that they would go about circumventing this and posting the uncensored one was they would look for websites that necessarily did not have CSAM Detection Tools, And in the event that a link was taken down, they would log into the "test" account, which was where the video is usually hosted, and change any of the links that were in the video's description.

The very first link they had posted on this day was hosted by catbox.moe, In the video's description there was a backwards link separated by spaces, that directed users where to go to download and watch the material. Soon as I was aware of this I reported the video to Youtube's Trust and Safety Team and the video was taken down immediately.
![[Screenshot_20240915-034518 2.png]]

I then reached out to multiple other users who saw the events happen firsthand. and was told that There seems to be an individual or group that is working in connection with each other to spread this material and was given the following information : 

*It is believed that the group behind this may be a split off from a group known as UTTP, they are known for spamming replies and comment sections with racist garbage ca; just like the joseph account does. you can find these Joseph accounts that promote this material by going to popular new youtube videos and shorts and checking the replies of top comments.* 

 
 The reason for this belief is due to the account naming structure, the way that the profiles are designed, and the channel that is actually uploading the material or directing users on where to go to access this material.
![[Screenshot_20240915-035145.png]]

The accounts that do the promotion of where to go are usually named Joseph with a set of digits at the end of their name. If you look at the two accounts that I have shown, the one above this text, the account follows the same numbers as the count that has just recently been caught. They also have a Mr.Beast profile picture with the same background as their banner which is the MAPs Flag ( Minor Attracted People, A fake LBGTQ group created by 4Chan as a troll).

The rate at which these accounts are able to spread and lead what is essentially a campaign across YouTube to get this material exposed and seen is what allows me to believe that there is a bot necessarily behind this activity.

The account that is usually used to either direct users to the material or to spread the material itself are usually labeled 'test'. This makes me believe that there is usually a testing phase in which they will go through before they start promoting. 

## Second Attack
 On August 25th they had started another campaign where they would do the exact same thing, this time linking to a discord.
![[Screenshot_20240915-034606.png]]

 ![[Screenshot_20240915-034548.png]]Immediately I have reached out to YouTube and got made them aware of that and then made an email out to the archive.is System Admin.
![[Screenshot_20240915-035442.png]]
![[Screenshot_20240915-034533.png]]
After talking with the system admin of Archive.is, it was made aware to me that the link that was posted on the site likely linked to a Discord and it's possible that the material that they are sharing is on discord or they are using Discord as a middleman service to link directly to the actual material.

There have been multiple attempts to try to track down these users by independent individuals, and yet nothing has arisen that would necessarily confirm the identity of the perpetrators who are spreading this material. As much as I would like to find this person, I realize that I also have to make sure that I play the game safe and don't get myself wrapped up in something that ultimately might mess me up.

The video has been taken down once again and seems Discord has officially started taking down some of the servers that were linked in the archive.is post. It is only a matter of time before I believe these users are to strike again, and when they do, it will be equally as bad.
## "I know the pieces fit"

If UTTP is behind this, several key figures might be involved, starting with OfficerBMT.

BMT is notorious for trolling and spamming on YouTube, primarily in Penguinz0’s comments. One of his infamous videos features a woman crying over her dog's death while UTTP officers fly across the screen with inappropriate music playing. BMT has also made various disturbing claims, including supporting pedophilia and MAP rights. Although banned from UTTP for being exposed as a pedophile, BMT's involvement in these attacks seems likely due to his past behavior and tactics.

Other likely suspects include:

- **UTTP Admiral/Midnight/Lizarus**: Known for creating spamming bots, Admiral is second-in-command in UTTP and likely responsible for bot activity. He uses several aliases and primarily operates within the UTTP Empire Discord.
- **NWO (Emperor of MAP Pride)**: This individual is suspected of involvement, but there is no concrete documentation linking them to these events.


## Youtubes Systemic Error.
YouTube’s autocensorship mechanisms are effective, but these individuals are employing relatively straightforward techniques to circumvent them. YouTube uses CSAI Match, a proprietary technology designed to combat CSAI/CSAM. CSAI Match utilizes fingerprinting and video hashing. Video hashing generates a unique digital signature or "hash" for a video file, which is a fixed-length string of characters created by processing the video’s data through an algorithm. This hash can be compared against a database of hashes from known abusive videos. Fingerprinting, on the other hand, is more complex as it does not rely on exact matches. Instead, it analyzes specific features or characteristics of the video, such as patterns in the audio, visual elements, or frame sequences, to create a "fingerprint"—a digital representation capturing the unique aspects of the video content. Typically, when violative content is detected, it is flagged for partners to review, confirm, and report in accordance with local laws and regulations. However, these individuals appear to be bypassing these measures using various methods.

During my initial encounter with these groups, they had posted a heavily censored version on YouTube itself. The title card was edited using a color-changing video filter and other techniques. This was their first method of bypassing.

Video fingerprinting algorithms are designed to detect core patterns in a video, such as shapes, movements, or scene transitions, which remain consistent even with visual effects like color changes. However, they employed multiple techniques to evade CSAI Match, including extensive color grading and audio manipulation (e.g., silencing the entire video).

One method they used involves text reversal Unicode, specifically RLO (RIGHT-TO-LEFT OVERRIDE). This technique is commonly used by hackers to disguise file extensions. For example, using RLO in the file name my-text.'U+202E'cod.exe displays it as my-text.exe.doc, making it appear as a .doc file while it is actually an .exe file. YouTube’s auto-moderation system relies heavily on keyword detection and text pattern matching. The latter could potentially address this issue, but employing RLO or Unicode characters that look visually identical but are technically different can bypass these systems. For instance, someone posting illicit links or inappropriate comments might reverse the text or use alternative Unicode characters to prevent YouTube’s automated systems from detecting the message, while still allowing other users to decode it manually.

It is to my belief and understanding with these bots that they are or can be quite complicated, considering the methods we are talking about we can say that a few features of the bot are sure :

- **Automated Posting**: The bot would automate the process of posting comments or video descriptions across YouTube. It could post at regular intervals or flood multiple videos in a short period to maximize exposure.

- **Text Reversal**: The bot could reverse harmful or spammy text strings like URLs or specific words to avoid detection by YouTube's filters. For example, the bot could post "moc.elpmaxe.www" instead of "[www.example.com](http://www.example.com)".
  
- **Unicode Obfuscation**: The bot could replace characters with visually similar Unicode characters. For example, it could post "𝔢𝔵𝔞𝔪𝔭𝔩𝔢" instead of "example." This would confuse basic keyword detection while still being human-readable.
  
- **Keyword Variation**: The bot might use a database of word variants or misspellings to rotate different forms of a keyword, making it harder for filters to catch repetitive patterns. For instance, it could post "c0ntent" instead of "content" or "uпcode" using a Cyrillic "п" instead of "n".
