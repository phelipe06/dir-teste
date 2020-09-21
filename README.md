# sousa-hp

import random
##By: felipe
                ##by;; criador phelipe
s = True
n = False
list = [2020, 2021, 2022, 2023, 2024]
nume = random.randrange(1, 9999999999999999)
cvv = random.randint(3, 999)
data1 = random.randrange(1, 31)
data2 = random.randrange(1, 12)
data3 = random.choice(list)
cpf = random.randrange(1, 99999999999)

bi = str(input('ᴠᴏᴄᴇ ᴅᴇsᴇᴊᴀ ɪɴsᴇʀɪʀ sᴜᴀ 𝗕I𝗡? Sim ou Nao?: '))
if bi == 's':
    nume2 = random.randrange(1, 9999999999)
    bin = int(input('Digite sua BIN de 6 digitos : '))
    print('Número do cartão', bin, nume2)
    print('CVV do cartão:',cvv)
    print('Data do cartão:', data1, data2, data3)
    print('CPF cadastrado no cartão:', cpf)
else:
    print('𝙽𝚄𝙼𝙴𝚁𝙾 𝙳𝙾 𝙲𝙰𝚁𝚃𝙰𝙾:',nume)
    print('𝘊𝘝𝘝 𝙳𝙾 𝙲𝙰𝚁𝚃𝙰𝙾:',cvv)
    print('𝙳𝙰𝚃𝙰:',data1,data2,data3)
    print('𝘊𝘗𝘍 𝙲𝙰𝙳𝙰𝚂𝚃𝚁𝙰𝙳𝙾 𝙽𝙾 𝙲𝙰𝚁𝚃𝙰𝙾:',cpf)
