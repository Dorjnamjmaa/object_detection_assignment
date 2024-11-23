# object_detection_assignment
1. dataset хавтсанд хуваасан өгөгдлөө байршуулсан
2. dataset.yaml файлд файлуудын зам мөн ангиллуудыг зааж өгсөн
3. Train хийхдээ дараах коммандыг ажиллуулж болно
python yolov5/train.py --img 640 --batch 16 --epochs 5 --data dataset.yaml --weights yolov5s.pt
4. Validation хийхдээ дараах коммандаар ажиллуулж болно
python yolov5/val.py --img 640 --batch 16 --data dataset.yaml --weights yolov5/runs/train/exp9/weights/best.pt

Дэд ангилалуудыг дараах байдлаар индексжүүлсэн
    'a' - 0,  
    'b1 - 1', 'b2 - 2', 'b3 - 3', 'b4 - 4', 
    'c1 - 5', 'c2 - 6',             
    'd1 - 7',                 
    'e1 - 8', 'e2 - 9', 'e3 - 10',       
    'f1 - 11', 'f2 - 12',               
    'g1 - 13', 'g2 - 14', 'g3 - 14',        
    'h1 - 16', 'h2 - 17', 'h3 - 18',        
    'i1 - 19'   