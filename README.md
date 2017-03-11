# context.js
Минималистичная библиотека для расширения возможностей HTML5 Canvas 2D Rendering Context.

## Методы
### CanvasRenderingContext2D.strokeEllipse(centerX, centerY, width, height)                                CanvasRenderingContext2D.fillEllipse(centerX, centerY, width, height)
Отрисовывет элипс. Точнее рисуется не элипс, а кривая Безье, максимально соответсвующая фломе элипса. Для отрисовки "честного" элипса необходимо нарисовать и растянуть круг, что более ресурсоемко. 

### CanvasRenderingContext2D.strokePolygon(polygon)                                                              CanvasRenderingContext2D.fillPolygon(polygon)
Отрисовывает полигон. Метод предназначен для работы с моей библиотекой math2d.js (https://github.com/AgentX001/math2d.js).

### CanvasRenderingContext2D.strokePoint(point)
Схематически рисует точку. Метод предназначен для работы с моей библиотекой math2d.js (https://github.com/AgentX001/math2d.js).
