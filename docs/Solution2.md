# ถ้าติดตั้งและเปิดม็อดแล้วเข้าเกมผ่าน launcher แล้วม็อดยังไม่ทำงาน

## วิธีแก้ที่ 1 (Windows OS)
1. ไปที่โฟลเดอร์เกม HOI4 คือ C:/Program Files/Steam/Steamapps/common/hearts of iron IV
2. รัน "launcher-installer-windows.exe" จะมีหน้าต่างขึ้นมา ให้ทำการ uninstall Paradox Launcher v2
3. รันเกม HOI4 ผ่าน Steam ตัว Paradox Launcher ก็จะติดตั้งของมันเองอัตโนมัติ ทดลองลองเข้าเกมผ่าน Launcher

## วิธีแก้ที่ 2 (Windows OS)
1. ออก Steam แล้วเข้า Steam ใหม่โดยใช้สิทธิ์ Administrator (คลิกขวาที่ Steam.exe > Run as administrator)
2. รันตัวเกม "hoi4.exe" โดยตรง ที่โฟลเดอร์เกม HOI4 คือ C:/Program Files/Steam/Steamapps/common/hearts of iron IV
3. ออก Steam แล้วเข้าไป uninstall โปรแกรม Paradox Launcher โดยกดปุ่ม Start > Settings > Apps > Paradox Launcher v2 หรือจะลบทาง Control Panel ก็ได้ จากนั้นเข้าเกมอีกครั้งมันจะให้เราติดตั้ง Paradox Launcher ใหม่ ให้เราตกลงติดตั้งตามนั้นคิดว่าปัญหาน่าจะหมดไป แต่ถ้ายังไม่ได้อีกให้ลองทำตามด้านล่างนี้

 ### ขั้นที่ 1 : ลบไฟล์หรือโฟลเดอร์ทุกอย่างที่ launcher สร้างขึ้นที่ C:\Users\\{ชื่อผู้ใช้}\Documents\Paradox Interactive\Hearts of Iron IV
 1. ลบโฟลเดอร์ ".launcher-cache"
 2. ลบไฟล์ "dlc_load.json"
 3. ลบไฟล์ "game_data.json"
 4. ลบไฟล์ "mods_registry.json" (ถ้ามี)
 5. ลบโฟลเดอร์ "mod"

 ### ขั้นที่ 2 : Uninstall launcher และลบไฟล์ settings
 1. uninstall โปรแกรม Paradox Launcher โดยกดปุ่ม Start > Setting > Apps > Paradox Launcher v2 หรือจะลบทาง Control Panel ก็ได้ 
 2. ออก Steam 
 3. ลบไฟล์หรือโฟลเดอร์ดังต่อไปนี้ (ถ้ามี):
   - C:\Users\\{ชื่อผู้ใช้}\AppData\Roaming\Paradox Interactive\launcher-v2
   - C:\Users\\{ชื่อผู้ใช้}\AppData\Local\Paradox Interactive\launcherpath
   - C:\Users\\{ชื่อผู้ใช้}\AppData\Local\Paradox Interactive\launcher-v2

 ### ขั้นที่ 3 : 
 1. เข้า Steam โดยใช้สิทธิ์ Administrator (คลิกขวาที่ Steam.exe > Run as administrator) 
 2. เข้าเกมผ่าน Launcher 


อ้างอิง:
https://support.paradoxplaza.com/hc/en-us/articles/360010684620-My-launcher-doesn-t-work-my-game-wont-s-start-
