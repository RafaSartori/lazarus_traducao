# lazarus_traducao
Exemplo em Lazarus com as mensagens traduzidas para o português

Para traduzir um programa em Lazarus seguir os seguintes passos:

1) Entrar em Projeto / Opções de Projeto / "i18n"

![image](https://github.com/user-attachments/assets/4dee9402-37e9-4bbd-9c5f-06f75b2e2a90)

2) Informar um "Diretório de Saída PO"
3) Copiar o arquivo "lclstrconsts.pt_BR.po" na "pasta do Lazarus\lcl\languages" para a pasta criada dentro do seu sistema, neste caso "languages"
4) No Formulário Principal dar um Uses em "LCLTranslator"
5) No OnCreate do Formulário Principal dar um SetDefaultLang('pt_BR')
6) A pasta "languages" deve estar sempre junto do seu executável
7) Seja Feliz
