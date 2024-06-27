Sistema de Controle de Presença Baseado em Reconhecimento Facial
Um sistema de controle de presença integrado com interface gráfica usando reconhecimento facial para registrar a presença.

Neste projeto em Python, desenvolvi um sistema de controle de presença que registra a presença usando técnica de reconhecimento facial. Também integrei com uma interface gráfica (GUI) para ser fácil de usar por qualquer pessoa. A GUI para este projeto também foi feita em Python usando tkinter.

TECNOLOGIA UTILIZADA:

tkinter para toda a GUI
OpenCV para captura de imagens e reconhecimento facial (cv2.face.LBPHFaceRecognizer_create())
CSV, Numpy, Pandas, datetime etc. para outros fins.
CARACTERÍSTICAS:

Fácil de usar com suporte interativo de GUI.
Proteção por senha para o registro de novas pessoas.
Cria/Atualiza arquivo CSV com os detalhes dos alunos no registro.
Cria um novo arquivo CSV todos os dias para registrar a presença e marca a presença com a data e hora corretas.
Exibe atualizações ao vivo da presença do dia na tela principal em formato tabular com ID, nome, data e hora.
