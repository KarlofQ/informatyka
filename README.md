
# Sprawozdanie - Polecenia konsolowe - Karol Petryniak 2Ia gr.2

## Informacje o systemie

1. **Sprawdzenie informacji o systemie operacyjnym**
   ```bash
   uname -a
   ```

2. **Sprawdzenie konfiguracji sprzętowej**
   ```bash
   lshw
   ```

3. **Sprawdzenie adresów IP i MAC**
   ```bash
   ip a
   ```

4. **Sprawdzenie nazwy użytkownika**
   ```bash
   whoami
   ```

5. **Sprawdzenie działających procesów i zużycia zasobów**
   ```bash
   top
   ```

6. **Sprawdzenie daty i godziny**
   ```bash
   date
   ```

7. **Ustawienie czasowego wyłączenia/wylogowania użytkownika**
   ```bash
   shutdown -h +60  # Wyłączenie komputera za 60 minut
   shutdown -r +60  # Restart komputera za 60 minut
   logout
   ```

## Operacje na plikach i katalogach

8. **Wyświetlanie struktury katalogu**
   ```bash
   ls -lah --color=always
   ```

9. **Tworzenie i zarządzanie ścieżkami zagnieżdżonymi**
   ```bash
   mkdir -p /path/to/linux/ubuntu /path/to/mac/mojave /path/to/windows/win10
   ```

10. **Tworzenie plików**
    ```bash
    touch newfile.txt
    echo "Hello World!" > newfile.txt
    cat newfile.txt
    ```

11. **Sprawdzenie, ile czasu działa komputer**
    ```bash
    uptime
    ```

12. **Monitorowanie zużycia zasobów**
    ```bash
    htop
    ```

13. **Wyświetlanie struktury plików i katalogów w postaci drzewka**
    ```bash
    tree /path/to/directory
    ```

## Monitorowanie i zarządzanie procesami

14. **Wyświetlanie działających procesów**
    ```bash
    ps aux
    ```

15. **Filtrowanie procesów**
    ```bash
    ps aux | grep process_name
    ```

16. **Zabijanie procesów**
    ```bash
    kill -9 PID
    ```

## Inne polecenia

17. **Tworzenie aliasów**
    ```bash
    alias powitanie='echo "Cześć $USER, dzisiaj jest `date +%A`, godzina `date +%H:%M:%S`"'
    ```

18. **Sprawdzanie logów systemowych**
    ```bash
    journalctl
    ```

19. **Historia poleceń wprowadzonych w terminalu**
    ```bash
    history
    ```
