# tomislav_madjarevic_mttp

U projektu sam koristio Katalon Recorder koji koristimo za generiranje automatskih test skripti,  preteća ovog alata je
Selenium IDE Firefox extension.
Testirao sam stranicu na linku: "https://demowebshop.tricentis.com/".
Testirane slučajeve sam exportao u C#(WebDriver + NUnit).
Napravio sam u Visual Studio-u novi projekt u "NUnit Test Project (.NET Core).
Nakon toga dodao u projektu sam dodao NUget pakete potrebene za testiranje ( NUnit framework , Selenium WebDriver  ,Selenium Support, Nunit3 Test Adapter   )
Generirane automatske testove (čiji roditeljski folderi završavaju sa "_Katalon") potrebno je importat u solution Visual Studia (TestVisual_solution.sln).
U wordu sam koristio template za opis test slučajeva u kojem se detaljno svaki testni slučaj opisuje .
