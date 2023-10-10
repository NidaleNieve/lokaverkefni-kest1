# Lokaverkefni í KEST1VL
# það sem við gerðum í verkefninu 
1. við byrjuðum á því að setja upp Virtualbox og Ubuntu
2. svo byrjuðum á að búa til hópinn og við notuðum þessi comands til þess: "sudo adduser" og þá setu við nafn maneskunar og notanda nafn og hópana og paswordið þeira.
3. svo gerðum við directorise og aðgangs leyfi fyrir áhveðna notendur. til þess að búa til möppuna gögn notuðum við skipunina "sudo mkdir /Gögn", svo til að búa til undir      möppurnar notuðum við þessar skipanir:
  sudo mkdir /GÖGN/Sameign
  sudo mkdir /GÖGN/Forritun
  sudo mkdir /GÖGN/Markadsmal
4. svo gerðum við þesssa skipun til að komast inn í möppurnar: <br>
   ```sudo chown :allir /GÖGN/Sameign/``` <br>
   við breyttum svo nafninu á möppunum fyrir hverja möppu<br>
   svo notuðum við þetta comand til að búat til pasword<br>
   ```sudo chmod 2775 /GÖGN/Sameign```<br>
   við breyttum svo nafninu á möppunum fyrir hverja möppu<br>
5. svo læstum við aðgangnium hjá Erlendur and Erla og til þess notuðum við þessar skipunir:<br>
    ``` sudo passwd -l erlendur ```<br>
     ```sudo passwd -l erla ```<br>
   svo til þess að leifa Áslaugu að hafa aðgang að sudo skipunini notuðum við:<br>
      ```sudo usermod -aG sudo aslaug ```<br>
# Leiðbendingar fyrir Áslaugu 
  þetta er allt sem þú þarft að vita.<br>
  til þess að búa til nýan user notaru þetta comand:<br>
   ```sudo useradd -m -s /bin/bash -c "FULL_NAME" -G GROUPS USERNAME ```<br>
  til að búa pasword nottaru þetta comand :<br>
  ``` echo "USERNAME:PASSWORD" | sudo chpasswd ```<br>
  til þess að læsa og aflæsa aðgang notaru þessi comands:<br>
   ```sudo passwd -u USERNAME ``` <br>
   ```sudo passwd -l USERNAME ```<br>
  til þess að búa til möppur notaru:<br>
   ```sudo mkdir DIRECTORY_PATH ```<br>
  til þess að gefa aðganga og búa til password notatur þessi comands:<br>
     ```sudo chown :GROUP_NAME DIRECTORY_PATH ```<br>
     ```sudo chmod 2775 DIRECTORY_PATH ```<br>
# hver gerði hvað
  Daníel gerði allt í terminalinu og leit yfir stafstniga villur
  Pétur gerði allt á git hub 

# Skjáskot:
<img width="699" alt="Screenshot 2023-10-10 at 12 02 29" src="https://github.com/NidaleNieve/lokaverkefni-kest1/assets/62642672/f390a589-666a-43e4-a489-d7700e36ed1d">
<img width="699" alt="Screenshot 2023-10-10 at 12 04 51" src="https://github.com/NidaleNieve/lokaverkefni-kest1/assets/62642672/a01b6232-90a1-42d6-8e2c-c8f3bf80b650">
<img width="729" alt="Screenshot 2023-10-10 at 11 29 22" src="https://github.com/NidaleNieve/lokaverkefni-kest1/assets/62642672/266a3541-9ad1-4167-b293-4c1471d4848c">
<img width="729" alt="Screenshot 2023-10-10 at 11 29 06" src="https://github.com/NidaleNieve/lokaverkefni-kest1/assets/62642672/457df7f9-955b-4e37-9d64-38dc46dda525">



   
  

