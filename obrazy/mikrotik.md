# Mikrotik

Ze strony mikrotika pobieramy `Raw disk image` w wersji `Stable`. Będzie on w zakładce `Cloud Hosted Router`&#x20;

{% embed url="https://mikrotik.com/download" %}

![](https://i.imgur.com/CrzOewB.png)

Po pobraniu rozpakowujemy archiwum i przenosimy plik `chr-x.x.x.img` do folderu z obrazami

Uruchamiamy GNS3 i przechodzimy do `Edit > Preferences > QEMU > Qemu VMs`  i naciskamy `New`, aby utworzyć nowy szablon:

![](https://i.imgur.com/FQ5YSgX.png)

Wybieramy `Run this Qemu VM on the GNS3 VM`:

![](https://i.imgur.com/wb7nEL8.png)

Następnie nazywamy urządzenie `Mikrotik` i przechodzimy dalej:

![](https://i.imgur.com/z91dx6L.png)

Wybieramy obraz `New Image > Browse...` i wybieramy obraz Mikrotika z folderu:

![](https://i.imgur.com/wwaCnzb.png)

Gotowe! Urządzenie powinno być już dostępne do użytku. Warto je dodać do grupy routerów i dodać ikonę. Więcej w dziale `Grupowanie obrazów`:

{% content-ref url="../podstawowe-koncepty/szablony/grupowanie-obrazow.md" %}
[grupowanie-obrazow.md](../podstawowe-koncepty/szablony/grupowanie-obrazow.md)
{% endcontent-ref %}

Natomiast ilość portów sieciowych w dziale `Edycja szablonów`:

{% content-ref url="../podstawowe-koncepty/szablony/edycja-szablonow.md" %}
[edycja-szablonow.md](../podstawowe-koncepty/szablony/edycja-szablonow.md)
{% endcontent-ref %}
