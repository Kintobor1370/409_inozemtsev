# 409_inozemtsev

Необходимо устновить arcfaceresnet100-8.onnx в директорию ArcFace_Test
https://github.com/onnx/models/blob/main/vision/body_analysis/arcface/model/arcfaceresnet100-8.onnx

NuGet пакет выполнен в двух версиях: с использованием оператора lock() и семафоров SemaphoreSlim.

- Команда для установки пакета с lock():
```
dotnet add package Kintobor_ARcFace_NuGet_Locks --version 1.0.0
```

- Команда для установки пакета с SemaphoreSlim:
```
dotnet add package Kintobor_ArcFace_NuGet_Semaphores --version 1.0.2
```
