# LAB 8 (Fibonacci Calculator)

1) Utworzenie programu
2) Konfigurowanie  Dockerfile.dev i docker-compose.dev na maszyne lokala i produkcyjna 
4) Skonfigurowanie pliku .travis.yml i wysłanie zmian na repozytorium
5) Utworzenie konta na AWS EBS i stworzenie aplikacji poprzez Elastic Beanstalk
6) Utworzenie konta na Travis CI, podanie secretów do aplikacji EBS
7) Uruchomienie Travis'a


## Uruchamianie lokalnie (Docker):

- Pobierz github repo:
```
git clone https://github.com/PseudooUkasz/Cloud_lab8

cd lab8
docker-compose -f docker-compose.dev.yml up -d
```
- Otorz http://localhost:3000

## Uruchamianie przez NPM:

- Pobierz github repo:
```
git clone https://github.com/PseudooUkasz/Cloud_lab8
cd lab8
npm install
npm start
```
- Uruchom http://localhost:3000

## Uruchomianie wersji produkcyjnej lokalnie (Docker):

- Pobierz the github repo:
```
git clone https://github.com/PseudooUkasz/Cloud_lab8
cd lab8
docker-compose up -d
```
- Uruchom http://localhost
