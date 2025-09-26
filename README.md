# Dermstyle
Dermstyle is a repository that allows you to customize the color theme in the Termux terminal, such as changing the background color, text, and more. I've provided several custom color themes in this repository.

Before customizing the color theme, be sure to check if there is a folder named ".termux" in your home directory by using a basic command like this.

```$ ls -la ~/.termux```

If there is no ".termux" folder in the home directory, please create it by doing the following:

```$ mkdir ~/.termux```

# Available Themes
Following are the custom color themes available

## Preview Themes

| Theme     | Preview |
|-----------|---------|
| Bluezard  | [Preview](./Theme_Colors/Bluezard/bluezard.jpg) |
| Gruvbox   | [Preview](./Theme_Colors/Gruvbox/gruvbox.jpg) |
| Kiyodark  | [Preview](./Theme_Colors/Kiyodark/kiyodark.jpg) |
| LuminaCode| [Preview](./Theme_Colors/LuminaCode/luminacode.jpg) |
| Monokai   | [Preview](./Theme_Colors/Monokai/monokai.jpg) |
| Twilight  | [Preview](./Theme_Colors/Twilight/twilight.jpg) |


# How to use?
How to use it is very easy, for example if you want to use the Monokai color theme, you only need to move or copy the "colors.properties" file to the home directory ".termux"

Example:

```$ cp ~/Dermstyle/Theme_Colors/Monokai/colors.properties ~/.termux/```

After moving or copying the "colors.properties" file, please restart the Termux application.

# How to set default color theme?
Setting the default color theme is easy; simply delete the "colors.properties" file. Here's how to remove a custom color theme.

```$ rm -rf ~/.termux/colors.properties```

After remove the "colors.properties" file, please restart the Termux application.
