# yii2-phpstorm-commandlinetool
Yii2 CLI tool description for PhpStorm.
We can used autocomplete for all console commands Yii2 in command line PHPStorm IDE.

Add new command line tool in PHPStorm:
- File / Settings / Tools / Command Line Tool Support / Add
Choose tool: Custom tool
Visibility: project

Tool path: path yii root directory. Command yii for linux, or yii.bat for windows
Alias: y
Description: any think

And after added tool opening xml configuration file. Paste content from yii_version.xml file.
