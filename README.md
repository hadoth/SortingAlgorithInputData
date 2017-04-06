# SortingAlgorithInputData
Powyższa paczka zawiera 480 plików z wygenberowanymi automatycznie danymi dotyczacymi prrocesów

Struktura rekordu:
UUID (unikalne ID procesu), czas zarejestrowania procesu w kolejce, czas niezbędny do wykonania procesu, szacowany czas niezbędny do wykonania procesu
Poszczególne dane w rekordzie oddzielone są przecinkiem i pojedynczą spacją

Nazwa pliku:
1: Rozmiar procesu:
	EQUAL		10
	SMALLER		2
	GREATER		100
2. Trend zmiany czasu wykonania w czasie
	CONST		stały dla wszystkich
	EXPDEC		malejący wykładniczo
	EXPINC		rosnący wykładniczo
	LINDEC		malejący liniowo
	LININC		rosnący liniowo
	ONEBIG		stała wartość i jeden element o 2 rzędy większy
	RAND020		lekko losowe wartości
	RAND100		silnie losowe wartości
3. Czas pojawienia się procesu
	ATONCE		wszystkie procesy pojawiają się w czasie 0
	CLUSTERS	procesy pojawiają się w dużych odstępach czasowych ale po kilka na raz
	CONST		czas pomiędzy zarejestrowaniem kolejnych procesów jest stały
	RAND		czas pomiędzy zarejestrowaniem kolejnych procesów jest losowy
4. Odstępstwo czasu szacowanego względem czasu rzeczywistego
	GOOD		idealne dopasowanie
	INMINUS		czas jest zawsze niedoszacowany
	INPLUS		czas jest zawsze przeszacowany
	RANDOM020	czas szacowany ma nieznaczne odstępstwa od czasu rzeczywistego
	RANDOM100	czas szacowany jest całkowicie losowy i niezależny od czasu rzeczywistego

Z uwagi na ilość wygenerowanych przypadków testowych nie byłem w stanie ich wszystkich przejrzeć. W razie jakbyś Drogi Użytkowniku znalazł jakieś błędy proszę o kontakt na facebooku.

Pozdrawiam i życzę powodzenia w testowaniu
	Stefan Kopara


Copyright 2017 Stefan Kopara

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


Czy coś...
