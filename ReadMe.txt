Model Validation

web api i�erisinde bir request body'sin ald���m�zda zorunluluk kontrollerini yapaca��m�z sistemdir. DataAnotition �zerinde tan�ml�d�r ve model �zerinden ger�ekle�tirebiilirsiniz. �ifre alanlar�n�n mail k�sm�mlar�n�n zorunluluklar�n�n yap�lmas� gibidir.


------------------------------web Api T�rleri------------------------------------------------------------------------------
	1- Required
	2- Range:uzunluk
	3- CreditCard
	4- EmailAdress
	5- Compare: �ifre alan�n iki defa yaz�lmas�

	6- Url: kay�t yap�ld���nda url isteyen olabilir. ve bu ger�ekten url mi ona bakar.
	7- StringLenght: min max de�ere aaral��� belirlenir. karakter say�s�n� bakar
	8- REgularExpression: gerekli expressi�n yazularak do�rulamalar yap�l�r
	9- Phone: telefon numaras� ile ilgili kontroller�
	
-------------------------------&&&&&&&&&&&&&&&&-----------------------------------------------------------------------------
	         Model Valitadion Kullan�m T�rleri
-----------------------------------------------------------------------------------------------------------------------------
	1- ModelStat: modalstate is valid mi ona bakar.
	2- Validatete Model: model attribute ile kontrol sa�lan�yor.
	3- Validate model Filter : web api i�erisinde olu�turdu�umuz attrubuteleri filterlar ekledi�imizde bir controller'a eklemeden hangi action �zerinden filter do�rulmas�� yap�lmas�.
-------------------------------&&&&&&&&&&&&&&&&------------------------------------------------------------------------------
-- MVC taraf�ndan model is valid 'i kulland�k - alt�nda hataa masajlar� c�karma gibi.!