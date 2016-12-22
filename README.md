/ Gua 0.0.1

table.create("name")

/ Egy tábla létrehozása. A táblában tárolt érték még most csak 0.

table.var(2, name)

/ A táblában tártolt érték megváltoztatása! 0 => 2

table.delete(name)

/ A "name" nevű tábla törlése

/A táblában lévő érték növelése.

table.dir(name, +5)

/így most az érték a "name" nevű táblában 7 lesz.

/Ha ki akarjuk íratni a táblában lévő értéket akkor a következőt kell tennünk:

chatbox["name"] 

/Így most csak ennyit fogunk látni:

7

/Ha csak simán akarunk valamit kiiratni akkor:

chatbox{"Gua 0.0.1"}

/Function

function nev[table=name] /a táblában tároló adatokat meglehessen hívni 
table.create("errors")
table.dir("errors" , "40: Nem létezik ilyen név!")
If name (sanyi) then
chatbox{"Köszöntelek sanyi!"}
Else
chatbox[error:40] /40=Nem létezik ilyen név!
end

/Így nézki egy funkció. Meglehet hívni bárhova.

nev[] /Meg is van hívva.
