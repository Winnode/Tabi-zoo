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

3. Create a `rawdata.txt` file in the project directory. This file should contain the NEAR account credentials in the following format:

    ```
	account1_rawdata
	account2_rawdata
	account3_rawdata
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

