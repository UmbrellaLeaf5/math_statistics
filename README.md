# Математическая статистика

## Assignments

### First
* [T.1](./assignment_1/task_1.pdf), [T.2](./assignment_1/task_2.ipynb), [T.3](./assignment_1/task_3.pdf) (до 09.03.2025; 23:59)
* [T.4](./assignment_1/task_4.pdf), T.5([a, b, c, d, e](./assignment_1/task_5_a_b_c_d_e.pdf), [f, g, h](./assignment_1/task_5_f_g_h.ipynb)), T.6([a, b, c](./assignment_1/task_6_a_b_c.pdf), [d, e, f](./assignment_1/task_6_d_e_f.ipynb)) (до 23.03.2025; 23:59)

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