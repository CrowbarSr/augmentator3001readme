# Augmentator3001

[LINK TO THE TOOL](https://augmentator3001-production.up.railway.app/)

How to use this tool using 2 different methods to output your best buff targets within a given EM window. 

This tool was originally created by [Liroo](https://github.com/Liroo) and I have picked it up.

## Initial Configuration - you'll only need to do this once
1. Log into [Warcraft Logs](https://www.warcraftlogs.com/)

2. Navigate to [Manage Your Clients](https://www.warcraftlogs.com/api/clients/)

3. Select 'Create Client'

   <img width="127" height="40" alt="image" src="https://github.com/user-attachments/assets/8749a154-a389-4256-9ef4-6c4a4991a273" />

4. Populate the fields with whatever you want

   Example:

   <img width="701" height="208" alt="91ae721d-5d4f-4cc3-894a-815378446399" src="https://github.com/user-attachments/assets/24d1960a-69dd-417e-a25b-ee619b06e4d3" />

5. Note your ClientID & ClientSecret somewhere SAFE

   <img width="986" height="67" alt="image" src="https://github.com/user-attachments/assets/0f50162c-5343-43d3-aea1-93ccc375f3c7" />

6. Complete the WCL Credentials section with the ClientID & ClientSecret you generated and select 'Validate'

   <img width="161" height="30" alt="dbf86c82-dcf8-409f-a3cc-fd06f36eec89" src="https://github.com/user-attachments/assets/77bae82e-fd84-4d96-82c6-9d100c25c98d" />

7. Select your region in the top right corner

## Select your preferred method

<details>

<summary>Basic Usage Method #1 - Custom Logs Snapshot (Recommended for beginners)</summary>

### Use this method to analyse your logs and provide a snapshot of your best targets based on the average results of kills and/or pulls. This is effective for a snapshot but less effective if more logs are coalesced over time due to faster kill times, better gear and smarter play.

1. Expand the Custom Logs section, provide a link to your logs and click 'Add Custom Report'

2. Select your desired boss encounter

   <img width="789" height="71" alt="483bb9e4-b4ad-4c45-848a-7e2298449bb9" src="https://github.com/user-attachments/assets/0a1a2c9f-82b1-430b-84ad-234978faa102" />

3. (Optional) Tick 'Filter by current encounter'

   <img width="200" height="33" alt="45d97a94-be9e-467f-a710-0862bbe42ec1" src="https://github.com/user-attachments/assets/24eb531b-4ed0-4b25-aa6b-e2e84e949db5" />

4. Select the kills and/or pull attempts you wish to analyse

   <img width="439" height="55" alt="26e3279b-45b7-4b7d-9aea-91e27726e433" src="https://github.com/user-attachments/assets/f589b729-e4f7-46f5-b82a-dfa9ff43337c" />

5. Select the 'Import DPS Characters' button to populate your roster

   <img width="230" height="34" alt="a5e8a050-9157-40a6-8a82-4f3015575ebc" src="https://github.com/user-attachments/assets/f843d5cd-d148-4399-bed7-af867439c4ed" />

6. Select the 'Compute' button

   <img width="207" height="70" alt="cede8ce6-a279-4917-a0f9-05da10018246" src="https://github.com/user-attachments/assets/7fcbc7ed-6bf6-4704-b57f-ffda6292f3be" />

7. You'll be provided a list of your approximate best buff targets within a given time window

   <img width="785" height="235" alt="6c2114fd-15ff-4275-bc4f-3df84168072f" src="https://github.com/user-attachments/assets/dad0219c-c00c-46c7-bd89-d9362f4e98d5" />

8. (Optional) You can then export this data using the 'Copy Note' button at the bottom of the page to use with the provided Weakaura

9. (Optional) Proceed to the Weakaura Integration section

</details>

<details>

<summary>Basic Usage Method #2 - Best Logs</summary>

### Use this method to pull each roster member's best overall performance for a particular boss instead of using provided custom logs. This is effective for longer term usage as it will always provide the 'best' data instead of a snapshot from logs.

1. Expand the Edit Roster section & populate it with your DPS roster

2. Select your desired boss encounter

   <img width="789" height="71" alt="483bb9e4-b4ad-4c45-848a-7e2298449bb9" src="https://github.com/user-attachments/assets/0a1a2c9f-82b1-430b-84ad-234978faa102" />

3. Expand the Best Logs section & select the 'Refresh Best Logs for current encounter'

4. You'll be provided an output of your roster's best performance for that encounter, by default the highest parse should be selected

   <img width="914" height="318" alt="b5d5046f-7ebc-4d3e-af85-c9dbada037a9" src="https://github.com/user-attachments/assets/d8acdc22-bae6-45b1-939c-6c7ab964800b" />

5. Select the 'Compute' button

   <img width="207" height="70" alt="cede8ce6-a279-4917-a0f9-05da10018246" src="https://github.com/user-attachments/assets/7fcbc7ed-6bf6-4704-b57f-ffda6292f3be" />

6. You'll be provided a list of your approximate best buff targets within a given time window

   <img width="784" height="234" alt="cd3ce698-73bf-43d2-9d5d-61a6811accf0" src="https://github.com/user-attachments/assets/0a035187-1055-46a7-9a2a-dca49216ba07" />

7. (Optional) You can then export this data using the 'Copy Note' button at the bottom of the page to use with the provided Weakaura

8. (Optional) Proceed to the Weakaura Integration section

</details>

## Weakaura & MRT Integration

### Weakaura

1. Navigate to the [Weakaura](https://wago.io/-0f1A1GEK) page

   :warning: **NOTE: You can ignore the warning, the Weakaura still currently functions**

2. Select 'Copy Import String'

3. In WoW type `/wa` to access your Weakauras

4. Import the Weakaura into WoW using the string from step #2

5. Close the Weakaura window

### MRT

1. In WoW type `/mrt` to access the MRT window

2. Select 'Note'

3. Select 'Personal Note'

4. Paste the Augmentator3001 note

   <img width="1018" height="546" alt="image" src="https://github.com/user-attachments/assets/36973ba0-e1f9-4cc7-b434-c750e181905b" />

5. Close MRT - it should now work on pull

   [Example video of the frame highlights](https://www.youtube.com/watch?v=de6IcYMpm7Q)

7. To disable this - simply clear your Personal Note

**Optional**

1. Instead of Personal Note, add a draft note

   <img width="241" height="87" alt="image" src="https://github.com/user-attachments/assets/686141e8-3ad6-4003-9d26-f8cc05d8a30e" />

2. Select the appropriate boss

   <img width="711" height="261" alt="image" src="https://github.com/user-attachments/assets/c5a0b561-bf56-4920-a5b1-fbba0e5b08c8" />

3. Paste the Augmentator3001 note here instead

4. When you're ready to pull a boss, either select 'Set as Personal Note'

    <img width="235" height="52" alt="image" src="https://github.com/user-attachments/assets/556779ee-f1e0-4eef-82f8-313067ef86b2" />

    or set your MRT Notes to autoload per boss in Settings

    <img width="369" height="97" alt="image" src="https://github.com/user-attachments/assets/ef03f422-3bc0-46db-b057-7a64f04362c6" />

## Advanced Usage - Custom EM Timings

TO BE COMPLETED

## FAQs

**Do I need the note visible during the boss fight for the Weakaura to work?**
- You don't need your MRT note visible for the Weakaura to function. You can disable the note to hide it

  <img width="323" height="62" alt="image" src="https://github.com/user-attachments/assets/39a0240b-275a-4245-b341-50be655712f1" />

**My raid group has many players with alt-chars in their name, how can I import them easily?**
- You can add a custom log containing those players, import the DPS characters from it and then delete the log

**How can I change the colour of the Prescience frame glow?**
- Search for `local color =` in the Weakaura code and adjust it to your preference
- The format is `{R, G, B, Alpha}`
- Blue would be `local color = {0, 0.3, 1, 1}`
- Green would be `local color = {0, 1, 0, 1}`

**My logs or best pulls aren't being populated, what is wrong?**

- Ensure you have selected the correct boss encounter
- Ensure your logs aren't private
- You might be limited by the Warcraft Logs API, check at the bottom of the [Warcraftlogs settings page](https://www.warcraftlogs.com/profile)

**Can you support private logs?**
- I don't know but I don't think so

**Does Xeph eat breakfast?**
- Originally he was grey parsing but has improved

