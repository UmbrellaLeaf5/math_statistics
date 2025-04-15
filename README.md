# Математическая статистика

## Assignments

### First
* [T.1](./assignment_1/task_01.pdf), [T.2](./assignment_1/task_02.ipynb), [T.3](./assignment_1/task_03.pdf) (до 09.03.2025; 23:59)
* [T.4](./assignment_1/task_04.pdf), T.5([a, b, c, d, e](./assignment_1/task_05_a_b_c_d_e.pdf), [f, g, h](./assignment_1/task_05_f_g_h.ipynb)), T.6([a, b, c](./assignment_1/task_06_a_b_c.pdf), [d, e, f](./assignment_1/task_06_d_e_f.ipynb)) (до 23.03.2025; 23:59)
* [Т.7](./assignment_1/task_07.pdf), [Т.8](./assignment_1/task_08.pdf), [Т.9](./assignment_1/task_09.pdf), Т.10([письм.](./assignment_1/task_10.pdf), [bootstrap](./assignment_1/task_10.ipynb)) (до 30.03.2025; 23:59)
* [Т.11](./assignment_1/task_11.pdf), [Т.12](./assignment_1/task_12.pdf), Т.13([письм.](./assignment_1/task_13.pdf), [jupyter](./assignment_1/task_13.ipynb)), Т.14([письм.](./assignment_1/task_14.pdf), [jupyter](./assignment_1/task_14.ipynb)) (до 13.04.2025; 23:59)

### Second

## Installation

0.  **Клонирование репозитория:**

    Перед тем как начать, вам необходимо клонировать репозиторий с исходным кодом проекта.
 
    ```bash
    git clone https://github.com/UmbrellaLeaf5/math_statistics.git
    ```

    Перейдите в директорию, куда был клонирован репозиторий:

    ```bash
    cd math_statistics
    ``` 


1.  **Создание виртуального окружения:**

    Откройте терминал или командную строку в корневой директории вашего проекта (там, где находится файл `requirements.txt`) и выполните следующую команду для создания виртуального окружения с именем `.venv`:

    ```bash
    python3 -m venv .venv
    ```

    или

    ```bash
    python -m venv .venv
    ```

    *   Если у вас установлена только версия `Python 3`, можете использовать `python` вместо `python3`.
    *   Если виртуальное окружение уже существует (вы его создавали ранее), пропустите этот шаг.


2.  **Активация виртуального окружения:**

    Активируйте виртуальное окружение, чтобы `Python` использовал библиотеки, установленные внутри него:

    *   **Linux/macOS:**

        ```bash
        source .venv/bin/activate
        ```

    *   **Windows (Command Prompt):**

        ```cmd
        .venv\Scripts\activate
        ```

    *   **Windows (PowerShell):**

        ```powershell
        .venv\Scripts\Activate.ps1
        ```

    После активации вы увидите `(.venv)` в начале строки терминала, указывающее на то, что виртуальное окружение активно.


3.  **Установка зависимостей из `requirements.txt`:**

    Установите все библиотеки, перечисленные в файле `requirements.txt`, выполнив следующую команду:

    ```bash
    ./.venv/Scripts/pip install -r requirements.txt
    ```

    или просто:

    ```bash
    pip install -r requirements.txt
    ```