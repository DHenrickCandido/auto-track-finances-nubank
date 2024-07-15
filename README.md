# Auto Track Finances Nubank
Este repositório contém um script em Python que automatiza o processo de rastreamento de seus dados financeiros do Nubank a partir de seus extratos em PDF.

# Funcionalidades
  - Processamento automático de PDFs: O script extrai automaticamente dados relevantes dos seus extratos em PDF do Nubank.
  - Organização de dados: Os dados extraídos são organizados em um arquivo CSV de fácil leitura.
  - Fácil de usar: Basta fornecer o caminho para o seu extrato em PDF do Nubank e o script fará o resto.

# Requisitos
Os seguintes pacotes Python são necessários para executar o script:
  - pdfquery
  - bs4
  - pandas
Você pode instalar esses pacotes usando pip:
`pip install -r requirements.txt`
# Uso
  1. Baixe o seu extrato em PDF do Nubank.
  2. Renomeie o arquivo PDF para Nubank_YYYY-MM-DD.pdf, onde YYYY-MM-DD é a data do extrato.
  3. Coloque o arquivo PDF no mesmo diretório que o script main.py.
  4. Execute o script:
    `python main.py`

O script criará um arquivo CSV chamado out.csv contendo seus dados financeiros.

# Aviso
Este script é fornecido apenas para fins informativos. Não é destinado a ser usado como aconselhamento financeiro ou para quaisquer fins comerciais. O autor não se responsabiliza por qualquer perda ou dano que possa resultar do uso deste script.

# Contribuindo
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request se tiver alguma sugestão ou melhoria.

# Licença
Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE para mais detalhes.






