<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket. We'll be using our Admin account to define everything and setting up the environment so that it's ready to be used.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machine Windows 10 Pro)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10 Pro</b>

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure osTicket
- Configure Agents
- Configure Users
- Configure SLAs
- Configure Help Topics

<h2>Configuration Steps:</h2>

- Configure Roles. Observations: We'll be creating a Supreme Admin Role that will do anything from creating tickets, deleting tickets, etc.

![Annotation 2024-07-05 132315](https://github.com/erik-salgado/post-install-config/assets/173113320/49aea764-f3cd-4298-a4d8-ed0a29f77bd8)
![Annotation 2024-07-05 132414](https://github.com/erik-salgado/post-install-config/assets/173113320/34027adc-0399-4cbf-8c9c-0af086618874)
![Annotation 2024-07-05 132455](https://github.com/erik-salgado/post-install-config/assets/173113320/a04e6c8e-e9b4-4349-a33a-904f6e834af9)
![Annotation 2024-07-05 132531](https://github.com/erik-salgado/post-install-config/assets/173113320/8a4bea3c-c68e-4a35-836d-ffb65ec66fe4)
![Annotation 2024-07-05 132555](https://github.com/erik-salgado/post-install-config/assets/173113320/f270e1a3-e759-4180-b916-3aa0b809ce71)
![Annotation 2024-07-05 132714](https://github.com/erik-salgado/post-install-config/assets/173113320/4ae5e768-5ec4-4cf3-bb49-9641f7cda02f)

- Configure Departments.

![Annotation 2024-07-05 133045](https://github.com/erik-salgado/post-install-config/assets/173113320/77bcf0a9-ef7e-4b7b-a713-60ca4e7e9450)
![Annotation 2024-07-05 133214](https://github.com/erik-salgado/post-install-config/assets/173113320/a21fad16-50dd-4f69-a700-0c4bb3e399b4)
![Annotation 2024-07-05 133311](https://github.com/erik-salgado/post-install-config/assets/173113320/3ef2d716-4af1-4412-b3d6-3a24f71ac68a)

- Configure Teams.

![Annotation 2024-07-05 133708](https://github.com/erik-salgado/post-install-config/assets/173113320/b5acb7ba-7bef-4e7c-9def-59fc8f1193c9)
![Annotation 2024-07-05 133814](https://github.com/erik-salgado/post-install-config/assets/173113320/69cd106b-a125-4020-b575-15797ca11e59)
![Annotation 2024-07-05 135249](https://github.com/erik-salgado/post-install-config/assets/173113320/5a652adc-a8de-4209-9e3e-45b7610e0a3e)
![Annotation 2024-07-05 133853](https://github.com/erik-salgado/post-install-config/assets/173113320/901857e5-828e-42be-b224-f3eeb44e45eb)

- Configure osTicket. Observations: We'll be allowing anyone to create tickets, even anonymous users can create tickets even though they are not a user in the system. Make sure to leave the box unchecked under Authentication Settings > Registration Required.

![Annotation 2024-07-05 134548](https://github.com/erik-salgado/post-install-config/assets/173113320/107297fa-0aeb-4d02-b9ac-ca16f30a2d0b)

- Configure Agents. Observations: In this Lab the agents will be the actual help desk professionals who are going to check and resolve tickets. Assign the agent in the department of System Administrators and add them to the Level II Support Team.

![Annotation 2024-07-05 134808](https://github.com/erik-salgado/post-install-config/assets/173113320/067543b7-5127-4cc0-849c-34f81c92fdec)
![Annotation 2024-07-05 135045](https://github.com/erik-salgado/post-install-config/assets/173113320/75fc3392-4855-47e4-b798-fc6964d3bb59)
![Annotation 2024-07-05 135122](https://github.com/erik-salgado/post-install-config/assets/173113320/9c6bb2df-b08c-4f84-88a3-d22ed973300c)
![Annotation 2024-07-05 135231](https://github.com/erik-salgado/post-install-config/assets/173113320/a33770f5-6f8d-4c5e-aa57-2345b5a58942)
![Annotation 2024-07-05 135249](https://github.com/erik-salgado/post-install-config/assets/173113320/e0ca4cd6-8e7b-4db0-af75-1cb23be40ff9)
![Annotation 2024-07-05 135609](https://github.com/erik-salgado/post-install-config/assets/173113320/4d698a81-0a11-4972-b2ab-610b6409e1ff)

- Configure Users. Observations: These will be the actual customers.

![Annotation 2024-07-05 135700](https://github.com/erik-salgado/post-install-config/assets/173113320/aefea3a4-67e4-45d9-b528-399d97b53023)
![Annotation 2024-07-05 135922](https://github.com/erik-salgado/post-install-config/assets/173113320/43f1debc-4e16-4e3b-ab59-4d215beca443)
![Annotation 2024-07-05 135959](https://github.com/erik-salgado/post-install-config/assets/173113320/efa3ac61-a747-45a7-92ad-5a72c66f9b55)
![Annotation 2024-07-05 140123](https://github.com/erik-salgado/post-install-config/assets/173113320/3ad88e7b-0c1a-41b0-beb9-2c2f4624f0ca)
![Annotation 2024-07-05 140142](https://github.com/erik-salgado/post-install-config/assets/173113320/2b2446ad-3f70-434c-84ff-855253ac05a7)

- Configure SLAs. 

![Annotation 2024-07-05 140312](https://github.com/erik-salgado/post-install-config/assets/173113320/12067708-186a-4320-b5cc-357c14260ab9)
![Annotation 2024-07-05 140433](https://github.com/erik-salgado/post-install-config/assets/173113320/2c2bf204-08ed-41fd-b201-0e75e7856583)
![Annotation 2024-07-05 140703](https://github.com/erik-salgado/post-install-config/assets/173113320/50cd909d-30a7-4fce-953d-7461e7a91352)
![Annotation 2024-07-05 140809](https://github.com/erik-salgado/post-install-config/assets/173113320/7fb9e33a-c81f-4da7-a3eb-871cce1ada80)
![Annotation 2024-07-05 140832](https://github.com/erik-salgado/post-install-config/assets/173113320/16ab773c-29ae-4346-9579-1fa813781023)

- Configure Help Topics

![Annotation 2024-07-05 140914](https://github.com/erik-salgado/post-install-config/assets/173113320/366c6edd-1a1b-48de-a552-306bf29857eb)
![Annotation 2024-07-05 141026](https://github.com/erik-salgado/post-install-config/assets/173113320/a96bc320-0d62-4094-9113-a790536ea896)
![Annotation 2024-07-05 141124](https://github.com/erik-salgado/post-install-config/assets/173113320/f5cc86fb-5502-4ad5-9fca-5cdbcf8cd908)
![Annotation 2024-07-05 141213](https://github.com/erik-salgado/post-install-config/assets/173113320/f748b6bb-61a9-4ed1-9562-0903ac701a32)
![Annotation 2024-07-05 141254](https://github.com/erik-salgado/post-install-config/assets/173113320/2e77fc04-4bd6-419d-9179-2adf7f404923)
![Annotation 2024-07-05 141316](https://github.com/erik-salgado/post-install-config/assets/173113320/faec851d-8f58-4b2e-8583-290fa1626258)

This brings the conclusion for this lab, thank you for watching! :)
