# Auto-Member-Group-Assignment-SB
Actions to be able to automatically and manually assign members to groups through YouTube membership events.




## **Description** 
 
With this you will be able to have members assigned automatically to groups to be able to have command permissions in Streamer.bot for specific member levels/tiers. 


Members get assigned to a group through these events:
- New Member(Sponsor) Event
- Member Mileston Event
- Gift Membership Received
- Manual Command (for when a user becomes a member offline)

Once a member gets assigned to a group, the date is saved/updated in Streamer.bot for that user as the date they last verified they were a member. Each first words event, Streamer.bot checks to see if it has been 30 days since the membership date and if has been more than 30 days, the member is removed from the group and can no longer use the commands that require that specific member group permission.

In order for them to get assigned back to the group again, they either need to 
1. Renew their membership
2. Send a Member Milestone celebration
3. You have the option to manually assign the member level/tier and date for the member through a command.


## **Import Code** 

[Streamer.bot Import](https://github.com/Haunter56/Auto-Member-Group-Assignment-SB/blob/main/youtube_member_auto_assign.sb)


## **Installation** 

In Streamerbot select the Import button from the top left menu.

Drag and drop the file or copy the text from the file and paste all the text into the Import String field.

![image](https://github.com/Haunter56/Auto-Member-Group-Assignment-SB/assets/107263697/6eb8274b-5847-4bde-836b-5ef96ea47199)

There should be 3 actions and 1 command.


## **Configuration** 


### C# Compiler
To make sure the C# code will run, go into any of the actions and  > Double-Click the "Execute Code" sub-action > click "compile" to make sure it compiles


![image](https://github.com/Haunter56/Auto-Member-Group-Assignment-SB/assets/107263697/cbbd08f8-2aaf-47d5-b6d7-7aa3ddf66a63)


![image](https://github.com/Haunter56/Auto-Member-Group-Assignment-SB/assets/107263697/dc2eb2e9-a96d-4515-8408-93ba30c2f7e7)



### Your YouTube Member Level/Tier Names
In the "New Member/Milestone/Gift Received Assign To Group" action update the member level/tier names with the names you set up on your channel. 

DO NOT DELETE THEM. Even if you don't have that many levels/tiers, you need to leave them in for the code to work.

![image](https://github.com/Haunter56/Auto-Member-Group-Assignment-SB/assets/107263697/69f40f6e-3cf6-45c2-811d-3e5412f8c1cd)

For example, if your level 1 member tier was "Level 1" you would update the text "[Level/Tier 1 Member Name Here]" to "Level 1"

![image](https://github.com/Haunter56/Auto-Member-Group-Assignment-SB/assets/107263697/53714694-79da-4f06-bdbb-26ca9e27cdee)


Do this for however many levels/tiers you have.




### Group Configuration

You will need to add the group names in > Settings > Groups

![image](https://github.com/Haunter56/Auto-Member-Group-Assignment-SB/assets/107263697/1a25c043-d8fd-4c99-8053-e1a41ed9eac3)

Add "Members Level #" for each level/tier you have. (Members Level 1, Members Level 2, etc.)


![image](https://github.com/Haunter56/Auto-Member-Group-Assignment-SB/assets/107263697/165c6279-f8d5-40e9-ae4d-9aafecd8aeec)



OPTIONAL - You can change the group names to your member level/tier names, just make sure to update the sub-actions of all 3 actions with the updated Streamer.bot group names

![image](https://github.com/Haunter56/Auto-Member-Group-Assignment-SB/assets/107263697/70d92949-12c3-438b-a31c-47e602e89f9e)



They must match the group names you create exactly. If you don't have up to 5 member levels/tiers, then just update the ones you have and leave the other ones as they are.



## Contributors
[Haunter](https://www.youtube.com/channel/UC9qO6-NFvWwhde5o2B_DMzQ) 👻


