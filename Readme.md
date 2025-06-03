DataFlow Analytics - B2B Landing Page
<div align="center"> <img src="https://via.placeholder.com/1200x600/0A2D5C/FFFFFF?text=Professional+B2B+Landing+Page" alt="DataFlow Analytics Preview">
HTML5
CSS3
JavaScript
D3.js
Leaflet

</div>
🚀 О проекте
Профессиональный лендинг для SaaS-платформы анализа бизнес-процессов, разработанный с фокусом на визуализацию данных и соответствие корпоративным стандартам. Проект сочетает в себе современный дизайн, интерактивные элементы и полную адаптивность для всех устройств.

Ключевые характеристики:

Современный B2B-дизайн с акцентом на контент

Полностью адаптивная верстка

Интерактивные элементы визуализации данных

Соответствие ГОСТ Р 7.0.97-2016

Оптимизированная производительность

✨ Особенности
Категория	Описание
Дизайн	Минималистичный интерфейс с профессиональной цветовой схемой
Адаптивность	Поддержка всех устройств (4 брейкпоинта: 1200px, 992px, 768px, 576px)
Интерактив	Drag-and-drop визуализация, интерактивная карта, анимированные элементы
Производительность	Оптимизированная загрузка, плавные анимации
Стандарты	Поддержка ГОСТ Р 7.0.97-2016 для госзаказчиков
🎨 Дизайн-система
Цветовая палитра
<div style="display: flex; gap: 10px; margin: 20px 0;"> <div style="background: #FFFFFF; width: 50px; height: 50px; border: 1px solid #ddd;"></div> <div style="background: #0A2D5C; width: 50px; height: 50px;"></div> <div style="background: #2F80ED; width: 50px; height: 50px;"></div> <div style="background: linear-gradient(135deg, #8BC6EC, #2F80ED); width: 50px; height: 50px;"></div> </div>
Основные: #FFFFFF (белый), #0A2D5C (темно-синий)

Акцентные: #2F80ED (голубой)

Градиенты: От #8BC6EC до #2F80ED

Типографика
Заголовки: Montserrat (600-800 weight)

Основной текст: Roboto (300-500 weight)

🧩 Интерактивные компоненты
1. Визуализация ETL-процессов
javascript
function initFlowVisualization() {
  // Создание узлов и связей
  const nodes = [
    { id: 1, label: 'Источник данных', type: 'source' },
    { id: 2, label: 'ETL-процесс', type: 'process' },
    { id: 3, label: 'Хранилище', type: 'storage' }
  ];
  
  // Drag-and-drop функционал
  node.call(d3.drag()
    .on('start', dragStarted)
    .on('drag', dragged)
    .on('end', dragEnded));
}
Drag-and-drop узлов

Динамическое обновление связей

Цветовая кодировка типов узлов

2. Геокарта логистических потоков
javascript
function initLogisticsGeomap() {
  // Создание карты
  const map = L.map('logistics-geomap').setView([55.7558, 37.6173], 4);
  
  // Добавление маршрутов
  const routes = [
    { from: [55.7558, 37.6173], to: [59.9343, 30.3351], volume: 150 }
  ];
}
Маршруты с изменяемой толщиной по объему

Интерактивные маркеры городов

DataFlow Analytics © 2023 | Оптимизация бизнес-процессов через анализ потоков данных
