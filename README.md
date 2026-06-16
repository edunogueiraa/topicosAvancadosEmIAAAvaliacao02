

## Criação de um ambiente virtual:

### Criação da venv
```bash
python -m venv .venv
```

### Ativação do ambiente
```bash
source .venv/bin/activate
```
### Desativação do ambiente:
```bash
deactivate
```

## Instalar dependências

```bash
pip install -r requirements.txt
```

## Executando o Servidor
```bash
# Opção 1: direto pelo Python
python main.py

# Opção 2: via uvicorn (recomendado)
uvicorn main:app --host 0.0.0.0 --port 8000 --reload
```
Acesse: **http://localhost:8000**


## Desenvolvedor

Eduardo Nogueira da Silva

![edunogueiraa](https://avatars.githubusercontent.com/u/102708905?v=4)