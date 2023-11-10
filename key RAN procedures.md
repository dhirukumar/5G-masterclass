- *Cell search*= Procedure by which a UE acquires time and frequency synchronization with a cell and detects the cell Id of that cell
<img width="1440" alt="Screenshot 2023-11-10 at 11 43 17 AM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/ae6a7535-0dd2-464c-b99f-58244c644a6f">
<img width="1440" alt="Screenshot 2023-11-10 at 11 43 23 AM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/379756c8-cac1-453b-9bdf-73c3880dfae9">
<img width="1440" alt="Screenshot 2023-11-10 at 11 43 30 AM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/cb823389-6c47-4ed7-bf72-8bb72b5b0f79">
*Working of cell search*
- In LTE there are tens of different bands, UE starts scanning a set of frquency band that is preferred. This informationis available in SIM card
- In LTE carrier raster is equal to synchronization raster which is 100kHz
- In LTE sync signals are transmitted every 5ms
- In NR there are much more bands than LTE
- In NR sync signals are transmitted every 20ms before checking next possible location
-  To improve the efficiency the Sync raster and carrier raster are decoupled
-  <img width="1440" alt="Screenshot 2023-11-10 at 11 43 36 AM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/0a76c9e5-d273-41fb-ad5f-3b4bc5a4943e">
- PSS can take one of  the three possible values
- SSS can take 336 possible values
- <img width="1440" alt="Screenshot 2023-11-10 at 11 43 43 AM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/9e980bca-ddba-483c-84a0-bd9c6d7533f5">
<img width="1440" alt="Screenshot 2023-11-10 at 11 43 49 AM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/37eca5a8-e99e-4939-aaa8-ae8820f83e33">
<img width="1440" alt="Screenshot 2023-11-10 at 11 43 57 AM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/38c9dfce-a58f-4425-8ebf-1e3ce58e2da1">
<img width="1440" alt="Screenshot 2023-11-10 at 11 44 04 AM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/2e8559d4-ade9-490f-9b1c-186f32fed68a">
<img width="1440" alt="Screenshot 2023-11-10 at 11 44 10 AM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/632328ef-3bc6-49f8-8d0d-d8cd3466dd18">
- UE decides if to camp or not
<img width="1440" alt="Screenshot 2023-11-10 at 11 49 58 AM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/fbdea69c-895f-4a99-a6ab-fe48b486b73f">
- *Triggers when*
   - RRC idle to RRC connected
   - Uplink data
   - Sync lost
   - Sync during handover
 <img width="1440" alt="Screenshot 2023-11-10 at 11 50 04 AM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/79e4b0f7-7900-4b90-ade3-519eba4e3838">
<img width="1440" alt="Screenshot 2023-11-10 at 11 50 11 AM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/87da7fe1-f15a-4c73-b604-4b9dc6744d88">
<img width="1440" alt="Screenshot 2023-11-10 at 11 50 18 AM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/10f509c0-40a1-427d-aa2b-c95dbc442072">
<img width="1440" alt="Screenshot 2023-11-10 at 11 50 24 AM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/8fc3e500-a681-4541-8081-984a18353a6d">
<img width="1440" alt="Screenshot 2023-11-10 at 11 50 30 AM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/1381709e-c1bd-454c-9f60-d741804c592e">
- Same preamble= same temp ID = Collision
<img width="1440" alt="Screenshot 2023-11-10 at 11 50 36 AM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/cee13b89-906b-4448-8143-e66edc695c5e">
<img width="1440" alt="Screenshot 2023-11-10 at 11 50 42 AM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/91169d67-556d-4444-ab63-1eea2d4b76b5">
<img width="1440" alt="Screenshot 2023-11-10 at 11 50 48 AM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/5953e650-145a-443b-9c9e-fb045af2e5e8">
<img width="1440" alt="Screenshot 2023-11-10 at 11 50 54 AM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/28d60658-22e2-4f44-92e2-91319c8c4311">
- *Triggers*:
   - Handover
   - DL data for UE
   - Non stand alone mode, NR cell

- gNB makes sure that id does not give same preamble to more than 1 device
- CBRA is triffered by UE whereas CFRA is triggered by gNB
<img width="1440" alt="Screenshot 2023-11-10 at 11 51 00 AM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/e5ad493c-608e-4938-98b6-bdd5e46ad353">
<img width="1440" alt="Screenshot 2023-11-10 at 11 51 06 AM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/b5320f3c-7244-4642-a011-9c4e73ba9bc4">















