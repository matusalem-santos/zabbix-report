# Objetivo 

Criar relatório de todas as triggers de um Zabbix Server

## Dependencias 

- Python3
- Modulo openpyxl do python3(pip3 install openpyxl)
- Modulo pyzabbix do python3(pip3 install pyzabbix)


## Modo de usar

- Depois de dar um clone no repositório, acesse o diretório **zabbix-report** onde o script **zabbix-report.py** está armazenado 
- Executar o script **zabbix-report.py** passando os parâmetros necessários:
```bash
python3 zabbix-report.py "https://seu-zabbix.com/zabbix" "user_zabbix" "senha_zabbix" "nome_output"
```

