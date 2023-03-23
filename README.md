# 🚀 42 HEADER MADRID 🚀

42 Header Madrid is a plugin header for Vim and NeoVim, inspired by the [42 Paris Header](https://github.com/42Paris/42header)  and designed specifically for the 42 Madrid coding school. This header plugin enhances your code files with a beautiful and informative header containing information such as filename, author, email, and creation/update timestamps. The header is compatible with multiple programming languages.
## 📦 Installation
### Vim
1. Download or clone this repository. 
2. Copy the `stdheaderMAD.vim` file to your `~/.vim/plugin` directory.
### NeoVim
1. Download or clone this repository. 
2. In your `init.lua` file, add the following lines:

```lua
vim.g.user42 = 'yourLogin'
vim.g.mail42 = 'yourLogin@student.42madrid.com'
```


## 🎯 Usage

After the installation, you can use the plugin by simply pressing the `<F1>` key while editing a file. The header will be inserted at the beginning of the file.
## 🔧 Customization

You can customize the plugin by modifying the `stdheaderMAD.vim` file. The following variables are available for customization: 
- `s:asciiart`: The ASCII art for the header. 
- `s:start`, `s:end`, `s:fill`: Characters used to create the header's layout. 
- `s:length`, `s:margin`: Dimensions of the header. 
- `s:types`: A dictionary containing file extensions and the corresponding header styles.

Functions in the script handle various aspects of the header, such as: 
- `s:filetype()`: Determines the file type and sets the appropriate header style. 
- `s:textline()`: Generates a line of text within the header. 
- `s:line()`: Generates different lines of the header. 
- `s:user()`, `s:mail()`: Retrieve the user's name and email. 
- `s:filename()`, `s:date()`: Retrieve the filename and current date.
## 🌟 Contributing

If you would like to contribute to this project, feel free to create a fork of the repository and submit a pull request with your changes. We appreciate your help in making this plugin even better! 💪

If you need help, feel free to contact me on Slack! 📩 My login is **slegaris** . 😊
