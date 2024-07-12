# Tabi Bot

This script automates interactions with the Tabi bot, including logging in, claiming rewards, checking in, and leveling up. The script also supports the use of proxies and can restart at configurable intervals.


1. Clone the repository and navigate to the project directory:

    ```bash
    git clone https://github.com/Winnode/Tabi-zoo.git
    cd Tabi-zoo
    ```

2. Install the required dependencies:

    ```bash
    npm install 
    ```
	Or
	
    ```bash
    npm install axios fs chalk readline gradient-string https-proxy-agent winston figlet readline-sync
    ```

3. Create a `rawdata.txt` file in the project directory:
![Tabi Bot Raw Data](https://github.com/Winnode/Tabi-zoo/blob/main/rawdata.png)
    ```
	rawdata1
	rawdata2
	rawdata3
    ```

4. Configuration

Ensure you have a `config.json` file in the same directory as the script with the following structure:

	```json
	{
	  "autoUpgrade": false,
	  "useProxy": false,
	  "restartIntervalHours": 3
	}
	```

## Usage

To start the bot, run the following command:

```bash
node run.js
```

## Password For those who are interested in joining our community, you can find the password at https://t.me/winsnip

```sh
Enter password: ********
```
## Create Telegram bot api and chat id 

Telegram bot api
```
https://t.me/BotFather
```

chat id 
```
https://t.me/GetMyChatID_Bot
```

