# Augmentator3001
How to use this tool using 2 different methods to output your best buff targets within a given EM window.

## Initial Configuration - you'll only need to do this once
1. Log into [WarcraftLogs](https://www.warcraftlogs.com/api/clients/) and generate an API key

   Example:

   <img width="701" height="208" alt="91ae721d-5d4f-4cc3-894a-815378446399" src="https://github.com/user-attachments/assets/24d1960a-69dd-417e-a25b-ee619b06e4d3" />

2. Complete the WCL Credentials section with the ClientID & ClientSecret you generated and click 'Validate'

   <img width="161" height="30" alt="dbf86c82-dcf8-409f-a3cc-fd06f36eec89" src="https://github.com/user-attachments/assets/77bae82e-fd84-4d96-82c6-9d100c25c98d" />

3. Select your region in the top right corner

## Basic Usage Method #1 - Custom Logs

Use this method to analyse your logs and provide a snapshot of your best targets based on the average results of kills and/or pulls. This is effective for a snapshot but less effective if more logs are coalesced over time due to faster kill times, better gear and smarter play.

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

## Basic Usage Method #2 - Best Logs

Use this method to pull each roster member's best overall performance for a particular boss instead of using provided custom logs. This is effective for longer term usage as it will always provide the 'best' data instead of a snapshot from logs.

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

## Weakaura Integration

1. Navigate to the Weakaura

## Advanced Usage - Custom EM Timings

