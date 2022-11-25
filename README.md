# Установка .NET (dotnet)
1. Полностью закрыть Visual Studio Code
2. Скачать [SDK](https://dotnet.microsoft.com/en-us/download) **не ASP.NET Core Runtime 6.0.11**
3. Скорее всего потребуется перезагрузить компьютер (даже Mac)
4. Открыть терминал и прописать `dotnet --info` в терминале должен быть пункт `.NET SDKs installed` с указанной версией SDK.
5. Открыть VS Code
6. Установить расширение [C# от Microsoft](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp)
7. Перезагрузить VS Code
8. Открыть новую папку File - Open Folder (указывайте папку, желательно, чтобы в пути не было кириллицы и пробелов)
9. Откройте новый терминал, Terminal - New Terminal
10. В терминале должно быть имя открытой папки
11. Выполните `dotnet new console` для создания нового C#-проекта
12. Выполните `dotnet new gitignore` для создания файла gitignore
13. Для создания readme файла можно выполнить `touch README.md`
14. Если всё сделано правильно, структура проекта будет похожей на то, что находится в этом проекте