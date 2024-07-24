# Używamy obrazu z Pythonem 3.9
FROM python:3.9

# Ustawiamy katalog roboczy w kontenerze
WORKDIR /code

# Kopiujemy plik requirements.txt do kontenera
COPY requirements.txt /code/

# Instalujemy wymagane pakiety
RUN pip install --no-cache-dir -r requirements.txt

# Kopiujemy resztę kodu aplikacji do kontenera
COPY . /code/
