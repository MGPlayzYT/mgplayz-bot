## MGPlayz' Bot
* A discord.js bot made by MGPlayzYT. Features a meme command, voice commands, and more!

## Contributors
* Thanks to the following people who made this project possible!
   * [Nick Chan](https://github.com/asdfugil/)
   * RandomPerson3465
* You are always free to contribute!

## Releases
* v1.0.0
* [Latest] v1.1.0

## Hosting
* Requirements:
  * Node v14
  * Latest version of npm
  * [Git](https://git-scm.com/download/win)
  * [nano](https://www.nano-editor.org/download.php)
  * Atleast 100MB of free memory
  * Atleast 500MB of free disk space

* Before you begin (IMPORTANT)
  - Make sure you installed a package called `windows-build-tools`. Without this, some packages might not install correctly or will outright fail. To install this package, open an administrative command prompt or powershell window and type `npm i -g windows-build-tools` and it should install. 

* Step 1: Clone the repository
```
git clone https://github.com/MGPlayzYT/mgplayz-bot <custom folder name>
```
* Step 2: cd to your folder path
```
cd <your-custom-folder-name>
```
* Step 3: Rename files using `mv`
```
mv .env.example .env
mv config.js.example config.js
```
* Step 4: Change the contents of your `.env` file
```
BOT_TOKEN=<put your bot token here>
```
* Step 5: Start the installation process
   ```
   npm install package.json
   ```
* Step 6: Start the bot
   ```
   node index.js
   ```

- If you see something like `Shard 0 ready!` on your logs, you're done!

## License
This project uses the [AGPL 3 License](https://raw.githubusercontent.com/MGPlayzYT/mgplayz-bot/main/LICENSE).
> The AGPL license differs from the other GNU licenses in that it was built for network software. You can distribute modified versions if you keep track of the changes and the date you made them. As per usual with GNU licenses, you must license derivatives under AGPL. It provides the same restrictions and freedoms as the GPLv3 but with an additional clause which makes it so that source code must be distributed along with web publication. Since web sites and services are never distributed in the traditional sense, the AGPL is the GPL of the web.
- Simply put, if you use this project on your own, you will have to open-source it on GitHub and include the same license file.
