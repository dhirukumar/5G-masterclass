<img width="1440" alt="Screenshot 2023-11-09 at 8 00 51 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/e08002ea-e17a-4538-a0e8-a2f3b9fea6db">

- There are two types of RAN protocol stack

- UPPS-Supports carrying user data between different network and UE
  
- CPPS-Carry control information between UE and core network
<img width="1440" alt="Screenshot 2023-11-09 at 8 00 57 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/02e02dd7-1e25-4655-bc89-39d99ef37391">

- SDAP layer is to support quality of service
  
- Each down layer provides services to upper layers.

<img width="1440" alt="Screenshot 2023-11-09 at 8 01 03 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/7460f18b-f6b9-4a7f-938f-0a712ffd5080">

## User plane protocol stack

1.Physical Layer(PHY) - For Efficient wireless communication.

2.Medium access control layer(MAC) - Retransmission, multiplexing/demultiplexing and secheduling

3.Radio link control layer(RLC)- ARQ(Automatic repeat query) segmentation

4.Packet data convergence protocol(PDCP)-Header compression, ciphering and intergrity protection and duplicate removal.

5.Service data adaption protocol(SDAP)-Quality of service

<img width="1440" alt="Screenshot 2023-11-09 at 8 01 12 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/4c4cd825-8788-4d7a-aa5e-e15292789017">
<img width="1440" alt="Screenshot 2023-11-09 at 8 01 22 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/5cf0d759-efd4-424e-b918-ebfdcee74528">
<img width="1440" alt="Screenshot 2023-11-09 at 8 01 31 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/6500c1c4-c2b7-45ba-9f5b-36b5d0005f7e">
<img width="1440" alt="Screenshot 2023-11-09 at 8 01 37 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/46707a3b-647f-45f3-9253-4013463a7313">
<img width="1440" alt="Screenshot 2023-11-09 at 8 01 44 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/dc07c74e-6ccd-46ff-a1d1-0054d829f047">
<img width="1440" alt="Screenshot 2023-11-09 at 8 01 50 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/81a685cc-271a-4cf1-9ce0-06887402f4bd">
<img width="1440" alt="Screenshot 2023-11-09 at 8 01 56 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/e451a59a-7b66-45f7-b225-ac2bf503f28e">

## Control plane protocol stack

1.Non access stratum(NAS)- Authentication, security and idle model procedures also assigns IP address 2.Radio resource control(RRC)-System information, radio bearers and measurement configuration; responsbile for RAN related control plane procedures i.e broadcasting systum


<img width="1440" alt="Screenshot 2023-11-09 at 8 02 03 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/d68d790f-13af-43fd-a78c-79692aaaa7b6">
<img width="1440" alt="Screenshot 2023-11-09 at 8 02 10 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/96a005e3-a362-42f1-8c79-08839170933a">
<img width="1440" alt="Screenshot 2023-11-09 at 8 02 16 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/0e197e8b-27d2-44ae-ae4c-d113069011df">
<img width="1440" alt="Screenshot 2023-11-09 at 8 02 24 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/5df1227e-f197-48aa-be1a-3d82e352adb1">
<img width="1440" alt="Screenshot 2023-11-09 at 8 05 07 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/4e01fbe9-209b-4ce0-9467-8b08b85a1e5a">

- ### type of trafic
  
<img width="1440" alt="Screenshot 2023-11-09 at 8 05 14 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/f06f8cb8-86d9-4352-b3bb-30b084c2dc58">

- #### QoS flows
  - When addtional QoS flow is required it can be established when corresponding application triggers traffic.
<img width="1440" alt="Screenshot 2023-11-09 at 8 05 20 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/faf42585-66c9-4cf8-8dd6-b858e2eb6823">

- QoS flow types
  
  - GBR- Guranteed bit rate QoS flow
  
- Non- GBR- Used for traffic that are more bursty in nature

- Delay critical- for self driving cars and remote control devices

<img width="1440" alt="Screenshot 2023-11-09 at 8 05 26 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/be74f93c-faef-4c65-8186-7d91d0ce9ce3">
<img width="1440" alt="Screenshot 2023-11-09 at 8 05 34 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/64cf1377-c012-4c9b-821b-147080e7c096">
<img width="1440" alt="Screenshot 2023-11-09 at 8 05 47 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/e40c79df-53f6-4011-9175-fd4391f8388b">
<img width="1440" alt="Screenshot 2023-11-09 at 8 05 53 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/e966d39a-47dd-4366-833a-cd4e1d3623f1">
<img width="1440" alt="Screenshot 2023-11-09 at 8 05 59 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/d37b4519-a690-4466-8a97-0a990ab1f6f2">
<img width="1440" alt="Screenshot 2023-11-09 at 8 06 05 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/5df484b4-581c-4c32-8a8f-2c9119806b23">
<img width="1440" alt="Screenshot 2023-11-09 at 8 07 36 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/4e81d21c-2523-421e-ac05-5e8fa9cd17fd">
<img width="1440" alt="Screenshot 2023-11-09 at 8 07 44 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/596f200c-8767-49d9-baa7-afd52c8befd4">

