# stock_notify

## 簡介

`股票提醒` 是一個用於追蹤和通知股票價格變化的工具。通過此項目，用戶可以設置特定的股票，並在價格達到預定值時接收通知。

## 目錄

- [簡介](#簡介)
- [目錄](#目錄)
- [環境要求](#環境要求)
- [安裝](#安裝)
  - [Windows](#windows)
  - [Mac](#mac)
- [運行項目](#運行項目)
- [配置](#配置)
- [許可](#許可)

## 環境要求

- Python 版本：3.8 或更高
- pip
- Git

## 安裝

### Windows

1. **克隆倉庫**

    打開 PowerShell 並運行以下命令：
    ```powershell
    git clone https://github.com/Terrywu0208/stock_notify.git
    cd stock_notify
    ```

2. **創建虛擬環境**

    ```powershell
    python -m venv venv
    ```

3. **激活虛擬環境**

    ```powershell
    .\venv\Scripts\Activate
    ```

4. **安裝依賴**

    ```powershell
    pip install -r requirements.txt
    ```

### Mac

1. **克隆倉庫**

    打開終端並運行以下命令：
    ```sh
    git clone https://github.com/Terrywu0208/stock_notify.git
    cd stock_notify
    ```

2. **創建虛擬環境**

    ```sh
    python3 -m venv venv
    ```

3. **激活虛擬環境**

    ```sh
    source venv/bin/activate
    ```

4. **安裝依賴**

    ```sh
    pip3 install -r requirements.txt
    ```

## 運行項目

### Windows

1. **激活虛擬環境**（如果尚未激活）

    ```powershell
    .\venv\Scripts\Activate
    ```

2. **運行項目**

    ```powershell
    python StockNotify.py
    ```

### Mac

1. **激活虛擬環境**（如果尚未激活）

    ```sh
    source venv/bin/activate
    ```

2. **運行項目**

    ```sh
    python3 StockNotify.py
    ```

## 配置

在 `stock_code_csv` 文件中放置你想要追踪的股票代碼，確保文件格式正確，每行一個股票代碼。可以按照以下步驟進行：

1. 在項目文件夾中找到 `stock_code_csv` 文件。
2. 打開該文件，並按照以下格式將你想要追踪的股票代碼寫入文件中：其中，`股票1`、`股票2`、`股票3` 是你想要追踪的股票代碼，每行一個。
3. 保存文件並關閉。

這樣，程序就會讀取 `stock_code_csv` 文件中的股票代碼，並開始追踪這些股票的價格變化。
