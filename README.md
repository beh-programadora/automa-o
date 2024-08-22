# Projeto de Automação de Envio de Email com PyAutoGUI

Este projeto demonstra o uso do PyAutoGUI para automatizar o envio de um email no Gmail. O script abre o navegador, acessa o Gmail em uma janela anônima, faz login, compõe e envia um email automaticamente.

## Funcionalidades

- Abre o navegador e acessa o Gmail.
- Faz login em uma conta do Gmail.
- Compõe um novo email, preenchendo o destinatário, assunto e corpo do email.
- Envia o email automaticamente.

## Requisitos

- Python 3.x
- Biblioteca: `pyautogui`, `time`

Você pode instalar a biblioteca necessária executando:
```bash
pip install pyautogui
Como Executar
1.Clone este repositório:
git clone https://github.com/seu-usuario/nome-do-repositorio.git
2.Navegue até o diretório do projeto:
cd nome-do-repositorio
3.Abra o arquivo Python (automacao_email.py) e insira seu email, senha, destinatário, assunto e mensagem onde indicado no código.
4.Execute o script Python:
python automacao_email.py
Notas Importantes
Credenciais: Não é recomendado armazenar credenciais de email diretamente no código. Use este script apenas para fins de aprendizado e testes em contas de email secundárias.
Certifique-se de que as coordenadas de clique (pyautogui.click) estão corretas para a sua tela. Você pode precisar ajustar essas coordenadas se a resolução ou layout do seu sistema for diferente.
O tempo de espera (time.sleep) pode precisar de ajustes dependendo da velocidade do seu sistema e da conexão com a internet.
Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

Licença
Este projeto é licenciado sob a MIT License.
