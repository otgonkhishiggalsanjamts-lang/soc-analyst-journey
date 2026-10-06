# soc-analyst-journey
Миний SOC analyst суралцах тэмдэглэл болон лабораторийн ажил

 Нөөц тооцоо
Хостынхоо RAM-ыг доорх хүснэгтээр тааруул. Энэ хуваарийг бүх сургалтын туршид ашиглана.

VM	RAM	CPU	Диск	Хэзээ асаах
Wazuh server (Ubuntu Server 24.04, GUI-гүй)	3.5 GB
indexer heap 1 GB	2	50 GB	Үргэлж
Windows endpoint (Windows Server 2022 Eval, Desktop)	2 GB	2	50 GB	Wazuh-тай зэрэг
Kali Linux (сонголтоор)	1.5–2 GB	2	25 GB	Зөвхөн Windows VM унтарсан үед
Splunk (Ubuntu Server, тусдаа VM)	4 GB	2	40 GB	Зөвхөн ганцаараа, 2-р долоо хоногийн 4 дэх өдөр
Хостод үлдэх	≥ 2.5 GB	—	—	Браузер, Wireshark
