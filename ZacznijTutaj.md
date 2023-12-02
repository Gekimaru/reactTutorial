

# To repozytorium jest dla ludzi chcących nauczyć się reacta znając już podstawy android studio

[Lekcja1](Lekcja1/Lekcja1.md)
# Spis treści



# 1. Pobierasz nodejs
Z tej strony: https://nodejs.org/en
Instalujesz wersje LTS bo jest bardziej stabilna

Jak zrobisz to dobrze to powinno to po wpisaniu komendy:  
`node --version`  
powinno ci wypluć wersje  
![nodeVersion](https://github.com/Gekimaru/reactTutorial/assets/85436765/80496753-8dc2-4069-9602-47ebbd3a2cbb)

# 2. Tworzysz swój pierwszy projekt
## Pobierasz narzędzie do tworzenia apki reactowej
W cmd wpisujesz:  
  `npm install -g create-react-app`    

Powinno ci zacząć pobierać pakiet, u mnie jest pobrany więc po wpisaniu tej samej komendy powinno wyświetlić się:
![InstallReactApp](https://github.com/Gekimaru/reactTutorial/assets/85436765/aa11a124-4312-4be0-a8f0-8cca8c3a1bbc)


## Używasz narzędzia do utworzenia projektu
Przechodzisz do miejsca gdzie chcesz stworzyć folder projektu
Wpisujesz:  
`npx create-react-app nazwa_projektu`   

W tym tutorialu mój projekt ma nazwe tutorialek  

![npxCreatReactAppStart](https://github.com/Gekimaru/reactTutorial/assets/85436765/3ae6272f-f6db-49a3-bb3b-e91ce7149be1)
![npxCreatReactAppEnd](https://github.com/Gekimaru/reactTutorial/assets/85436765/c09aa6e3-5644-4844-97ef-805664f872f8)


## Odpalasz projekt
Wchodzisz do folderu projektu w cmd i wpisujesz:
`npm start`  

![image](https://github.com/Gekimaru/reactTutorial/assets/85436765/256d8def-978c-476f-86df-3c067e52b951)

Po poprawnym uruchomieniu powinno to wyglądać tak:

![image](https://github.com/Gekimaru/reactTutorial/assets/85436765/c6f47187-0059-48d0-97dd-0cf1c9a35dea)"

# 3.Przygotowanie folderu do pracy  
W folderze CzystyProjekt jest projekt który jest odpowiedni przygotowany do początku pracy, wystarczy że pobierzemy go w dane miejsce, wejdziemy do niego  
za pomocą konsoli i wpiszemy:  
`
npm install
`
Na egzaminie sami musimy oczyścić projekt z niepotrzebnych nam rzeczy więc tu jest opis jak to zrobić:
Z podfolderu src z projektu usuwamy:  
- App.css
- App.test.ks
- logo.svg
- reportWebVitals.js
- setupTests.js  
  
Wchodzimy do index.js, usuwamy połączenia do nieisniejących już plików oraz ostatnią linijke o treści reportWebVitals() wraz z komentarzem do niej.  
  
  
Wchodzimy do App.js i zastępujemy całą zawartość tym kodem:  
```
export default function Przycisk() {
  return <button className="przycisk">X</button>;
}
```
Do pliku index.css dodajemy:
`
.przycisk{
  font-size:100px;
}
`

Następnie wchodzimy do podfolderu public i usuwamy stamtąd:
- favicon.ico
- logo192.png
- robots.txt
- manifest.json  
Na końcu powinno to wyglądać w ten sposób:
### App.js  
![appjs](https://github.com/Gekimaru/reactTutorial/assets/85436765/07911284-d13f-4974-804e-c71be8ffdfd6)  
### index.css
![indexcss](https://github.com/Gekimaru/reactTutorial/assets/85436765/7aecd107-f3ee-4775-8637-27cb4da2be86)
### index.js
![indexjs](https://github.com/Gekimaru/reactTutorial/assets/85436765/c7663977-b829-4b14-bad9-cf9f9c797ff5)



Będę w tutorialu będę używał konsoli wbudowanej w VScode ale można też używać cmd 


[Przejdź do spisu treści](#spis-treści)  

