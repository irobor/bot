pip install pandas
pip install pybit
pip install matplotlib  (для тестов)
pip install mplfinance  (инструмент для отображения графиков финансовых данных с различными стилями)
py -m pip install --upgrade pip
pip install requests pandas pandas-ta
pip install python-dotenv #python-dotenv для загрузки переменных окружения из файла .env
pip install plotly  # Для отображения графиков в вебе. для сервера не нужно (import plotly.graph_objects as go)

--- pandas-ta может быть не совместима с numpy. Помогает это:
pip install numpy==1.23.5 pandas-ta
