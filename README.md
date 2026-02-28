# Check-in simples com QR Code

Aplicativo web mínimo em Flask:
- Página inicial mostra um **QR Code** para abrir o formulário.
- Usuário digita o nome.
- O nome é salvo localmente no arquivo **`nomes.xlsx`**.

## Como executar

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python app.py
```

Acesse: `http://localhost:5000`

## Arquivo gerado

Depois do primeiro envio, o arquivo `nomes.xlsx` será criado na raiz do projeto.
