=== SISTEMA AUTOPECAS PRO ===

INSTALACAO:
1. Instale Python 3.10+ (https://python.org)
2. Abra o terminal na pasta sistema_autopecas
3. Execute: pip install flask requests openai

CONFIGURACAO (OBRIGATORIA):
Abra o arquivo services.py e substitua:
- API_PLACA_TOKEN = "SEU_TOKEN_PLACA_AQUI"
  -> Crie conta em: https://placafipe.com.br ou https://apiplacas.com.br

- OPENAI_API_KEY = "SUA_CHAVE_OPENAI_AQUI"
  -> Crie chave em: https://platform.openai.com/api-keys
  -> Modelo usado: gpt-3.5-turbo (custo muito baixo)

RODAR:
  python app.py

ACESSAR:
  http://127.0.0.1:5000

FUNCIONALIDADES:
- Consulta por placa (via API externa)
- Consulta manual: modelo / ano / motor / bloco
- Catalogo completo: motor, suspensao, freio, ignicao, transmissao, filtros, eletrico, direcao, oleos
- Assistente IA com codigos de pecas (NGK, Wega, Bosch, Delphi, Sabo, Perfect, Nakata, Cofap...)
- Chat com historico e contexto de veiculo