## PDCP(Packet data convergence protocol)
  - Fucntions of PDCP

- Header compression
  
- Ciphering and integrity protection
  
- Routing and duplication of split bearers
  
- In sequence delivery

<img width="1440" alt="Screenshot 2023-11-09 at 8 07 50 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/7fb400d0-bbde-4424-b6b0-c37add7f991b">

- For small data packets, header itself would itself be as long as data packet.
  
- PDCP performs header compression to reduce header length to a couple of bytes for wireless trasmission
  
- Decompression of header size before it is transmitted over IP protocols in the wired network is also done by PDCP
  
- The header compression scheme is based on Robust header Compression(ROHC) protocol
  
<img width="1440" alt="Screenshot 2023-11-09 at 8 07 57 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/19fe9faa-d31e-464e-baf3-2b33b8542128">
<img width="1440" alt="Screenshot 2023-11-09 at 8 08 03 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/0b5e9984-4490-4a34-99bb-9bd241434199">
<img width="1440" alt="Screenshot 2023-11-09 at 8 08 09 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/0aa61871-d8a1-4379-b276-ceebc26e7a56">

- If one fails , UE's can recieve data from the other bearer.
  
- In recieving side PDCP is responsible for discarding the duplicates and picking the packet (selection diversity) if there is an error in any radio bearers
  
<img width="1440" alt="Screenshot 2023-11-09 at 8 08 15 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/a0f894f4-2614-4dbf-a00e-72674246e13c">

- PDCP acts as a sequence number to ensure in-sequence delivery
  
<img width="1440" alt="Screenshot 2023-11-09 at 8 19 41 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/2a7460af-70e5-492f-a3f3-73c99d36ada8">
<img width="1440" alt="Screenshot 2023-11-09 at 8 19 47 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/fcc2455d-373e-48f3-85fe-bf0b600f2edf">
<img width="1440" alt="Screenshot 2023-11-09 at 8 19 54 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/7dd3debe-cf62-4236-a394-45dce64e4ca6">

## RLC(Radio Link Control

- Function of RLC
 
  - Segmentation
    
- ARQ - Retransmissions
  
<img width="1440" alt="Screenshot 2023-11-09 at 8 20 00 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/ba8f4e91-335d-4556-91b9-36c8dd9f39ef">

- Transparent mode- In these cases the channels are already designed in such a way that there is no need for segmentation and retransmission
  
- Unacknoledged mode - When error free delivery is not required
  
- Acknowlaged mode- For web browsing , file transfer etc.
  
<img width="1440" alt="Screenshot 2023-11-09 at 8 20 06 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/4f475b3c-3ebc-405e-ba65-680d7b083c2e">

- 6 and 12 bits for unacknowledged mode
  
- 12 and 18 bits for acknowledged mode
  
- In case of segmentation each SDU carries same sequence number as unsegmented SDU
  
- RLC PDU are assembled as soon as possible without waiting and the MAC layer performers the concatination depending on the trasferred larger size which ultimately helps in low latency applications.
  
- In LTE the PDU's are also concatenated to one big PDU, in NR this is not done by RLC layer.

<img width="1440" alt="Screenshot 2023-11-09 at 8 20 14 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/af6a8676-0c80-4291-8fb4-53a65859c9ab">

### Retransmissions
- In LTE, RLC takes care of in sequence delivery
  
- In NR this is taken care by PDCP because of two reasons:
  
  - Latency
    
  - Buffering requirements
    
