
# Cấu hình Terminal
- Sử dụng ZSH và Oh my zsh!

## Cài đặt homebrew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

## Cài đặt ZSH
```
brew install zsh
```

### Cài đặt Oh my ZSH!
```
cd
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```


# Cài đặt Homebrew cho M1

## Cài đặt Homebrew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

## Tạo file .zshrc (nếu chưa có)
```
touch .zshrc
```

## Export đường dẫn
```
export PATH=/opt/homebrew/bin:$PATH
```

## Chạy file .zshrc để đường dẫn được khả dụng
```
source ~/.zshrc
```

## Sử dụng brew
```
brew help
```

## Thay đổi theme
https://github.com/ohmyzsh/ohmyzsh/wiki/Themes
- Để thay đổi theme, edit file ~/.zshrc sửa dòng ZSH_THEME="avit", trong ngoặc kép là tên theme
