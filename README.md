# **NN Function Approximation**

## **Opis projektu**

Projekt **NN Function Approximation** służy do aproksymacji funkcji matematycznych przy użyciu sieci neuronowych. Celem jest zademonstrowanie, jak sieci neuronowe mogą być używane do aproksymacji złożonych funkcji, oraz ocena skuteczności tych modeli za pomocą różnych miar, takich jak MSE, RMSE i R².

## **Zawartość repozytorium**

- `data/` - Folder zawierający przykładowe dane do treningu i testowania modeli.
- `models/` - Folder z zapisanymi modelami sieci neuronowych po treningu.
- `notebooks/` - Notatniki Jupyter zawierające kody źródłowe do trenowania modeli, analizy wyników i wizualizacji.
- `src/` - Źródłowe skrypty Pythona do tworzenia, trenowania i ewaluacji modeli.
- `README.md` - Dokumentacja projektu.
- `requirements.txt` - Lista wymaganych bibliotek Python do uruchomienia projektu.

## **Instalacja**

Aby uruchomić projekt lokalnie, postępuj zgodnie z poniższymi instrukcjami:

1. **Sklonuj repozytorium**:
    ```bash
    git clone https://github.com/DominikMML/NN_function_approximation.git
    cd NN_function_approximation
    ```

2. **Zainstaluj wymagane biblioteki**:
    Wymagane biblioteki są wymienione w pliku `requirements.txt`. Możesz je zainstalować za pomocą pip:
    ```bash
    pip install -r requirements.txt
    ```

3. **Uruchomienie Jupyter Notebook**:
    Aby uruchomić notatniki Jupyter, użyj następującego polecenia:
    ```bash
    jupyter notebook
    ```
    Następnie otwórz notatnik w folderze `notebooks/` i wykonaj komórki kodu.

## **Użycie**

Po uruchomieniu Jupyter Notebook, przejdź przez kroki opisane w notatnikach, aby:

1. **Załadować dane**: Przygotuj dane wejściowe do aproksymacji.
2. **Trenować modele**: Użyj dostarczonych skryptów do trenowania modeli sieci neuronowych na danych.
3. **Ewaluacja modeli**: Ocena skuteczności modeli za pomocą różnych metryk, takich jak MSE, RMSE i R².
4. **Wizualizacja wyników**: Zobacz, jak dobrze sieć neuronowa aproksymuje funkcję, wizualizując predykcje modelu w porównaniu do rzeczywistych wartości.

## **Licencja**

Ten projekt jest objęty licencją MIT. Szczegóły można znaleźć w pliku LICENSE.

## **Autor**

DominikMML - [GitHub Profile](https://github.com/DominikMML)
