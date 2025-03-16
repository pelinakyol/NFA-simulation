Bu proje, kullanıcıların belirli diller için Otomato (Sonlu Otomato - NFA) simülasyonlarını görsel olarak 
deneyimlemelerine olanak tanır. Kullanıcılar, farklı diller için dizgeleri kontrol edebilir ve her adımda durum
 geçişlerini gözlemleyebilirler. Ayrıca, geçişlerin olmadığı durumlar için - işareti gösterilecektir.  
Özellikler:  
Dil A: "a" ve "b" harflerinden oluşan, ardışık iki "aa" içermeyen tüm dizgeler.  
Dil B: Boş dizge veya "a" ile başlayıp "b" ile biten tüm dizgeler.  
Dil C: En az iki "a" ve iki "b" içeren tüm dizgeler.  
Proje çalıştırıldığında, üç farklı dil için birer GUI penceresi açılacaktır   
Automaton Sınıfı: Bu sınıf, bir otomatanın geçiş tablosu, başlangıç durumu ve kabul durumları ile ilgili 
işlevleri içerir. Kullanıcı tarafından girilen dizgeleri işlemek için process_string metodunu sağlar.  
AutomatonApp Sınıfı: Tkinter GUI'sini oluşturur. Kullanıcının dizgeleri girmesine ve sonucu görmesine 
olanak tanır. Her bir dil için bir GUI penceresi açılır.  
Geçişler ve Durumlar: Her adımda, kullanıcıya mevcut sembol ve geçerli durumlar hakkında bilgi verilir. 
Eğer geçiş bulunamazsa, - işareti gösterilir.  
Başlangıçta Simülasyonu Çalıştırma:  
start_simulation() fonksiyonu, tüm otomataları çalıştırarak her bir dilin GUI'sini başlatır. 
-----------------------------------------------------------------------------------------------------------------
This project allows users to visually experience Automaton (Finite Automaton - NFA) simulations for specific languages. Users can test strings for different languages and observe state transitions at each step. Additionally, a - symbol will be shown when no valid transition exists.

Features:

Language A: All strings consisting of the letters "a" and "b" that do not contain consecutive "aa".
Language B: The empty string or any string that starts with "a" and ends with "b".
Language C: All strings that contain at least two "a"s and two "b"s.
When the project is run, a separate GUI window will open for each of the three languages.

Automaton Class:
This class manages the transition table, start state, and accepting states of an automaton. It provides the process_string method to process strings entered by the user.

AutomatonApp Class:
This class creates the Tkinter GUI, allowing users to enter strings and see the results. A separate GUI window opens for each language.

Transitions and States:
At each step, the user is informed about the current symbol and active states. If no valid transition is found, a - symbol will be displayed.

Starting the Simulation:
The start_simulation() function runs all automatons and launches a GUI window for each language.








