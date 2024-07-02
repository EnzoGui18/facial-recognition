# Sistema de Controle de Presença Baseado em Reconhecimento Facial
Um sistema de controle de presença integrado com interface gráfica usando reconhecimento facial para registrar a presença.

Neste projeto em Python, desenvolvi um sistema de controle de presença que registra a presença usando técnica de reconhecimento facial. Também integrei com uma interface gráfica (GUI) para ser fácil de usar por qualquer pessoa. A GUI para este projeto também foi feita em Python usando tkinter.

## TECNOLOGIA UTILIZADA:
1) tkinter para toda a GUI
2) OpenCV para captura de imagens e reconhecimento facial (cv2.face.LBPHFaceRecognizer_create())
3) CSV, Numpy, Pandas, datetime etc. para outros fins.

## CARACTERÍSTICAS:
1) Fácil de usar com suporte interativo de GUI.
2) Proteção por senha para o registro de novas pessoas.
3) Cria/Atualiza arquivo CSV com os detalhes dos alunos no registro.
4) Cria um novo arquivo CSV todos os dias para registrar a presença e marca a presença com a data e hora corretas.
5) Exibe atualizações ao vivo da presença do dia na tela principal em formato tabular com ID, nome, data e hora.

## CAPTURAS DE TELA
### TELA PRINCIPAL:
![Screenshot (9)](![WhatsApp Image 2024-06-26 at 21 15 17](https://github.com/EnzoGui18/facial-recognition/assets/81970792/1b70114e-e92a-4acc-8576-176aebe9d03f)
)

### REGISTRANDO PRESENÇA:
![Teste](https://github.com/EnzoGui18/facial-recognition/assets/81970792/3767fc69-4aa0-4e4f-bd93-9ef6264622c1)

### MOSTRANDO PRESENÇA REGISTRADA:
![WhatsApp Image 2024-06-26 at 21 15 16](https://github.com/EnzoGui18/facial-recognition/assets/81970792/1a1c478e-ca0d-4238-82bd-1bb2b66db5f4)

### OPÇÃO DE AJUDA NA BARRA DE MENU:
![Screenshot (12)](https://user-images.githubusercontent.com/37211676/58502152-991d5700-81a3-11e9-861a-9115526010c2.png)

### OPÇÃO DE MUDANÇA DE SENHA:
![Screenshot (13)](https://user-images.githubusercontent.com/37211676/58502146-97539380-81a3-11e9-8536-0c68160ecc55.png)
