

# Fast Retopology Decimate Blender
Быстрая оптимизация сетки 3D-модели с помощью модификатора Decimate в Blender


## 01. Включение отображение статистики 
Для отслеживания количества вершин и полигонов необходимо включить отображение статистики в Blender 
- Viewport  Overlays -> Statistics ON
<img width="366" height="240" alt="image" src="https://github.com/user-attachments/assets/e37c083e-e7f3-4d7d-9693-9ec1a9f8ebed" />
<img width="263" height="180" alt="image" src="https://github.com/user-attachments/assets/5434937f-3598-4a93-a173-4bae0c6da4a6" />

## 02. Объединение дублирующих вершин 
Удалить лишние вершины используя Merge By Distance
- Выделить объект -> режим редактирования (tab) -> Merge (M)-> By Distance
<img width="233" height="154" alt="image" src="https://github.com/user-attachments/assets/bf52c4c9-debc-4b5f-9ca4-dc673b09efe4" />
<img width="225" height="27" alt="image" src="https://github.com/user-attachments/assets/9ed77e53-fdf1-43de-bea9-2d37e95c6ac1" />

## 03. Добавление модификатора Decimate 
- Добавлю модификатор Decimate к 3D-модели выставляя значение Ratio 0.1-0.2
<img width="454" height="385" alt="image" src="https://github.com/user-attachments/assets/b2b46a71-b0af-494d-a77e-7bcf01cc885d" />

## 4. Исправление бликов и заломов
- Добавляю модификатор Shade Auto Smooth и WeightedNormal. Weight 100 , Keep Sharp On 
- <img width="412" height="347" alt="image" src="https://github.com/user-attachments/assets/fabb60a1-f3f4-4b17-a29d-58d6c50eb061" />

## 5. Применение модификаторов 
Применяю модификаторы к 3D-модели в следующем порядке  Decimate -> Shade Auto Smooth  ->  WeightedNormal

  
