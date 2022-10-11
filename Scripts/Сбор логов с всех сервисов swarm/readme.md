С OS Windows(Необходимо что бы был установленн  putty)
plink IP -ssh -batch -l USER -pw "PASS" "cd logs && ./get_stack_logs.sh PMP --since=2m --until=2s"


Скачай файлы get_stack_logs.sh и skipt.py

Поправь в файле skipt.py Указать свои верные данные
host = 'IPorNAME'
user = 'USER'
secret = 'PASSWORD'

Запусти skipt.py