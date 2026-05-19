# Лабораторные работы по дисциплине Операционные системы

## Лабораторная работа №1:

## Часть 1. Реализация функции: подсчет числа Фибоначчи

### 1) Создаем заголовочный файл
<img width="478" height="106" alt="1" src="https://github.com/user-attachments/assets/98b032bf-4d00-44b1-8d07-9382791319f9" />

### 2) Реализация функции на C++
<img width="538" height="311" alt="2" src="https://github.com/user-attachments/assets/c5af0b51-c3dd-4517-955e-9382f8651abf" />

### 3) Основная программа
<img width="592" height="263" alt="3" src="https://github.com/user-attachments/assets/659a7751-69bc-4727-826a-c99ceb17085f" />

### 4) Запуск и проверка
<img width="715" height="169" alt="4" src="https://github.com/user-attachments/assets/2c304a43-8fab-4e16-aa6d-2a9061484f1d" />

## Часть 2. Проводим компиляцию в ассемблерный код
### 1) Без оптимизации: -O0
<img width="469" height="28" alt="5" src="https://github.com/user-attachments/assets/2684df51-46a5-46cc-aeaa-f1956e9649e2" />!
<img width="816" height="688" alt="6" src="https://github.com/user-attachments/assets/46423383-c4a3-4ec6-a7e0-6077b6e3a2e0" />
<img width="868" height="669" alt="7" src="https://github.com/user-attachments/assets/d2503348-cfac-4cb3-ad21-6560297bbb19" />

### 2) Оптимизация -O3
<img width="856" height="869" alt="8" src="https://github.com/user-attachments/assets/acdbdeed-76c1-4d0f-a5e4-09c6a302bc2e" />

## Часть 3. Создание Makefile
### 1) Makefile
<img width="542" height="407" alt="9" src="https://github.com/user-attachments/assets/e6869ffb-5557-4e40-8a41-ae83dca8bb1d" />

### 2) Результат выполнения
<img width="670" height="109" alt="10" src="https://github.com/user-attachments/assets/d4476ec4-ebad-4a97-81c8-9ee721820cc5" />

## Часть 4. Усовершенствование программы
### 1) Для этого добавим параллельный поток вычислений и синхронизацию
<img width="750" height="771" alt="11" src="https://github.com/user-attachments/assets/79de20f2-161d-4c97-b018-67d0dfa52d6b" />

### 2) Обновленный Makefile
<img width="566" height="501" alt="12" src="https://github.com/user-attachments/assets/73ee69ce-c25c-491b-9f1f-af1c1120952f" />

## Лабораторная работа №2
### Создание Виртруальной машины
[Видео здесь](https://github.com/prodbyAP/operating_system/blob/main/os_lab2.mp4)

## Лабораторная работа №3а
### Вариант 1 - Скопировать из все изображения в папку резервного хранения.
### Сначала устанавливаем nano, чтобы удобнее работать с кодом
<img width="1080" height="455" alt="1" src="https://github.com/user-attachments/assets/e70b8e7d-e68e-473d-8666-5a6a604f6e64" />

### Затем создаем две папки: в images1 позже добавим изображения и перенесем их в images2 с помощью bash скрипта
<img width="840" height="163" alt="2" src="https://github.com/user-attachments/assets/6ef74e83-a362-4f81-9650-78384037ed25" />

### main.sh
<img width="722" height="141" alt="3" src="https://github.com/user-attachments/assets/110baa33-b209-4dd8-9597-4c3100a3d28c" />

### Теперь покажем, что обе папки изначально пустые. В images1 добавим три изображения в форматах .png и .jpg. Затем запускаем скрипт и проверяем копирование изображений в папку images2
<img width="730" height="309" alt="4" src="https://github.com/user-attachments/assets/ca88d719-f5bd-4e83-a67c-b9818d4d2a46" />

## Лабораторная работа №3b
## Для начала создаем файл для скрипта
<img width="904" height="222" alt="1b" src="https://github.com/user-attachments/assets/59989cb0-9b4d-4e59-bb3c-75af70befda5" />

## Редактируем скрипт под PowerShell
<img width="461" height="155" alt="photo_2026-05-20_05-24-05" src="https://github.com/user-attachments/assets/ef3891c5-6243-4f0b-a82d-adcdfeecf7cc" />

## В first_dir добавляем два изображения и проверяем их наличие (добавил два рендера из Blender). Запускаем скрипт и копируем файлы в папку second_dir
<img width="641" height="531" alt="photo_2026-05-20_05-23-45" src="https://github.com/user-attachments/assets/01295afb-5aaf-4ce1-b040-18aadf1395a8" />






















