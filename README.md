# SQL


SELECT *FROM kurssisuoritus
SELECT kurssi FROM kurssisuoritus
SELECT DISTINCT kurssi FROM kurssisuoritus
SELECT * FROM Opiskelija WHERE nimi = 'anna'
SELECT * FROM kurssisuoritus WHERE opiskelija= '999999'
SELECT * FROM Opiskelija WHERE pääaine LIKE '%tiede%' SELECT * FROM Opiskelija WHERE pääaine NOT LIKE '%tiede%' jäljelle jää kaksi matematiikkaa
SELECT kurssi.nimi, kurssisuoritus.päivämäärä, kurssisuoritus.arvosana FROM Kurssi, Kurssisuoritus WHERE Kurssi.kurssitunnus=kurssisuoritus.kurssi
SELECT opiskelija .nimi, kurssisuoritus .päivämäärä, kurssisuoritus .arvosana FROM opiskelija, kurssisuoritus WHERE kurssisuoritus.opiskelija
