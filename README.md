Репозиторий содержит файлы решения для «ФИЦ 2024: Хакатон», задача "Разработка модуля классификации опор ЛЭП". Команда "Сборная 3 ФИЦ".
1. Первый этап решнеения - разметка данных, предоставленых организаторами. Мы использовали бесплатную программу "label Studio".
2. Вторым этапом выполнена альбументация новых данных, из размеченных на втором этапе. Код был написан самостоятельно и предоставлен в файле "Albumentations.ipynb".
3. Далее было проедено обучение модели YOLO, на новых данных. В качестве валидации были использованны исходные размеченные данные. Код обучения в файле «yolo.ipynb».
4. Паралельно был написан код телеграм-бота и сайт на «flask» (архивы «Bot.zip» и «flask.zip» соотвественно).
5. Контроль метрик во время обучения осуществлялся через «Mlflow».
Представленое решение показало хорошие результаты на валидационных данных.