# Msi-GL72-6QD-Opencore-EFI-monterey
Greetings, I installed this device, I can't say that I did a great job, I didn't have a lot of time. But I still wanted to share in case anyone doesn't know.
System features;
Cpu: I7 6700HQ
Ram: 16 GB Ram 2133mhz
Gpu:  Nvida 950M (disabled) Intel HD Graphics 530 
storage: 128 GB M2 SSD (HFS128G39MNC-3510A Media)  1 TB Hardisk (HGST HTS721010A9E630 Media)
Sound card:Realtek ALC892 (I used vooodooHDA) That's why it's not in EFI
laptop model: MSI GL72 6QD-077XTR
 Working:
 Sound(with VooodooHDA)
 Touchpad
 HDMI
 Bluetooh
 Wi-Fi
 Smbus
 Ethernet
 Not working:
 Sleep 
 external video card (Nvida 950M)
 Camera
 ![Ekran Resmi 2021-11-06 15 26 49](https://user-images.githubusercontent.com/79666042/140609896-16e511ea-beec-4287-a23c-e542fd5254b1.png)
 
![Ekran Resmi 2021-11-06 15 38 06](https://user-images.githubusercontent.com/79666042/140609927-59cd779a-fa5d-455b-b433-c7b55b0f4d22.png)
![Ekran Resmi 2021-11-06 15 38 32](https://user-images.githubusercontent.com/79666042/140609944-a5eec93d-0bfa-4f78-9070-3aed5256c9c1.png)
![Ekran Resmi 2021-11-06 15 39 01](https://user-images.githubusercontent.com/79666042/140610004-326324fb-b0b5-4d85-88b5-f4c27f12a639.png)

Türkçe kısmı (Turkish part)
Selamlar  bu cihaza kurulum yaptım ve paylaşmak istedim. Çok iyi bir iş çıkardığım denilemez ama yinede bilmeyenler için belki yardımı dokunur diye buraya EFI'yi yüklüyorum. 
Sistem parçaları
İşlemci: I7 6700HQ
Bellek: 16 GB Ram 2133mhz
Grafik kartı: Nvida 950M(devre dışı) Intel HD Graphics 530 
Depolama:128 GB M2 SSD (HFS128G39MNC-3510A Media)  1 TB Hardisk (HGST HTS721010A9E630 Media)
laptop modeli: MSI GL72 6QD-077XTR
Çalışanlar:
Ses(vooodooHDA ile)
 Touchpad
 HDMI
 Bluetooh
 Wi-Fi
 Smbus
 Ethernet
 Çalışmayanlar:
 Uyku
 Harici grafik kartı(Nvida 950M)
 Kamera
 
 
 The action to run the sound
First we enter recovery, then we open the terminal, then we write csrutil disable in the terminal and restart the system, we use the tool called kext droplet made by chris1111 https://github.com/chris1111/Kext-Droplet-Big-Sur   After that, we drag the kext to the application and tell it to install it to the L/E location.
We allow the expansion in the Security and Privacy section under system preferences and we want us to restart the system, we say restart. And audio needs work.
