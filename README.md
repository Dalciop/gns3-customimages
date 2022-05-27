# Instalacja GNS3

Pobieramy potrzebne pliki z repozytorium GNS3:

* `GNS3-x.x.x-all-in-one.exe`
* `GNS3.VM.VirtualBox.x.x.x.zip`

{% embed url="https://github.com/GNS3/gns3-gui/releases/" %}

Uruchamiamy `GNS3-x.x.x-all-in-one.exe`

Wybieramy lokalną instalację i przechodzimy dalej

![](https://i.imgur.com/w0Bs6EE.png)

Jako hosta wirtualnej maszyny GNS3 wybieramy VirtualBox i naciskamy install

![](https://i.imgur.com/q5NvdaC.png)

Po zainstalowaniu GNS3 rozpakowujemy `GNS3.VM.VirtualBox.x.x.x.zip` i importujemy maszynę klikając dwa razy na GNS3 VM.ova

![](https://i.imgur.com/3CFX7HP.png)

Po zaimportowaniu maszyny przechodzimy do GNS3 w którym powinien nam się uruchomić kreator:

![](https://i.imgur.com/PobU0pl.png)

Wybieramy `Run appliances in a virtual machine` i przechodzimy dalej

Jeżeli wyskoczy błąd VMware, a używamy VirtualBoxa do wirtualizacji maszyny GNS3 to można go bez problemu pominąć (komunikat informuje o braku VMware, nie jest on nam potrzebny, ponieważ używamy do tego VirtualBoxa):

![](https://i.imgur.com/o9q9Q0J.png)

Jako program wirtualizujący wybieramy VirtualBox oraz z listy maszyn wybieramy GNS3. Warto zmienić ilość przydzielanej pamięci RAM oraz procesorów, ponieważ wszystkie urządzenia będą uruchamiane wewnątrz jej. (Aktualnie maszyna GNS3 będzie się uruchamiać w osobnym oknie, jednak możemy włączyć, aby pracowała w tle. W tym celu przechodzimy do `Edit > Preferences > GNS3 VM` i zaznaczamy opcję `Run headless` )

![](https://i.imgur.com/Cl0LZOw.png)

Gotowe! GNS3 jest gotowy do pracy.&#x20;

