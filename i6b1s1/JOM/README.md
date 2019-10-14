JOM (Java Optimization Modeler) - darmowa, opensourcowa biblioteka Javy umożliwiająca programom napisanym w Javie na modelowanie i rozwiązywanie problemów optymalizacyjnych, definiowanie ich parametrów wejściowych, zmiennych decyzyjnych, funkcji celu i ograniczeń. Wyrażenia matematyczne łączące zmienne, stałe parametry, operatory i funkcje są definiowane poprzez użycie składnik podobnej do MATLAB. JOM pozwala obsługę wielowymiarowych tablic zmiennych i stałych. To umożliwia np. definiowanie tablic ograniczeń w jednym wierszu kodu. 
	Aby rozwiązać problem JOM może pracować z innymi zainstalowanymi rozwiązaniami. Obecna wersja JOM’a jest kompatybilna z MIPCL i GLPK, które są darmowe oraz z CPLEX i XPRESS które są w wersji komercjalnej. Powyższe rozwiązania dotyczą problemów linowych z liczbami mieszanymi. Natomiast dla problemów nieliniowych jest IPOPT, który jest również darmowy.
	JOM jest uznany jako narzędzie wspomagające działania dydaktyczne i badawcze, które skupione są na optymalizacji, albo tam gdzie problemy są związane z optymalizacją. Pozwala na rozwiązywanie problemów dotyczących optymalizacji i analizowanie uzyskanych rozwiązań; pozbycie się ciężkich interfejsów do solverów; korzystanie z elastyczności zapewnianej przez Javę do obsługi problemów dotyczących danych. Dostęp do JOM jest uzyskiwany poprzez wywołanie metody z klasy JOM OptimizationProblem. 
	Zasada działania przedstawiona jest na w przykładzie podanego na stronie JOM. Przedstawiony kod w  Javie rozwiązuje problem za pomocą JOM i GLPK solver dla losowo wybranych współczynników.
 


Jak uruchomić

W celu uruchomienia biblioteki należy ściągnąć pliki z rozszerzeniem .jar ze strony https://github.com/girtel/JOM/releases,
http://www.net2plan.com/jom/externalsoftware/jna.jar
Oraz http://www.net2plan.com/jom/externalsoftware/parallelcolt-0.9.4.jar

Następnie dołączyć do projektu.

Dodatkowo w celu uruchomienia podanego przykładu należy zainstalować GLPK solver
Ze strony http://winglpk.sourceforge.net systemu Windows.
W przypadku systemu Linux, niektóre wydania powinny mieć już to zainstalowanie. W innym przypadku należy pobrać odpowiednią wersję ze strony http://ftp.gnu.org/gnu/glpk.

 
Link do strony:  
http://www.net2plan.com/jom/index.php 
Javadocs: 
http://www.net2plan.com/jom/releases/jom-0.3.2/index.html 
 
 
 

