# Api-mensagem-autom-tica-Whatsapp
Api mensagem automática Whatsapp


import pywhatkit 
telefone_numero = 'NUMERO DE TELEFONE'
#Mensagem para mandar"
mensagem = 'Mensagem enviada'
horas = 13
minutos = 42
pywhatkit.sendwhatmsg(telefone_numero, mensagem, horas, minutos)
print("Mensagem enviada")
