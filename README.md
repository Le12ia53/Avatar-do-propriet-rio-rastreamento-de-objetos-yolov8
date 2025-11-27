Isso é compatível apenas com ultralytics==8.0.0. No entanto, recomendo fortemente o uso da versão mais recente do pacote Ultralytics e a consulta do código-fonte oficial do Ultralytics aqui: Repositório GitHub .

Emblema Estático

Passos para executar o código
Clone o repositório
https://github.com/RizwanMunawar/yolov8-object-tracking.git
Acesse a pasta clonada.
cd yolov8-object-tracking
Instale o pacote ultralytics
pip install ultralytics==8.0.0
Faça o rastreamento com o comando mencionado abaixo.
#video file
python yolo\v8\detect\detect_and_trk.py model=yolov8s.pt source="test.mp4" show=True

#imagefile
python yolo\v8\detect\detect_and_trk.py model=yolov8m.pt source="path to image"

#Webcam
python yolo\v8\detect\detect_and_trk.py model=yolov8m.pt source=0 show=True

#External Camera
python yolo\v8\detect\detect_and_trk.py model=yolov8m.pt source=1 show=True
O arquivo de saída será criado com runs/detect/traino nome de arquivo original.
Resultados 📊
Rastreamento de objetos YOLOv8s	Rastreamento de objetos YOLOv8m
	
Referências 🔗
🔗 https://github.com/ultralytics/ultralytics
🔗 https://github.com/abewley/sort
🔗 https://docs.ultralytics.com/
Alguns dos meus artigos/trabalhos de pesquisa | Recursos incríveis de aprendizado em visão computacional | Como me apresento ao mundo? 🚀

Título e link do artigo	Data de publicação
Ultralytics YOLO11: Detecção de Objetos e Segmentação de Instâncias🤯	Data de publicação
Gestão de estacionamento usando Ultralytics YOLO11	Data de publicação
Meus projetos de visão computacional como hobby que me renderam dinheiro	Data de publicação
Melhores recursos para aprender visão computacional	Data de publicação
Roteiro para Engenheiro de Visão Computacional	Data de publicação
Como passei o ano de 2022 na área de Visão Computacional	Data de publicação
Mapeamento de características de domínio com YOLOv7 para inspeções automatizadas de estanterias paletizadas baseadas em borda.	Data de publicação
Regeneração de exsudato para detecção automatizada de exsudato em imagens de fundo de olho.	Data de publicação
Mapeamento de características para detecção de defeitos em folhas de arroz baseado em uma arquitetura convolucional personalizada.	Data de publicação
Comparação de desempenho entre YOLOv5, YOLO-X, YOLO-R e YOLOv7: uma pesquisa	Data de publicação
Inteligência Artificial Explicável na Predição da Sensibilidade a Medicamentos em Linhagens de Células Cancerígenas	Data de publicação
Treine o YOLOv8 em dados personalizados.	Data de publicação
