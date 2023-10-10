# Lokaverkefni í KEST1VL
# það sem við gerðum í verkefninu 
1. við byrjuðum á því að setja upp Virtualbox og Ubuntu
2. svo byrjuðum á að búa til hópinn og við notuðum þessi comands til þess: "sudo adduser" og þá setu við nafn maneskunar og notanda nafn og hópana og paswordið þeira.
3. svo gerðum við directorise og aðgangs leyfi fyrir áhveðna notendur. til þess að búa til möppuna gögn notuðum við skipunina "sudo mkdir /Gögn", svo til að búa til undir      möppurnar notuðum við þessar skipanir:
  sudo mkdir /GÖGN/Sameign
  sudo mkdir /GÖGN/Forritun
  sudo mkdir /GÖGN/Markadsmal
4. svo gerðum við það að það þarf pasword til að komast inn í möppurnar
   sudo chown :allir /GÖGN/Sameign
   sudo chmod 2775 /GÖGN/Sameign
  
  sudo chown :forritun /GÖGN/Forritun
  sudo chmod 2775 /GÖGN/Forritun
  
  sudo chown :markadsmal /GÖGN/Markadsmal
  sudo chmod 2775 /GÖGN/Markadsmal