<img width="1440" alt="Screenshot 2023-11-09 at 8 20 20 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/7626e820-6c85-409e-aad7-432f15c78b5b">
<img width="1440" alt="Screenshot 2023-11-09 at 8 20 26 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/9464ae04-bbba-46fd-a668-0b6f9371afb4">
<img width="1440" alt="Screenshot 2023-11-09 at 8 20 32 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/4206e14d-82dc-42ff-af93-cb1268d8c193">
<img width="1440" alt="Screenshot 2023-11-09 at 8 20 38 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/923d4ea4-58fa-43e0-a611-fde4ce925d40">
<img width="1440" alt="Screenshot 2023-11-09 at 8 20 44 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/04b256fa-5940-463f-8079-78e1a1636c80">
<img width="1440" alt="Screenshot 2023-11-09 at 8 20 51 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/3084e565-f221-49f2-a888-de360c967ae9">
<img width="1440" alt="Screenshot 2023-11-09 at 8 20 57 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/a966d48b-731e-4d56-b394-9f51d61258f6">
<img width="1440" alt="Screenshot 2023-11-09 at 8 21 03 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/d0578542-630a-4825-bc20-cfd9e25712aa">
<img width="1440" alt="Screenshot 2023-11-09 at 8 29 03 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/7e8dc66b-a5fa-47c4-bcb4-0afbe567395a">
<img width="1440" alt="Screenshot 2023-11-09 at 8 29 11 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/290026fe-c21f-47bb-bad0-2a7337f49bf1">
<img width="1440" alt="Screenshot 2023-11-09 at 8 29 17 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/d1781803-dfb0-4cbf-be2b-f43582353fa3">
<img width="1440" alt="Screenshot 2023-11-09 at 8 29 23 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/c60766d4-d224-46b8-becf-6bd44be40981">
<img width="1440" alt="Screenshot 2023-11-09 at 8 29 31 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/d38bcc07-4dea-4e51-9250-96b4646ff272">
<img width="1440" alt="Screenshot 2023-11-09 at 8 29 37 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/e86e6712-fcd3-41e2-8b8d-fefca6185fcb">
<img width="1440" alt="Screenshot 2023-11-09 at 8 29 43 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/12fb1e93-1d67-4258-9952-5f3a9b1de5e7">
<img width="1440" alt="Screenshot 2023-11-09 at 8 29 49 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/306b4758-6db8-4824-ade7-f8a1c8fa98b0">
<img width="1440" alt="Screenshot 2023-11-09 at 8 29 56 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/c67b9bde-a378-4cb3-a9cb-17e33b6e7c84">
<img width="1440" alt="Screenshot 2023-11-09 at 8 30 02 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/22ee4448-8b34-41a1-b173-82ef5e869748">
<img width="1440" alt="Screenshot 2023-11-09 at 8 32 14 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/6698f06f-923c-4840-91af-8eb7d686e230">
<img width="1440" alt="Screenshot 2023-11-09 at 8 32 21 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/5be5251f-281f-4d98-9230-fc6920baf8f5">
<img width="1440" alt="Screenshot 2023-11-09 at 8 32 27 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/9562b642-c1bd-444c-9b8d-048d87b6abbb">
<img width="1440" alt="Screenshot 2023-11-09 at 8 32 33 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/91da3dbe-435d-4827-864e-7f2ad28ca7a5">
<img width="1440" alt="Screenshot 2023-11-09 at 8 32 40 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/5b9bd35b-1692-4232-8634-96fcb5756d59">
<img width="1440" alt="Screenshot 2023-11-09 at 8 32 45 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/644d8f9f-1b4e-4642-9411-418195f0771d">
<img width="1440" alt="Screenshot 2023-11-09 at 8 32 54 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/b7702a0e-a922-4857-8252-e89521176940">
<img width="1440" alt="Screenshot 2023-11-09 at 8 33 00 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/eb251964-3c07-44a7-9d48-96bb7a498eaa">
<img width="1440" alt="Screenshot 2023-11-09 at 8 33 06 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/307a7677-256e-4ca9-a261-e0ea14a47a69">
<img width="1440" alt="Screenshot 2023-11-09 at 8 33 12 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/f362f5b0-0f94-4d98-af54-857ccd4adad2">
<img width="1440" alt="Screenshot 2023-11-09 at 8 33 20 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/96f7b9d0-1754-4809-8086-d09c270aac6f">
<img width="1440" alt="Screenshot 2023-11-09 at 8 33 26 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/0dff820c-64a6-4ffe-8c2b-87c097ccc034">
<img width="1440" alt="Screenshot 2023-11-09 at 8 33 32 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/b30e354b-c3b2-4010-8eed-5eb85ab77496">
<img width="1440" alt="Screenshot 2023-11-09 at 8 36 45 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/847d97ba-5c7f-4ad0-870a-6e1144e7dccb">
<img width="1440" alt="Screenshot 2023-11-09 at 8 36 51 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/d04fc735-8b77-48e2-ac5e-cf97225af1ad">
<img width="1440" alt="Screenshot 2023-11-09 at 8 36 58 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/b15850c2-0394-439e-9d4a-9e86de08e05e">
<img width="1440" alt="Screenshot 2023-11-09 at 8 37 04 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/7ebc4819-b251-40bf-a4c2-4b4a65233c9f">
<img width="1440" alt="Screenshot 2023-11-09 at 8 37 10 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/8b02ff37-ea54-4e45-a44d-cde8bbe003c2">
<img width="1440" alt="Screenshot 2023-11-09 at 8 37 16 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/565ad27c-c1f4-4130-955b-75100a68e7cc">
<img width="1440" alt="Screenshot 2023-11-09 at 8 37 24 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/c4d5cf40-7a44-46ef-b82d-e05997f33ef8">
<img width="1440" alt="Screenshot 2023-11-09 at 8 37 30 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/904c1231-9d75-4852-a5e7-e0eb0962cd9d">
<img width="1440" alt="Screenshot 2023-11-09 at 8 37 38 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/cb57be36-5a66-43e3-be26-64
<img width="1440" alt="Screenshot 2023-11-09 at 8 37 38 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/3b004007-3ad1-4b8f-8f0a-1c618fe52357">
<img width="1440" alt="Screenshot 2023-11-09 at 8 37 45 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/240d0f1c-2498-4c97-bf8b-ab9e0b44621d">
<img width="1440" alt="Screenshot 2023-11-09 at 8 37 52 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/2add2436-7475-4072-ab8d-ac50fd2e902d">
<img width="1440" alt="Screenshot 2023-11-09 at 8 38 01 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/884afc2c-8e3c-4446-846a-e4ce1419cce0">
<img width="1440" alt="Screenshot 2023-11-09 at 8 38 08 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/995efe5d-0e08-414f-a54c-3225665bb5ac">
<img width="1440" alt="Screenshot 2023-11-09 at 8 38 15 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/361ffafd-103c-4487-81a1-21df4734929e">
<img width="1440" alt="Screenshot 2023-11-09 at 8 38 21 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/4c1294ad-f812-4865-a401-85b07e96005d">
<img width="1440" alt="Screenshot 2023-11-09 at 8 38 28 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/44e3f03c-5882-4fa5-a4db-d99afe75d627">
<img width="1440" alt="Screenshot 2023-11-09 at 8 44 23 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/a20145a7-b4c4-4205-a88f-1576bb6b256f">
<img width="1440" alt="Screenshot 2023-11-09 at 8 44 29 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/ae2cd7bc-14f5-41b7-9130-e71529f1bac7">
<img width="1440" alt="Screenshot 2023-11-09 at 8 44 36 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/15c4b095-6f2b-488c-a8be-6957119c13fb">
<img width="1440" alt="Screenshot 2023-11-09 at 8 44 42 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/129d86c3-6431-4cdc-b147-380887cd54cc">
<img width="1440" alt="Screenshot 2023-11-09 at 8 44 48 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/d0251ca4-4f6d-4c30-b91a-98a18d9bb18b">
<img width="1440" alt="Screenshot 2023-11-09 at 8 44 54 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/6fceba71-0d02-41cc-bc9c-7abc1e38ebbf">
<img width="1440" alt="Screenshot 2023-11-09 at 8 45 02 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/0f8b8371-7079-4543-bd27-06c7984bfbb1">
<img width="1440" alt="Screenshot 2023-11-09 at 8 45 08 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/ea99d7bf-036c-4bf0-8389-b9936d94c3ce">
<img width="1440" alt="Screenshot 2023-11-09 at 8 45 15 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/0d0fe9a9-baf1-4036-8661-6215d28906b7">
<img width="1440" alt="Screenshot 2023-11-09 at 8 45 21 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/8236478e-e050-45e8-8816-f03aa124bdfc">
<img width="1440" alt="Screenshot 2023-11-09 at 8 46 55 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/3574961a-b3b3-4f16-b3b6-9dd5149b71fa">
<img width="1440" alt="Screenshot 2023-11-09 at 8 47 02 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/c181dbe8-ccae-43c6-a6cf-b9577dba7ff0">
<img width="1440" alt="Screenshot 2023-11-09 at 8 47 08 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/d0e62049-0622-4a81-bc9b-5369bda26321">
<img width="1440" alt="Screenshot 2023-11-09 at 8 47 14 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/92a83f62-8a77-4704-847f-f4919fd0dbd3">
<img width="1440" alt="Screenshot 2023-11-09 at 8 47 20 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/74b3ea19-8703-4b2d-a945-36cf15de07be">
<img width="1440" alt="Screenshot 2023-11-09 at 8 47 26 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/b0b9b2cd-c350-4344-894e-44d51c6edf5b">
<img width="1440" alt="Screenshot 2023-11-09 at 8 47 32 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/7e3a1967-ea83-40a4-a6c8-3b6f3ee95418">
<img width="1440" alt="Screenshot 2023-11-09 at 8 47 39 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/568c5238-722b-4f80-841a-1ebf22dbfa8c">
<img width="1440" alt="Screenshot 2023-11-09 at 8 47 45 PM" src="https://github.com/dhirukumar/5G-masterclass/assets/146316525/738ac83f-eee5-4858-977e-2f64d5a8946e">

















