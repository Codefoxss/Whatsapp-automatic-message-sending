# Whatsapp-automatic-message-sending
These codes can automatically send messages from WhatsApp at certain times.   These codes can automatically send messages from WhatsApp at certain times.  

#"pip install pywhatkit" don't forget to write pls :)
import pywhatkit as kit

number = "+number" #Type the country code of the number you will write
msg = "Whatsapp Bot Testi : Oyunu bırak " #Message to write
hour = 16 #hours
minute = 26 #minute
second = 00 #second

kit.sendwhatmsg(number,msg,hour,minute,second)

#or  

import pywhatkit as kit

kit.sendwhatmsg("Phone Number", "Message","Hours","Minute","second")
